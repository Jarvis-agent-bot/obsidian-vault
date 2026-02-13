# DAA Tasks Archive

## Done


## Done

- [x] backtest-drift-sim-v0 :: 漂移+再平衡回测 v0：给定历史价格→模拟执行→输出指标 (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/111)
- [x] funds-hub-portfolio-editor-v0 :: Funds hub portfolio editor v0：编辑 cash/positions（schemaVersioned），并能一键 copy JSON (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/112)
- [x] funds-hub-price-input-v0 :: Funds hub price input v0：为 symbols 提供手动输入/粘贴价格快照，并持久化 (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/113)
- [x] funds-hub-rebalance-run-paper-v0 :: Funds hub rebalance run (paper) v0：trigger policy→orders→record execution log→更新 portfolioState.lastRebalance (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/114)
- [x] funds-hub-target-weights-editor-v0 :: Funds hub 目标权重编辑 v0：手工编辑/粘贴 targetWeights 并持久化；paper rebalance 优先使用该输入 (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/115)
- [x] funds-hub-rebalance-policy-editor-v0 :: Funds hub policy 编辑 v0：阈值/最小交易额/冷却时间（防抖）可配置，并写入 core request (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/116)
- [x] funds-hub-rebalance-log-view-v0 :: Funds hub log view v0：展示最近 N 次 paper rebalance（trigger/weights/orders）并支持 copy/export (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/117)
- [x] backtest-drift-ui-v0 :: 回测 UI v0：粘贴价格序列/价格快照 → drift+rebalance simulator → 输出指标摘要（用于复盘/调参） (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/118)
- [x] funds-hub-shortest-path-v1 :: Funds hub 最短路径 v1：默认展开 DAA Workflow；顶部给出“下一步”+一键跳转；错误提示一致 (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/119)
- [x] funds-hub-sample-scenario-v0 :: Funds hub demo v0：一键填充 sample portfolio/weights/prices（用于演示+回归） (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/120)

## Log

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
