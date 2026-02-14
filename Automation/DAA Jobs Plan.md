# DAA Jobs Plan (Active; Guardrails)

更新时间：2026-02-14

目标：让项目“按 /daa/dashboard + SQLite 主线推进”，同时用 jobs 做到：推进不跑偏、失败可见、尽量不刷屏。

## 当前启用的 jobs（已优化：清理 legacy；compact 只报错；planner 合并进 cycle；cycle 增加自愈 rebase）

### A) Ops / Observability

1) `daa-admin-healthcheck-hourly` (hourly)
- Run: `scripts/daa_admin_healthcheck.py`
- Check: engine-health / Twitter token-info / 雪球 quotec / `/daa/dashboard` HTTP 200
- Output: 成功静默；失败 1 行 TG 告警
- Side effects: 无（只读）

2) `daa-sqlite-backup-daily` (daily)
- Run: `scripts/daa_sqlite_backup_vps.sh`
- Effect: 备份 VPS `/var/lib/daa/daa.sqlite` → `/var/lib/daa/backups/daa.sqlite.<timestamp>.bak`
- Output: 成功静默；失败 1 行 TG 告警
- Notes: 目前不做 rotate/delete（避免误删）；后续确认保留策略再加

### B) Mainline推进（受控自动化）

3) `daa-workflow-cycle-ci-5min-v2` (every 5min)
- Effect: 对当前 active milestone 创建/跟踪 PR（1 milestone = 1 PR），并更新 Obsidian（NOW/PR/done/log）
- Planner: 已合并进 cycle（cycle 会在发现无 inflight 时，自动从 Backlog 激活下一条；planner runner: `scripts/obsidian_planner_tick_silent.sh`，只在失败时告警）
- Planner state repair: 修复 SoT 里“存在 queued/active milestone 但 currentMilestoneKey=null”这种卡死状态（会自动补齐 currentMilestoneKey 并保证只有 1 个 active）
- Auto-merge policy: 全部任务开启 GitHub auto-merge（CI 通过后自动合并）
- Self-heal: 遇到“merge commit cannot be cleanly created / not mergeable”类问题，会自动 rebase 分支到 main 并重试
- Hard rules:
  - `/daa/dashboard` 是唯一入口；旧 `/daa*` 路由只做 redirect
  - 永不自动执行交易（AI 只能产出 draft，人工确认+手动执行）

### C) 内容维护

5) `daa-obsidian-board-compact-daily` (daily)
- Effect: 压缩 Obsidian `Automation/DAA Tasks.md`（保留最近 done/log；其余归档）
- Output: 成功静默；失败 1 行 TG 告警（避免“静默失败”）

6) `obsidian-vault-git-sync-hourly` (hourly)
- Effect: Obsidian vault 有变更时自动 commit+pull(rebase)+push
- Output: 无变更静默；push 成功打印 1 行 `vault pushed: <sha>`；失败 1 行错误
- Note: 这是对外写操作（push），仅在你明确同意后启用

## 明确保持禁用/移除的 jobs（避免跑偏/刷屏）
- Backlog autofill：保持禁用（避免自动加任务导致主线漂移；必要时手动打开做一次补充）
- Legacy stuck-running workflow-cycle：已移除（避免两套 cycle 打架）
- 独立 planner job：已移除（planner 已合并进 cycle，减少并发修改 SoT/Obsidian 的概率）

## 本次启动时的里程碑状态
- SoT 已激活：`dashboard-route-redirect-cleanup-v0`
- 下一步：workflow-cycle 将在下一次 tick 创建对应 PR 并开始推进
