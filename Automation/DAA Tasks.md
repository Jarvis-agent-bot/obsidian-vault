# DAA Tasks

## Now

- [ ] (auto) NOW: mainline-dod-sets-session-cookie-and-redirects-to-v4 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/consume` sets session cookie and redirects to `/daa/dashboard`.
## Backlog

Planning note: priority = top to bottom. Keep each task ~1 PR.

Mainline (2026-02-16): Architecture refactor first — keep Next.js as the ONLY public backend for `/api/daa/*`, but replace sqlite(sql.js) with Postgres + Resend magic link.





























































































































































- [ ] mainline-dod-sets-session-cookie-and-redirects-to-v4 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/consume` sets session cookie and redirects to `/daa/dashboard`. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/416)

- [ ] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v4 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI).

- [ ] mainline-dod-prod-smoke-200-200-v4 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200.

- [ ] mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v5 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline GOAL: Remove `sql.js`/SQLite from server runtime (no bundler/strict-mode footguns).
## Done

- [x] mainline-dod-sets-session-cookie-and-redirects-to-v3 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/consume` sets session cookie and redirects to `/daa/dashboard`.

- [x] mainline-dod-sends-email-via-resend-v3 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/request` sends email via Resend.

- [x] mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v3 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline GOAL: Python service becomes optional (engine-only) and must NOT own `/api/daa/*`.

- [x] mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v4 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline GOAL: Remove `sql.js`/SQLite from server runtime (no bundler/strict-mode footguns).

- [x] mainline-dod-prod-smoke-200-200-v3 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200.

- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v3 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI).

- [x] mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v4 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline GOAL: Python service becomes optional (engine-only) and must NOT own `/api/daa/*`.

- [x] mainline-dod-sends-email-via-resend-v4 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/request` sends email via Resend. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/415)

## Log

- 2026-02-17 23:50 backlog-guard completed stale mainline-dod-sends-email-via-resend-v3
- 2026-02-17 23:50 activated mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v3
- 2026-02-18 00:00 backlog-guard completed stale mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v3
- 2026-02-18 00:00 backlog-guard added mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v4
- 2026-02-18 00:00 backlog-guard added mainline-dod-sends-email-via-resend-v4
- 2026-02-18 00:00 backlog-guard added mainline-dod-sets-session-cookie-and-redirects-to-v4
- 2026-02-18 00:00 activated mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v4
- 2026-02-18 00:20 backlog-guard completed stale mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v4
- 2026-02-18 00:20 activated mainline-dod-prod-smoke-200-200-v3
- 2026-02-18 00:50 backlog-guard completed stale mainline-dod-prod-smoke-200-200-v3
- 2026-02-18 00:50 activated mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v3
- 2026-02-18 01:20 backlog-guard completed stale mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v3
- 2026-02-18 01:20 backlog-guard added mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v4
- 2026-02-18 01:20 backlog-guard added mainline-dod-prod-smoke-200-200-v4
- 2026-02-18 01:20 backlog-guard added mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v5
- 2026-02-18 01:20 activated mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v4
- 2026-02-18 01:30 backlog-guard completed stale mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v4
- 2026-02-18 01:30 activated mainline-dod-sends-email-via-resend-v4
- 2026-02-18 03:17 backlog-guard completed stale mainline-dod-sends-email-via-resend-v4
- 2026-02-18 03:17 activated mainline-dod-sets-session-cookie-and-redirects-to-v4

