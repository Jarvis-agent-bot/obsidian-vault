# DAA Tasks

## Now
- [ ] (auto) NOW: funds-hub-price-input-v0 :: Funds hub price input v0：为 symbols 提供手动输入/粘贴价格快照，并持久化

## Backlog

Planning note: priority = top to bottom. Keep each task ~1 PR.

Funds hub epic (human note): make `/daa/market/funds` the primary hub and expose the shortest workflow path.


Dynamic rebalancing core (main objective)

- [ ] funds-hub-price-input-v0 :: Funds hub price input v0：为 symbols 提供手动输入/粘贴价格快照，并持久化
- [ ] funds-hub-rebalance-run-paper-v0 :: Funds hub rebalance run (paper) v0：trigger policy→orders→record execution log→更新 portfolioState.lastRebalance


## Done

- [x] funds-hub-workflow-checklist-v0 :: Funds hub checklist v0：DAA Workflow 面板（Checklist + Jump actions） (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/102)

- [x] funds-hub-workflow-export-v0 :: Funds hub export v0：一键导出 Step2/4/5/6/7 bundle JSON (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/103)

- [x] funds-hub-workflow-import-v0 :: Funds hub import v0：粘贴 bundle JSON → restore 状态（带校验/错误提示） (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/99)

- [x] funds-hub-step1-entry-v0 :: Funds hub Step1 v0：提供回测入口 + 当前策略/结果摘要回写 (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/104)

- [x] rebalance-engine-core-v0 :: 动态再平衡核心 v0：输入(当前持仓/价格/目标权重)→输出(orders/target weights) + 可复制 JSON (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/105)

- [x] portfolio-state-store-v0 :: 投资组合状态存储 v0：positions/cash/lastRebalance + schema versioning (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/106)

- [x] rebalance-threshold-policy-v0 :: 再平衡触发策略 v0：阈值/最小交易额/冷却时间（防抖） (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/107)

- [x] execution-adapter-paper-v0 :: 执行适配（paper）v0：把 orders 记录成 execution log（不真下单） (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/108)

- [x] funds-hub-rebalance-panel-v0 :: /daa/market/funds 增加 Rebalance 面板 v0：展示当前 vs 目标、偏离度、生成建议单 (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/109)

- [x] observability-rebalance-log-v0 :: 可观测性 v0：rebalancing log + 导出 bundle（用于复盘/追溯） (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/110)

- [x] backtest-drift-sim-v0 :: 漂移+再平衡回测 v0：给定历史价格→模拟执行→输出指标 (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/111)

- [x] funds-hub-portfolio-editor-v0 :: Funds hub portfolio editor v0：编辑 cash/positions（schemaVersioned），并能一键 copy JSON (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/112)
## Log

- 2026-02-12 11:11 activated funds-hub-integrate-steps-v0
- 2026-02-12 12:03 refined milestone granularity; switched active to funds-hub-workflow-checklist-v0

- 2026-02-12 12:20 DONE funds-hub-workflow-checklist-v0 merged: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/102

- 2026-02-12 12:26 activated funds-hub-workflow-export-v0

- 2026-02-12 12:34 DONE funds-hub-workflow-export-v0 — merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/103

- 2026-02-12 12:40 activated funds-hub-workflow-import-v0

- 2026-02-12 12:46 DONE funds-hub-workflow-import-v0 — merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/99 (SoT advanced: no next milestone)

- 2026-02-12 12:51 activated funds-hub-step1-entry-v0

- 2026-02-12 13:06 DONE: funds-hub-step1-entry-v0 :: Funds hub Step1 v0：提供回测入口 + 当前策略/结果摘要回写 — merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/104

- 2026-02-12 13:10 activated rebalance-engine-core-v0

- 2026-02-12 13:25 DONE rebalance-engine-core-v0 → merged PR #105: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/105

- 2026-02-12 13:31 activated portfolio-state-store-v0

- 2026-02-12 13:43 DONE: portfolio-state-store-v0 merged (#106)

- 2026-02-12 13:46 activated rebalance-threshold-policy-v0

- 2026-02-12 14:03 DONE rebalance-threshold-policy-v0: merged PR #107 (rebalance trigger policy threshold/minTrade/cooldown) — https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/107

- 2026-02-12 14:05 activated execution-adapter-paper-v0

- 2026-02-12 14:21 DONE: execution-adapter-paper-v0 merged (#108) — paper execution log (localStorage)

- 2026-02-12 14:26 activated funds-hub-rebalance-panel-v0

- 2026-02-12 14:38 DONE: funds-hub-rebalance-panel-v0 merged via PR #109

- 2026-02-12 14:50 activated observability-rebalance-log-v0

- 2026-02-12 15:46 DONE observability-rebalance-log-v0: merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/110 (CI: test/typecheck/build OK).

- 2026-02-12 15:51 activated backtest-drift-sim-v0

- 2026-02-12 16:02 DONE: backtest-drift-sim-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/111

- 2026-02-12 16:23 activated funds-hub-portfolio-editor-v0

- 2026-02-12 16:36 DONE: funds-hub-portfolio-editor-v0 merged → https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/112

- 2026-02-12 16:40 activated funds-hub-price-input-v0
