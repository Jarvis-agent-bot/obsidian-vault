# DAA Mainline

## Epoch
Arch refactor (Next.js backend + Postgres; remove sql.js)

## Goal (what "done" looks like)
- Next.js remains the ONLY public backend for `/api/daa/*` (no FastAPI migration for the public surface).
- Postgres is the ONLY persistence for auth + runs + audit + admin users.
- Auth is email magic-link (Resend) + cookie session (SameSite=Lax).
- Remove `sql.js`/SQLite from server runtime (no bundler/strict-mode footguns).
- Python service becomes optional (engine-only) and must NOT own `/api/daa/*`.

## DoD (verifiable)
- `/api/daa/auth/email-login/request` sends email via Resend.
- `/api/daa/auth/email-login/consume` sets session cookie and redirects to `/daa/dashboard`.
- `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI).
- Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200.

## Avoid (low ROI during this epoch)
- UI micro-polish unless it is required to finish auth migration.
- Migrating the entire `/api/daa/*` surface to FastAPI (too much rework; focus on Postgres + magic link first).
- New product features (Funds Hub / E2E execution) until persistence + auth is stable.

## Execution Rules
- 1 milestone = 1 PR.
- WIP: at most 1 open PR.
- Every milestone must include a minimal smoke/verification step.

## Config (email)
- RESEND_API_KEY
- DAA_AUTH_EMAIL_FROM
- DAA_PUBLIC_ORIGIN

