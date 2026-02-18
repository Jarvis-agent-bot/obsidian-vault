# DAA Jobs Plan (Active; Guardrails)

更新时间：2026-02-18

目标：让项目按 DAA 主线自动推进，同时做到：推进不跑偏、失败可见、尽量不刷屏。

## 当前启用的 jobs（已精简）

### A) Autopilot 主线推进
1) `daa-autopilot-cycle-15min` (every 15min)
- Run: `scripts/daa_workflow_cycle_runner.py`
- Includes: planner tick + backlog guard + auto-merge + advance + re-activate
- Output: 成功静默；异常或等待输出 1 行
- Side effects: 更新 SoT + Obsidian

### B) Ops / Observability
2) `daa-ops-review-digest-6h` (every 6h)
- Run: `scripts/daa_review_digest.py`
- Output: 仅当需要时输出摘要（含 healthcheck 结果）

3) `daa-ops-deploy-daily-10am` (daily 10:00)
- Run: `scripts/daa_vps_deploy_daa_daily_silent.sh`
- Output: 成功静默；失败 1 行

### C) 内容与状态维护
4) `obsidian-vault-git-sync-hourly` (hourly)
- Effect: Obsidian vault 有变更时 commit + pull(rebase) + push
- Output: 无变更静默；push 成功 1 行；失败 1 行

5) `todo-watcher-scan-30min` (every 30min)
- Run: `scripts/todo_watcher.py --mode scan`
- Output: 仅当逾期或即将到期时通知

6) `daa-ops-maintenance-daily` (daily)
- Run: `scripts/obsidian_board_compact_silent.sh` + `scripts/cron_sessions_gc.py --keep-per-job 12` + `scripts/session_store_compact.py --apply --prune-missing-refs --quiet-if-noop` + `scripts/daa_sqlite_backup_vps.sh`
- Output: 仅在清理发生时输出（maintenance 本身默认静默）

## 明确保持移除的 jobs
- 独立 backlog guard job：已合并进 cycle
- Legacy workflow cycle：已移除

## 状态说明
- SoT 以 `memory/automation-state.json` 为准
- 若 currentMilestoneKey 为空，cycle 会通过 planner 自动激活 Backlog 首项
