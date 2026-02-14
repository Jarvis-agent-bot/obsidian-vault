# DAA Tasks

## Now
- [ ] (auto) Nothing active

## Backlog

Planning note: priority = top to bottom. Keep each task ~1 PR.

Mainline (2026-02-14): UI refactor first — adopt shadcn for /daa/login + /daa/dashboard, and simplify auth UX to “email login”.

- [ ] auth-email-login-v0 :: Auth: treat username as email (UI labels, basic validation, normalize lower-case); keep server contract minimal
- [ ] auth-bootstrap-first-admin-v0 :: Auth/Deploy: enable one-time bootstrap for first admin on fresh prod deploy without legacy bearer tokens (guarded)


- [ ] ui-shadcn-daa-login-form-v0 :: shadcn: refactor /daa/login form + validation states (loading/error)

- [ ] dashboard-ui-shadcn-session-banner-v0 :: dashboard UI: add shadcn session banner (who am I + logout)

- [ ] dashboard-auth-email-login-ux-v0 :: Dashboard/Auth: polish email login UX (loading, inline errors, resend hint, better empty states)

- [ ] dashboard-ui-shadcn-admin-users-v0-v4 :: Dashboard: refactor Admin Users table/drawer UI to shadcn (search/sort/status filters) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/244)
## Done

- [x] dashboard-daa-audit-log-pagination-v0 :: Dashboard: add pagination + page size controls to DAA audit log table (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/233)

- [x] api-daa-admin-users-activate-deactivate-v0 :: Admin API + dashboard: allow activating/deactivating users and show status badge (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/234)

- [x] dashboard-daa-admin-users-copy-id-action-v0 :: DAA admin users: add Copy User ID action (toast + clipboard) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/235)

- [x] backend-sqlite-daa-audit-events-filter-by-actor-v0 :: SQLite audit: support filtering audit events by actor/user id (API + indexed query) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/236)

- [x] dashboard-daa-admin-users-status-filter-v0 :: DAA admin users: add status filter (active/inactive) + preserve in URL (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/237)

- [x] dashboard-daa-audit-log-copy-json-action-v0 :: DAA audit log: add Copy JSON action in row details (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/238)

- [x] api-daa-auth-accounts-v0 :: Auth: port 基估宝-style account/session module for DAA (no legacy token-only auth) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/239)

- [x] dashboard-auth-login-v0 :: Dashboard: add /daa/login + session flow to replace token header usage (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/240)

- [x] ui-shadcn-foundation-v0 :: UI: add Tailwind + shadcn base (Button/Input/Card/Tabs/Dialog/Toast) and align theme tokens with existing globals.css (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/241)

- [x] dashboard-ui-shadcn-layout-v0 :: Dashboard: refactor /daa/login + /daa/dashboard layout/shell to shadcn primitives (consistent spacing/typography) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/242)

- [x] dashboard-ui-shadcn-confirm-executed-v0 :: Dashboard: refactor Confirm/Executed module UI to shadcn (forms, error states, loading) and reduce inline styles (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/243)

- [x] dashboard-ui-shadcn-admin-users-v0 :: Dashboard: refactor Admin Users table/drawer UI to shadcn (search/sort/status filters) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/244)
## Log

- 2026-02-14 20:54 dashboard-daa-admin-users-table-search-sort-v0: Opened PR https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/231
- 2026-02-14 20:58 DONE: dashboard-daa-admin-users-table-search-sort-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/232
- 2026-02-14 21:00 autofill added dashboard-daa-audit-log-copy-json-action-v0
- 2026-02-14 21:05 activated dashboard-daa-audit-log-pagination-v0
- 2026-02-14 21:13 Merged: dashboard-daa-audit-log-pagination-v0 (#233) https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/233
- 2026-02-14 21:20 activated api-daa-admin-users-activate-deactivate-v0
- 2026-02-14 21:40 activated dashboard-daa-admin-users-copy-id-action-v0
- 2026-02-14 21:48 [Merged] dashboard-daa-admin-users-copy-id-action-v0 :: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/235
- 2026-02-14 21:50 activated backend-sqlite-daa-audit-events-filter-by-actor-v0
- 2026-02-14 22:06 merged backend-sqlite-daa-audit-events-filter-by-actor-v0 → https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/236
- 2026-02-14 22:10 activated dashboard-daa-admin-users-status-filter-v0
- 2026-02-14 22:20 Merged PR #237 for dashboard-daa-admin-users-status-filter-v0 (Admin Users status filter; URL param adminUsersStatus)
- 2026-02-14 22:25 activated dashboard-daa-audit-log-copy-json-action-v0
- 2026-02-14 22:25 added auth system tasks: api-daa-auth-accounts-v0, dashboard-auth-login-v0 (per sheng cai request: 基估宝 approach, drop legacy)
- 2026-02-14 22:38 2026-02-14 22:38 DONE: dashboard-daa-audit-log-copy-json-action-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/238
- 2026-02-14 22:40 activated api-daa-auth-accounts-v0
- 2026-02-14 22:51 api-daa-auth-accounts-v0: Opened PR https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/239
- 2026-02-14 22:53 DONE: api-daa-auth-accounts-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/239; SoT advanced -> none
- 2026-02-14 22:55 activated dashboard-auth-login-v0
- 2026-02-14 23:16 DONE: dashboard-auth-login-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/240; SoT advanced -> none


- 2026-02-14 23:25 activated ui-shadcn-foundation-v0

- 2026-02-14 23:40 activated dashboard-ui-shadcn-layout-v0

- 2026-02-14 23:48 2026-02-14 23:46 merged dashboard-ui-shadcn-layout-v0 via PR #242; SoT advanced (no next milestone queued)

- 2026-02-14 23:49 activated dashboard-ui-shadcn-confirm-executed-v0

- 2026-02-15 00:15 activated dashboard-ui-shadcn-confirm-executed-v0

- 2026-02-15 00:20 autofill added ui-shadcn-daa-login-form-v0

- 2026-02-15 00:20 autofill added dashboard-ui-shadcn-session-banner-v0

- 2026-02-15 00:25 activated dashboard-ui-shadcn-admin-users-v0

- 2026-02-15 00:34 PR opened: dashboard-ui-shadcn-admin-users-v0 -> https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/244

- 2026-02-15 00:45 activated dashboard-ui-shadcn-admin-users-v0

- 2026-02-15 00:47 autofill added dashboard-auth-email-login-ux-v0

- 2026-02-15 00:55 activated dashboard-ui-shadcn-admin-users-v0

- 2026-02-15 01:00 activated dashboard-ui-shadcn-admin-users-v0

- 2026-02-15 01:05 merged dashboard-ui-shadcn-admin-users-v0 :: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/244
