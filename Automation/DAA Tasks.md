# DAA Tasks

## Now
- [ ] (auto) NOW: <none> :: (idle)

## Backlog

Planning note: priority = top to bottom. Keep each task ~1 PR.

Funds hub epic (human note): make `/daa/market/funds` the primary hub and expose the shortest workflow path.


Dynamic rebalancing core (main objective)







































- [ ] funds-hub-rebalance-e2e-dynamic-rebalance-preview-timeline-v0 :: Funds Hub: Dynamic rebalance preview timeline (drift over time + trigger points)

- [ ] funds-hub-rebalance-e2e-target-allocation-import-json-v0 :: Funds hub: import target allocation (JSON) into rebalance E2E

- [ ] funds-hub-rebalance-e2e-rebalance-plan-compare-scenarios-v0 :: Funds hub: compare two rebalance plan scenarios (dynamic rebalancing)
## Done

- [x] rebalance-orders-review-v0 :: Orders review v0：把 orders 展成表格（side/notional/reason）+ 风险提示（cash不足/minTrade） (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/121)

- [x] rebalance-report-export-v0 :: Rebalance report export v0：导出最近一次 run 的 request/response/logs 为可下载 JSON（带 schemaVersion） (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/122)

- [x] backtest-policy-sweep-v0 :: Policy sweep v0：对 threshold/minTrade/cooldown 做参数扫描，输出指标对比（用于调参） (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/123)

- [x] execution-adapter-interface-v0 :: Execution adapter interface v0：抽象 paper vs real 执行接口；paper 作为默认实现 (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/124)

- [x] funds-hub-rebalance-whatif-preview-v0 :: Funds hub: rebalance what-if preview (fees/slippage + expected drift) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/125)

- [x] funds-hub-rebalance-e2e-smoke-v0 :: Funds hub: one-click rebalance E2E smoke (generate orders, review, export) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/126)

- [x] funds-hub-rebalance-preview :: Funds hub: show per-fund pre/post target weights for dynamic rebalancing preview (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/127)

- [x] funds-hub-rebalance-drift-badges :: Funds hub: add drift badges + quick filters (over/under target) for rebalancing (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/128)

- [x] funds-hub-rebalance-live-drift-alerts-v0 :: Funds hub: show live drift alerts during dynamic rebalance run (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/129)

- [x] funds-hub-rebalance-run-retry-ux-v0 :: Funds hub: add retry UX for failed dynamic rebalance run (keep context) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/130)

- [x] funds-hub-rebalance-run-summary-v0 :: Funds Hub: add post-run summary banner (filled vs target + next-step CTA) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/131)

- [x] funds-hub-rebalance-preview-turnover-v0 :: Funds Hub: show estimated turnover + fees/slippage in rebalance preview (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/132)

- [x] funds-hub-rebalance-run-cancel-ux-v0 :: Funds Hub: add cancel/abort flow for an in-progress rebalance run (UI + API) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/133)

- [x] funds-hub-rebalance-postrun-healthcheck-v0 :: Funds Hub: show post-run healthcheck (expected vs actual drift/turnover) with clear pass/fail (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/134)

- [x] funds-hub-rebalance-brokerage-fees-v0 :: Funds hub: show estimated brokerage fees + net impact in rebalance preview (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/135)

- [x] funds-hub-rebalance-execution-mode-toggle-v0 :: Funds hub: add execution mode toggle (paper vs live) to rebalance run flow (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/136)

- [x] funds-hub-rebalance-dry-run-mode-v0 :: Funds hub: add "Dry run" mode for rebalancing (no orders sent) with clear UI copy (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/137)

- [x] funds-hub-rebalance-e2e-dynamic-drift-v0 :: Dynamic rebalancing E2E: simulate price drift across steps and verify suggested trade set updates (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/138)

- [x] funds-hub-rebalance-e2e-cash-check-v0 :: Funds Hub: add pre-trade cash/settlement check + blocking warning in rebalance flow (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/139)

- [x] funds-hub-rebalance-e2e-auto-plan-v0 :: Funds Hub: one-click generate dynamic rebalance plan (drift -> orders) with preview diff (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/140)

- [x] funds-hub-rebalance-preview-slippage-sensitivity-v0 :: Funds Hub: add slippage/spread sensitivity toggle in rebalance preview (impact estimate) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/141)

- [x] funds-hub-rebalance-whatif-threshold-slider-v0 :: Funds Hub: drift-threshold what-if slider + instant recompute of proposed trades (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/142)

- [x] daa-fix-rebalance-core-route-404 :: Fix prod /api/daa/rebalance/core (currently 404) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/143)

- [x] daa-fix-market-digest-fetch-failed :: Fix /api/daa/analysis/market-digest (500 fetch failed) + make cron-ready (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/144)

- [x] daa-okx-crypto-data-ingest-v0 :: Crypto v0: integrate OKX market data (server-side) + normalize (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/145)

- [x] funds-hub-rebalance-preview-cash-buffer-rounding-v0 :: Funds Hub: rebalance preview includes cash buffer + rounding/lot-size impacts in diff (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/146)

- [x] funds-hub-rebalance-plan-min-trade-warnings-v0 :: Funds Hub: warn when rebalance plan produces trades below min size / precision (blockers + suggestions) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/147)

- [x] funds-hub-rebalance-preview-fee-estimate-v0 :: Funds Hub: show estimated total fees in Rebalance Preview (v0) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/148)

- [x] funds-hub-rebalance-e2e-sell-blocker-warnings-v0 :: Funds hub: surface sell-blocker warnings in rebalance plan (E2E, v0) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/149)

- [x] data-price-series-provider-yfinance-v0 :: Data layer: add yfinance price-series provider (US/HK ETFs/stocks) to replace mock (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/150)

- [x] data-step1-backtest-default-real-provider-v0 :: Step1 backtest: default to real price-series provider (yfinance for non-crypto; OKX for crypto), keep mock only as debug option (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/151)

- [x] data-step4-signals-from-real-series-v0 :: Step4 signals: replace makeMockSeries with real price-series fetch (provider selectable) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/152)

- [x] data-step2-market-events-auto-ingest-v0 :: Step2 market events: add one-click auto-ingest from server routes (Twitter/Xueqiu/Yahoo) into MarketEvent store (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/153)

- [x] funds-hub-rebalance-e2e-okx-sandbox-connect-v0 :: Funds hub: E2E OKX sandbox connect + balances check for dynamic rebalancing (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/154)

- [x] funds-hub-rebalance-e2e-order-rounding-cash-buffer-v0 :: Funds hub: E2E dynamic rebalance handles cash buffer + order rounding consistently (preview matches execution) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/155)

- [x] funds-hub-rebalance-e2e-portfolio-import-v0 :: Funds hub: E2E import portfolio holdings into rebalance flow (dynamic rebalancing) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/156)

- [x] funds-hub-rebalance-e2e-order-status-tracker-v0 :: Funds hub: show live order status + auto-refresh during rebalance run (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/157)

- [x] funds-hub-rebalance-e2e-rebalance-history-v0 :: Funds hub: persist and view rebalance run history (plan + executed trades) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/158)

- [x] funds-hub-rebalance-e2e-trade-rationale-panel-v0 :: Funds Hub Rebalance E2E: add trade rationale panel (why each trade) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/159)

- [x] funds-hub-rebalance-e2e-cash-sweep-to-target-v0 :: Funds Hub: E2E cash sweep to target cash buffer (one-click) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/160)

- [x] funds-hub-rebalance-e2e-min-order-size-handling-v0 :: Funds hub: E2E dynamic rebalance handles exchange min order size (split/skip) with clear UI warnings (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/161)

- [x] funds-hub-rebalance-e2e-allocation-diff-chart-v0 :: Funds hub: show pre-trade vs post-trade allocation diff chart in dynamic rebalance run summary (E2E) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/162)

- [x] funds-hub-rebalance-e2e-asset-level-order-breakdown-v0 :: Funds Hub: Rebalance run — show asset-level order breakdown (qty, est fee/slippage) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/163)

- [x] funds-hub-rebalance-e2e-drift-threshold-presets-v0 :: Funds hub: drift threshold presets for dynamic rebalancing (Conservative/Standard/Aggressive) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/164)

- [x] funds-hub-rebalance-e2e-constraint-violations-panel-v0 :: Funds hub: in dynamic rebalance E2E, show a clear constraint/validation violations panel (min trade, cash buffer, sell blockers) before execute (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/165)

- [x] funds-hub-rebalance-e2e-rebalance-run-share-link-v0 :: Funds hub: add share/copy link for a rebalance run summary (E2E) so results can be reviewed across sessions/devices (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/166)

- [x] funds-hub-rebalance-e2e-rebalance-plan-export-csv-v0 :: Funds Hub: Export rebalance plan to CSV (orders + allocations) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/167)
## Log

- 2026-02-12 16:02 DONE: backtest-drift-sim-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/111
- 2026-02-12 16:23 activated funds-hub-portfolio-editor-v0
- 2026-02-12 16:36 DONE: funds-hub-portfolio-editor-v0 merged → https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/112
- 2026-02-12 16:40 activated funds-hub-price-input-v0
- 2026-02-12 16:51 DONE: funds-hub-price-input-v0 merged via https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/113
- 2026-02-12 16:55 activated funds-hub-rebalance-run-paper-v0
- 2026-02-12 17:08 DONE funds-hub-rebalance-run-paper-v0: merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/114 (Market/Funds DAA Workflow → Rebalance v0 adds paper run button: core request→core endpoint→paper execution log + portfolioState.lastRebalance).
- 2026-02-12 17:56 activated funds-hub-target-weights-editor-v0
- 2026-02-12 18:08 DONE funds-hub-target-weights-editor-v0 merged: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/115
- 2026-02-12 18:15 activated funds-hub-rebalance-policy-editor-v0
- 2026-02-12 18:23 DONE: funds-hub-rebalance-policy-editor-v0 :: Funds hub policy 编辑 v0（threshold/minTradeNotional/cooldownSeconds 可配置并写入 core request） — merged PR #116 https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/116
- 2026-02-12 18:25 activated funds-hub-rebalance-log-view-v0
- 2026-02-12 18:34 DONE: funds-hub-rebalance-log-view-v0 merged → https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/117
- 2026-02-12 18:40 activated backtest-drift-ui-v0
- 2026-02-12 18:51 DONE: backtest-drift-ui-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/118
- 2026-02-12 20:10 activated funds-hub-shortest-path-v1
- 2026-02-12 20:25 DONE: funds-hub-shortest-path-v1 merged: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/119
- 2026-02-12 20:30 activated funds-hub-sample-scenario-v0
- 2026-02-12 20:42 DONE: funds-hub-sample-scenario-v0 merged via https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/120
- 2026-02-12 20:45 activated rebalance-orders-review-v0
- 2026-02-12 20:57 DONE: rebalance-orders-review-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/121
- 2026-02-12 21:00 activated rebalance-report-export-v0
- 2026-02-12 21:13 DONE: rebalance-report-export-v0 -> merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/122
- 2026-02-12 21:20 activated backtest-policy-sweep-v0
- 2026-02-12 21:53 DONE: backtest-policy-sweep-v0 :: Policy sweep v0（threshold/minTrade/cooldown 参数扫描） merged: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/123
- 2026-02-12 21:55 activated execution-adapter-interface-v0
- 2026-02-12 22:07 DONE execution-adapter-interface-v0 -> merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/124
- 2026-02-12 22:13 autofill added funds-hub-rebalance-whatif-preview-v0
- 2026-02-12 22:13 autofill added funds-hub-rebalance-e2e-smoke-v0
- 2026-02-12 22:15 activated funds-hub-rebalance-whatif-preview-v0
- 2026-02-12 22:36 DONE: funds-hub-rebalance-whatif-preview-v0 merged -> https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/125
- 2026-02-12 22:40 activated funds-hub-rebalance-e2e-smoke-v0
- 2026-02-12 22:49 DONE: funds-hub-rebalance-e2e-smoke-v0 merged (#126) https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/126
- 2026-02-13 00:14 autofill added funds-hub-rebalance-preview
- 2026-02-13 00:14 autofill added funds-hub-rebalance-drift-badges
- 2026-02-13 00:20 activated funds-hub-rebalance-preview
- 2026-02-13 00:34 DONE: funds-hub-rebalance-preview :: merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/127
- 2026-02-13 00:40 activated funds-hub-rebalance-drift-badges
- 2026-02-13 00:50 DONE: funds-hub-rebalance-drift-badges merged → https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/128
- 2026-02-13 02:12 autofill added funds-hub-rebalance-live-drift-alerts-v0
- 2026-02-13 02:12 autofill added funds-hub-rebalance-run-retry-ux-v0
- 2026-02-13 02:15 activated funds-hub-rebalance-live-drift-alerts-v0
- 2026-02-13 02:27 DONE: funds-hub-rebalance-live-drift-alerts-v0 :: merged PR #129 (live drift alerts during paper rebalance run). currentMilestoneKey cleared (no next queued).
- 2026-02-13 02:30 activated funds-hub-rebalance-run-retry-ux-v0
- 2026-02-13 02:41 DONE: funds-hub-rebalance-run-retry-ux-v0 :: Funds hub: add retry UX for failed dynamic rebalance run (keep context) :: merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/130
- 2026-02-13 04:12 autofill added funds-hub-rebalance-run-summary-v0
- 2026-02-13 04:12 autofill added funds-hub-rebalance-preview-turnover-v0
- 2026-02-13 04:15 activated funds-hub-rebalance-run-summary-v0
- 2026-02-13 04:28 DONE funds-hub-rebalance-run-summary-v0: merged PR #131 (post-run summary banner). SoT advanced; no next milestone queued.
- 2026-02-13 04:30 activated funds-hub-rebalance-preview-turnover-v0
- 2026-02-13 04:39 DONE: funds-hub-rebalance-preview-turnover-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/132
- 2026-02-13 06:12 autofill added funds-hub-rebalance-run-cancel-ux-v0
- 2026-02-13 06:12 autofill added funds-hub-rebalance-postrun-healthcheck-v0
- 2026-02-13 06:15 activated funds-hub-rebalance-run-cancel-ux-v0
- 2026-02-13 06:28 DONE: funds-hub-rebalance-run-cancel-ux-v0 :: merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/133
- 2026-02-13 06:30 activated funds-hub-rebalance-postrun-healthcheck-v0
- 2026-02-13 06:44 DONE: funds-hub-rebalance-postrun-healthcheck-v0 :: merged PR #134 (post-run healthcheck: expected vs actual drift/turnover)
- 2026-02-13 08:12 autofill added funds-hub-rebalance-brokerage-fees-v0
- 2026-02-13 08:12 autofill added funds-hub-rebalance-execution-mode-toggle-v0
- 2026-02-13 08:15 activated funds-hub-rebalance-brokerage-fees-v0
- 2026-02-13 08:25 DONE: funds-hub-rebalance-brokerage-fees-v0 merged (#135) https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/135
- 2026-02-13 08:30 activated funds-hub-rebalance-execution-mode-toggle-v0
- 2026-02-13 08:40 DONE: funds-hub-rebalance-execution-mode-toggle-v0 merged via PR #136 https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/136
- 2026-02-13 10:12 autofill added funds-hub-rebalance-dry-run-mode-v0
- 2026-02-13 10:12 autofill added funds-hub-rebalance-e2e-dynamic-drift-v0
- 2026-02-13 10:15 activated funds-hub-rebalance-dry-run-mode-v0
- 2026-02-13 10:31 DONE: funds-hub-rebalance-dry-run-mode-v0 merged via https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/137
- 2026-02-13 10:35 activated funds-hub-rebalance-e2e-dynamic-drift-v0
- 2026-02-13 10:41 DONE: funds-hub-rebalance-e2e-dynamic-drift-v0 :: Dynamic rebalancing E2E: simulate price drift across steps and verify suggested trade set updates (merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/138)
- 2026-02-13 12:01 autofill added funds-hub-rebalance-e2e-cash-check-v0
- 2026-02-13 12:01 autofill added funds-hub-rebalance-e2e-auto-plan-v0
- 2026-02-13 14:00 activated funds-hub-rebalance-e2e-cash-check-v0
- 2026-02-13 14:13 DONE: funds-hub-rebalance-e2e-cash-check-v0 :: merged PR #139 https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/139
- 2026-02-13 14:15 autofill added funds-hub-rebalance-preview-slippage-sensitivity-v0
- 2026-02-13 14:15 autofill added funds-hub-rebalance-whatif-threshold-slider-v0
- 2026-02-13 14:20 activated funds-hub-rebalance-e2e-auto-plan-v0
- 2026-02-13 14:44 smoke test report written: [[Automation/DAA System Smoke Test 2026-02-13]]
- 2026-02-13 14:50 DONE: funds-hub-rebalance-e2e-auto-plan-v0 :: merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/140
- 2026-02-13 14:51 autofill added funds-hub-rebalance-preview-cash-buffer-rounding-v0
- 2026-02-13 14:51 activated funds-hub-rebalance-preview-slippage-sensitivity-v0


- 2026-02-13 14:54 manual compact: keep_done=20 keep_log=80 movedDone=20 movedLog=22 (archived to Automation/DAA Tasks Archive.md)

- 2026-02-13 15:03 DONE: funds-hub-rebalance-preview-slippage-sensitivity-v0 :: merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/141

- 2026-02-13 15:03 autofill added funds-hub-rebalance-plan-min-trade-warnings-v0

- 2026-02-13 15:05 activated funds-hub-rebalance-whatif-threshold-slider-v0

- 2026-02-13 15:09 hard-trimmed archive: kept last 10 Done + 12 Log (backup created).

- 2026-02-13 15:21 DONE: funds-hub-rebalance-whatif-threshold-slider-v0 merged: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/142

- 2026-02-13 15:23 autofill added funds-hub-rebalance-preview-fee-estimate-v0

- 2026-02-13 15:25 activated daa-fix-rebalance-core-route-404

- 2026-02-13 15:33 DONE: daa-fix-rebalance-core-route-404 :: merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/143

- 2026-02-13 15:34 autofill added funds-hub-rebalance-e2e-sell-blocker-warnings-v0

- 2026-02-13 15:35 activated daa-fix-market-digest-fetch-failed

- 2026-02-13 15:45 DONE: daa-fix-market-digest-fetch-failed :: Fix /api/daa/analysis/market-digest (500 fetch failed) + make cron-ready :: merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/144

- 2026-02-13 15:47 autofill added funds-hub-rebalance-e2e-okx-sandbox-connect-v0

- 2026-02-13 15:47 prod verified after VPS deploy: POST /api/daa/rebalance/core returns 200 (was code/deploy mismatch, not nginx).

- 2026-02-13 15:50 activated daa-okx-crypto-data-ingest-v0

- 2026-02-13 16:03 DONE: daa-okx-crypto-data-ingest-v0 merged (#145) — OKX candles route + normalize + Step1 provider selector

- 2026-02-13 16:05 autofill added funds-hub-rebalance-e2e-order-rounding-cash-buffer-v0

- 2026-02-13 16:10 activated funds-hub-rebalance-preview-cash-buffer-rounding-v0

- 2026-02-13 16:22 ACK: yfinance approved by sheng cai; switched provider todo to data-price-series-provider-yfinance-v0; added Step1 default-real provider task

- 2026-02-13 16:28 DONE funds-hub-rebalance-preview-cash-buffer-rounding-v0 merged: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/146

- 2026-02-13 16:30 activated funds-hub-rebalance-plan-min-trade-warnings-v0

- 2026-02-13 16:51 DONE: funds-hub-rebalance-plan-min-trade-warnings-v0 merged via auto-merge PR#147

- 2026-02-13 16:55 activated funds-hub-rebalance-preview-fee-estimate-v0

- 2026-02-13 17:06 DONE: funds-hub-rebalance-preview-fee-estimate-v0 :: Funds Hub: show estimated total fees in Rebalance Preview (v0) — merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/148

- 2026-02-13 17:10 activated funds-hub-rebalance-e2e-sell-blocker-warnings-v0

- 2026-02-13 17:25 DONE: funds-hub-rebalance-e2e-sell-blocker-warnings-v0 merged via https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/149

- 2026-02-13 17:28 Priority bump: moved yfinance mock->real tasks to top and set NOW=data-price-series-provider-yfinance-v0 (requested by sheng cai)

- 2026-02-13 17:30 activated data-price-series-provider-yfinance-v0

- 2026-02-13 17:42 DONE: data-price-series-provider-yfinance-v0 merged via PR https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/150

- 2026-02-13 17:43 autofill added funds-hub-rebalance-e2e-portfolio-import-v0

- 2026-02-13 17:45 activated data-step1-backtest-default-real-provider-v0

- 2026-02-13 17:56 DONE: data-step1-backtest-default-real-provider-v0 merged via https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/151

- 2026-02-13 18:00 activated data-step4-signals-from-real-series-v0

- 2026-02-13 18:10 DONE data-step4-signals-from-real-series-v0 merged: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/152

- 2026-02-13 18:11 autofill added funds-hub-rebalance-e2e-order-status-tracker-v0

- 2026-02-13 18:11 autofill added funds-hub-rebalance-e2e-rebalance-history-v0

- 2026-02-13 18:15 activated data-step2-market-events-auto-ingest-v0

- 2026-02-13 18:26 DONE: data-step2-market-events-auto-ingest-v0 merged via PR #153 https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/153

- 2026-02-13 18:28 autofill added funds-hub-rebalance-e2e-trade-rationale-panel-v0

- 2026-02-13 18:30 activated funds-hub-rebalance-e2e-okx-sandbox-connect-v0

- 2026-02-13 18:42 DONE: funds-hub-rebalance-e2e-okx-sandbox-connect-v0 merged: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/154 (mergedAt=2026-02-13 18:41 Asia/Shanghai)

- 2026-02-13 18:43 autofill added funds-hub-rebalance-e2e-cash-sweep-to-target-v0

- 2026-02-13 18:45 activated funds-hub-rebalance-e2e-order-rounding-cash-buffer-v0

- 2026-02-13 18:57 DONE: funds-hub-rebalance-e2e-order-rounding-cash-buffer-v0 :: merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/155

- 2026-02-13 18:59 autofill added funds-hub-rebalance-e2e-min-order-size-handling-v0

- 2026-02-13 19:00 activated funds-hub-rebalance-e2e-portfolio-import-v0

- 2026-02-13 19:13 DONE: funds-hub-rebalance-e2e-portfolio-import-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/156

- 2026-02-13 19:14 autofill added funds-hub-rebalance-e2e-allocation-diff-chart-v0

- 2026-02-13 19:15 activated funds-hub-rebalance-e2e-order-status-tracker-v0

- 2026-02-13 19:27 DONE: funds-hub-rebalance-e2e-order-status-tracker-v0 :: merged PR #157 (Funds hub order status tracker v0)

- 2026-02-13 19:28 autofill added funds-hub-rebalance-e2e-asset-level-order-breakdown-v0

- 2026-02-13 19:30 activated funds-hub-rebalance-e2e-rebalance-history-v0

- 2026-02-13 19:49 DONE: funds-hub-rebalance-e2e-rebalance-history-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/158

- 2026-02-13 19:51 autofill added funds-hub-rebalance-e2e-drift-threshold-presets-v0

- 2026-02-13 19:55 activated funds-hub-rebalance-e2e-trade-rationale-panel-v0

- 2026-02-13 20:03 Merged funds-hub-rebalance-e2e-trade-rationale-panel-v0 (PR #159): trade rationale panel shipped; SoT advanced (no next milestone).

- 2026-02-13 20:05 activated funds-hub-rebalance-e2e-cash-sweep-to-target-v0

- 2026-02-13 20:19 DONE: funds-hub-rebalance-e2e-cash-sweep-to-target-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/160

- 2026-02-13 20:25 activated funds-hub-rebalance-e2e-min-order-size-handling-v0

- 2026-02-13 20:39 DONE: funds-hub-rebalance-e2e-min-order-size-handling-v0 :: Funds hub: E2E dynamic rebalance handles exchange min order size (split/skip) with clear UI warnings (merged: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/161)

- 2026-02-13 20:45 activated funds-hub-rebalance-e2e-allocation-diff-chart-v0

- 2026-02-13 20:54 DONE: funds-hub-rebalance-e2e-allocation-diff-chart-v0 merged via PR #162

- 2026-02-13 20:56 autofill added funds-hub-rebalance-e2e-constraint-violations-panel-v0

- 2026-02-13 20:56 autofill added funds-hub-rebalance-e2e-rebalance-run-share-link-v0

- 2026-02-13 21:00 activated funds-hub-rebalance-e2e-asset-level-order-breakdown-v0

- 2026-02-13 21:10 DONE: funds-hub-rebalance-e2e-asset-level-order-breakdown-v0 :: Funds Hub: Rebalance run — show asset-level order breakdown (qty, est fee/slippage) (merged: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/163)

- 2026-02-13 21:11 autofill added funds-hub-rebalance-e2e-rebalance-plan-export-csv-v0

- 2026-02-13 21:11 autofill added funds-hub-rebalance-e2e-dynamic-rebalance-preview-timeline-v0

- 2026-02-13 21:15 activated funds-hub-rebalance-e2e-drift-threshold-presets-v0

- 2026-02-13 21:21 DONE: funds-hub-rebalance-e2e-drift-threshold-presets-v0 merged (#164) — drift threshold presets (Conservative/Standard/Aggressive)

- 2026-02-13 21:23 autofill added funds-hub-rebalance-e2e-target-allocation-import-json-v0

- 2026-02-13 21:23 autofill added funds-hub-rebalance-e2e-rebalance-plan-compare-scenarios-v0

- 2026-02-13 21:25 activated funds-hub-rebalance-e2e-constraint-violations-panel-v0

- 2026-02-13 21:37 DONE: funds-hub-rebalance-e2e-constraint-violations-panel-v0 :: merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/165 (2026-02-13 21:35 Asia/Shanghai)

- 2026-02-13 21:40 activated funds-hub-rebalance-e2e-rebalance-run-share-link-v0

- 2026-02-13 21:50 DONE: funds-hub-rebalance-e2e-rebalance-run-share-link-v0 :: merged PR #166 https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/166

- 2026-02-13 21:55 activated funds-hub-rebalance-e2e-rebalance-plan-export-csv-v0

- 2026-02-13 22:05 DONE: funds-hub-rebalance-e2e-rebalance-plan-export-csv-v0 :: Export rebalance plan to CSV (orders + allocations) — merged PR #167 https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/167
