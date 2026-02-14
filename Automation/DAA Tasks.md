# DAA Tasks

## Now
- [ ] (auto) NOW: backend-sqlite-daa-migrations-v0 :: SQLite: add schema_migrations table + boot-time migration runner w/ audit log

## Backlog

Planning note: priority = top to bottom. Keep each task ~1 PR.

Mainline (2026-02-14): Make /daa/dashboard the ONLY entry and turn it into a real admin console (no JSON-first UX).









- [ ] backend-sqlite-daa-migrations-v0 :: SQLite: add schema_migrations table + boot-time migration runner w/ audit log

- [ ] api-daa-admin-users-readonly-v0 :: Admin API: add read-only endpoint to list admin users + roles for dashboard

- [ ] backend-sqlite-daa-audit-events-table-v0 :: SQLite: add audit_events table + write path for DAA admin actions

- [ ] dashboard-daa-audit-log-export-csv-v0 :: Dashboard: add CSV export button for DAA audit log table

- [ ] dashboard-daa-audit-log-row-details-modal-v0 :: DAA dashboard: audit log row details modal (expand payload + metadata)

- [ ] dashboard-daa-admin-users-detail-drawer-v0 :: DAA admin dashboard: add user detail drawer (roles, status, last login)
## Done

- [x] funds-hub-rebalance-e2e-dynamic-rebalance-run-audit-log-download-csv-v0 :: Funds hub: add audit log download (CSV) for dynamic rebalance run (E2E) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/212)

- [x] funds-hub-rebalance-e2e-dynamic-rebalance-run-notes-and-tags-v0 :: Funds hub: allow adding notes + tags to a dynamic rebalance run (E2E) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/213)

- [x] dashboard-route-redirect-cleanup-v0 :: Routes: redirect /daa,/daa?step=*,/daa/step/*,/daa/wizard,/daa/market/funds -> /daa/dashboard?tab=... (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/214)

- [x] backend-sqlite-daa-store-v0 :: Backend: add SQLite storage (runs/portfolio/confirm/executed/audit) + migrations (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/215)

- [x] api-daa-admin-auth-v0 :: API: add DAA_ADMIN_TOKEN auth (bearer) for write endpoints; keep read minimal (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/216)

- [x] dashboard-portfolio-confirm-executed-v0 :: Dashboard: Confirm/Executed flow + auto-update portfolio_state using latest price snapshot (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/217)

- [x] dashboard-history-audit-v0 :: Dashboard: history/audit list (runs, AI text, confirmed/executed, before/after portfolio) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/218)

- [x] dashboard-market-events-module-v0 :: Dashboard: Market Events module (twitter/yfinance/xueqiu fetch+filter) with non-JSON-first UI (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/219)

- [x] dashboard-daa-audit-log-filters-v0-v3 :: Dashboard: add audit log filters (date range + actor) for DAA activity (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/221)

- [x] dashboard-daa-audit-log-filters-v0 :: Dashboard: add audit log filters (date range + actor) for DAA activity (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/221)

- [x] fix-build-dashboard-historyaudit-selected-v0 :: Fix build: DaaDashboardHistoryAudit selected must be boolean (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/223)

- [x] api-daa-admin-authz-roles-v0 :: Admin/API: enforce role-based access for DAA admin endpoints (viewer vs editor) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/222)
## Log

- 2026-02-14 13:40 activated dashboard-route-redirect-cleanup-v0
- 2026-02-14 13:54 dashboard-route-redirect-cleanup-v0: Opened PR https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/214
- 2026-02-14 13:55 dashboard-route-redirect-cleanup-v0: MERGED PR #214
- 2026-02-14 14:00 activated backend-sqlite-daa-store-v0
- 2026-02-14 14:13 PR opened for backend-sqlite-daa-store-v0: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/215
- 2026-02-14 14:37 DONE: dashboard-route-redirect-cleanup-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/214
- 2026-02-14 14:37 DONE: backend-sqlite-daa-store-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/215
- 2026-02-14 14:39 DONE backend-sqlite-daa-store-v0 merged: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/215 (SQLite store + migrations). SoT advanced to currentMilestoneKey=null (no next queued).
- 2026-02-14 14:48 activated api-daa-admin-auth-v0
- 2026-02-14 15:00 activated dashboard-portfolio-confirm-executed-v0
- 2026-02-14 15:35 activated dashboard-portfolio-confirm-executed-v0
- 2026-02-14 15:38 DONE: dashboard-portfolio-confirm-executed-v0 (SoT key dashboard-portfolio-confirm-executed-v0-v2) merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/217; SoT advanced -> none
- 2026-02-14 15:40 activated dashboard-history-audit-v0
- 2026-02-14 15:53 merged dashboard-history-audit-v0: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/218
- 2026-02-14 15:55 activated dashboard-market-events-module-v0
- 2026-02-14 16:07 dashboard-market-events-module-v0: Opened PR https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/219
- 2026-02-14 16:07 DONE: dashboard-market-events-module-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/219; SoT advanced -> none
- 2026-02-14 16:28 autofill added dashboard-daa-audit-log-filters-v0
- 2026-02-14 16:28 autofill added api-daa-admin-authz-roles-v0
- 2026-02-14 16:29 activated dashboard-daa-audit-log-filters-v0


- 2026-02-14 17:14 autofill added backend-sqlite-daa-migrations-v0

- 2026-02-14 17:14 autofill added api-daa-admin-users-readonly-v0

- 2026-02-14 17:15 activated dashboard-daa-audit-log-filters-v0

- 2026-02-14 17:29 autofill added backend-sqlite-daa-audit-events-table-v0

- 2026-02-14 17:29 autofill added dashboard-daa-audit-log-export-csv-v0

- 2026-02-14 17:30 activated dashboard-daa-audit-log-filters-v0

- 2026-02-14 17:34 merged+advanced: dashboard-daa-audit-log-filters-v0-v3 -> done (PR #221)

- 2026-02-14 17:40 activated dashboard-daa-audit-log-filters-v0

- 2026-02-14 17:46 self-heal: dedup active milestone dashboard-daa-audit-log-filters-v0-v4 (already merged as #221); advanced SoT -> none

- 2026-02-14 17:47 autofill added dashboard-daa-audit-log-row-details-modal-v0

- 2026-02-14 17:50 activated api-daa-admin-authz-roles-v0

- 2026-02-14 17:57 pr opened api-daa-admin-authz-roles-v0: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/222

- 2026-02-14 18:00 activated fix-build-dashboard-historyaudit-selected-v0

- 2026-02-14 18:02 pr opened fix-build-dashboard-historyaudit-selected-v0: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/223

- 2026-02-14 18:03 merged fix-build-dashboard-historyaudit-selected-v0

- 2026-02-14 18:03 merged api-daa-admin-authz-roles-v0

- 2026-02-14 18:04 autofill added dashboard-daa-admin-users-detail-drawer-v0

- 2026-02-14 18:05 activated backend-sqlite-daa-migrations-v0
