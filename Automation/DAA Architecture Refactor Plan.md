# DAA Architecture Refactor Plan

## Decision
- Target: Python (FastAPI) becomes the only backend for all server-side logic under `/api/daa/*`.
- Next.js becomes UI-only (no DB, no auth logic, no server-side persistence).
- DB: Postgres (with Alembic migrations); optional Redis later for sessions/rate-limit.

## Why (what we are fixing)
- `sql.js` in a Next.js server bundle is brittle (Emscripten/`this`/strict-mode + bundler issues). We already hit a production crash on login.
- Persistence/auth/audit are core; they should not depend on a JS-in-SQLite shim.
- One backend = clearer ownership, easier observability, and fewer Next server runtime footguns.

## Target Runtime Topology
- `daa-web` (Next): UI only; talks to API via HTTPS.
- `daa-api` (FastAPI): auth/session, runs, audit, admin users; calls compute endpoints if needed.
- `daa-worker` (optional): long-running jobs / cron / backtests.
- `postgres`: durable storage.

Nginx routing
- `/daa/*` -> Next
- `/api/daa/*` -> FastAPI

## Migration Outline (PR-sized)
1) Introduce `daa-api` container + Postgres + Alembic; define schemas: accounts, magic_link_tokens, sessions, runs, audit_events, admin_users.
2) Implement auth in Python as email magic-link:
   - `POST /api/daa/auth/request-link` (rate-limited) -> send email
   - `GET /api/daa/auth/verify?token=...` -> set session cookie (SameSite=Lax)
   - `POST /api/daa/auth/logout`, `GET /api/daa/auth/me`
   Provider abstraction: SMTP/Resend-style; dev fallback can log the link (never for public prod).
3) Move store endpoints (runs/audit/admin users) from Next to Python; keep response shape compatible to avoid UI churn.
4) Update Next to call Python API; delete Node-side sqlite/sql.js code paths.
5) Decommission legacy bearer tokens and any bootstrap hacks; keep one clean bootstrap flow for first admin (guarded).

## Notes
- Current prod has a temporary empty-password mode gated by env; this is a stopgap for early-stage UX, not the final auth design.
