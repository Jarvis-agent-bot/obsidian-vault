# DAA Tasks

## Now

- [ ] (auto) NOW: mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v10 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI).

## Backlog

Planning note: priority = top to bottom. Keep each task ~= 1 PR.

- [ ] mainline-dod-sets-session-cookie-and-redirects-to-v9 :: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/consume` sets session cookie and redirects to `/daa/dashboard`.
- [ ] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v9 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/446)
- [ ] mainline-dod-prod-smoke-200-200-v9 :: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/447)
- [ ] mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v9 :: Follow-up hardening: Mainline GOAL: Python service becomes optional (engine-only) and must NOT own `/api/daa/*`. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/448)
- [ ] mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v10 :: Follow-up hardening: Mainline GOAL: Remove `sql.js`/SQLite from server runtime (no bundler/strict-mode footguns). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/449)

## Done (Recent)

- [x] mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v9 :: Follow-up hardening: Mainline GOAL: Remove `sql.js`/SQLite from server runtime (no bundler/strict-mode footguns). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/443)
- [x] mainline-dod-prod-smoke-200-200-v8 :: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/442)
- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v8 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/441)
- [x] mainline-dod-sets-session-cookie-and-redirects-to-v8 :: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/consume` sets session cookie and redirects to `/daa/dashboard`. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/440)
- [x] mainline-dod-sends-email-via-resend-v8 :: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/request` sends email via Resend. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/439)
- [x] mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v8 :: Follow-up hardening: Mainline GOAL: Python service becomes optional (engine-only) and must NOT own `/api/daa/*`. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/438)
- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v7 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/437)
- [x] mainline-dod-prod-smoke-200-200-v7 :: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/436)

## Log (Recent)

- 2026-02-18 16:16 backlog-guard added mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v10
- 2026-02-18 16:16 backlog-guard added mainline-dod-prod-smoke-200-200-v9
- 2026-02-18 16:16 backlog-guard added mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v9
- 2026-02-18 16:16 activated mainline-dod-sets-session-cookie-and-redirects-to-v9
- 2026-02-18 16:02 backlog-guard completed stale mainline-dod-prod-smoke-200-200-v8
- 2026-02-18 16:02 activated mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v9
- 2026-02-18 15:50 backlog-guard completed stale mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v8
- 2026-02-18 15:50 activated mainline-dod-prod-smoke-200-200-v8

- [ ] mainline-dod-sends-email-via-resend-v9 :: Follow-up hardening: Mainline DOD: /api/daa/auth/email-login/request sends email via Resend. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/445)

- [ ] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v10 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI).

- [ ] mainline-dod-prod-smoke-200-200-v10 :: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200.

- [ ] mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v10 :: Follow-up hardening: Mainline GOAL: Python service becomes optional (engine-only) and must NOT own `/api/daa/*`.

- [ ] mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v11 :: Follow-up hardening: Mainline GOAL: Remove `sql.js`/SQLite from server runtime (no bundler/strict-mode footguns).
