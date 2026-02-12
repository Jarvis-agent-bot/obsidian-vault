# DAA Tasks

## Now
- [ ] (auto) NOW: funds-hub-workflow-checklist-v0 :: Funds hub workflow checklist

## Backlog

Planning note: priority = top to bottom. Keep each task ~1 PR.

Funds hub epic (human note): make `/daa/market/funds` the primary hub and expose the shortest workflow path.

- [ ] funds-hub-workflow-checklist-v0 :: Funds hub checklist v0：DAA Workflow 面板（Checklist + Jump actions）
- [ ] funds-hub-workflow-export-v0 :: Funds hub export v0：一键导出 Step2/4/5/6/7 bundle JSON
- [ ] funds-hub-workflow-import-v0 :: Funds hub import v0：粘贴 bundle JSON → restore 状态（带校验/错误提示）
- [ ] funds-hub-step1-entry-v0 :: Funds hub Step1 v0：提供回测入口 + 当前策略/结果摘要回写

Dynamic rebalancing core (main objective)

- [ ] rebalance-engine-core-v0 :: 动态再平衡核心 v0：输入(当前持仓/价格/目标权重)→输出(orders/target weights) + 可复制 JSON
- [ ] portfolio-state-store-v0 :: 投资组合状态存储 v0：positions/cash/lastRebalance + schema versioning
- [ ] rebalance-threshold-policy-v0 :: 再平衡触发策略 v0：阈值/最小交易额/冷却时间（防抖）
- [ ] execution-adapter-paper-v0 :: 执行适配（paper）v0：把 orders 记录成 execution log（不真下单）
- [ ] funds-hub-rebalance-panel-v0 :: /daa/market/funds 增加 Rebalance 面板 v0：展示当前 vs 目标、偏离度、生成建议单
- [ ] observability-rebalance-log-v0 :: 可观测性 v0：rebalancing log + 导出 bundle（用于复盘/追溯）
- [ ] backtest-drift-sim-v0 :: 漂移+再平衡回测 v0：给定历史价格→模拟执行→输出指标

## Done

## Log

- 2026-02-12 11:11 activated funds-hub-integrate-steps-v0
- 2026-02-12 12:03 refined milestone granularity; switched active to funds-hub-workflow-checklist-v0
