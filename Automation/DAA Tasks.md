# DAA Tasks

## Now
- [ ] (auto) Nothing active

## Backlog

Planning note: priority = top to bottom. Keep each task ~1 PR.

Mainline (2026-02-14): UI refactor first — adopt shadcn for /daa/login + /daa/dashboard, and simplify auth UX to “email login”.






























## Done

- [x] dashboard-ui-shadcn-admin-users-v0 :: Dashboard: refactor Admin Users table/drawer UI to shadcn (search/sort/status filters) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/244)

- [x] auth-email-login-v0 :: Auth: treat username as email (UI labels, basic validation, normalize lower-case); keep server contract minimal (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/245)

- [x] auth-bootstrap-first-admin-v0 :: Auth/Deploy: enable one-time bootstrap for first admin on fresh prod deploy without legacy bearer tokens (guarded) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/246)

- [x] ui-shadcn-daa-login-form-v0 :: shadcn: refactor /daa/login form + validation states (loading/error) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/247)

- [x] dashboard-ui-shadcn-session-banner-v0 :: dashboard UI: add shadcn session banner (who am I + logout) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/248)

- [x] dashboard-auth-email-login-ux-v0 :: Dashboard/Auth: polish email login UX (loading, inline errors, resend hint, better empty states) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/249)

- [x] dashboard-ui-shadcn-admin-users-v0-v4 :: Dashboard: refactor Admin Users table/drawer UI to shadcn (search/sort/status filters) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/244)

- [x] dashboard-ui-shadcn-audit-log-table-v0 :: Shadcn table for audit log on /daa/dashboard (filters + pagination parity) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/250)

- [x] dashboard-ui-shadcn-audit-log-table-v0-v2 :: Shadcn table for audit log on /daa/dashboard (filters + pagination parity) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/251)

- [x] dashboard-ui-shadcn-audit-log-table-v0-v3 :: Shadcn table for audit log on /daa/dashboard (filters + pagination parity) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/252)

- [x] auth-email-login-loading-and-errors-v0 :: Polish email login UX: loading state + inline error copy (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/253)

- [x] dashboard-ui-shadcn-dashboard-skeleton-v0 :: shadcn: /daa/dashboard loading skeleton + empty/error states (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/254)

- [x] ui-shadcn-daa-login-form-validation-v0 :: DAA login (shadcn): add inline validation + disable submit while invalid (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/255)

- [x] dashboard-ui-shadcn-dashboard-empty-error-states-v0 :: DAA dashboard (shadcn): add empty/error states + retry CTA for key panels (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/256)

- [x] auth-email-login-success-state-v0 :: Email login: show success + resend state after request (check inbox, resend link)

- [x] auth-email-login-success-state-v0-v2 :: Email login: show success + resend state after request (check inbox, resend link) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/258)

- [x] ui-shadcn-daa-login-layout-v0 :: shadcn: /daa/login layout polish (header, spacing, responsive) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/259)

- [x] dashboard-ui-shadcn-dashboard-nav-v0 :: shadcn: /daa/dashboard top nav (app title, user menu, logout) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/260)

- [x] auth-email-login-resend-link-v0 :: Auth (email login): add resend link + cooldown and clearer copy (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/261)

- [x] auth-email-login-check-inbox-helper-v0 :: Email login: add clear "check your inbox" helper + open-mail links (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/262)

- [x] dashboard-ui-shadcn-dashboard-overview-cards-v0 :: shadcn: /daa/dashboard overview cards (balance, status, last sync) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/263)

- [x] auth-email-login-expired-link-ux-v0 :: Auth: email login expired/invalid link state + retry CTA (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/264)

- [x] dashboard-ui-shadcn-dashboard-page-layout-v0 :: Dashboard: shadcn page layout (header, content width, spacing) for /daa/dashboard (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/266)

- [x] dashboard-ui-shadcn-dashboard-nav-active-state-v0 :: Dashboard: shadcn nav active state + keyboard focus ring polish (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/267)

- [x] dashboard-auth-session-expired-redirect-v0 :: Dashboard auth UX: when session expires, redirect to /daa/login with clear toast (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/268)

- [x] auth-email-login-rate-limit-message-v0 :: Email login: show clear message when requests are rate-limited (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/269)

- [x] dashboard-ui-shadcn-dashboard-breadcrumbs-v0-v5 :: Dashboard: add page title + breadcrumbs (shadcn) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/270)

- [x] dashboard-ui-shadcn-dashboard-breadcrumbs-v0 :: Dashboard: add page title + breadcrumbs (shadcn) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/270)

- [x] dashboard-ui-shadcn-dashboard-account-menu-v0 :: Add shadcn account menu (profile + sign out) on /daa/dashboard (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/271)

- [x] dashboard-ui-shadcn-dashboard-nav-icons-v0 :: Dashboard: shadcn nav icons + spacing polish (align with active state) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/272)

- [x] auth-email-login-magic-link-invalid-token-v0-v2 :: Auth: email magic-link invalid/used token screen with retry + resend CTA (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/273)

- [x] ui-shadcn-daa-login-help-links-v0 :: shadcn /daa/login: add helper links + copy (privacy/terms + support) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/274)

- [x] dashboard-ui-shadcn-dashboard-mobile-nav-v0 :: shadcn /daa/dashboard: mobile nav + responsive sidebar behavior (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/275)

- [x] dashboard-ui-shadcn-dashboard-shell-component-v0 :: Dashboard UI (shadcn): extract reusable DashboardShell (sidebar + topbar + content) for /daa/dashboard (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/276)

- [x] auth-email-login-preserve-email-v0 :: Auth UX: preserve entered email across resend/refresh during email login (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/277)
## Log

- 2026-02-15 03:29 PR opened: dashboard-ui-shadcn-audit-log-table-v0-v3 -> https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/252
- 2026-02-15 03:29 board repair: de-dupe key (v0 already merged in #250) -> v0-v3
- 2026-02-15 01:25 DONE: auth-email-login-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/245 (closed duplicate activation that created auth-email-login-v0-v2)
- 2026-02-15 01:30 activated auth-bootstrap-first-admin-v0
- 2026-02-15 01:40 PR opened: auth-bootstrap-first-admin-v0 -> https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/246
- 2026-02-15 01:41 DONE: auth-bootstrap-first-admin-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/246
- 2026-02-15 01:42 autofill added dashboard-ui-shadcn-audit-log-table-v0
- 2026-02-15 01:42 autofill added auth-email-login-loading-and-errors-v0
- 2026-02-15 01:45 activated ui-shadcn-daa-login-form-v0
- 2026-02-15 01:54 autofill added dashboard-ui-shadcn-dashboard-skeleton-v0
- 2026-02-15 01:55 activated dashboard-ui-shadcn-session-banner-v0
- 2026-02-15 02:10 activated dashboard-auth-email-login-ux-v0
- 2026-02-15 02:23 merged dashboard-auth-email-login-ux-v0 (#249)
- 2026-02-15 02:26 autofill added ui-shadcn-daa-login-form-validation-v0
- 2026-02-15 02:26 autofill added dashboard-ui-shadcn-dashboard-empty-error-states-v0
- 2026-02-15 02:30 activated dashboard-ui-shadcn-admin-users-v0-v4
- 2026-02-15 02:35 activated dashboard-ui-shadcn-admin-users-v0-v4
- 2026-02-15 02:37 activated dashboard-ui-shadcn-admin-users-v0-v4
- 2026-02-15 02:40 activated dashboard-ui-shadcn-audit-log-table-v0
- 2026-02-15 02:59 autofill added auth-email-login-success-state-v0
- 2026-02-15 03:00 activated dashboard-ui-shadcn-audit-log-table-v0
- 2026-02-15 03:15 DONE: dashboard-ui-shadcn-audit-log-table-v0-v2 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/251; SoT advanced -> none


- 2026-02-15 03:20 activated dashboard-ui-shadcn-audit-log-table-v0

- 2026-02-15 03:30 DONE: dashboard-ui-shadcn-audit-log-table-v0-v3 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/252; SoT advanced -> none

- 2026-02-15 03:35 activated auth-email-login-loading-and-errors-v0

- 2026-02-15 03:43 merged (squash) auth-email-login-loading-and-errors-v0 — https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/253

- 2026-02-15 03:45 activated dashboard-ui-shadcn-dashboard-skeleton-v0

- 2026-02-15 03:55 Merged: dashboard-ui-shadcn-dashboard-skeleton-v0 -> https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/254

- 2026-02-15 03:56 autofill added ui-shadcn-daa-login-layout-v0

- 2026-02-15 03:56 autofill added dashboard-ui-shadcn-dashboard-nav-v0

- 2026-02-15 04:00 activated ui-shadcn-daa-login-form-validation-v0

- 2026-02-15 04:08 activated ui-shadcn-daa-login-form-validation-v0

- 2026-02-15 04:09 autofill added auth-email-login-resend-link-v0

- 2026-02-15 04:21 DONE: ui-shadcn-daa-login-form-validation-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/255; SoT was stuck on ui-shadcn-daa-login-form-validation-v0-v2

- 2026-02-15 04:21 activated dashboard-ui-shadcn-dashboard-empty-error-states-v0

- 2026-02-15 04:39 PR opened: dashboard-ui-shadcn-dashboard-empty-error-states-v0 -> https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/256

- 2026-02-15 04:41 activated dashboard-ui-shadcn-dashboard-empty-error-states-v0

- 2026-02-15 04:41 DONE: dashboard-ui-shadcn-dashboard-empty-error-states-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/256

- 2026-02-15 04:42 activated auth-email-login-success-state-v0

- 2026-02-15 05:05 activated auth-email-login-success-state-v0

- 2026-02-15 05:16 PR opened: auth-email-login-success-state-v0-v2 -> https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/258

- 2026-02-15 05:18 DONE: auth-email-login-success-state-v0-v2 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/258; SoT advanced -> none

- 2026-02-15 05:20 activated ui-shadcn-daa-login-layout-v0

- 2026-02-15 05:28 Merged: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/259 — ui: polish /daa/login layout (shadcn)

- 2026-02-15 05:30 activated dashboard-ui-shadcn-dashboard-nav-v0

- 2026-02-15 05:38 PR opened: dashboard-ui-shadcn-dashboard-nav-v0 -> https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/260

- 2026-02-15 05:39 DONE: dashboard-ui-shadcn-dashboard-nav-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/260; SoT advanced -> none

- 2026-02-15 05:40 autofill added auth-email-login-check-inbox-helper-v0

- 2026-02-15 05:40 autofill added dashboard-ui-shadcn-dashboard-overview-cards-v0

- 2026-02-15 05:45 activated auth-email-login-resend-link-v0

- 2026-02-15 05:53 PR opened: auth-email-login-resend-link-v0 -> https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/261

- 2026-02-15 05:54 DONE: auth-email-login-resend-link-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/261; SoT advanced -> none

- 2026-02-15 05:55 autofill added auth-email-login-expired-link-ux-v0

- 2026-02-15 05:55 autofill added dashboard-ui-shadcn-dashboard-page-layout-v0

- 2026-02-15 06:00 activated auth-email-login-check-inbox-helper-v0

- 2026-02-15 06:10 Merged auth-email-login-check-inbox-helper-v0 via PR #262: add subject hint + open-mail links in email-link login flow.

- 2026-02-15 06:11 autofill added dashboard-ui-shadcn-dashboard-nav-active-state-v0

- 2026-02-15 06:11 autofill added dashboard-auth-session-expired-redirect-v0

- 2026-02-15 06:15 activated dashboard-ui-shadcn-dashboard-overview-cards-v0

- 2026-02-15 06:24 opened PR #263

- 2026-02-15 06:25 merged PR #263; advanced SoT

- 2026-02-15 06:26 autofill added auth-email-login-rate-limit-message-v0

- 2026-02-15 06:26 autofill added dashboard-ui-shadcn-dashboard-breadcrumbs-v0

- 2026-02-15 06:30 activated auth-email-login-expired-link-ux-v0

- 2026-02-15 06:39 PR created for auth-email-login-expired-link-ux-v0: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/264

- 2026-02-15 06:43 merged auth-email-login-expired-link-ux-v0: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/264 (SoT advanced)

- 2026-02-15 06:46 hotfix merged: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/265 (fix /daa/dashboard build compile error)

- 2026-02-15 06:47 autofill added dashboard-ui-shadcn-dashboard-account-menu-v0

- 2026-02-15 06:50 activated dashboard-ui-shadcn-dashboard-page-layout-v0

- 2026-02-15 07:12 merged dashboard-ui-shadcn-dashboard-page-layout-v0 (PR #266)

- 2026-02-15 07:15 activated dashboard-ui-shadcn-dashboard-nav-active-state-v0

- 2026-02-15 07:23 autofill added dashboard-ui-shadcn-dashboard-nav-icons-v0

- 2026-02-15 07:23 autofill added auth-email-login-magic-link-invalid-token-v0

- 2026-02-15 07:25 activated dashboard-auth-session-expired-redirect-v0

- 2026-02-15 07:39 PR opened: dashboard-auth-session-expired-redirect-v0 -> https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/268

- 2026-02-15 07:39 DONE: dashboard-auth-session-expired-redirect-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/268; SoT advanced -> none

- 2026-02-15 07:45 activated auth-email-login-rate-limit-message-v0

- 2026-02-15 07:54 DONE: auth-email-login-rate-limit-message-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/269; SoT advanced -> none

- 2026-02-15 07:55 autofill added ui-shadcn-daa-login-help-links-v0

- 2026-02-15 07:55 autofill added dashboard-ui-shadcn-dashboard-mobile-nav-v0

- 2026-02-15 08:00 activated dashboard-ui-shadcn-dashboard-breadcrumbs-v0

- 2026-02-15 08:10 activated dashboard-ui-shadcn-dashboard-breadcrumbs-v0

- 2026-02-15 08:15 activated dashboard-ui-shadcn-dashboard-breadcrumbs-v0

- 2026-02-15 08:20 activated dashboard-ui-shadcn-dashboard-breadcrumbs-v0

- 2026-02-15 08:25 activated dashboard-ui-shadcn-dashboard-breadcrumbs-v0

- 2026-02-15 08:29 Merged: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/270

- 2026-02-15 08:35 activated dashboard-ui-shadcn-dashboard-breadcrumbs-v0

- 2026-02-15 08:37 activated dashboard-ui-shadcn-dashboard-breadcrumbs-v0

- 2026-02-15 08:38 activated dashboard-ui-shadcn-dashboard-account-menu-v0

- 2026-02-15 08:44 activated dashboard-ui-shadcn-dashboard-nav-icons-v0

- 2026-02-15 08:50 PR opened: dashboard-ui-shadcn-dashboard-nav-icons-v0 -> https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/272

- 2026-02-15 08:51 DONE: dashboard-ui-shadcn-dashboard-nav-icons-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/272; SoT advanced -> none

- 2026-02-15 08:52 autofill added dashboard-ui-shadcn-dashboard-shell-component-v0

- 2026-02-15 08:52 autofill added auth-email-login-preserve-email-v0

- 2026-02-15 08:55 activated auth-email-login-magic-link-invalid-token-v0

- 2026-02-15 09:10 activated auth-email-login-magic-link-invalid-token-v0

- 2026-02-15 09:15 DONE: auth-email-login-magic-link-invalid-token-v0-v2 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/273

- 2026-02-15 09:16 activated ui-shadcn-daa-login-help-links-v0

- 2026-02-15 09:21 DONE: ui-shadcn-daa-login-help-links-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/274

- 2026-02-15 09:21 activated dashboard-ui-shadcn-dashboard-mobile-nav-v0

- 2026-02-15 09:34 PR created: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/275

- 2026-02-15 09:35 merged: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/275

- 2026-02-15 09:40 activated dashboard-ui-shadcn-dashboard-shell-component-v0

- 2026-02-15 09:51 DONE: dashboard-ui-shadcn-dashboard-shell-component-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/276

- 2026-02-15 09:55 activated auth-email-login-preserve-email-v0

- 2026-02-15 10:04 opened PR #277
