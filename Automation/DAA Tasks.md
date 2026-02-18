# DAA Tasks

## Now

- [ ] (auto) NOW: frontend-uiux-funds-hub-step-card-hierarchy-v1 :: Frontend UIUX follow-up: complete funds hub step-card hierarchy and action priority polish

## Backlog

Planning note: priority = top to bottom. Keep each task ~= 1 PR.
Planning override (2026-02-19): architecture-first; avoid repetitive hardening loops unless blocking.

- [ ] frontend-uiux-funds-hub-step-card-hierarchy-v1 :: Frontend UIUX follow-up: complete funds hub step-card hierarchy and action priority polish

- [ ] backend-nextjs-postgres-platform-hardening-v2 :: Follow-up hardening: Backend system A follow-up: close remaining Next.js + Postgres API boundary and migration gaps

- [ ] mainline-dod-prod-smoke-200-200-v19 :: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200.

- [ ] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v19 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI).
## Done (Recent)

- [x] mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v8 :: Follow-up hardening: Mainline GOAL: Python service becomes optional (engine-only) and must NOT own `/api/daa/*`. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/438)

- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v7 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/437)

- [x] mainline-dod-prod-smoke-200-200-v7 :: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/436)

- [x] mainline-dod-sets-session-cookie-and-redirects-to-v9 :: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/consume` sets session cookie and redirects to `/daa/dashboard`.

- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v9 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/446)

- [x] mainline-dod-prod-smoke-200-200-v9 :: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/447)

- [x] mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v9 :: Follow-up hardening: Mainline GOAL: Python service becomes optional (engine-only) and must NOT own `/api/daa/*`. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/448)

- [x] mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v10 :: Follow-up hardening: Mainline GOAL: Remove `sql.js`/SQLite from server runtime (no bundler/strict-mode footguns). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/449)

- [x] backend-nextjs-postgres-platform-hardening-v1 :: Backend system A follow-up: close remaining Next.js + Postgres API boundary and migration gaps (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/484)

- [x] backend-engine-service-contract-hardening-v1 :: Backend system B follow-up: finish Python engine contract timeout/error mapping hardening (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/485)

- [x] frontend-uiux-dashboard-information-architecture-v1 :: Frontend UIUX follow-up: complete dashboard information architecture and operator scan flow (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/486)
## Log (Recent)

- 2026-02-18 16:16 backlog-guard added mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v10
- 2026-02-18 16:16 backlog-guard added mainline-dod-prod-smoke-200-200-v9
- 2026-02-18 16:16 backlog-guard added mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v9
- 2026-02-18 16:16 activated mainline-dod-sets-session-cookie-and-redirects-to-v9
- 2026-02-18 16:02 backlog-guard completed stale mainline-dod-prod-smoke-200-200-v8
- 2026-02-18 16:02 activated mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v9
- 2026-02-18 15:50 backlog-guard completed stale mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v8
- 2026-02-18 15:50 activated mainline-dod-prod-smoke-200-200-v8
- 2026-02-19 03:30 backlog-guard completed stale mainline-dod-sets-session-cookie-and-redirects-to-v9
- 2026-02-19 03:30 backlog-guard completed stale mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v9
- 2026-02-19 03:30 backlog-guard completed stale mainline-dod-prod-smoke-200-200-v9
- 2026-02-19 03:30 backlog-guard completed stale mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v9
- 2026-02-19 03:30 backlog-guard completed stale mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v10


- 2026-02-19 03:40 activated backend-nextjs-postgres-platform-hardening-v1

- 2026-02-19 03:51 backlog-guard added backend-nextjs-postgres-platform-hardening-v2

- 2026-02-19 03:51 backlog-guard added mainline-dod-prod-smoke-200-200-v19

- 2026-02-19 03:51 backlog-guard added mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v19

- 2026-02-19 03:51 activated backend-engine-service-contract-hardening-v1

- 2026-02-19 04:01 activated frontend-uiux-dashboard-information-architecture-v1

- 2026-02-19 04:11 activated frontend-uiux-funds-hub-step-card-hierarchy-v1
