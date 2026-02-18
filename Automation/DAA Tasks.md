# DAA Tasks

## Now

- [ ] (auto) NOW: mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v8 :: Follow-up hardening: Mainline GOAL: Python service becomes optional (engine-only) and must NOT own `/api/daa/*`.
## Backlog

Planning note: priority = top to bottom. Keep each task ~1 PR.

Mainline (2026-02-16): Architecture refactor first — keep Next.js as the ONLY public backend for `/api/daa/*`, but replace sqlite(sql.js) with Postgres + Resend magic link.



















































































































































































- [ ] mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v8 :: Follow-up hardening: Mainline GOAL: Python service becomes optional (engine-only) and must NOT own `/api/daa/*`.

- [ ] mainline-dod-sends-email-via-resend-v8 :: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/request` sends email via Resend.

- [ ] mainline-dod-sets-session-cookie-and-redirects-to-v8 :: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/consume` sets session cookie and redirects to `/daa/dashboard`.

- [ ] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v8 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI).

- [ ] mainline-dod-prod-smoke-200-200-v8 :: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200.

- [ ] mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v9 :: Follow-up hardening: Mainline GOAL: Remove `sql.js`/SQLite from server runtime (no bundler/strict-mode footguns).
## Done

- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v6 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/429)

- [x] mainline-dod-prod-smoke-200-200-v6 :: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/430)

- [x] mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v7 :: Follow-up hardening: Mainline GOAL: Remove `sql.js`/SQLite from server runtime (no bundler/strict-mode footguns). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/431)

- [x] mainline-dod-sets-session-cookie-and-redirects-to-v7 :: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/consume` sets session cookie and redirects to `/daa/dashboard`. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/432)

- [x] mainline-dod-sends-email-via-resend-v7 :: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/request` sends email via Resend. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/433)

- [x] mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v7 :: Follow-up hardening: Mainline GOAL: Python service becomes optional (engine-only) and must NOT own `/api/daa/*`. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/434)

- [x] mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v8 :: Follow-up hardening: Mainline GOAL: Remove `sql.js`/SQLite from server runtime (no bundler/strict-mode footguns). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/435)

- [x] mainline-dod-prod-smoke-200-200-v7 :: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/436)

- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v7 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/437)
## Log

- 2026-02-18 13:16 backlog-guard completed stale mainline-dod-prod-smoke-200-200-v6
- 2026-02-18 13:16 activated mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v7
- 2026-02-18 13:31 backlog-guard completed stale mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v7
- 2026-02-18 13:31 backlog-guard added mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v8
- 2026-02-18 13:31 backlog-guard added mainline-dod-prod-smoke-200-200-v7
- 2026-02-18 13:31 backlog-guard added mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v7
- 2026-02-18 13:31 activated mainline-dod-sets-session-cookie-and-redirects-to-v7
- 2026-02-18 13:46 backlog-guard completed stale mainline-dod-sets-session-cookie-and-redirects-to-v7
- 2026-02-18 13:46 activated mainline-dod-sends-email-via-resend-v7
- 2026-02-18 14:01 backlog-guard completed stale mainline-dod-sends-email-via-resend-v7
- 2026-02-18 14:01 activated mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v7
- 2026-02-18 14:16 backlog-guard completed stale mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v7
- 2026-02-18 14:16 backlog-guard added mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v8
- 2026-02-18 14:16 backlog-guard added mainline-dod-sends-email-via-resend-v8
- 2026-02-18 14:16 backlog-guard added mainline-dod-sets-session-cookie-and-redirects-to-v8
- 2026-02-18 14:16 activated mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v8
- 2026-02-18 14:31 backlog-guard completed stale mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v8
- 2026-02-18 14:31 activated mainline-dod-prod-smoke-200-200-v7
- 2026-02-18 14:46 backlog-guard completed stale mainline-dod-prod-smoke-200-200-v7
- 2026-02-18 14:46 activated mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v7


- 2026-02-18 15:01 backlog-guard completed stale mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v7

- 2026-02-18 15:01 backlog-guard added mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v8

- 2026-02-18 15:01 backlog-guard added mainline-dod-prod-smoke-200-200-v8

- 2026-02-18 15:01 backlog-guard added mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v9

- 2026-02-18 15:01 activated mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v8
