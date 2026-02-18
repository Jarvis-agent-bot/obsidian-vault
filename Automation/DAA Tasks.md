# DAA Tasks

## Now

- [ ] (auto) NOW: mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v7 :: Follow-up hardening: Mainline GOAL: Python service becomes optional (engine-only) and must NOT own `/api/daa/*`.
## Backlog

Planning note: priority = top to bottom. Keep each task ~1 PR.

Mainline (2026-02-16): Architecture refactor first — keep Next.js as the ONLY public backend for `/api/daa/*`, but replace sqlite(sql.js) with Postgres + Resend magic link.















































































































































































- [ ] mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v7 :: Follow-up hardening: Mainline GOAL: Python service becomes optional (engine-only) and must NOT own `/api/daa/*`.

- [ ] mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v8 :: Follow-up hardening: Mainline GOAL: Remove `sql.js`/SQLite from server runtime (no bundler/strict-mode footguns).

- [ ] mainline-dod-prod-smoke-200-200-v7 :: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200.

- [ ] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v7 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI).
## Done

- [x] mainline-dod-sets-session-cookie-and-redirects-to-v3 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/consume` sets session cookie and redirects to `/daa/dashboard`.

- [x] mainline-dod-sends-email-via-resend-v3 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/request` sends email via Resend.

- [x] mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v3 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline GOAL: Python service becomes optional (engine-only) and must NOT own `/api/daa/*`.

- [x] mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v4 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline GOAL: Remove `sql.js`/SQLite from server runtime (no bundler/strict-mode footguns).

- [x] mainline-dod-prod-smoke-200-200-v3 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200.

- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v3 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI).

- [x] mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v4 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline GOAL: Python service becomes optional (engine-only) and must NOT own `/api/daa/*`.

- [x] mainline-dod-sends-email-via-resend-v4 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/request` sends email via Resend. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/415)

- [x] mainline-dod-sets-session-cookie-and-redirects-to-v4 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/consume` sets session cookie and redirects to `/daa/dashboard`. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/416)

- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v4 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/417)

- [x] mainline-dod-prod-smoke-200-200-v4 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200.

- [x] mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v5 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline GOAL: Remove `sql.js`/SQLite from server runtime (no bundler/strict-mode footguns). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/419)

- [x] mainline-dod-sets-session-cookie-and-redirects-to-v5 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/consume` sets session cookie and redirects to `/daa/dashboard`. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/420)

- [x] mainline-dod-sends-email-via-resend-v5 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/request` sends email via Resend. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/421)

- [x] mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v5 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline GOAL: Python service becomes optional (engine-only) and must NOT own `/api/daa/*`. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/422)

- [x] mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v6 :: Follow-up hardening: Mainline GOAL: Remove `sql.js`/SQLite from server runtime (no bundler/strict-mode footguns). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/423)

- [x] mainline-dod-prod-smoke-200-200-v5 :: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/424)

- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v5 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/425)

- [x] mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v6 :: Follow-up hardening: Mainline GOAL: Python service becomes optional (engine-only) and must NOT own `/api/daa/*`. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/426)

- [x] mainline-dod-sends-email-via-resend-v6 :: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/request` sends email via Resend. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/427)

- [x] mainline-dod-sets-session-cookie-and-redirects-to-v6 :: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/consume` sets session cookie and redirects to `/daa/dashboard`. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/428)

- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v6 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/429)

- [x] mainline-dod-prod-smoke-200-200-v6 :: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/430)

- [x] mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v7 :: Follow-up hardening: Mainline GOAL: Remove `sql.js`/SQLite from server runtime (no bundler/strict-mode footguns). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/431)

- [x] mainline-dod-sets-session-cookie-and-redirects-to-v7 :: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/consume` sets session cookie and redirects to `/daa/dashboard`. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/432)

- [x] mainline-dod-sends-email-via-resend-v7 :: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/request` sends email via Resend. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/433)
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


- 2026-02-18 10:00 backlog-guard completed stale mainline-dod-sets-session-cookie-and-redirects-to-v4

- 2026-02-18 10:00 backlog-guard added mainline-dod-sets-session-cookie-and-redirects-to-v5

- 2026-02-18 10:00 backlog-guard added mainline-dod-sends-email-via-resend-v5

- 2026-02-18 10:00 backlog-guard added mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v5

- 2026-02-18 10:00 activated mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v4

- 2026-02-18 10:07 backlog-guard completed stale mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v4

- 2026-02-18 10:10 activated mainline-dod-prod-smoke-200-200-v4

- 2026-02-18 11:00 backlog-guard completed stale mainline-dod-prod-smoke-200-200-v4

- 2026-02-18 11:00 activated mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v5

- 2026-02-18 11:17 backlog-guard completed stale mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v5

- 2026-02-18 11:17 backlog-guard added mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v6

- 2026-02-18 11:17 backlog-guard added mainline-dod-prod-smoke-200-200-v5

- 2026-02-18 11:17 backlog-guard added mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v5

- 2026-02-18 11:17 activated mainline-dod-sets-session-cookie-and-redirects-to-v5

- 2026-02-18 11:20 backlog-guard completed stale mainline-dod-sets-session-cookie-and-redirects-to-v5

- 2026-02-18 11:20 activated mainline-dod-sends-email-via-resend-v5

- 2026-02-18 11:23 mainline-dod-sends-email-via-resend-v5: merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/421

- 2026-02-18 11:25 activated mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v5

- 2026-02-18 11:28 backlog-guard completed stale mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v5

- 2026-02-18 11:28 backlog-guard added mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v6

- 2026-02-18 11:28 backlog-guard added mainline-dod-sends-email-via-resend-v6

- 2026-02-18 11:28 backlog-guard added mainline-dod-sets-session-cookie-and-redirects-to-v6

- 2026-02-18 11:28 activated mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v6

- 2026-02-18 11:37 backlog-guard completed stale mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v6

- 2026-02-18 11:45 activated mainline-dod-prod-smoke-200-200-v5

- 2026-02-18 12:00 backlog-guard completed stale mainline-dod-prod-smoke-200-200-v5

- 2026-02-18 12:00 activated mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v5

- 2026-02-18 12:01 backlog-guard completed stale mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v5

- 2026-02-18 12:01 backlog-guard added mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v6

- 2026-02-18 12:01 backlog-guard added mainline-dod-prod-smoke-200-200-v6

- 2026-02-18 12:01 backlog-guard added mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v7

- 2026-02-18 12:01 activated mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v6

- 2026-02-18 12:16 backlog-guard completed stale mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v6

- 2026-02-18 12:16 activated mainline-dod-sends-email-via-resend-v6

- 2026-02-18 12:31 backlog-guard completed stale mainline-dod-sends-email-via-resend-v6

- 2026-02-18 12:31 activated mainline-dod-sets-session-cookie-and-redirects-to-v6

- 2026-02-18 12:46 backlog-guard completed stale mainline-dod-sets-session-cookie-and-redirects-to-v6

- 2026-02-18 12:46 backlog-guard added mainline-dod-sets-session-cookie-and-redirects-to-v7

- 2026-02-18 12:46 backlog-guard added mainline-dod-sends-email-via-resend-v7

- 2026-02-18 12:46 backlog-guard added mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v7

- 2026-02-18 12:46 activated mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v6

- 2026-02-18 13:01 backlog-guard completed stale mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v6

- 2026-02-18 13:01 activated mainline-dod-prod-smoke-200-200-v6

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
