# DAA Dashboard Admin Plan (No-iframe; shadcn/ui; SQLite)

更新时间：2026-02-14

## Decision
- Canonical entry: `/daa/dashboard` (唯一入口)
- Old routes: redirect to `/daa/dashboard?tab=...`
- UI: 渐进式迁移到 shadcn/ui（不使用 iframe）；旧页面代码可暂留但不再作为入口
- Storage: 最小后端存储（SQLite）用于 runs/portfolio/confirm/executed/audit

## Phase A (Shell)
- Add Dashboard shell with tabs:
  - Overview
  - Portfolio
  - Market Events
  - Money Plan
  - Recommendation (Baseline)
  - AI Analysis
  - Confirm/Executed
  - History/Audit

## Phase B (Backend)
- SQLite DB + minimal API (server-side only)
- Auth: `DAA_ADMIN_TOKEN` (bearer) for write operations (and optionally read)
- Tables (minimal):
  - `daa_runs` (metadata + json blobs)
  - `daa_portfolios` (current + snapshots)
  - `daa_job_runs` (cron health/backup logs)

## Phase C (Module migration)
- Move key logic from step/funds pages into dashboard modules (copy components; refactor to shared libs)
- Replace JSON textarea UX with real form/table UI; keep “Advanced JSON” collapsible view.

## Phase D (Route cleanup)
- Implement redirects:
  - `/daa` -> `/daa/dashboard`
  - `/daa/wizard` -> `/daa/dashboard`
  - `/daa?step=n` -> `/daa/dashboard?tab=...`
  - `/daa/step/n` -> `/daa/dashboard?tab=...`
  - `/daa/market/funds` -> `/daa/dashboard?tab=...` (or Overview)

## Open Questions
- Deploy target (VPS only?) and SQLite file path (e.g. `/var/lib/daa/daa.sqlite`)
- Multi-user vs single admin? (auth scope)
