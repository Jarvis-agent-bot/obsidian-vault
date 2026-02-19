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

- [x] data-price-series-provider-yfinance-v0 :: Data layer: add yfinance price-series provider (US/HK ETFs/stocks) to replace mock (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/173)

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

- [x] funds-hub-rebalance-e2e-dynamic-rebalance-preview-timeline-v0 :: Funds Hub: Dynamic rebalance preview timeline (drift over time + trigger points) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/168)

- [x] funds-hub-rebalance-e2e-target-allocation-import-json-v0 :: Funds hub: import target allocation (JSON) into rebalance E2E (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/169)

- [x] funds-hub-rebalance-e2e-rebalance-plan-compare-scenarios-v0 :: Funds hub: compare two rebalance plan scenarios (dynamic rebalancing) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/170)

- [x] funds-hub-rebalance-e2e-asset-blacklist-v0 :: Funds hub: rebalance E2E support asset blacklist (exclude holdings + targets) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/171)

- [x] funds-hub-rebalance-e2e-sell-proceeds-routing-v0 :: Funds hub: rebalance E2E show & configure sell proceeds routing (cash vs target cash bucket) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/172)

- [x] funds-hub-rebalance-e2e-missing-price-data-warnings-v0 :: Funds hub: rebalance E2E show missing price data warnings + per-asset fallback (last close) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/174)

- [x] funds-hub-rebalance-e2e-cash-bucket-targets-v0 :: Funds hub: rebalance E2E add cash bucket targets (keep cash vs invest) with preview impact (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/175)

- [x] funds-hub-dynamic-rebalance-schedule-ui-v0 :: Funds hub: add schedule UI for dynamic rebalancing runs (daily/weekly) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/176)

- [x] funds-hub-dynamic-rebalance-guardrails-panel-v0 :: Funds hub: show dynamic rebalance guardrails panel (max turnover, min order, cash buffer) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/177)

- [x] funds-hub-rebalance-e2e-preflight-checklist-v0 :: Funds hub: add preflight checklist before running dynamic rebalance (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/178)

- [x] ui-market-data-client-v0 :: UI refactor: centralize market-data fetch (price series + market events) behind a client/hook layer (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/179)

- [x] ui-step-pages-remove-sample-json-v0 :: UI cleanup: Step pages remove SAMPLE JSON blobs; keep demo via server-side fixtures/one-click ingest (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/180)

- [x] funds-hub-rebalance-e2e-dynamic-rebalance-status-pill-v0 :: Funds hub: show dynamic rebalance status pill (last eval + next run) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/181)

- [x] funds-hub-drift-rebalance-cta :: Funds hub: show allocation drift and a one-click "Rebalance" CTA from the overview (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/182)

- [x] funds-hub-rebalance-preview-fees :: Funds hub: add a rebalance preview card (estimated trades + fees) before confirmation (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/183)

- [x] funds-hub-dynamic-rebalance-next-run-countdown-v0 :: Funds Hub: show next scheduled dynamic rebalance run + countdown (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/184)

- [x] funds-hub-rebalance-e2e-dynamic-rebalance-safety-stop-modal-v0 :: Funds Hub: add safety-stop confirmation modal before executing dynamic rebalance (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/185)

- [x] funds-hub-rebalance-e2e-dynamic-rebalance-impact-summary-v0 :: Funds Hub: add impact summary card in dynamic rebalance preview (trades/turnover/drift-after) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/186)

- [x] funds-hub-rebalance-e2e-dynamic-rebalance-paused-reason-banner-v0 :: Funds Hub: show paused/stalled reason banner for dynamic rebalance status (market hours/data stale) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/187)

- [x] funds-hub-rebalance-e2e-dynamic-rebalance-skip-history-v0 :: Funds Hub: show recent dynamic rebalance skip reasons/history (last N runs) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/188)

- [x] funds-hub-rebalance-e2e-dynamic-rebalance-order-count-confirm-v0 :: Funds Hub: add pre-run confirmation showing estimated order count + trades summary (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/189)

- [x] funds-hub-dynamic-rebalance-run-history-filter-v0 :: Funds Hub: add Dynamic Rebalance run history with status filter + quick details (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/190)

- [x] funds-hub-dynamic-rebalance-post-trade-allocation-chart-v0 :: Funds Hub: show projected post-trade allocation chart in Dynamic Rebalance preview (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/191)

- [x] funds-hub-rebalance-e2e-dynamic-rebalance-simulated-slippage-preview-v0 :: Funds hub: dynamic rebalancing E2E — show simulated slippage/price-impact preview before confirm (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/192)

- [x] funds-hub-rebalance-e2e-dynamic-rebalance-notification-preferences-v0 :: Funds hub: dynamic rebalancing E2E — user notification preferences for schedule/run events (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/193)

- [x] funds-hub-rebalance-e2e-dynamic-rebalance-failure-retry-ui-v0 :: Funds hub: dynamic rebalancing E2E — show failure reason + one-click retry (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/194)

- [x] funds-hub-rebalance-e2e-dynamic-rebalance-dry-run-simulator-v0 :: Funds hub: dynamic rebalancing E2E — dry-run simulator (no orders) with expected allocations (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/195)

- [x] funds-hub-dynamic-rebalance-what-changed-diff-view-v0 :: Funds Hub: show "What changed" diff between current vs proposed allocations in dynamic rebalance preview (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/196)

- [x] funds-hub-rebalance-e2e-execution-window-estimate-v0 :: Funds Hub: add execution window estimate + countdown for dynamic rebalance runs (E2E) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/197)

- [x] funds-hub-rebalance-e2e-tax-lots-impact-summary-v0 :: Funds Hub: show tax-lot / realized gain impact summary in dynamic rebalance preview (E2E) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/198)

- [x] funds-hub-rebalance-e2e-broker-order-status-live-refresh-v0 :: Funds Hub: live-refresh broker order statuses + partial fill progress during dynamic rebalance run (E2E) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/199)

- [x] funds-hub-dynamic-rebalance-run-details-panel-v0 :: Funds Hub: show dynamic rebalance run details (timestamps, orders, allocations) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/200)

- [x] funds-hub-rebalance-e2e-order-receipts-download-v0 :: Funds Hub: download broker order receipts from a rebalance run (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/201)

- [x] funds-hub-rebalance-e2e-rebalance-approval-summary-v0 :: Funds Hub: Rebalance run approval summary (orders/costs/constraints) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/202)

- [x] funds-hub-dynamic-rebalance-risk-disclosure-banner-v0 :: Funds Hub: Dynamic rebalance risk disclosure banner + learn more (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/203)

- [x] funds-hub-dynamic-rebalance-run-cancel-cta-v0 :: Funds hub: dynamic rebalancing — add Cancel Run CTA (queued/scheduled) + confirmation (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/204)

- [x] funds-hub-dynamic-rebalance-manual-run-trigger-v0 :: Funds hub: dynamic rebalancing — add Manual Run Now trigger with preflight gating (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/205)

- [x] funds-hub-dynamic-rebalance-preflight-errors-inline-v0 :: Funds hub: show preflight check errors inline + CTA to fix (dynamic rebalance) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/206)

- [x] funds-hub-rebalance-e2e-rebalance-run-progress-stepper-v0 :: Funds hub: E2E rebalance run progress stepper + time remaining hint (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/207)

- [x] funds-hub-dynamic-rebalance-run-completion-toast-v0 :: Funds hub: show run completion toast + link to run details (dynamic rebalance) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/208)

- [x] funds-hub-rebalance-e2e-cash-impact-breakdown-panel-v0 :: Funds hub: add cash impact breakdown panel in rebalance preview (E2E) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/209)

- [x] funds-hub-dynamic-rebalance-run-alerts-banner-v0 :: Funds hub: show last dynamic rebalance outcome banner (success/failure/canceled) with quick actions (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/210)

- [x] funds-hub-rebalance-e2e-dynamic-rebalance-run-export-json-v0 :: Funds hub: allow exporting dynamic rebalance run details as JSON/CSV (audit download) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/211)

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

- [x] backend-sqlite-daa-migrations-v0-v2 :: SQLite: add schema_migrations table + boot-time migration runner w/ audit log (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/225)

- [x] api-daa-admin-users-readonly-v0 :: Admin API: add read-only endpoint to list admin users + roles for dashboard (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/226)

- [x] backend-sqlite-daa-audit-events-table-v0 :: SQLite: add audit_events table + write path for DAA admin actions (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/227)

- [x] dashboard-daa-audit-log-export-csv-v0 :: Dashboard: add CSV export button for DAA audit log table (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/228)

- [x] dashboard-daa-audit-log-row-details-modal-v0 :: DAA dashboard: audit log row details modal (expand payload + metadata) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/229)

- [x] dashboard-daa-admin-users-detail-drawer-v0 :: DAA admin dashboard: add user detail drawer (roles, status, last login) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/230)

- [x] dashboard-daa-admin-users-table-search-sort-v0 :: DAA admin users: add search + sort to users table (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/232)

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

- [x] dashboard-ui-shadcn-dashboard-page-header-v0 :: DAA dashboard: shadcn page header (title + actions slot) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/278)

- [x] auth-email-login-a11y-autofocus-v0 :: Email login: improve accessibility + autofocus + Enter-to-submit (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/279)

- [x] dashboard-ui-shadcn-dashboard-toast-notifications-v0 :: DAA dashboard: shadcn toast notifications for auth/session events (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/280)

- [x] auth-email-login-spam-folder-tip-v0 :: Email login: pending state deliverability tip (check spam, allowlist sender) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/281)

- [x] dashboard-auth-logout-button-v0 :: Dashboard: add Logout button in account menu (clear session + redirect to /daa/login) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/282)

- [x] dashboard-ui-shadcn-dashboard-refresh-indicator-v0 :: Dashboard: show subtle data refresh indicator (skeleton/last-updated) in shadcn shell (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/283)

- [x] auth-email-login-link-sent-shadcn-ui-v0 :: Auth: restyle magic-link "Check your email" screen with shadcn + clearer next steps (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/284)

- [x] dashboard-ui-shadcn-daa-dashboard-layout-v0 :: DAA dashboard: shadcn page shell + header layout for /daa/dashboard (responsive) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/266)

- [x] auth-email-login-redirect-if-authed-v0 :: On /daa/login, redirect to /daa/dashboard when session exists (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/285)

- [x] dashboard-ui-shadcn-dashboard-account-menu-copy-userid-v0 :: Dashboard account menu: add Copy User ID / Email action (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/286)

- [x] ui-shadcn-daa-login-email-autocomplete-v0 :: DAA login (shadcn): set email input autocomplete + inputMode for smoother email entry (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/287)

- [x] dashboard-ui-shadcn-dashboard-topbar-user-menu-v0 :: DAA dashboard (shadcn): add topbar user menu with email + logout entry (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/288)

- [x] dashboard-ui-shadcn-dashboard-theme-toggle-v0 :: Dashboard: add theme toggle (light/dark) in topbar (shadcn) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/289)

- [x] ui-shadcn-daa-login-keyboard-submit-v0-v2 :: DAA login: keyboard UX (Enter submits + focus management) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/291)

- [x] ui-shadcn-daa-login-submit-loading-v0 :: DAA /daa/login: disable submit + show loading spinner while sending email (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/292)

- [x] dashboard-auth-email-login-return-to-dashboard-v0 :: Auth UX: after email login, return to the originally requested /daa/dashboard page (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/293)

- [x] ui-shadcn-daa-login-error-alert-v0 :: DAA Login: add shadcn Alert for magic-link/submit errors (clear copy + retry) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/294)

- [x] dashboard-ui-shadcn-dashboard-loading-skeleton-v0 :: Dashboard: show shadcn skeleton/loading state while session+data hydrate (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/295)

- [x] ui-shadcn-daa-login-magic-link-helper-text-v0 :: DAA /daa/login: add helper text about magic link delivery + expiry (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/296)

- [x] dashboard-auth-session-expired-toast-v0 :: Dashboard auth: show a shadcn toast on session-expired before redirecting to /daa/login (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/297)

- [x] ui-shadcn-daa-login-email-clear-button-v0 :: Login (shadcn): add clear button to email input for quick correction (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/298)

- [x] dashboard-ui-shadcn-dashboard-unauthorized-empty-state-v0 :: Dashboard (shadcn): friendly unauthorized/empty state with action to re-auth (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/299)

- [x] auth-email-login-resend-cooldown-timer-v0 :: Email login: disable resend and show cooldown timer (shadcn) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/300)

- [x] dashboard-ui-shadcn-dashboard-unauthorized-cta-button-v0 :: Dashboard unauthorized state: add primary Sign in CTA + clearer copy (shadcn) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/301)

- [x] dashboard-ui-shadcn-dashboard-error-boundary-retry-v0 :: Dashboard (shadcn): add page-level error boundary with retry button (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/302)

- [x] auth-email-login-network-offline-ux-v0 :: Auth (email login): improve offline/network-failure UX with clear retry guidance (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/303)

- [x] ui-shadcn-daa-login-passwordless-explainer-copy-v0 :: DAA login: add concise magic-link explainer + security note (shadcn) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/304)

- [x] dashboard-ui-shadcn-dashboard-settings-account-section-v0 :: Dashboard: add Account/Settings section shell with shadcn components (placeholder content) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/305)

- [x] dashboard-ui-shadcn-dashboard-settings-route-v0 :: Dashboard: add /daa/dashboard/settings route + nav item (shadcn placeholder) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/306)

- [x] dashboard-auth-session-refresh-on-focus-v0 :: Dashboard auth: refresh session on tab focus (avoid stale session UX) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/307)

- [x] ui-shadcn-daa-login-email-help-tooltip-v0 :: Login: add shadcn tooltip/help popover explaining magic link (and spam folder tip) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/308)

- [x] dashboard-ui-shadcn-dashboard-settings-security-section-v0 :: Dashboard settings: add Security section (sessions/passwordless copy) with shadcn components (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/309)

- [x] dashboard-auth-bootstrap-no-admin-cta-v0 :: Dashboard bootstrap: if no admin exists yet, show setup CTA instead of generic unauthorized (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/310)

- [x] auth-email-login-change-email-link-v0 :: Email login: add Change email link on link-sent state (back to form) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/311)

- [x] dashboard-ui-shadcn-dashboard-deploy-status-card-v0 :: Dashboard: add Deploy Status card (env + build SHA) for bootstrap visibility (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/313)

- [x] dashboard-auth-email-login-return-to-route-v1 :: Auth: magic-link login should return user to intended dashboard route (not just /daa/dashboard) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/314)

- [x] dashboard-ui-shadcn-dashboard-deploy-status-copy-sha-v0 :: Dashboard: Deploy Status card — add Copy Build SHA action (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/315)

- [x] dashboard-ui-shadcn-dashboard-deploy-status-copy-sha-v0-v2 :: Dashboard: Deploy Status card — add Copy Build SHA action (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/316)

- [x] ui-shadcn-daa-login-magic-link-resend-inline-v0 :: Login: magic-link state — add inline Resend Link action (shadcn) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/317)

- [x] auth-email-login-resend-disabled-reason-v0 :: Email login: show why Resend is disabled (cooldown/help text) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/318)

- [x] dashboard-ui-shadcn-dashboard-deploy-bootstrap-cta-v0 :: Dashboard: deploy bootstrap card CTA when no deployments yet (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/319)

- [x] ui-shadcn-daa-login-magic-link-sent-state-v0 :: Login: magic link sent screen/state (shadcn) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/320)

- [x] dashboard-ui-shadcn-dashboard-deploy-bootstrap-docs-link-v0 :: Dashboard: deploy bootstrap CTA links to docs + quickstart (shadcn) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/321)

- [x] dashboard-ui-shadcn-dashboard-deploy-bootstrap-command-copy-v0 :: Dashboard: Deploy bootstrap step card with copyable CLI command (shadcn) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/322)

- [x] auth-email-login-link-already-used-ux-v0 :: Auth: Email login shows friendly message for already-used/invalid magic link (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/323)

- [x] dashboard-ui-shadcn-dashboard-deploy-bootstrap-prereqs-checklist-v0 :: Dashboard: deploy bootstrap card shows prerequisites checklist (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/324)

- [x] auth-email-login-open-mail-app-cta-v0 :: Auth: email login sent state adds Open Mail CTA + helper copy (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/325)

- [x] dashboard-ui-shadcn-dashboard-deploy-bootstrap-env-vars-card-v0 :: Dashboard: deploy bootstrap shows env vars card + copy-to-clipboard (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/326)

- [x] ui-shadcn-daa-login-email-lowercase-normalization-v0 :: DAA login: normalize email to lowercase and show subtle hint (prevents magic-link mismatch) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/327)

- [x] dashboard-ui-shadcn-dashboard-deploy-bootstrap-copy-env-snippet-v0 :: Deploy bootstrap: add Copy button for env export snippet + toast (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/328)

- [x] ui-shadcn-daa-login-mobile-email-keyboard-v0 :: Login: improve mobile email keyboard (inputMode=email, autoCapitalize off) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/329)

- [x] ui-shadcn-daa-login-mobile-email-keyboard-v0-v2 :: Login: improve mobile email keyboard (inputMode=email, autoCapitalize off) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/330)

- [x] ui-shadcn-daa-login-email-paste-trim-v0-v2 :: Login: trim whitespace + lowercase on paste, keep cursor stable (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/331)

- [x] ui-shadcn-daa-login-email-paste-trim-v0 :: Login: trim whitespace + lowercase on paste, keep cursor stable (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/331)

- [x] ui-shadcn-daa-login-email-paste-trim-v0-v3 :: Login: trim whitespace + lowercase on paste, keep cursor stable (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/332)

- [x] dashboard-ui-shadcn-dashboard-deploy-bootstrap-last-updated-v0 :: Dashboard deploy status: show last-updated timestamp + retry CTA (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/333)

- [x] ui-shadcn-daa-login-email-inline-validation-message-v0 :: DAA /login: show inline email validation + help text in shadcn form (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/334)

- [x] dashboard-ui-shadcn-dashboard-deploy-bootstrap-copy-troubleshooting-v0 :: Dashboard: add shadcn callout with deploy bootstrap copy + quick troubleshooting (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/335)

- [x] dashboard-ui-shadcn-dashboard-deploy-bootstrap-validate-env-v0 :: Dashboard: deploy bootstrap panel validates required env vars (missing/ok) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/336)

- [x] ui-shadcn-daa-login-email-domain-suggestions-v0 :: DAA login: suggest common email domains when user types before @ (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/337)

- [x] auth-email-login-device-link-open-in-browser-hint-v0 :: Email login: detect in-app browser magic-link opens and show Open in Browser hint (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/338)

- [x] dashboard-ui-shadcn-dashboard-deploy-bootstrap-permissions-checklist-v0 :: Dashboard deploy bootstrap: add permissions/secrets checklist card (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/340)

- [x] arch-daa-api-store-runs-audit-v0 :: FastAPI: implement runs + audit_events storage APIs (match existing response shapes) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/341)

- [x] arch-daa-api-email-sender-v0 :: Email delivery for magic links (Resend provider + env checks; no secret leakage) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/342)

- [x] arch-next-postgres-auth-magic-link-v0 :: Next: email magic-link auth (`/api/daa/auth/email-login/request|consume`) + cookie session (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/344)

- [x] arch-next-postgres-store-v0 :: Next: store v0 (runs/audit/admin users) persistence -> Postgres (contract-compatible) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/345)

- [x] arch-remove-sqljs-sqlite-v0 :: Remove sql.js/SQLite from server runtime; keep contracts stable (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/346)

- [x] arch-daa-api-auth-magic-link-v0 :: FastAPI: email magic-link auth ( + ) + cookie session (SameSite=Lax) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/343)

- [x] arch-next-postgres-email-sender-v0 :: Next: Resend email sender (env checks + no secret leakage) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/347)

- [x] arch-next-postgres-session-cookie-v0 :: Postgres-backed cookie session for magic-link auth (Next.js /api/daa/* only) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/348)

- [x] backend-postgres-admin-users-v0 :: Postgres admin users: CRUD + authz check for /api/daa/* (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/349)

- [x] backend-postgres-runs-store-v0 :: Persist DAA runs in Postgres (schema + insert/query via Next.js /api/daa) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/345)

- [x] backend-postgres-audit-store-v0 :: Persist auth/audit events in Postgres (schema + write path; read via /api/daa for admin) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/352)

- [x] (auto) arch-remove-sqljs-dependency-v1 :: Remove sql.js from server runtime dependency graph (Next.js /api/daa) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/353)

- [x] arch-remove-sqljs-dependency-v1 :: Remove sql.js from server runtime dependency graph (Next.js /api/daa) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/354)

- [x] backend-postgres-auth-magiclink-tokens-v0 :: Postgres-backed magic-link tokens table (request + consume) for Resend auth (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/344)

- [x] backend-postgres-auth-session-cookie-guard-v0 :: Cookie session guard for /api/daa/* using Postgres-backed auth session (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/355)

- [x] backend-postgres-audit-store-v0-v2 :: Persist auth/audit events in Postgres (schema + write path; read via /api/daa for admin) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/351)

- [x] (auto) arch-next-postgres-auth-magic-link-e2e-v1 :: Ship Next.js /api/daa auth magic-link request and consume on Postgres with cookie session (no sqlite fallback) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/355)

- [x] arch-next-postgres-auth-magic-link-e2e-v1-v2 :: Ship Next.js /api/daa auth magic-link request and consume on Postgres with cookie session (no sqlite fallback) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/355)

- [x] arch-next-postgres-auth-magic-link-e2e-v1-v4 :: Ship Next.js /api/daa auth magic-link request and consume on Postgres with cookie session (no sqlite fallback) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/355)

- [x] arch-next-postgres-auth-magic-link-e2e-v1 :: Ship Next.js /api/daa auth magic-link request and consume on Postgres with cookie session (no sqlite fallback)

- [x] arch-remove-sqljs-server-runtime-block-v0 :: Enforce Postgres-only server runtime by hard-failing when sql.js or sqlite runtime is configured (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/356)

- [x] arch-next-postgres-api-daa-runs-read-write-v0 :: Route /api/daa/runs read+write through Next.js Postgres store (no sqlite path) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/357)

- [x] (auto) backend-postgres-auth-magiclink-consume-session-cookie-v0 :: Consume magic-link in Next.js and issue cookie session backed by Postgres (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/348)

- [x] backend-postgres-auth-magiclink-consume-session-cookie-v0 :: Consume magic-link in Next.js and issue cookie session backed by Postgres (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/348)

- [x] arch-next-postgres-api-daa-runs-by-id-v0 :: Migrate /api/daa/store/v0/run/[runId] to Postgres-backed Next.js handlers (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/357)

- [x] arch-next-postgres-api-daa-runs-audit-stream-v0 :: Migrate /api/daa/store/v0/run/[runId]/audit and /audit-events to Postgres paths

- [x] backend-postgres-auth-magiclink-request-resend-v0 :: Move email-login request and resend rate-limit persistence to Postgres (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/344)

- [x] backend-postgres-auth-magiclink-token-expiry-v0 :: Add Postgres token-expiry cleanup and validation parity for magic-link auth

- [x] backend-postgres-auth-session-refresh-v0 :: Implement Postgres session refresh and last-seen update path for /api/daa/auth/me

- [x] arch-next-postgres-api-daa-store-contract-parity-v0 :: Verify /api/daa/store/v0 payload and status-code parity after Postgres migration

- [x] arch-next-postgres-prod-smoke-dashboard-engine-v0 :: Add production smoke checks for /daa/dashboard and /api/daa/engine-health

- [x] arch-remove-fastapi-public-daa-surface-v0 :: Ensure no public /api/daa route is served by FastAPI in current epoch

- [x] backend-postgres-audit-query-index-v0 :: Add Postgres indexes for audit queries used by admin API and dashboard

- [x] backend-postgres-runs-query-pagination-v0 :: Stabilize runs list pagination and ordering on Postgres-backed /api/daa/store/v0/runs

- [x] arch-next-postgres-prod-smoke-dashboard-engine-v1 :: Strengthen prod smoke checks for /daa/dashboard and /api/daa/engine-health with explicit error fingerprints

- [x] backend-postgres-auth-magiclink-rate-limit-parity-v0 :: Enforce Postgres-backed rate-limit parity for auth email-login request and resend endpoints

- [x] backend-postgres-auth-session-cookie-rotation-v0 :: Add session-cookie rotation and stale-cookie invalidation checks for Postgres auth sessions

- [x] backend-postgres-runs-query-filters-v0 :: Add deterministic Postgres filters for /api/daa/store/v0/runs (status/date/source) with stable ordering

- [x] backend-postgres-audit-retention-cleanup-v0 :: Implement retention-safe cleanup for old audit rows and verify admin query paths remain contract-compatible

- [x] arch-next-postgres-api-daa-store-error-contract-v0 :: Lock /api/daa/store/v0 error status/body contract for Postgres paths via focused regression tests

- [x] arch-remove-fastapi-route-ownership-smoke-v0 :: Add a route-ownership smoke test proving public /api/daa routes are only served by Next.js

- [x] arch-next-postgres-daa-api-regression-pack-v0 :: Add a minimal regression pack for auth plus store endpoints on Postgres-backed /api/daa routes

- [x] product-funds-hub-entry-path-v0 :: Make /daa/market/funds the default DAA hub entry with clear jump-off into run workflow

- [x] product-funds-hub-step-status-panel-v0 :: Show Step1-7 completion status in funds hub with missing-data highlights

- [x] product-funds-hub-step-actions-jump-fix-v0 :: Add jump-to-fix actions from hub status cards into the corresponding step screens

- [x] backend-dashboard-bundle-money-plan-schema-v0 :: Extend dashboard bundle schema with Step3 money-plan fields and compatibility guards

- [x] backend-dashboard-bundle-import-export-hub-v0 :: Support import/export of the DAA dashboard bundle directly from the funds hub UI

- [x] api-daa-hub-run-refresh-workflow-v0 :: Provide a single Run DAA path in funds hub to refresh steps and generate recommendation

- [x] qa-hub-deeplink-compat-step-wizard-v0 :: Verify /daa/step/* and /daa/wizard deep-links remain compatible after hub-first flow

- [x] ops-hub-regression-smoke-pack-v0 :: Add smoke checks for funds hub run path, recommendation rendering, and bundle export

- [x] backend-nextjs-postgres-platform-hardening-v0 :: Backend system A: harden Next.js + Postgres API boundaries, migrations, and failure handling

- [x] backend-engine-service-contract-hardening-v0 :: Backend system B: harden Python engine contracts, timeouts, and upstream error mapping

- [x] backend-marketdata-provider-adapters-v0 :: Backend system B: stabilize provider adapters for twitter/xueqiu token and quote ingestion

- [x] frontend-uiux-dashboard-information-architecture-v0 :: Frontend UIUX: restructure dashboard information hierarchy for faster operator scanning

- [x] frontend-uiux-component-consistency-shadcn-v0 :: Frontend UIUX: unify table/form/feedback component states under shadcn patterns

- [x] frontend-uiux-accessibility-feedback-states-v0 :: Frontend UIUX: improve loading/error/empty and keyboard-accessibility behavior on DAA pages

- [x] frontend-uiux-funds-hub-information-density-v0 :: Frontend UIUX: tune funds hub information density for faster scan and lower scroll cost

- [x] frontend-uiux-funds-hub-step-card-hierarchy-v0 :: Frontend UIUX: establish stronger visual hierarchy for step cards and action priority

- [x] frontend-uiux-dashboard-action-rail-v0 :: Frontend UIUX: add a persistent action rail for high-frequency dashboard operations

- [x] frontend-uiux-dashboard-empty-state-guidance-v0 :: Frontend UIUX: redesign empty and first-run states with clearer next actions

- [x] frontend-uiux-dashboard-error-recovery-v0 :: Frontend UIUX: improve inline error recovery controls and retry affordances

- [x] frontend-uiux-funds-hub-mobile-navigation-v0 :: Frontend UIUX: optimize mobile navigation and sticky actions for funds hub flow

- [x] frontend-uiux-funds-hub-form-friction-pass-v0 :: Frontend UIUX: reduce form friction in funds hub with defaults, hints, and validation timing

- [x] frontend-uiux-dashboard-visual-regression-guards-v0 :: Frontend UIUX: add visual-regression guardrails for critical dashboard surfaces

- [x] frontend-uiux-shadcn-token-consistency-pass-v0 :: Frontend UIUX: align spacing, typography, and color tokens across shadcn components

- [x] frontend-uiux-step-flow-cta-copy-pass-v0 :: Frontend UIUX: tighten CTA copy across step flow to reduce decision ambiguity

- [x] frontend-uiux-accessibility-keyboard-focus-map-v0 :: Frontend UIUX: complete keyboard focus map for dashboard and funds hub interactions

- [x] frontend-uiux-performance-skeleton-loading-pass-v0 :: Frontend UIUX: refine skeleton and progressive-loading behavior for perceived performance

- [x] mainline-goal-next-js-remains-the-only-public-backend-for-no-fastapi-migration-for-v0 :: Mainline GOAL: Next.js remains the ONLY public backend for `/api/daa/*` (no FastAPI migration for the public surface).

- [x] mainline-goal-postgres-is-the-only-persistence-for-auth-runs-audit-admin-users-v0 :: Mainline GOAL: Postgres is the ONLY persistence for auth + runs + audit + admin users.

- [x] mainline-goal-auth-is-email-magic-link-resend-cookie-session-samesite-lax-v0 :: Mainline GOAL: Auth is email magic-link (Resend) + cookie session (SameSite=Lax).

- [x] mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v0 :: Mainline GOAL: Remove `sql.js`/SQLite from server runtime (no bundler/strict-mode footguns).

- [x] mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v0 :: Mainline GOAL: Python service becomes optional (engine-only) and must NOT own `/api/daa/*`.

- [x] mainline-dod-sends-email-via-resend-v0 :: Mainline DOD: `/api/daa/auth/email-login/request` sends email via Resend.

- [x] mainline-dod-sets-session-cookie-and-redirects-to-v0 :: Mainline DOD: `/api/daa/auth/email-login/consume` sets session cookie and redirects to `/daa/dashboard`.

- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v0 :: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI).

- [x] mainline-dod-prod-smoke-200-200-v0 :: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200.

- [x] mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v1 :: Follow-up hardening: Mainline GOAL: Remove `sql.js`/SQLite from server runtime (no bundler/strict-mode footguns).

- [x] mainline-dod-sets-session-cookie-and-redirects-to-v1 :: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/consume` sets session cookie and redirects to `/daa/dashboard`.

- [x] mainline-dod-sends-email-via-resend-v1 :: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/request` sends email via Resend.

- [x] mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v1 :: Follow-up hardening: Mainline GOAL: Python service becomes optional (engine-only) and must NOT own `/api/daa/*`.

- [x] mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v2 :: Follow-up hardening: Follow-up hardening: Mainline GOAL: Remove `sql.js`/SQLite from server runtime (no bundler/strict-mode footguns).

- [x] mainline-dod-prod-smoke-200-200-v1 :: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200.

- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v1 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI).

- [x] mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v2 :: Follow-up hardening: Follow-up hardening: Mainline GOAL: Python service becomes optional (engine-only) and must NOT own `/api/daa/*`.

- [x] mainline-dod-sends-email-via-resend-v2 :: Follow-up hardening: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/request` sends email via Resend.

- [x] mainline-dod-sets-session-cookie-and-redirects-to-v2 :: Follow-up hardening: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/consume` sets session cookie and redirects to `/daa/dashboard`.

- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v2 :: Follow-up hardening: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI).

- [x] mainline-dod-prod-smoke-200-200-v2 :: Follow-up hardening: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200.

- [x] mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v3 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline GOAL: Remove `sql.js`/SQLite from server runtime (no bundler/strict-mode footguns).

- [x] mainline-dod-sets-session-cookie-and-redirects-to-v3 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/consume` sets session cookie and redirects to `/daa/dashboard`.

- [x] mainline-dod-sends-email-via-resend-v3 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/request` sends email via Resend.

- [x] mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v3 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline GOAL: Python service becomes optional (engine-only) and must NOT own `/api/daa/*`.

- [x] mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v4 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline GOAL: Remove `sql.js`/SQLite from server runtime (no bundler/strict-mode footguns).

- [x] mainline-dod-prod-smoke-200-200-v3 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200.

- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v3 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI).

- [x] mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v4 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline GOAL: Python service becomes optional (engine-only) and must NOT own `/api/daa/*`.

- [x] mainline-dod-sends-email-via-resend-v4 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/request` sends email via Resend. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/415)

- [x] mainline-dod-sets-session-cookie-and-redirects-to-v4 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/consume` sets session cookie and redirects to `/daa/dashboard`. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/416)

- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v4 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/417)

- [x] mainline-dod-prod-smoke-200-200-v4 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200.

- [x] mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v5 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline GOAL: Remove `sql.js`/SQLite from server runtime (no bundler/strict-mode footguns). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/419)

- [x] mainline-dod-sets-session-cookie-and-redirects-to-v5 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/consume` sets session cookie and redirects to `/daa/dashboard`. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/420)

- [x] mainline-dod-sends-email-via-resend-v5 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/request` sends email via Resend. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/421)

- [x] mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v5 :: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Follow-up hardening: Mainline GOAL: Python service becomes optional (engine-only) and must NOT own `/api/daa/*`. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/422)

- [x] mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v6 :: Follow-up hardening: Mainline GOAL: Remove `sql.js`/SQLite from server runtime (no bundler/strict-mode footguns). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/423)

- [x] mainline-dod-prod-smoke-200-200-v5 :: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/424)

- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v5 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/425)

- [x] mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v6 :: Follow-up hardening: Mainline GOAL: Python service becomes optional (engine-only) and must NOT own `/api/daa/*`. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/426)

- [x] mainline-dod-sends-email-via-resend-v6 :: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/request` sends email via Resend. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/427)

- [x] mainline-dod-sets-session-cookie-and-redirects-to-v6 :: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/consume` sets session cookie and redirects to `/daa/dashboard`. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/428)

- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v6 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/429)

- [x] mainline-dod-prod-smoke-200-200-v6 :: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/430)

- [x] mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v7 :: Follow-up hardening: Mainline GOAL: Remove `sql.js`/SQLite from server runtime (no bundler/strict-mode footguns). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/431)

- [x] mainline-dod-sets-session-cookie-and-redirects-to-v7 :: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/consume` sets session cookie and redirects to `/daa/dashboard`. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/432)

- [x] mainline-dod-sends-email-via-resend-v7 :: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/request` sends email via Resend. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/433)

- [x] mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v9 :: Follow-up hardening: Mainline GOAL: Remove `sql.js`/SQLite from server runtime (no bundler/strict-mode footguns). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/443)

- [x] mainline-dod-prod-smoke-200-200-v8 :: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/442)

- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v8 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/441)

- [x] mainline-dod-sets-session-cookie-and-redirects-to-v8 :: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/consume` sets session cookie and redirects to `/daa/dashboard`. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/440)

- [x] mainline-dod-sends-email-via-resend-v8 :: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/request` sends email via Resend. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/439)

- [x] mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v8 :: Follow-up hardening: Mainline GOAL: Python service becomes optional (engine-only) and must NOT own `/api/daa/*`. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/438)

- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v7 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/437)

- [x] mainline-dod-prod-smoke-200-200-v7 :: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/436)

- [x] mainline-dod-sets-session-cookie-and-redirects-to-v9 :: Follow-up hardening: Mainline DOD: `/api/daa/auth/email-login/consume` sets session cookie and redirects to `/daa/dashboard`.

- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v9 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/446)

- [x] mainline-dod-prod-smoke-200-200-v9 :: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/447)

- [x] mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v9 :: Follow-up hardening: Mainline GOAL: Python service becomes optional (engine-only) and must NOT own `/api/daa/*`. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/448)

- [x] mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v10 :: Follow-up hardening: Mainline GOAL: Remove `sql.js`/SQLite from server runtime (no bundler/strict-mode footguns). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/449)

- [x] backend-nextjs-postgres-platform-hardening-v1 :: Backend system A follow-up: close remaining Next.js + Postgres API boundary and migration gaps (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/484)

- [x] backend-engine-service-contract-hardening-v1 :: Backend system B follow-up: finish Python engine contract timeout/error mapping hardening (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/485)

- [x] frontend-uiux-dashboard-information-architecture-v1 :: Frontend UIUX follow-up: complete dashboard information architecture and operator scan flow (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/486)

- [x] frontend-uiux-funds-hub-step-card-hierarchy-v1 :: Frontend UIUX follow-up: complete funds hub step-card hierarchy and action priority polish (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/487)

- [x] backend-nextjs-postgres-platform-hardening-v2 :: Follow-up hardening: Backend system A follow-up: close remaining Next.js + Postgres API boundary and migration gaps (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/488)

- [x] mainline-dod-prod-smoke-200-200-v19 :: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/489)

- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v19 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/490)

- [x] frontend-uiux-funds-hub-step-card-hierarchy-v2 :: Follow-up hardening: Frontend UIUX follow-up: complete funds hub step-card hierarchy and action priority polish (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/491)

- [x] frontend-uiux-dashboard-information-architecture-v2 :: Follow-up hardening: Frontend UIUX follow-up: complete dashboard information architecture and operator scan flow (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/492)

- [x] backend-engine-service-contract-hardening-v2 :: Follow-up hardening: Backend system B follow-up: finish Python engine contract timeout/error mapping hardening (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/493)

- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v20 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/494)

- [x] mainline-dod-prod-smoke-200-200-v20 :: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/495)

- [x] backend-nextjs-postgres-platform-hardening-v3 :: Follow-up hardening: Backend system A follow-up: close remaining Next.js + Postgres API boundary and migration gaps (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/496)

- [x] backend-engine-service-contract-hardening-v3 :: Follow-up hardening: Backend system B follow-up: finish Python engine contract timeout/error mapping hardening (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/497)

- [x] frontend-uiux-dashboard-information-architecture-v3 :: Follow-up hardening: Frontend UIUX follow-up: complete dashboard information architecture and operator scan flow (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/498)

- [x] frontend-uiux-funds-hub-step-card-hierarchy-v3 :: Follow-up hardening: Frontend UIUX follow-up: complete funds hub step-card hierarchy and action priority polish (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/499)

- [x] backend-nextjs-postgres-platform-hardening-v4 :: Follow-up hardening: Backend system A follow-up: close remaining Next.js + Postgres API boundary and migration gaps (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/500)

- [x] mainline-dod-prod-smoke-200-200-v21 :: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/501)

- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v21 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/502)

- [x] frontend-uiux-funds-hub-step-card-hierarchy-v4 :: Follow-up hardening: Frontend UIUX follow-up: complete funds hub step-card hierarchy and action priority polish (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/503)

- [x] frontend-uiux-dashboard-information-architecture-v4 :: Follow-up hardening: Frontend UIUX follow-up: complete dashboard information architecture and operator scan flow (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/504)

- [x] backend-engine-service-contract-hardening-v4 :: Follow-up hardening: Backend system B follow-up: finish Python engine contract timeout/error mapping hardening (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/505)

- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v22 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/506)

- [x] mainline-dod-prod-smoke-200-200-v22 :: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/507)

- [x] backend-nextjs-postgres-platform-hardening-v5 :: Follow-up hardening: Backend system A follow-up: close remaining Next.js + Postgres API boundary and migration gaps (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/508)

- [x] backend-engine-service-contract-hardening-v5 :: Follow-up hardening: Backend system B follow-up: finish Python engine contract timeout/error mapping hardening (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/509)

- [x] frontend-uiux-dashboard-information-architecture-v5 :: Follow-up hardening: Frontend UIUX follow-up: complete dashboard information architecture and operator scan flow (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/510)

- [x] frontend-uiux-funds-hub-step-card-hierarchy-v5 :: Follow-up hardening: Frontend UIUX follow-up: complete funds hub step-card hierarchy and action priority polish (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/511)

- [x] backend-nextjs-postgres-platform-hardening-v6 :: Follow-up hardening: Backend system A follow-up: close remaining Next.js + Postgres API boundary and migration gaps (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/512)

- [x] mainline-dod-prod-smoke-200-200-v23 :: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/513)

- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v23 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/514)

- [x] frontend-uiux-funds-hub-step-card-hierarchy-v6 :: Follow-up hardening: Frontend UIUX follow-up: complete funds hub step-card hierarchy and action priority polish (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/515)

- [x] frontend-uiux-dashboard-information-architecture-v6 :: Follow-up hardening: Frontend UIUX follow-up: complete dashboard information architecture and operator scan flow (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/516)

- [x] backend-engine-service-contract-hardening-v6 :: Follow-up hardening: Backend system B follow-up: finish Python engine contract timeout/error mapping hardening (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/517)

- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v24 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/518)

- [x] mainline-dod-prod-smoke-200-200-v24 :: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/519)

- [x] backend-nextjs-postgres-platform-hardening-v7 :: Follow-up hardening: Backend system A follow-up: close remaining Next.js + Postgres API boundary and migration gaps (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/520)

- [x] backend-engine-service-contract-hardening-v7 :: Follow-up hardening: Backend system B follow-up: finish Python engine contract timeout/error mapping hardening (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/521)

- [x] frontend-uiux-dashboard-information-architecture-v7 :: Follow-up hardening: Frontend UIUX follow-up: complete dashboard information architecture and operator scan flow (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/522)

- [x] frontend-uiux-funds-hub-step-card-hierarchy-v7 :: Follow-up hardening: Frontend UIUX follow-up: complete funds hub step-card hierarchy and action priority polish (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/523)

- [x] backend-nextjs-postgres-platform-hardening-v8 :: Follow-up hardening: Backend system A follow-up: close remaining Next.js + Postgres API boundary and migration gaps (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/524)

- [x] mainline-dod-prod-smoke-200-200-v25 :: Follow-up hardening: Mainline DOD: Prod smoke: `/api/daa/engine-health` 200; `/daa/dashboard` 200. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/525)

- [x] mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v25 :: Follow-up hardening: Mainline DOD: `/api/daa/store/v0/*` reads/writes Postgres (contract-compatible with current UI). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/526)

- [x] frontend-uiux-funds-hub-step-card-hierarchy-v8 :: Follow-up hardening: Frontend UIUX follow-up: complete funds hub step-card hierarchy and action priority polish (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/527)

- [x] frontend-uiux-dashboard-information-architecture-v8 :: Follow-up hardening: Frontend UIUX follow-up: complete dashboard information architecture and operator scan flow (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/528)

- [x] backend-engine-service-contract-hardening-v8 :: Follow-up hardening: Backend system B follow-up: finish Python engine contract timeout/error mapping hardening (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/529)

- [x] feature-dashboard-quick-actions-panel-v0 :: Feature sprint: dashboard quick-actions panel with one-click operator jumps (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/530)

- [x] feature-funds-hub-batch-edit-weights-v0 :: Feature sprint: funds hub batch edit + normalize target weights with inline validation

- [x] feature-funds-hub-scenario-presets-v0 :: Feature sprint: save/load scenario presets for repeated DAA workflows (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/531)

- [x] feature-run-history-compare-view-v0 :: Feature sprint: compare two runs and highlight trade/metric deltas (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/532)

- [x] feature-backend-run-tagging-notes-v0 :: Feature sprint: add run tags + notes for operator annotations (API + UI) (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/533)

- [x] feature-backend-run-list-search-sort-v0 :: Feature sprint: run list search/sort optimization for faster retrieval (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/534)

- [x] feature-dashboard-guided-empty-state-v0 :: Dashboard v0: guided first-run empty state with progressive CTA path (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/536)

- [x] feature-funds-hub-trade-execution-checklist-v0 :: Feature sprint: funds hub pre-trade execution checklist with blocker-aware next actions (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/537)

- [x] feature-interaction-keyboard-shortcuts-v0 :: Interaction v0: add keyboard shortcuts for high-frequency dashboard/funds hub actions (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/538)

- [x] mainline-goal-keep-next-js-as-the-only-public-backend-for-with-postgres-persistence-v0 :: Mainline GOAL: Keep Next.js as the ONLY public backend for `/api/daa/*` with Postgres persistence. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/539)

- [x] mainline-goal-increase-user-visible-delivery-ui-polish-interaction-flow-and-practical-operator-features-v0 :: Mainline GOAL: Increase user-visible delivery: UI polish, interaction flow, and practical operator features. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/540)

- [x] mainline-goal-keep-daa-workflow-reliable-while-improving-speed-to-action-for-daily-operations-v0 :: Mainline GOAL: Keep DAA workflow reliable while improving speed-to-action for daily operations. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/541)

- [x] mainline-dod-each-active-milestone-pr-includes-at-least-one-user-visible-functional-change-v0 :: Mainline DOD: Each active milestone PR includes at least one user-visible functional change (not only test hardening). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/542)

- [x] mainline-dod-and-both-improve-operator-efficiency-for-the-targeted-scenario-v0 :: Mainline DOD: `/daa/dashboard` and `/daa/market/funds` both improve operator efficiency for the targeted scenario. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/543)

- [x] mainline-dod-backend-api-changes-preserve-contract-compatibility-and-pass-ci-build-test-typecheck-v0 :: Mainline DOD: Backend/API changes preserve contract compatibility and pass CI (build/test/typecheck). (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/544)

- [x] mainline-dod-prod-smoke-remains-green-200-200-v0 :: Mainline DOD: Prod smoke remains green: `/api/daa/engine-health` 200; `/daa/dashboard` 200. (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/545)

- [x] feature-live-execution-timeline-v0 :: Feature sprint: add a live execution timeline so operators can watch each automation step in real time (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/546)

- [x] feature-self-serve-run-debugger-v0 :: Feature sprint: add run debugger panel with one-click diagnostics and guided recovery actions (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/547)

- [x] feature-inline-detection-review-workspace-v0 :: Feature sprint: add inline detection review workspace with quick approve/reject actions (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/548)

- [x] feature-daa-command-palette-v0 :: Feature sprint: add command palette for fast jump and action execution across DAA modules (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/549)

- [x] feature-funds-hub-smart-defaults-v0 :: Feature sprint: add smart defaults and inline hints to speed up funds hub input completion (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/550)

- [x] feature-run-history-anomaly-highlights-v0 :: Feature sprint: highlight anomalies in run history and surface likely root-cause signals (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/551)

- [x] feature-dashboard-ops-alert-center-v0 :: Feature sprint: add dashboard alert center with grouped warnings and suggested next actions (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/552)

- [x] feature-policy-impact-simulator-v0 :: Feature sprint: add policy impact simulator to preview allocation and risk changes before confirm (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/553)

- [x] feature-portfolio-drift-alerts-v0 :: Feature sprint: add portfolio drift alerts with threshold-based action suggestions (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/554)

- [x] feature-rebalance-whatif-lab-v0 :: Feature sprint: add what-if lab to compare rebalance scenarios side by side (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/555)

- [x] feature-run-incident-playbooks-v0 :: Feature sprint: add incident playbooks with step-by-step recovery flows for failed runs (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/556)

- [x] feature-watchlist-signal-inbox-v0 :: Feature sprint: add watchlist signal inbox that groups market events by urgency and symbol (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/557)

- [x] feature-step-readiness-score-v0 :: Feature sprint: add step readiness scorecard to show blockers before execution (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/558)

- [x] feature-execution-cost-preview-v0 :: Feature sprint: add execution cost preview with estimated slippage and fee ranges (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/559)

- [x] feature-operator-shift-handover-v0 :: Feature sprint: add operator handover summary for next shift continuity (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/560)

- [x] feature-cross-market-ledger-risk-view-v0 :: Feature sprint: add cross-market A/H/US ledger risk view with unified base-ccy exposure (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/561)

- [x] feature-human-factor-scoreboard-v0 :: Feature sprint: add analyst/manager human-factor scoreboard (elite/neutral/incompetent) with transparent score breakdown (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/562)

- [x] feature-analyst-logic-consistency-alerts-v0 :: Feature sprint: add logic-consistency alerts when analyst thesis and environment regime diverge (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/563)

- [x] feature-qat-weight-adjusted-targets-v0 :: Feature sprint: implement quality-adjusted target weights (W_qat) with operator-visible factor trace (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/564)

- [x] feature-rebalance-scenario-a-b-gates-v0 :: Feature sprint: add scenario A/B decision gates (strong-hold vs value-trap) for rebalance routing (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/565)

- [x] feature-risk-tag-maxin-lock-center-v0 :: Feature sprint: add tag-based risk control center with physical MaxIn lock for isolated assets (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/566)

- [x] feature-liquidity-settlement-pretrade-gate-v0 :: Feature sprint: add pre-trade liquidity and T+N settlement gate with cash-gap forecast (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/567)

- [x] feature-monthly-attribution-evolution-report-v0 :: Feature sprint: add monthly attribution report splitting rebalance alpha vs human-factor alpha vs avoided loss (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/568)
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
- 2026-02-13 22:10 activated funds-hub-rebalance-e2e-dynamic-rebalance-preview-timeline-v0
- 2026-02-13 22:20 DONE funds-hub-rebalance-e2e-dynamic-rebalance-preview-timeline-v0 (merged PR #168)
- 2026-02-13 22:25 activated funds-hub-rebalance-e2e-target-allocation-import-json-v0
- 2026-02-13 22:34 DONE: funds-hub-rebalance-e2e-target-allocation-import-json-v0 :: merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/169
- 2026-02-13 22:40 activated funds-hub-rebalance-e2e-rebalance-plan-compare-scenarios-v0
- 2026-02-13 22:57 DONE: funds-hub-rebalance-e2e-rebalance-plan-compare-scenarios-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/170
- 2026-02-13 23:01 autofill added funds-hub-rebalance-e2e-asset-blacklist-v0
- 2026-02-13 23:01 autofill added funds-hub-rebalance-e2e-sell-proceeds-routing-v0
- 2026-02-13 23:05 activated funds-hub-rebalance-e2e-asset-blacklist-v0
- 2026-02-13 23:27 DONE: funds-hub-rebalance-e2e-asset-blacklist-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/171
- 2026-02-13 23:30 activated funds-hub-rebalance-e2e-sell-proceeds-routing-v0
- 2026-02-13 23:43 DONE: funds-hub-rebalance-e2e-sell-proceeds-routing-v0 merged → https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/172
- 2026-02-13 23:45 autofill added funds-hub-rebalance-e2e-missing-price-data-warnings-v0
- 2026-02-13 23:45 autofill added funds-hub-rebalance-e2e-cash-bucket-targets-v0
- 2026-02-13 23:50 PR#173 opened: yfinance history (engine) + Next proxy route
- 2026-02-13 23:50 activated funds-hub-rebalance-e2e-missing-price-data-warnings-v0
- 2026-02-14 00:03 DONE: funds-hub-rebalance-e2e-missing-price-data-warnings-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/174
- 2026-02-14 00:05 activated funds-hub-rebalance-e2e-cash-bucket-targets-v0
- 2026-02-14 00:19 DONE: funds-hub-rebalance-e2e-cash-bucket-targets-v0 merged -> https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/175
- 2026-02-14 00:31 autofill added funds-hub-dynamic-rebalance-schedule-ui-v0
- 2026-02-14 00:31 autofill added funds-hub-dynamic-rebalance-guardrails-panel-v0
- 2026-02-14 00:35 activated funds-hub-dynamic-rebalance-schedule-ui-v0
- 2026-02-14 00:48 DONE: funds-hub-dynamic-rebalance-schedule-ui-v0 :: Funds hub: add schedule UI for dynamic rebalancing runs (daily/weekly) — merged PR #176
- 2026-02-14 00:50 activated funds-hub-dynamic-rebalance-guardrails-panel-v0
- 2026-02-14 01:07 DONE: funds-hub-dynamic-rebalance-guardrails-panel-v0 merged via https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/177 (mergedAt=2026-02-13T17:02:21Z)
- 2026-02-14 01:16 autofill added funds-hub-rebalance-e2e-preflight-checklist-v0
- 2026-02-14 01:16 autofill added funds-hub-rebalance-e2e-dynamic-rebalance-status-pill-v0
- 2026-02-14 01:20 activated funds-hub-rebalance-e2e-preflight-checklist-v0
- 2026-02-14 01:28 Board cleanup: grouped Backlog into Real data/UI refactor vs Funds hub; collapsed excessive blank lines
- 2026-02-14 01:30 DONE: funds-hub-rebalance-e2e-preflight-checklist-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/178
- 2026-02-14 01:35 activated ui-market-data-client-v0
- 2026-02-14 01:46 DONE: ui-market-data-client-v0 :: UI refactor: centralize market-data fetch (price series + market events) behind a client/hook layer — merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/179
- 2026-02-14 01:50 activated ui-step-pages-remove-sample-json-v0
- 2026-02-14 02:07 DONE: ui-step-pages-remove-sample-json-v0 merged (PR #180) — moved step-page SAMPLE JSON to server-side fixtures; Step2 one-click demo ingest
- 2026-02-14 02:10 activated funds-hub-rebalance-e2e-dynamic-rebalance-status-pill-v0
- 2026-02-14 02:18 DONE: funds-hub-rebalance-e2e-dynamic-rebalance-status-pill-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/181
- 2026-02-14 02:33 autofill added funds-hub-drift-rebalance-cta
- 2026-02-14 02:33 autofill added funds-hub-rebalance-preview-fees
- 2026-02-14 02:35 activated funds-hub-drift-rebalance-cta
- 2026-02-14 02:48 DONE: funds-hub-drift-rebalance-cta :: merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/182
- 2026-02-14 02:50 activated funds-hub-rebalance-preview-fees
- 2026-02-14 03:02 DONE: funds-hub-rebalance-preview-fees :: merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/183; advanced SoT (no next milestone queued)
- 2026-02-14 03:16 autofill added funds-hub-dynamic-rebalance-next-run-countdown-v0
- 2026-02-14 03:16 autofill added funds-hub-rebalance-e2e-dynamic-rebalance-safety-stop-modal-v0
- 2026-02-14 03:20 activated funds-hub-dynamic-rebalance-next-run-countdown-v0
- 2026-02-14 03:25 DONE funds-hub-dynamic-rebalance-next-run-countdown-v0 :: Funds Hub: show next scheduled dynamic rebalance run + countdown (merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/184)
- 2026-02-14 03:30 activated funds-hub-rebalance-e2e-dynamic-rebalance-safety-stop-modal-v0
- 2026-02-14 03:42 DONE: funds-hub-rebalance-e2e-dynamic-rebalance-safety-stop-modal-v0 :: Funds Hub: add safety-stop confirmation modal before executing dynamic rebalance (merged: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/185)
- 2026-02-14 03:44 autofill added funds-hub-rebalance-e2e-dynamic-rebalance-impact-summary-v0
- 2026-02-14 03:44 autofill added funds-hub-rebalance-e2e-dynamic-rebalance-paused-reason-banner-v0
- 2026-02-14 03:45 activated funds-hub-rebalance-e2e-dynamic-rebalance-impact-summary-v0
- 2026-02-14 03:52 DONE: funds-hub-rebalance-e2e-dynamic-rebalance-impact-summary-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/186
- 2026-02-14 03:54 autofill added funds-hub-rebalance-e2e-dynamic-rebalance-skip-history-v0
- 2026-02-14 03:54 autofill added funds-hub-rebalance-e2e-dynamic-rebalance-order-count-confirm-v0
- 2026-02-14 03:55 activated funds-hub-rebalance-e2e-dynamic-rebalance-paused-reason-banner-v0
- 2026-02-14 04:06 DONE: funds-hub-rebalance-e2e-dynamic-rebalance-paused-reason-banner-v0 merged via https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/187
- 2026-02-14 04:10 activated funds-hub-rebalance-e2e-dynamic-rebalance-skip-history-v0
- 2026-02-14 04:28 DONE: funds-hub-rebalance-e2e-dynamic-rebalance-skip-history-v0 merged via PR #188
- 2026-02-14 04:30 activated funds-hub-rebalance-e2e-dynamic-rebalance-order-count-confirm-v0
- 2026-02-14 04:38 DONE: funds-hub-rebalance-e2e-dynamic-rebalance-order-count-confirm-v0 merged via PR #189
- 2026-02-14 04:39 autofill added funds-hub-dynamic-rebalance-run-history-filter-v0
- 2026-02-14 04:39 autofill added funds-hub-dynamic-rebalance-post-trade-allocation-chart-v0
- 2026-02-14 04:40 activated funds-hub-dynamic-rebalance-run-history-filter-v0
- 2026-02-14 04:49 funds-hub-dynamic-rebalance-run-history-filter-v0: merged PR #190 https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/190
- 2026-02-14 04:55 activated funds-hub-dynamic-rebalance-post-trade-allocation-chart-v0

- 2026-02-14 05:02 DONE funds-hub-dynamic-rebalance-post-trade-allocation-chart-v0 (merged PR #191); advanced -> none
- 2026-02-14 05:16 autofill added funds-hub-rebalance-e2e-dynamic-rebalance-simulated-slippage-preview-v0
- 2026-02-14 05:16 autofill added funds-hub-rebalance-e2e-dynamic-rebalance-notification-preferences-v0
- 2026-02-14 05:20 activated funds-hub-rebalance-e2e-dynamic-rebalance-simulated-slippage-preview-v0
- 2026-02-14 05:27 DONE: funds-hub-rebalance-e2e-dynamic-rebalance-simulated-slippage-preview-v0 (merged) :: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/192
- 2026-02-14 05:30 activated funds-hub-rebalance-e2e-dynamic-rebalance-notification-preferences-v0
- 2026-02-14 05:44 DONE: funds-hub-rebalance-e2e-dynamic-rebalance-notification-preferences-v0 — merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/193
- 2026-02-14 05:45 autofill added funds-hub-rebalance-e2e-dynamic-rebalance-failure-retry-ui-v0
- 2026-02-14 05:45 autofill added funds-hub-rebalance-e2e-dynamic-rebalance-dry-run-simulator-v0
- 2026-02-14 05:50 activated funds-hub-rebalance-e2e-dynamic-rebalance-failure-retry-ui-v0
- 2026-02-14 06:06 DONE: funds-hub-rebalance-e2e-dynamic-rebalance-failure-retry-ui-v0 -> merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/194
- 2026-02-14 06:10 activated funds-hub-rebalance-e2e-dynamic-rebalance-dry-run-simulator-v0

- 2026-02-14 06:26 DONE: funds-hub-rebalance-e2e-dynamic-rebalance-dry-run-simulator-v0 merged via PR #195 (no-op dry-run surfaces expected allocations)
- 2026-02-14 06:31 autofill added funds-hub-dynamic-rebalance-what-changed-diff-view-v0
- 2026-02-14 06:31 autofill added funds-hub-rebalance-e2e-execution-window-estimate-v0
- 2026-02-14 06:35 activated funds-hub-dynamic-rebalance-what-changed-diff-view-v0
- 2026-02-14 06:40 DONE: funds-hub-dynamic-rebalance-what-changed-diff-view-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/196
- 2026-02-14 06:45 activated funds-hub-rebalance-e2e-execution-window-estimate-v0
- 2026-02-14 06:58 DONE: funds-hub-rebalance-e2e-execution-window-estimate-v0 merged (#197) — Adds CN market execution window estimate + countdown surfaces (status pill / pause banner / schedule UI).
- 2026-02-14 07:00 autofill added funds-hub-rebalance-e2e-tax-lots-impact-summary-v0
- 2026-02-14 07:00 autofill added funds-hub-rebalance-e2e-broker-order-status-live-refresh-v0
- 2026-02-14 07:05 activated funds-hub-rebalance-e2e-tax-lots-impact-summary-v0
- 2026-02-14 07:20 DONE: funds-hub-rebalance-e2e-tax-lots-impact-summary-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/198
- 2026-02-14 07:25 activated funds-hub-rebalance-e2e-broker-order-status-live-refresh-v0
- 2026-02-14 07:37 DONE: funds-hub-rebalance-e2e-broker-order-status-live-refresh-v0 merged (PR #199) — live-refresh order status fill progress (paper broker simulation)
- 2026-02-14 07:46 autofill added funds-hub-dynamic-rebalance-run-details-panel-v0
- 2026-02-14 07:46 autofill added funds-hub-rebalance-e2e-order-receipts-download-v0
- 2026-02-14 07:50 activated funds-hub-dynamic-rebalance-run-details-panel-v0
- 2026-02-14 08:01 DONE: funds-hub-dynamic-rebalance-run-details-panel-v0 :: merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/200
- 2026-02-14 08:05 activated funds-hub-rebalance-e2e-order-receipts-download-v0
- 2026-02-14 08:13 DONE: funds-hub-rebalance-e2e-order-receipts-download-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/201 at 2026-02-14T00:12:05Z
- 2026-02-14 08:16 autofill added funds-hub-rebalance-e2e-rebalance-approval-summary-v0
- 2026-02-14 08:16 autofill added funds-hub-dynamic-rebalance-risk-disclosure-banner-v0
- 2026-02-14 08:20 activated funds-hub-rebalance-e2e-rebalance-approval-summary-v0
- 2026-02-14 08:34 DONE: funds-hub-rebalance-e2e-rebalance-approval-summary-v0 merged (#202) — Funds Hub: Rebalance run approval summary (orders/costs/constraints)
- 2026-02-14 08:40 activated funds-hub-dynamic-rebalance-risk-disclosure-banner-v0
- 2026-02-14 08:47 DONE: funds-hub-dynamic-rebalance-risk-disclosure-banner-v0 :: merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/203
- 2026-02-14 09:01 autofill added funds-hub-dynamic-rebalance-run-cancel-cta-v0
- 2026-02-14 09:01 autofill added funds-hub-dynamic-rebalance-manual-run-trigger-v0
- 2026-02-14 09:05 activated funds-hub-dynamic-rebalance-run-cancel-cta-v0
- 2026-02-14 09:21 DONE: funds-hub-dynamic-rebalance-run-cancel-cta-v0 merged → https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/204
- 2026-02-14 09:25 activated funds-hub-dynamic-rebalance-manual-run-trigger-v0
- 2026-02-14 09:33 DONE: funds-hub-dynamic-rebalance-manual-run-trigger-v0 merged via PR #205
- 2026-02-14 09:46 autofill added funds-hub-dynamic-rebalance-preflight-errors-inline-v0
- 2026-02-14 09:46 autofill added funds-hub-rebalance-e2e-rebalance-run-progress-stepper-v0
- 2026-02-14 09:50 activated funds-hub-dynamic-rebalance-preflight-errors-inline-v0
- 2026-02-14 09:58 DONE funds-hub-dynamic-rebalance-preflight-errors-inline-v0 merged: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/206
- 2026-02-14 09:58 ADVANCE cleared currentMilestoneKey (no next milestone).
- 2026-02-14 10:00 activated funds-hub-rebalance-e2e-rebalance-run-progress-stepper-v0
- 2026-02-14 10:12 DONE: funds-hub-rebalance-e2e-rebalance-run-progress-stepper-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/207
- 2026-02-14 10:14 autofill added funds-hub-dynamic-rebalance-run-completion-toast-v0
- 2026-02-14 10:14 autofill added funds-hub-rebalance-e2e-cash-impact-breakdown-panel-v0

- 2026-02-14 10:15 activated funds-hub-dynamic-rebalance-run-completion-toast-v0
- 2026-02-14 10:24 DONE: funds-hub-dynamic-rebalance-run-completion-toast-v0 merged via PR https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/208 (adds run completion toast + deep-link to run details).
- 2026-02-14 10:26 autofill added funds-hub-dynamic-rebalance-run-alerts-banner-v0
- 2026-02-14 10:26 autofill added funds-hub-rebalance-e2e-dynamic-rebalance-run-export-json-v0
- 2026-02-14 10:30 activated funds-hub-rebalance-e2e-cash-impact-breakdown-panel-v0
- 2026-02-14 10:39 DONE: funds-hub-rebalance-e2e-cash-impact-breakdown-panel-v0 merged: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/209
- 2026-02-14 10:40 autofill added funds-hub-rebalance-e2e-dynamic-rebalance-run-audit-log-download-csv-v0
- 2026-02-14 10:40 autofill added funds-hub-rebalance-e2e-dynamic-rebalance-run-notes-and-tags-v0
- 2026-02-14 10:45 activated funds-hub-dynamic-rebalance-run-alerts-banner-v0
- 2026-02-14 10:56 DONE: funds-hub-dynamic-rebalance-run-alerts-banner-v0 merged via PR #210 https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/210
- 2026-02-14 10:58 autofill added funds-hub-rebalance-e2e-dynamic-rebalance-run-compare-before-after-v0
- 2026-02-14 11:00 activated funds-hub-rebalance-e2e-dynamic-rebalance-run-export-json-v0
- 2026-02-14 11:09 DONE: funds-hub-rebalance-e2e-dynamic-rebalance-run-export-json-v0 :: export dynamic rebalance run details as JSON/CSV :: merged PR #211
- 2026-02-14 11:10 autofill added funds-hub-rebalance-e2e-dynamic-rebalance-run-copy-summary-v0
- 2026-02-14 11:15 activated funds-hub-rebalance-e2e-dynamic-rebalance-run-audit-log-download-csv-v0
- 2026-02-14 11:26 DONE: funds-hub-rebalance-e2e-dynamic-rebalance-run-audit-log-download-csv-v0 merged as PR #212 (audit CSV export for dynamic rebalance run).
- 2026-02-14 11:30 activated funds-hub-rebalance-e2e-dynamic-rebalance-run-notes-and-tags-v0
- 2026-02-14 11:43 DONE: funds-hub-rebalance-e2e-dynamic-rebalance-run-notes-and-tags-v0 :: Funds hub: allow adding notes + tags to a dynamic rebalance run (E2E) — merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/213
- 2026-02-14 11:45 autofill added funds-hub-rebalance-e2e-dynamic-rebalance-run-share-pdf-summary-v0
- 2026-02-14 11:45 autofill added funds-hub-rebalance-e2e-dynamic-rebalance-run-discrepancy-warning-banner-v0

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
- 2026-02-14 18:15 activated backend-sqlite-daa-migrations-v0
- 2026-02-14 18:28 backend-sqlite-daa-migrations-v0-v2: Opened PR https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/225
- 2026-02-14 18:35 backend-sqlite-daa-migrations-v0-v2: Merged PR https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/225
- 2026-02-14 18:35 autofill added dashboard-daa-admin-users-table-search-sort-v0
- 2026-02-14 18:40 activated api-daa-admin-users-readonly-v0
- 2026-02-14 18:51 Opened PR for api-daa-admin-users-readonly-v0: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/226
- 2026-02-14 18:52 Merged + advanced SoT: api-daa-admin-users-readonly-v0 (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/226)
- 2026-02-14 18:55 activated backend-sqlite-daa-audit-events-table-v0
- 2026-02-14 19:07 activated backend-sqlite-daa-audit-events-table-v0
- 2026-02-14 19:08 merged+advanced: backend-sqlite-daa-audit-events-table-v0 -> done (PR #227)
- 2026-02-14 19:09 activated dashboard-daa-audit-log-export-csv-v0
- 2026-02-14 19:25 activated dashboard-daa-audit-log-export-csv-v0
- 2026-02-14 19:30 activated dashboard-daa-audit-log-export-csv-v0
- 2026-02-14 19:32 autofill added dashboard-daa-audit-log-pagination-v0
- 2026-02-14 19:32 autofill added api-daa-admin-users-activate-deactivate-v0
- 2026-02-14 19:35 activated dashboard-daa-audit-log-export-csv-v0
- 2026-02-14 19:41 DONE: dashboard-daa-audit-log-export-csv-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/228; SoT advanced -> none
- 2026-02-14 19:45 activated dashboard-daa-audit-log-row-details-modal-v0
- 2026-02-14 20:02 autofill added dashboard-daa-admin-users-copy-id-action-v0
- 2026-02-14 20:10 activated dashboard-daa-audit-log-row-details-modal-v0
- 2026-02-14 20:15 activated dashboard-daa-audit-log-row-details-modal-v0
- 2026-02-14 20:20 activated dashboard-daa-audit-log-row-details-modal-v0
- 2026-02-14 20:25 activated dashboard-daa-audit-log-row-details-modal-v0
- 2026-02-14 20:30 activated dashboard-daa-audit-log-row-details-modal-v0
- 2026-02-14 20:35 DONE: dashboard-daa-audit-log-row-details-modal-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/229
- 2026-02-14 20:35 activated dashboard-daa-admin-users-detail-drawer-v0
- 2026-02-14 20:41 DONE: dashboard-daa-admin-users-detail-drawer-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/230
- 2026-02-14 20:41 activated dashboard-daa-admin-users-table-search-sort-v0
- 2026-02-14 20:42 autofill added backend-sqlite-daa-audit-events-filter-by-actor-v0
- 2026-02-14 20:42 autofill added dashboard-daa-admin-users-status-filter-v0

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
- 2026-02-15 01:10 activated auth-email-login-v0
- 2026-02-15 01:20 activated auth-email-login-v0

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
- 2026-02-15 10:15 autofill added dashboard-ui-shadcn-dashboard-page-header-v0
- 2026-02-15 10:15 autofill added auth-email-login-a11y-autofocus-v0
- 2026-02-15 10:20 activated dashboard-ui-shadcn-dashboard-page-header-v0
- 2026-02-15 10:35 PR opened: dashboard-ui-shadcn-dashboard-page-header-v0 -> https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/278
- 2026-02-15 10:36 DONE: dashboard-ui-shadcn-dashboard-page-header-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/278; SoT advanced -> none
- 2026-02-15 10:37 autofill added dashboard-ui-shadcn-dashboard-toast-notifications-v0
- 2026-02-15 10:37 autofill added auth-email-login-spam-folder-tip-v0
- 2026-02-15 10:40 activated auth-email-login-a11y-autofocus-v0
- 2026-02-15 10:49 DONE: auth-email-login-a11y-autofocus-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/279; SoT advanced -> none
- 2026-02-15 10:55 activated dashboard-ui-shadcn-dashboard-toast-notifications-v0
- 2026-02-15 11:05 merged PR#280: DAA dashboard toast notices for auth/session events — https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/280
- 2026-02-15 11:10 activated auth-email-login-spam-folder-tip-v0
- 2026-02-15 11:15 PR created: auth-email-login-spam-folder-tip-v0 -> https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/281
- 2026-02-15 11:16 merged: auth-email-login-spam-folder-tip-v0 -> https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/281
- 2026-02-15 11:31 autofill added dashboard-auth-logout-button-v0
- 2026-02-15 11:31 autofill added dashboard-ui-shadcn-dashboard-refresh-indicator-v0
- 2026-02-15 11:36 activated dashboard-auth-logout-button-v0
- 2026-02-15 11:45 activated dashboard-ui-shadcn-dashboard-refresh-indicator-v0
- 2026-02-15 11:57 merged PR #283 (dashboard refresh indicator)
- 2026-02-15 12:00 autofill added auth-email-login-link-sent-shadcn-ui-v0
- 2026-02-15 12:00 autofill added dashboard-ui-shadcn-daa-dashboard-layout-v0
- 2026-02-15 12:05 activated auth-email-login-link-sent-shadcn-ui-v0
- 2026-02-15 12:20 activated auth-email-login-link-sent-shadcn-ui-v0
- 2026-02-15 12:25 activated auth-email-login-link-sent-shadcn-ui-v0
- 2026-02-15 12:30 DONE: auth-email-login-link-sent-shadcn-ui-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/284
- 2026-02-15 12:30 activated dashboard-ui-shadcn-daa-dashboard-layout-v0
- 2026-02-15 12:31 DONE: dashboard-ui-shadcn-daa-dashboard-layout-v0 already covered by https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/266
- 2026-02-15 12:45 autofill added auth-email-login-redirect-if-authed-v0
- 2026-02-15 12:46 autofill added dashboard-ui-shadcn-dashboard-account-menu-copy-userid-v0
- 2026-02-15 12:50 activated auth-email-login-redirect-if-authed-v0
- 2026-02-15 13:00 activated dashboard-ui-shadcn-dashboard-account-menu-copy-userid-v0
- 2026-02-15 13:11 autofill added ui-shadcn-daa-login-email-autocomplete-v0
- 2026-02-15 13:11 autofill added dashboard-ui-shadcn-dashboard-topbar-user-menu-v0
- 2026-02-15 13:15 activated ui-shadcn-daa-login-email-autocomplete-v0
- 2026-02-15 13:25 pr opened ui-shadcn-daa-login-email-autocomplete-v0: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/287
- 2026-02-15 13:26 DONE: ui-shadcn-daa-login-email-autocomplete-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/287; SoT advanced -> none
- 2026-02-15 13:27 autofill added dashboard-ui-shadcn-dashboard-theme-toggle-v0
- 2026-02-15 13:27 autofill added ui-shadcn-daa-login-keyboard-submit-v0-v2
- 2026-02-15 13:30 activated dashboard-ui-shadcn-dashboard-topbar-user-menu-v0
- 2026-02-15 13:39 Merged dashboard-ui-shadcn-dashboard-topbar-user-menu-v0 (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/288)
- 2026-02-15 13:40 autofill added ui-shadcn-daa-login-submit-loading-v0
- 2026-02-15 13:41 autofill added dashboard-auth-email-login-return-to-dashboard-v0
- 2026-02-15 13:45 activated dashboard-ui-shadcn-dashboard-theme-toggle-v0
- 2026-02-15 13:54 autofill added ui-shadcn-daa-login-error-alert-v0
- 2026-02-15 13:54 autofill added dashboard-ui-shadcn-dashboard-loading-skeleton-v0
- 2026-02-15 13:55 activated ui-shadcn-daa-login-keyboard-submit-v0-v2
- 2026-02-15 14:05 activated ui-shadcn-daa-login-keyboard-submit-v0-v2
- 2026-02-15 14:11 board repair: rename key ui-shadcn-daa-login-keyboard-submit-v0 -> ui-shadcn-daa-login-keyboard-submit-v0-v2 (match SoT)
- 2026-02-15 14:12 PR opened: ui-shadcn-daa-login-keyboard-submit-v0-v2 -> https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/291
- 2026-02-15 14:12 DONE: ui-shadcn-daa-login-keyboard-submit-v0-v2 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/291; SoT advanced -> none
- 2026-02-15 14:15 activated ui-shadcn-daa-login-submit-loading-v0
- 2026-02-15 14:21 autofill added ui-shadcn-daa-login-magic-link-helper-text-v0
- 2026-02-15 14:21 autofill added dashboard-auth-session-expired-toast-v0
- 2026-02-15 14:25 activated dashboard-auth-email-login-return-to-dashboard-v0
- 2026-02-15 14:40 activated dashboard-auth-email-login-return-to-dashboard-v0
- 2026-02-15 14:48 DONE: dashboard-auth-email-login-return-to-dashboard-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/293 (de-dupe; SoT had v0-v2 active)
- 2026-02-15 14:48 activated ui-shadcn-daa-login-error-alert-v0
- 2026-02-15 14:52 DONE: ui-shadcn-daa-login-error-alert-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/294
- 2026-02-15 14:52 activated dashboard-ui-shadcn-dashboard-loading-skeleton-v0
- 2026-02-15 15:03 DONE: dashboard-ui-shadcn-dashboard-loading-skeleton-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/295; SoT advanced -> none
- 2026-02-15 15:05 activated ui-shadcn-daa-login-magic-link-helper-text-v0
- 2026-02-15 15:12 PR opened: ui-shadcn-daa-login-magic-link-helper-text-v0 -> https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/296
- 2026-02-15 15:13 DONE: ui-shadcn-daa-login-magic-link-helper-text-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/296; SoT advanced -> none
- 2026-02-15 15:15 activated dashboard-auth-session-expired-toast-v0
- 2026-02-15 15:27 Merged #297: toast on session-expired before redirect to /daa/login (avoids double-toast on login).
- 2026-02-15 15:28 autofill added ui-shadcn-daa-login-email-clear-button-v0
- 2026-02-15 15:28 autofill added dashboard-ui-shadcn-dashboard-unauthorized-empty-state-v0
- 2026-02-15 15:30 activated ui-shadcn-daa-login-email-clear-button-v0
- 2026-02-15 15:37 merged: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/298
- 2026-02-15 15:39 autofill added auth-email-login-resend-cooldown-timer-v0
- 2026-02-15 15:39 autofill added dashboard-ui-shadcn-dashboard-unauthorized-cta-button-v0
- 2026-02-15 15:40 activated dashboard-ui-shadcn-dashboard-unauthorized-empty-state-v0
- 2026-02-15 15:55 activated auth-email-login-resend-cooldown-timer-v0
- 2026-02-15 16:02 Merged PR #300; completed auth-email-login-resend-cooldown-timer-v0; SoT advanced (no next milestone).
- 2026-02-15 16:05 activated dashboard-ui-shadcn-dashboard-unauthorized-cta-button-v0
- 2026-02-15 16:15 activated dashboard-ui-shadcn-dashboard-unauthorized-cta-button-v0
- 2026-02-15 16:22 DONE: dashboard-ui-shadcn-dashboard-unauthorized-cta-button-v0 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/301 (state repair: cleared duplicate active milestone)
- 2026-02-15 16:23 autofill added dashboard-ui-shadcn-dashboard-error-boundary-retry-v0
- 2026-02-15 16:23 autofill added auth-email-login-network-offline-ux-v0
- 2026-02-15 16:25 activated dashboard-ui-shadcn-dashboard-error-boundary-retry-v0
- 2026-02-15 16:32 dashboard-ui-shadcn-dashboard-error-boundary-retry-v0 merged: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/302
- 2026-02-15 16:35 activated auth-email-login-network-offline-ux-v0
- 2026-02-15 16:44 PR created: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/303
- 2026-02-15 16:46 Merged: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/303
- 2026-02-15 17:01 autofill added ui-shadcn-daa-login-passwordless-explainer-copy-v0
- 2026-02-15 17:01 autofill added dashboard-ui-shadcn-dashboard-settings-account-section-v0
- 2026-02-15 17:05 activated ui-shadcn-daa-login-passwordless-explainer-copy-v0
- 2026-02-15 17:15 activated dashboard-ui-shadcn-dashboard-settings-account-section-v0
- 2026-02-15 17:27 autofill added dashboard-ui-shadcn-dashboard-settings-route-v0
- 2026-02-15 17:27 autofill added dashboard-auth-session-refresh-on-focus-v0
- 2026-02-15 17:30 activated dashboard-ui-shadcn-dashboard-settings-route-v0
- 2026-02-15 17:43 PR created: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/306
- 2026-02-15 17:44 Merged + advanced SoT: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/306
- 2026-02-15 17:45 autofill added ui-shadcn-daa-login-email-help-tooltip-v0
- 2026-02-15 17:45 autofill added dashboard-ui-shadcn-dashboard-settings-security-section-v0
- 2026-02-15 17:50 activated dashboard-auth-session-refresh-on-focus-v0
- 2026-02-15 18:00 dashboard-auth-session-refresh-on-focus-v0 merged: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/307
- 2026-02-15 18:05 activated ui-shadcn-daa-login-email-help-tooltip-v0
- 2026-02-15 18:25 activated ui-shadcn-daa-login-email-help-tooltip-v0
- 2026-02-15 18:32 activated dashboard-ui-shadcn-dashboard-settings-security-section-v0
- 2026-02-15 18:46 autofill added dashboard-auth-bootstrap-no-admin-cta-v0
- 2026-02-15 18:46 autofill added auth-email-login-change-email-link-v0
- 2026-02-15 18:50 activated dashboard-auth-bootstrap-no-admin-cta-v0
- 2026-02-15 19:05 activated auth-email-login-change-email-link-v0
- 2026-02-15 19:11 Merged #311: auth-email-login-change-email-link-v0
- 2026-02-15 19:16 autofill added dashboard-ui-shadcn-dashboard-deploy-status-card-v0
- 2026-02-15 19:16 autofill added dashboard-auth-email-login-return-to-route-v1
- 2026-02-15 19:20 activated dashboard-ui-shadcn-dashboard-deploy-status-card-v0
- 2026-02-15 19:30 activated dashboard-ui-shadcn-dashboard-deploy-status-card-v0
- 2026-02-15 19:34 autofill added dashboard-ui-shadcn-dashboard-deploy-status-copy-sha-v0
- 2026-02-15 19:34 autofill added ui-shadcn-daa-login-magic-link-resend-inline-v0
- 2026-02-15 19:35 activated dashboard-ui-shadcn-dashboard-deploy-status-card-v0
- 2026-02-15 19:44 DONE (repair): dashboard-ui-shadcn-dashboard-deploy-status-card-v0 already merged in #313; preventing duplicate activation
- 2026-02-15 19:44 activated dashboard-auth-email-login-return-to-route-v1
- 2026-02-15 19:46 PR opened: dashboard-auth-email-login-return-to-route-v1 -> https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/314
- 2026-02-15 19:47 DONE: dashboard-auth-email-login-return-to-route-v1 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/314
- 2026-02-15 19:50 activated dashboard-ui-shadcn-dashboard-deploy-status-copy-sha-v0
- 2026-02-15 20:00 activated dashboard-ui-shadcn-dashboard-deploy-status-copy-sha-v0
- 2026-02-15 20:10 PR created: #316 for dashboard-ui-shadcn-dashboard-deploy-status-copy-sha-v0-v2
- 2026-02-15 20:11 MERGED+advanced: #316 done; SoT cleared (no next milestone)
- 2026-02-15 20:12 autofill added auth-email-login-resend-disabled-reason-v0
- 2026-02-15 20:13 autofill added dashboard-ui-shadcn-dashboard-deploy-bootstrap-cta-v0
- 2026-02-15 20:15 activated ui-shadcn-daa-login-magic-link-resend-inline-v0
- 2026-02-15 20:29 autofill added ui-shadcn-daa-login-magic-link-sent-state-v0
- 2026-02-15 20:29 autofill added dashboard-ui-shadcn-dashboard-deploy-bootstrap-docs-link-v0
- 2026-02-15 20:30 activated auth-email-login-resend-disabled-reason-v0
- 2026-02-15 20:39 Opened PR #318 for auth-email-login-resend-disabled-reason-v0
- 2026-02-15 20:40 Merged PR #318; advanced SoT (no next milestone queued)
- 2026-02-15 20:41 autofill added dashboard-ui-shadcn-dashboard-deploy-bootstrap-command-copy-v0
- 2026-02-15 20:41 autofill added auth-email-login-link-already-used-ux-v0
- 2026-02-15 20:45 activated dashboard-ui-shadcn-dashboard-deploy-bootstrap-cta-v0
- 2026-02-15 20:53 merged dashboard-ui-shadcn-dashboard-deploy-bootstrap-cta-v0 (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/319)
- 2026-02-15 20:54 autofill added dashboard-ui-shadcn-dashboard-deploy-bootstrap-prereqs-checklist-v0
- 2026-02-15 20:54 autofill added auth-email-login-open-mail-app-cta-v0
- 2026-02-15 20:55 activated ui-shadcn-daa-login-magic-link-sent-state-v0
- 2026-02-15 21:10 activated dashboard-ui-shadcn-dashboard-deploy-bootstrap-docs-link-v0
- 2026-02-15 21:20 activated dashboard-ui-shadcn-dashboard-deploy-bootstrap-command-copy-v0
- 2026-02-15 21:31 Opened PR #322 for dashboard-ui-shadcn-dashboard-deploy-bootstrap-command-copy-v0
- 2026-02-15 21:32 Merged PR #322; SoT advanced (no next milestone)
- 2026-02-15 21:35 activated auth-email-login-link-already-used-ux-v0
- 2026-02-15 21:50 activated dashboard-ui-shadcn-dashboard-deploy-bootstrap-prereqs-checklist-v0
- 2026-02-15 22:00 activated auth-email-login-open-mail-app-cta-v0
- 2026-02-15 22:09 autofill added dashboard-ui-shadcn-dashboard-deploy-bootstrap-env-vars-card-v0
- 2026-02-15 22:09 autofill added ui-shadcn-daa-login-email-lowercase-normalization-v0
- 2026-02-15 22:10 activated dashboard-ui-shadcn-dashboard-deploy-bootstrap-env-vars-card-v0
- 2026-02-15 22:20 activated ui-shadcn-daa-login-email-lowercase-normalization-v0
- 2026-02-15 22:31 Merged: ui-shadcn-daa-login-email-lowercase-normalization-v0 -> https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/327
- 2026-02-15 22:45 autofill added dashboard-ui-shadcn-dashboard-deploy-bootstrap-copy-env-snippet-v0
- 2026-02-15 22:45 autofill added ui-shadcn-daa-login-mobile-email-keyboard-v0
- 2026-02-15 22:50 activated dashboard-ui-shadcn-dashboard-deploy-bootstrap-copy-env-snippet-v0
- 2026-02-15 23:00 activated ui-shadcn-daa-login-mobile-email-keyboard-v0
- 2026-02-15 23:09 autofill added ui-shadcn-daa-login-email-paste-trim-v0
- 2026-02-15 23:09 autofill added dashboard-ui-shadcn-dashboard-deploy-bootstrap-last-updated-v0
- 2026-02-15 23:15 activated ui-shadcn-daa-login-mobile-email-keyboard-v0
- 2026-02-15 23:24 autofill added ui-shadcn-daa-login-email-inline-validation-message-v0
- 2026-02-15 23:24 autofill added dashboard-ui-shadcn-dashboard-deploy-bootstrap-copy-troubleshooting-v0
- 2026-02-15 23:25 activated ui-shadcn-daa-login-email-paste-trim-v0
- 2026-02-15 23:35 activated ui-shadcn-daa-login-email-paste-trim-v0
- 2026-02-15 23:39 Merged PR #331; marked ui-shadcn-daa-login-email-paste-trim-v0-v2 done; SoT advanced (no next milestone).
- 2026-02-15 23:40 activated ui-shadcn-daa-login-email-paste-trim-v0
- 2026-02-15 23:55 activated dashboard-ui-shadcn-dashboard-deploy-bootstrap-last-updated-v0
- 2026-02-16 00:06 Merged: deploy status card shows last-updated + retry CTA (PR #333)
- 2026-02-16 00:10 activated ui-shadcn-daa-login-email-inline-validation-message-v0
- 2026-02-16 00:19 PR created: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/334
- 2026-02-16 00:20 merged: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/334
- 2026-02-16 00:25 activated dashboard-ui-shadcn-dashboard-deploy-bootstrap-copy-troubleshooting-v0
- 2026-02-16 00:34 PR created: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/335
- 2026-02-16 00:35 Merged: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/335
- 2026-02-16 00:46 autofill added dashboard-ui-shadcn-dashboard-deploy-bootstrap-validate-env-v0
- 2026-02-16 00:46 autofill added ui-shadcn-daa-login-email-domain-suggestions-v0
- 2026-02-16 00:50 activated dashboard-ui-shadcn-dashboard-deploy-bootstrap-validate-env-v0
- 2026-02-16 01:01 PR created: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/336
- 2026-02-16 01:02 Merged: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/336 (SoT advanced)
- 2026-02-16 01:05 activated ui-shadcn-daa-login-email-domain-suggestions-v0
- 2026-02-16 01:12 merged ui-shadcn-daa-login-email-domain-suggestions-v0 (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/337)
- 2026-02-16 01:15 autofill added auth-email-login-device-link-open-in-browser-hint-v0
- 2026-02-16 01:16 autofill added dashboard-ui-shadcn-dashboard-deploy-bootstrap-permissions-checklist-v0
- 2026-02-16 01:20 activated auth-email-login-device-link-open-in-browser-hint-v0
- 2026-02-16 01:41 Merged auth-email-login-device-link-open-in-browser-hint-v0 (PR: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/338)
- 2026-02-16 01:46 activated dashboard-ui-shadcn-dashboard-deploy-bootstrap-permissions-checklist-v0
- 2026-02-16 02:03 activated arch-daa-api-store-runs-audit-v0
- 2026-02-16 02:33 PR created for arch-daa-api-email-sender-v0: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/342
- 2026-02-16 02:33 Merged: arch-daa-api-email-sender-v0 -> https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/342 (SoT advanced; no next milestone)
- 2026-02-16 02:35 activated arch-daa-api-auth-magic-link-v0
- 2026-02-16 02:45 activated arch-daa-api-auth-magic-link-v0
- 2026-02-16 02:58 autofill added arch-next-postgres-session-cookie-v0
- 2026-02-16 02:58 autofill added backend-postgres-admin-users-v0
- 2026-02-16 03:28 PR created: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/344
- 2026-02-16 03:29 Merged+advanced: https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/344 -> arch-next-postgres-store-v0
- 2026-02-16 03:52 Merged arch-next-postgres-store-v0 (#345) + advanced SoT to arch-remove-sqljs-sqlite-v0
- 2026-02-16 11:26 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/343; advanced SoT
- 2026-02-16 11:27 merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/347; advanced SoT
- 2026-02-16 11:29 autofill added backend-postgres-runs-store-v0
- 2026-02-16 11:29 autofill added backend-postgres-audit-store-v0
- 2026-02-16 11:40 autofill added arch-remove-sqljs-dependency-v1
- 2026-02-16 11:40 autofill added backend-postgres-auth-magiclink-tokens-v0
- 2026-02-16 11:45 activated backend-postgres-admin-users-v0
- 2026-02-16 12:05 autofill added backend-postgres-auth-session-cookie-guard-v0
- 2026-02-16 12:10 activated backend-postgres-admin-users-v0
- 2026-02-16 12:15 activated backend-postgres-admin-users-v0
- 2026-02-16 12:18 backend-postgres-admin-users-v0 merged via PR 349 and SoT advanced
- 2026-02-16 12:20 activated backend-postgres-runs-store-v0
- 2026-02-16 12:24 Merged backend-postgres-runs-store-v0 via PR 345 and advanced SoT
- 2026-02-16 12:25 activated backend-postgres-audit-store-v0
- 2026-02-16 12:35 activated backend-postgres-audit-store-v0
- 2026-02-16 12:50 activated backend-postgres-audit-store-v0
- 2026-02-16 12:58 activated backend-postgres-audit-store-v0
- 2026-02-16 13:02 activated backend-postgres-audit-store-v0
- 2026-02-16 13:03 activated arch-remove-sqljs-dependency-v1
- 2026-02-16 13:10 Opened PR #353 for arch-remove-sqljs-dependency-v1
- 2026-02-16 13:10 Merged arch-remove-sqljs-dependency-v1 via PR 353 and advanced SoT
- 2026-02-16 13:15 activated arch-remove-sqljs-dependency-v1
- 2026-02-16 13:20 activated arch-remove-sqljs-dependency-v1
- 2026-02-16 13:31 Merged arch-remove-sqljs-dependency-v1-v3 (PR #354) + advanced SoT
- 2026-02-16 13:35 activated backend-postgres-auth-magiclink-tokens-v0
- 2026-02-16 13:38 merged backend-postgres-auth-magiclink-tokens-v0 -> https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/344
- 2026-02-16 13:40 activated backend-postgres-auth-session-cookie-guard-v0
- 2026-02-16 13:47 activated backend-postgres-auth-session-cookie-guard-v0
- 2026-02-16 13:48 merged backend-postgres-auth-session-cookie-guard-v0 -> https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/355
- 2026-02-16 13:48 activated backend-postgres-audit-store-v0-v2
- 2026-02-16 14:02 autofill added arch-next-postgres-auth-magic-link-e2e-v1
- 2026-02-16 14:02 autofill added arch-remove-sqljs-server-runtime-block-v0
- 2026-02-16 14:05 activated arch-next-postgres-auth-magic-link-e2e-v1
- 2026-02-16 14:08 DONE: arch-next-postgres-auth-magic-link-e2e-v1 merged via PR #355
- 2026-02-16 14:10 activated arch-next-postgres-auth-magic-link-e2e-v1
- 2026-02-16 14:13 Merged arch-next-postgres-auth-magic-link-e2e-v1-v2 via PR 355 and advanced SoT
- 2026-02-16 14:15 activated arch-next-postgres-auth-magic-link-e2e-v1
- 2026-02-16 14:20 activated arch-next-postgres-auth-magic-link-e2e-v1
- 2026-02-16 14:24 merged arch-next-postgres-auth-magic-link-e2e-v1-v4 -> https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/355
- 2026-02-16 14:30 activated arch-next-postgres-auth-magic-link-e2e-v1
- 2026-02-16 14:33 activated arch-next-postgres-auth-magic-link-e2e-v1
- 2026-02-16 14:34 activated arch-remove-sqljs-server-runtime-block-v0
- 2026-02-16 14:37 PR opened: arch-remove-sqljs-server-runtime-block-v0 -> https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/356
- 2026-02-16 14:38 merged arch-remove-sqljs-server-runtime-block-v0 -> https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/356
- 2026-02-16 14:47 autofill added arch-next-postgres-api-daa-runs-read-write-v0
- 2026-02-16 14:47 autofill added backend-postgres-auth-magiclink-consume-session-cookie-v0
- 2026-02-16 14:50 activated arch-next-postgres-api-daa-runs-read-write-v0
- 2026-02-16 14:57 merged arch-next-postgres-api-daa-runs-read-write-v0 https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/357
- 2026-02-16 15:00 activated backend-postgres-auth-magiclink-consume-session-cookie-v0
- 2026-02-16 15:03 DONE: backend-postgres-auth-magiclink-consume-session-cookie-v0 merged via PR #348
- 2026-02-16 15:05 activated backend-postgres-auth-magiclink-consume-session-cookie-v0
- 2026-02-16 15:08 DONE: backend-postgres-auth-magiclink-consume-session-cookie-v0 (duplicate active v2) adopted merged PR #348 and advanced SoT
- 2026-02-16 15:10 backlog-guard added arch-next-postgres-api-daa-runs-by-id-v0
- 2026-02-16 15:10 backlog-guard added arch-next-postgres-api-daa-runs-audit-stream-v0
- 2026-02-16 15:10 backlog-guard added backend-postgres-auth-magiclink-request-resend-v0
- 2026-02-16 15:10 backlog-guard added backend-postgres-auth-magiclink-token-expiry-v0
- 2026-02-16 15:10 activated arch-next-postgres-api-daa-runs-by-id-v0
- 2026-02-16 15:25 backlog-guard added backend-postgres-auth-session-refresh-v0
- 2026-02-16 15:25 backlog-guard added arch-next-postgres-api-daa-store-contract-parity-v0
- 2026-02-16 15:25 backlog-guard added arch-next-postgres-prod-smoke-dashboard-engine-v0
- 2026-02-16 15:26 activated arch-next-postgres-api-daa-runs-audit-stream-v0
- 2026-02-16 15:48 backlog-guard completed stale arch-next-postgres-api-daa-runs-audit-stream-v0
- 2026-02-16 15:48 activated backend-postgres-auth-magiclink-request-resend-v0
- 2026-02-16 15:53 merged backend-postgres-auth-magiclink-request-resend-v0 https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/344
- 2026-02-16 16:00 activated backend-postgres-auth-magiclink-token-expiry-v0
- 2026-02-16 16:07 backlog-guard completed stale backend-postgres-auth-magiclink-token-expiry-v0
- 2026-02-16 16:07 backlog-guard added arch-remove-fastapi-public-daa-surface-v0
- 2026-02-16 16:07 backlog-guard added backend-postgres-audit-query-index-v0
- 2026-02-16 16:07 backlog-guard added backend-postgres-runs-query-pagination-v0
- 2026-02-16 16:10 activated backend-postgres-auth-session-refresh-v0
- 2026-02-16 16:30 backlog-guard completed stale backend-postgres-auth-session-refresh-v0
- 2026-02-16 16:30 activated arch-next-postgres-api-daa-store-contract-parity-v0
- 2026-02-16 16:40 backlog-guard completed stale arch-next-postgres-api-daa-store-contract-parity-v0
- 2026-02-16 16:40 activated arch-next-postgres-prod-smoke-dashboard-engine-v0
- 2026-02-16 16:50 backlog-guard completed stale arch-next-postgres-prod-smoke-dashboard-engine-v0
- 2026-02-16 16:50 activated arch-remove-fastapi-public-daa-surface-v0
- 2026-02-16 17:00 backlog-guard added arch-next-postgres-prod-smoke-dashboard-engine-v1
- 2026-02-16 17:00 backlog-guard added backend-postgres-auth-magiclink-rate-limit-parity-v0
- 2026-02-16 17:00 backlog-guard added backend-postgres-auth-session-cookie-rotation-v0
- 2026-02-16 17:20 backlog-guard completed stale arch-remove-fastapi-public-daa-surface-v0
- 2026-02-16 17:20 activated backend-postgres-audit-query-index-v0
- 2026-02-16 17:30 backlog-guard completed stale backend-postgres-audit-query-index-v0
- 2026-02-16 17:30 activated backend-postgres-runs-query-pagination-v0
- 2026-02-16 17:50 backlog-guard completed stale backend-postgres-runs-query-pagination-v0
- 2026-02-16 17:50 backlog-guard added backend-postgres-runs-query-filters-v0
- 2026-02-16 17:50 backlog-guard added backend-postgres-audit-retention-cleanup-v0
- 2026-02-16 17:50 backlog-guard added arch-next-postgres-api-daa-store-error-contract-v0
- 2026-02-16 17:50 activated arch-next-postgres-prod-smoke-dashboard-engine-v1
- 2026-02-16 18:00 backlog-guard completed stale arch-next-postgres-prod-smoke-dashboard-engine-v1
- 2026-02-16 18:00 activated backend-postgres-auth-magiclink-rate-limit-parity-v0
- 2026-02-16 18:30 backlog-guard completed stale backend-postgres-auth-magiclink-rate-limit-parity-v0
- 2026-02-16 18:30 activated backend-postgres-auth-session-cookie-rotation-v0
- 2026-02-16 18:50 backlog-guard completed stale backend-postgres-auth-session-cookie-rotation-v0
- 2026-02-16 18:50 backlog-guard added arch-remove-fastapi-route-ownership-smoke-v0
- 2026-02-16 18:50 backlog-guard added arch-next-postgres-daa-api-regression-pack-v0
- 2026-02-16 18:50 activated backend-postgres-runs-query-filters-v0
- 2026-02-16 19:00 backlog-guard completed stale backend-postgres-runs-query-filters-v0
- 2026-02-16 19:00 activated backend-postgres-audit-retention-cleanup-v0
- 2026-02-16 19:50 backlog-guard completed stale backend-postgres-audit-retention-cleanup-v0
- 2026-02-16 19:50 activated arch-next-postgres-api-daa-store-error-contract-v0
- 2026-02-16 20:00 backlog-guard completed stale arch-next-postgres-api-daa-store-error-contract-v0
- 2026-02-16 20:00 activated arch-remove-fastapi-route-ownership-smoke-v0
- 2026-02-16 20:20 backlog-guard completed stale arch-remove-fastapi-route-ownership-smoke-v0
- 2026-02-16 20:20 activated arch-next-postgres-daa-api-regression-pack-v0
- 2026-02-16 20:30 backlog-guard completed stale arch-next-postgres-daa-api-regression-pack-v0
- 2026-02-17 03:46 backlog-guard added product-funds-hub-entry-path-v0
- 2026-02-17 03:46 backlog-guard added product-funds-hub-step-status-panel-v0
- 2026-02-17 03:46 backlog-guard added product-funds-hub-step-actions-jump-fix-v0
- 2026-02-17 03:46 backlog-guard added backend-dashboard-bundle-money-plan-schema-v0
- 2026-02-17 03:46 activated product-funds-hub-entry-path-v0
- 2026-02-17 03:58 backlog-guard completed stale product-funds-hub-entry-path-v0
- 2026-02-17 03:58 backlog-guard added backend-dashboard-bundle-import-export-hub-v0
- 2026-02-17 03:58 backlog-guard added api-daa-hub-run-refresh-workflow-v0
- 2026-02-17 03:58 backlog-guard added qa-hub-deeplink-compat-step-wizard-v0
- 2026-02-17 03:58 activated product-funds-hub-step-status-panel-v0
- 2026-02-17 04:10 backlog-guard completed stale product-funds-hub-step-status-panel-v0
- 2026-02-17 04:10 activated product-funds-hub-step-actions-jump-fix-v0
- 2026-02-17 04:30 backlog-guard completed stale product-funds-hub-step-actions-jump-fix-v0
- 2026-02-17 04:30 activated backend-dashboard-bundle-money-plan-schema-v0
- 2026-02-17 04:50 backlog-guard completed stale backend-dashboard-bundle-money-plan-schema-v0
- 2026-02-17 04:50 backlog-guard added ops-hub-regression-smoke-pack-v0
- 2026-02-17 04:50 backlog-guard added backend-nextjs-postgres-platform-hardening-v0
- 2026-02-17 04:50 backlog-guard added backend-engine-service-contract-hardening-v0
- 2026-02-17 04:50 activated backend-dashboard-bundle-import-export-hub-v0
- 2026-02-17 05:00 backlog-guard completed stale backend-dashboard-bundle-import-export-hub-v0
- 2026-02-17 05:00 activated api-daa-hub-run-refresh-workflow-v0
- 2026-02-17 05:30 backlog-guard completed stale api-daa-hub-run-refresh-workflow-v0
- 2026-02-17 05:30 activated qa-hub-deeplink-compat-step-wizard-v0
- 2026-02-17 05:50 backlog-guard completed stale qa-hub-deeplink-compat-step-wizard-v0
- 2026-02-17 05:50 backlog-guard added backend-marketdata-provider-adapters-v0
- 2026-02-17 05:50 backlog-guard added frontend-uiux-dashboard-information-architecture-v0
- 2026-02-17 05:50 backlog-guard added frontend-uiux-component-consistency-shadcn-v0
- 2026-02-17 05:50 activated ops-hub-regression-smoke-pack-v0
- 2026-02-17 06:00 backlog-guard completed stale ops-hub-regression-smoke-pack-v0
- 2026-02-17 06:00 activated backend-nextjs-postgres-platform-hardening-v0
- 2026-02-17 06:30 backlog-guard completed stale backend-nextjs-postgres-platform-hardening-v0
- 2026-02-17 06:30 activated backend-engine-service-contract-hardening-v0
- 2026-02-17 06:50 activated backend-engine-service-contract-hardening-v0
- 2026-02-17 07:00 backlog-guard completed stale backend-engine-service-contract-hardening-v0
- 2026-02-17 07:00 backlog-guard added frontend-uiux-accessibility-feedback-states-v0
- 2026-02-17 07:00 activated backend-marketdata-provider-adapters-v0
- 2026-02-17 07:20 backlog-guard completed stale backend-marketdata-provider-adapters-v0
- 2026-02-17 10:21 backlog-guard added frontend-uiux-funds-hub-information-density-v0
- 2026-02-17 10:21 backlog-guard added frontend-uiux-funds-hub-step-card-hierarchy-v0
- 2026-02-17 10:21 backlog-guard added frontend-uiux-dashboard-action-rail-v0
- 2026-02-17 10:21 activated frontend-uiux-dashboard-information-architecture-v0
- 2026-02-17 10:28 backlog-guard completed stale frontend-uiux-dashboard-information-architecture-v0
- 2026-02-17 10:30 activated frontend-uiux-component-consistency-shadcn-v0
- 2026-02-17 10:50 backlog-guard completed stale frontend-uiux-component-consistency-shadcn-v0
- 2026-02-17 10:50 activated frontend-uiux-accessibility-feedback-states-v0
- 2026-02-17 11:00 backlog-guard completed stale frontend-uiux-accessibility-feedback-states-v0
- 2026-02-17 11:00 backlog-guard added frontend-uiux-dashboard-empty-state-guidance-v0
- 2026-02-17 11:00 backlog-guard added frontend-uiux-dashboard-error-recovery-v0
- 2026-02-17 11:00 backlog-guard added frontend-uiux-funds-hub-mobile-navigation-v0
- 2026-02-17 11:00 activated frontend-uiux-funds-hub-information-density-v0
- 2026-02-17 11:14 backlog-guard completed stale frontend-uiux-funds-hub-information-density-v0
- 2026-02-17 11:20 activated frontend-uiux-funds-hub-step-card-hierarchy-v0
- 2026-02-17 11:30 backlog-guard completed stale frontend-uiux-funds-hub-step-card-hierarchy-v0
- 2026-02-17 11:30 activated frontend-uiux-dashboard-action-rail-v0
- 2026-02-17 11:50 backlog-guard completed stale frontend-uiux-dashboard-action-rail-v0
- 2026-02-17 11:50 backlog-guard added frontend-uiux-funds-hub-form-friction-pass-v0
- 2026-02-17 11:50 backlog-guard added frontend-uiux-dashboard-visual-regression-guards-v0
- 2026-02-17 11:50 backlog-guard added frontend-uiux-shadcn-token-consistency-pass-v0
- 2026-02-17 11:50 activated frontend-uiux-dashboard-empty-state-guidance-v0
- 2026-02-17 12:00 backlog-guard completed stale frontend-uiux-dashboard-empty-state-guidance-v0
- 2026-02-17 12:10 activated frontend-uiux-dashboard-error-recovery-v0
- 2026-02-17 12:20 backlog-guard completed stale frontend-uiux-dashboard-error-recovery-v0
- 2026-02-17 12:20 activated frontend-uiux-funds-hub-mobile-navigation-v0
- 2026-02-17 12:30 backlog-guard completed stale frontend-uiux-funds-hub-mobile-navigation-v0
- 2026-02-17 12:30 backlog-guard added frontend-uiux-step-flow-cta-copy-pass-v0
- 2026-02-17 12:30 backlog-guard added frontend-uiux-accessibility-keyboard-focus-map-v0
- 2026-02-17 12:30 backlog-guard added frontend-uiux-performance-skeleton-loading-pass-v0
- 2026-02-17 12:30 activated frontend-uiux-funds-hub-form-friction-pass-v0
- 2026-02-17 12:50 backlog-guard completed stale frontend-uiux-funds-hub-form-friction-pass-v0
- 2026-02-17 12:50 activated frontend-uiux-dashboard-visual-regression-guards-v0
- 2026-02-17 13:00 backlog-guard completed stale frontend-uiux-dashboard-visual-regression-guards-v0
- 2026-02-17 13:00 activated frontend-uiux-shadcn-token-consistency-pass-v0
- 2026-02-17 13:30 activated frontend-uiux-shadcn-token-consistency-pass-v0
- 2026-02-17 13:37 backlog-guard completed stale frontend-uiux-shadcn-token-consistency-pass-v0
- 2026-02-17 13:40 activated frontend-uiux-step-flow-cta-copy-pass-v0
- 2026-02-17 13:50 backlog-guard completed stale frontend-uiux-step-flow-cta-copy-pass-v0
- 2026-02-17 13:50 activated frontend-uiux-accessibility-keyboard-focus-map-v0
- 2026-02-17 14:00 backlog-guard completed stale frontend-uiux-accessibility-keyboard-focus-map-v0
- 2026-02-17 14:00 activated frontend-uiux-performance-skeleton-loading-pass-v0
- 2026-02-17 14:20 backlog-guard completed stale frontend-uiux-performance-skeleton-loading-pass-v0
- 2026-02-17 17:25 backlog-guard added mainline-goal-next-js-remains-the-only-public-backend-for-no-fastapi-migration-for-v0
- 2026-02-17 17:25 backlog-guard added mainline-goal-postgres-is-the-only-persistence-for-auth-runs-audit-admin-users-v0
- 2026-02-17 17:25 backlog-guard added mainline-goal-auth-is-email-magic-link-resend-cookie-session-samesite-lax-v0
- 2026-02-17 17:25 backlog-guard added mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v0
- 2026-02-17 17:25 activated mainline-goal-next-js-remains-the-only-public-backend-for-no-fastapi-migration-for-v0
- 2026-02-17 17:50 backlog-guard completed stale mainline-goal-next-js-remains-the-only-public-backend-for-no-fastapi-migration-for-v0
- 2026-02-17 17:50 backlog-guard added mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v0
- 2026-02-17 17:50 backlog-guard added mainline-dod-sends-email-via-resend-v0
- 2026-02-17 17:50 backlog-guard added mainline-dod-sets-session-cookie-and-redirects-to-v0
- 2026-02-17 17:50 activated mainline-goal-postgres-is-the-only-persistence-for-auth-runs-audit-admin-users-v0
- 2026-02-17 18:00 backlog-guard completed stale mainline-goal-postgres-is-the-only-persistence-for-auth-runs-audit-admin-users-v0
- 2026-02-17 18:00 activated mainline-goal-auth-is-email-magic-link-resend-cookie-session-samesite-lax-v0
- 2026-02-17 18:20 backlog-guard completed stale mainline-goal-auth-is-email-magic-link-resend-cookie-session-samesite-lax-v0
- 2026-02-17 18:20 activated mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v0
- 2026-02-17 18:30 backlog-guard completed stale mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v0
- 2026-02-17 18:30 backlog-guard added mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v0
- 2026-02-17 18:30 backlog-guard added mainline-dod-prod-smoke-200-200-v0
- 2026-02-17 18:30 backlog-guard added mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v1
- 2026-02-17 18:30 activated mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v0
- 2026-02-17 18:50 backlog-guard completed stale mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v0
- 2026-02-17 18:50 activated mainline-dod-sends-email-via-resend-v0
- 2026-02-17 19:00 backlog-guard completed stale mainline-dod-sends-email-via-resend-v0
- 2026-02-17 19:00 activated mainline-dod-sets-session-cookie-and-redirects-to-v0
- 2026-02-17 19:30 backlog-guard completed stale mainline-dod-sets-session-cookie-and-redirects-to-v0
- 2026-02-17 19:30 backlog-guard added mainline-dod-sets-session-cookie-and-redirects-to-v1
- 2026-02-17 19:30 backlog-guard added mainline-dod-sends-email-via-resend-v1
- 2026-02-17 19:30 backlog-guard added mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v1
- 2026-02-17 19:30 activated mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v0
- 2026-02-17 19:50 backlog-guard completed stale mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v0
- 2026-02-17 19:50 activated mainline-dod-prod-smoke-200-200-v0
- 2026-02-17 20:00 backlog-guard completed stale mainline-dod-prod-smoke-200-200-v0
- 2026-02-17 20:00 activated mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v1
- 2026-02-17 20:20 backlog-guard completed stale mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v1
- 2026-02-17 20:20 backlog-guard added mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v2
- 2026-02-17 20:20 backlog-guard added mainline-dod-prod-smoke-200-200-v1
- 2026-02-17 20:20 backlog-guard added mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v1
- 2026-02-17 20:20 activated mainline-dod-sets-session-cookie-and-redirects-to-v1
- 2026-02-17 20:30 backlog-guard completed stale mainline-dod-sets-session-cookie-and-redirects-to-v1
- 2026-02-17 20:30 activated mainline-dod-sends-email-via-resend-v1
- 2026-02-17 20:50 backlog-guard completed stale mainline-dod-sends-email-via-resend-v1
- 2026-02-17 20:50 activated mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v1
- 2026-02-17 21:00 backlog-guard completed stale mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v1
- 2026-02-17 21:00 backlog-guard added mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v2
- 2026-02-17 21:00 backlog-guard added mainline-dod-sends-email-via-resend-v2
- 2026-02-17 21:00 backlog-guard added mainline-dod-sets-session-cookie-and-redirects-to-v2
- 2026-02-17 21:00 activated mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v2
- 2026-02-17 21:20 backlog-guard completed stale mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v2
- 2026-02-17 21:20 activated mainline-dod-prod-smoke-200-200-v1
- 2026-02-17 21:30 backlog-guard completed stale mainline-dod-prod-smoke-200-200-v1
- 2026-02-17 21:30 activated mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v1
- 2026-02-17 21:50 backlog-guard completed stale mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v1
- 2026-02-17 21:50 backlog-guard added mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v2
- 2026-02-17 21:50 backlog-guard added mainline-dod-prod-smoke-200-200-v2
- 2026-02-17 21:50 backlog-guard added mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v3
- 2026-02-17 21:50 activated mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v2
- 2026-02-17 22:00 backlog-guard completed stale mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v2
- 2026-02-17 22:00 activated mainline-dod-sends-email-via-resend-v2
- 2026-02-17 22:20 backlog-guard completed stale mainline-dod-sends-email-via-resend-v2
- 2026-02-17 22:20 activated mainline-dod-sets-session-cookie-and-redirects-to-v2
- 2026-02-17 22:30 backlog-guard completed stale mainline-dod-sets-session-cookie-and-redirects-to-v2
- 2026-02-17 22:30 backlog-guard added mainline-dod-sets-session-cookie-and-redirects-to-v3
- 2026-02-17 22:30 backlog-guard added mainline-dod-sends-email-via-resend-v3
- 2026-02-17 22:30 backlog-guard added mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v3
- 2026-02-17 22:30 activated mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v2
- 2026-02-17 22:50 backlog-guard completed stale mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v2
- 2026-02-17 22:50 activated mainline-dod-prod-smoke-200-200-v2
- 2026-02-17 23:07 backlog-guard completed stale mainline-dod-prod-smoke-200-200-v2
- 2026-02-17 23:10 activated mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v3
- 2026-02-17 23:20 backlog-guard completed stale mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v3
- 2026-02-17 23:20 backlog-guard added mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v4
- 2026-02-17 23:20 backlog-guard added mainline-dod-prod-smoke-200-200-v3
- 2026-02-17 23:20 backlog-guard added mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v3
- 2026-02-17 23:20 activated mainline-dod-sets-session-cookie-and-redirects-to-v3
- 2026-02-17 23:30 backlog-guard completed stale mainline-dod-sets-session-cookie-and-redirects-to-v3
- 2026-02-17 23:30 activated mainline-dod-sends-email-via-resend-v3

- 2026-02-17 23:50 backlog-guard completed stale mainline-dod-sends-email-via-resend-v3
- 2026-02-17 23:50 activated mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v3
- 2026-02-18 00:00 backlog-guard completed stale mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v3
- 2026-02-18 00:00 backlog-guard added mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v4
- 2026-02-18 00:00 backlog-guard added mainline-dod-sends-email-via-resend-v4
- 2026-02-18 00:00 backlog-guard added mainline-dod-sets-session-cookie-and-redirects-to-v4
- 2026-02-18 00:00 activated mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v4
- 2026-02-18 00:20 backlog-guard completed stale mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v4
- 2026-02-18 00:20 activated mainline-dod-prod-smoke-200-200-v3
- 2026-02-18 00:50 backlog-guard completed stale mainline-dod-prod-smoke-200-200-v3
- 2026-02-18 00:50 activated mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v3
- 2026-02-18 01:20 backlog-guard completed stale mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v3
- 2026-02-18 01:20 backlog-guard added mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v4
- 2026-02-18 01:20 backlog-guard added mainline-dod-prod-smoke-200-200-v4
- 2026-02-18 01:20 backlog-guard added mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v5
- 2026-02-18 01:20 activated mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v4
- 2026-02-18 01:30 backlog-guard completed stale mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v4
- 2026-02-18 01:30 activated mainline-dod-sends-email-via-resend-v4
- 2026-02-18 03:17 backlog-guard completed stale mainline-dod-sends-email-via-resend-v4
- 2026-02-18 03:17 activated mainline-dod-sets-session-cookie-and-redirects-to-v4
- 2026-02-18 10:00 backlog-guard completed stale mainline-dod-sets-session-cookie-and-redirects-to-v4
- 2026-02-18 10:00 backlog-guard added mainline-dod-sets-session-cookie-and-redirects-to-v5
- 2026-02-18 10:00 backlog-guard added mainline-dod-sends-email-via-resend-v5
- 2026-02-18 10:00 backlog-guard added mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v5
- 2026-02-18 10:00 activated mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v4
- 2026-02-18 10:07 backlog-guard completed stale mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v4
- 2026-02-18 10:10 activated mainline-dod-prod-smoke-200-200-v4
- 2026-02-18 11:00 backlog-guard completed stale mainline-dod-prod-smoke-200-200-v4
- 2026-02-18 11:00 activated mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v5
- 2026-02-18 11:17 backlog-guard completed stale mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v5
- 2026-02-18 11:17 backlog-guard added mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v6
- 2026-02-18 11:17 backlog-guard added mainline-dod-prod-smoke-200-200-v5
- 2026-02-18 11:17 backlog-guard added mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v5
- 2026-02-18 11:17 activated mainline-dod-sets-session-cookie-and-redirects-to-v5
- 2026-02-18 11:20 backlog-guard completed stale mainline-dod-sets-session-cookie-and-redirects-to-v5
- 2026-02-18 11:20 activated mainline-dod-sends-email-via-resend-v5
- 2026-02-18 11:23 mainline-dod-sends-email-via-resend-v5: merged https://github.com/Jarvis-agent-bot/Dynamic-Asset-Allocation/pull/421
- 2026-02-18 11:25 activated mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v5
- 2026-02-18 11:28 backlog-guard completed stale mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v5
- 2026-02-18 11:28 backlog-guard added mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v6
- 2026-02-18 11:28 backlog-guard added mainline-dod-sends-email-via-resend-v6
- 2026-02-18 11:28 backlog-guard added mainline-dod-sets-session-cookie-and-redirects-to-v6
- 2026-02-18 11:28 activated mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v6
- 2026-02-18 11:37 backlog-guard completed stale mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v6
- 2026-02-18 11:45 activated mainline-dod-prod-smoke-200-200-v5
- 2026-02-18 12:00 backlog-guard completed stale mainline-dod-prod-smoke-200-200-v5
- 2026-02-18 12:00 activated mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v5
- 2026-02-18 12:01 backlog-guard completed stale mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v5
- 2026-02-18 12:01 backlog-guard added mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v6
- 2026-02-18 12:01 backlog-guard added mainline-dod-prod-smoke-200-200-v6
- 2026-02-18 12:01 backlog-guard added mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v7
- 2026-02-18 12:01 activated mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v6
- 2026-02-18 12:16 backlog-guard completed stale mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v6
- 2026-02-18 12:16 activated mainline-dod-sends-email-via-resend-v6
- 2026-02-18 12:31 backlog-guard completed stale mainline-dod-sends-email-via-resend-v6
- 2026-02-18 12:31 activated mainline-dod-sets-session-cookie-and-redirects-to-v6
- 2026-02-18 12:46 backlog-guard completed stale mainline-dod-sets-session-cookie-and-redirects-to-v6
- 2026-02-18 12:46 backlog-guard added mainline-dod-sets-session-cookie-and-redirects-to-v7
- 2026-02-18 12:46 backlog-guard added mainline-dod-sends-email-via-resend-v7
- 2026-02-18 12:46 backlog-guard added mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v7
- 2026-02-18 12:46 activated mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v6

- 2026-02-18 13:01 backlog-guard completed stale mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v6
- 2026-02-18 13:01 activated mainline-dod-prod-smoke-200-200-v6

- 2026-02-18 13:16 backlog-guard completed stale mainline-dod-prod-smoke-200-200-v6
- 2026-02-18 13:16 activated mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v7
- 2026-02-18 13:31 backlog-guard completed stale mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v7
- 2026-02-18 13:31 backlog-guard added mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v8
- 2026-02-18 13:31 backlog-guard added mainline-dod-prod-smoke-200-200-v7
- 2026-02-18 13:31 backlog-guard added mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v7
- 2026-02-18 13:31 activated mainline-dod-sets-session-cookie-and-redirects-to-v7
- 2026-02-18 13:46 backlog-guard completed stale mainline-dod-sets-session-cookie-and-redirects-to-v7
- 2026-02-18 13:46 activated mainline-dod-sends-email-via-resend-v7
- 2026-02-18 14:01 backlog-guard completed stale mainline-dod-sends-email-via-resend-v7
- 2026-02-18 14:01 activated mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v7
- 2026-02-18 14:16 backlog-guard completed stale mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v7
- 2026-02-18 14:16 backlog-guard added mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v8
- 2026-02-18 14:16 backlog-guard added mainline-dod-sends-email-via-resend-v8
- 2026-02-18 14:16 backlog-guard added mainline-dod-sets-session-cookie-and-redirects-to-v8
- 2026-02-18 14:16 activated mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v8

- 2026-02-18 16:16 backlog-guard added mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v10
- 2026-02-18 16:16 backlog-guard added mainline-dod-prod-smoke-200-200-v9
- 2026-02-18 16:16 backlog-guard added mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v9
- 2026-02-18 16:16 activated mainline-dod-sets-session-cookie-and-redirects-to-v9
- 2026-02-18 16:02 backlog-guard completed stale mainline-dod-prod-smoke-200-200-v8
- 2026-02-18 16:02 activated mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v9
- 2026-02-18 15:50 backlog-guard completed stale mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v8
- 2026-02-18 15:50 activated mainline-dod-prod-smoke-200-200-v8
- 2026-02-19 03:30 backlog-guard completed stale mainline-dod-sets-session-cookie-and-redirects-to-v9
- 2026-02-19 03:30 backlog-guard completed stale mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v9
- 2026-02-19 03:30 backlog-guard completed stale mainline-dod-prod-smoke-200-200-v9
- 2026-02-19 03:30 backlog-guard completed stale mainline-goal-python-service-becomes-optional-engine-only-and-must-not-own-v9
- 2026-02-19 03:30 backlog-guard completed stale mainline-goal-remove-sqlite-from-server-runtime-no-bundler-strict-mode-footguns-v10
- 2026-02-19 03:40 activated backend-nextjs-postgres-platform-hardening-v1
- 2026-02-19 03:51 backlog-guard added backend-nextjs-postgres-platform-hardening-v2
- 2026-02-19 03:51 backlog-guard added mainline-dod-prod-smoke-200-200-v19
- 2026-02-19 03:51 backlog-guard added mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v19
- 2026-02-19 03:51 activated backend-engine-service-contract-hardening-v1
- 2026-02-19 04:01 activated frontend-uiux-dashboard-information-architecture-v1
- 2026-02-19 04:11 activated frontend-uiux-funds-hub-step-card-hierarchy-v1
- 2026-02-19 04:21 backlog-guard added frontend-uiux-funds-hub-step-card-hierarchy-v2
- 2026-02-19 04:21 backlog-guard added frontend-uiux-dashboard-information-architecture-v2
- 2026-02-19 04:21 backlog-guard added backend-engine-service-contract-hardening-v2
- 2026-02-19 04:21 activated backend-nextjs-postgres-platform-hardening-v2
- 2026-02-19 04:31 activated mainline-dod-prod-smoke-200-200-v19
- 2026-02-19 04:41 activated mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v19 (lane fallback)
- 2026-02-19 04:51 backlog-guard added mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v20
- 2026-02-19 04:51 backlog-guard added mainline-dod-prod-smoke-200-200-v20
- 2026-02-19 04:51 backlog-guard added backend-nextjs-postgres-platform-hardening-v3
- 2026-02-19 04:51 activated frontend-uiux-funds-hub-step-card-hierarchy-v2 (lane fallback)
- 2026-02-19 05:01 activated frontend-uiux-dashboard-information-architecture-v2 (lane fallback)
- 2026-02-19 05:11 activated backend-engine-service-contract-hardening-v2 (lane fallback)
- 2026-02-19 05:21 backlog-guard added backend-engine-service-contract-hardening-v3
- 2026-02-19 05:21 backlog-guard added frontend-uiux-dashboard-information-architecture-v3
- 2026-02-19 05:21 backlog-guard added frontend-uiux-funds-hub-step-card-hierarchy-v3
- 2026-02-19 05:21 activated mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v20 (lane fallback)
- 2026-02-19 05:31 activated mainline-dod-prod-smoke-200-200-v20 (lane fallback)
- 2026-02-19 05:41 activated backend-nextjs-postgres-platform-hardening-v3 (lane fallback)
- 2026-02-19 05:51 backlog-guard added backend-nextjs-postgres-platform-hardening-v4
- 2026-02-19 05:51 backlog-guard added mainline-dod-prod-smoke-200-200-v21
- 2026-02-19 05:51 backlog-guard added mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v21
- 2026-02-19 05:51 activated backend-engine-service-contract-hardening-v3 (lane fallback)
- 2026-02-19 06:01 activated frontend-uiux-dashboard-information-architecture-v3 (lane fallback)
- 2026-02-19 06:11 activated frontend-uiux-funds-hub-step-card-hierarchy-v3 (lane fallback)
- 2026-02-19 06:21 backlog-guard added frontend-uiux-funds-hub-step-card-hierarchy-v4
- 2026-02-19 06:21 backlog-guard added frontend-uiux-dashboard-information-architecture-v4
- 2026-02-19 06:21 backlog-guard added backend-engine-service-contract-hardening-v4
- 2026-02-19 06:21 activated backend-nextjs-postgres-platform-hardening-v4 (lane fallback)
- 2026-02-19 06:31 activated mainline-dod-prod-smoke-200-200-v21 (lane fallback)
- 2026-02-19 06:41 activated mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v21 (lane fallback)
- 2026-02-19 06:51 backlog-guard added mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v22
- 2026-02-19 06:51 backlog-guard added mainline-dod-prod-smoke-200-200-v22
- 2026-02-19 06:51 backlog-guard added backend-nextjs-postgres-platform-hardening-v5
- 2026-02-19 06:51 activated frontend-uiux-funds-hub-step-card-hierarchy-v4 (lane fallback)
- 2026-02-19 07:01 activated frontend-uiux-dashboard-information-architecture-v4 (lane fallback)
- 2026-02-19 07:11 activated backend-engine-service-contract-hardening-v4 (lane fallback)
- 2026-02-19 07:21 backlog-guard added backend-engine-service-contract-hardening-v5
- 2026-02-19 07:21 backlog-guard added frontend-uiux-dashboard-information-architecture-v5
- 2026-02-19 07:21 backlog-guard added frontend-uiux-funds-hub-step-card-hierarchy-v5
- 2026-02-19 07:21 activated mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v22 (lane fallback)
- 2026-02-19 07:31 activated mainline-dod-prod-smoke-200-200-v22 (lane fallback)
- 2026-02-19 07:41 activated backend-nextjs-postgres-platform-hardening-v5 (lane fallback)
- 2026-02-19 07:51 backlog-guard added backend-nextjs-postgres-platform-hardening-v6
- 2026-02-19 07:51 backlog-guard added mainline-dod-prod-smoke-200-200-v23
- 2026-02-19 07:51 backlog-guard added mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v23

- 2026-02-19 07:51 activated backend-engine-service-contract-hardening-v5 (lane fallback)
- 2026-02-19 08:10 activated frontend-uiux-dashboard-information-architecture-v5 (lane fallback)
- 2026-02-19 08:22 activated frontend-uiux-funds-hub-step-card-hierarchy-v5 (lane fallback)
- 2026-02-19 08:31 backlog-guard added frontend-uiux-funds-hub-step-card-hierarchy-v6
- 2026-02-19 08:31 backlog-guard added frontend-uiux-dashboard-information-architecture-v6
- 2026-02-19 08:31 backlog-guard added backend-engine-service-contract-hardening-v6
- 2026-02-19 08:31 activated backend-nextjs-postgres-platform-hardening-v6 (lane fallback)
- 2026-02-19 08:41 activated mainline-dod-prod-smoke-200-200-v23 (lane fallback)
- 2026-02-19 08:51 activated mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v23 (lane fallback)
- 2026-02-19 09:01 backlog-guard added mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v24
- 2026-02-19 09:01 backlog-guard added mainline-dod-prod-smoke-200-200-v24
- 2026-02-19 09:01 backlog-guard added backend-nextjs-postgres-platform-hardening-v7
- 2026-02-19 09:01 activated frontend-uiux-funds-hub-step-card-hierarchy-v6 (lane fallback)
- 2026-02-19 09:11 activated frontend-uiux-dashboard-information-architecture-v6 (lane fallback)
- 2026-02-19 09:21 activated backend-engine-service-contract-hardening-v6 (lane fallback)
- 2026-02-19 09:31 backlog-guard added backend-engine-service-contract-hardening-v7
- 2026-02-19 09:31 backlog-guard added frontend-uiux-dashboard-information-architecture-v7
- 2026-02-19 09:31 backlog-guard added frontend-uiux-funds-hub-step-card-hierarchy-v7
- 2026-02-19 09:31 activated mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v24 (lane fallback)
- 2026-02-19 09:41 activated mainline-dod-prod-smoke-200-200-v24 (lane fallback)
- 2026-02-19 09:51 activated backend-nextjs-postgres-platform-hardening-v7 (lane fallback)
- 2026-02-19 11:05 backlog-guard added backend-nextjs-postgres-platform-hardening-v8
- 2026-02-19 11:05 backlog-guard added mainline-dod-prod-smoke-200-200-v25
- 2026-02-19 11:05 backlog-guard added mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v25
- 2026-02-19 11:05 activated backend-engine-service-contract-hardening-v7 (lane fallback)
- 2026-02-19 11:11 activated frontend-uiux-dashboard-information-architecture-v7 (lane fallback)
- 2026-02-19 11:21 activated frontend-uiux-funds-hub-step-card-hierarchy-v7 (lane fallback)
- 2026-02-19 11:31 backlog-guard added frontend-uiux-funds-hub-step-card-hierarchy-v8
- 2026-02-19 11:31 backlog-guard added frontend-uiux-dashboard-information-architecture-v8
- 2026-02-19 11:31 backlog-guard added backend-engine-service-contract-hardening-v8
- 2026-02-19 11:31 activated backend-nextjs-postgres-platform-hardening-v8 (lane fallback)
- 2026-02-19 11:41 activated mainline-dod-prod-smoke-200-200-v25 (lane fallback)
- 2026-02-19 11:51 activated mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v25 (lane fallback)
- 2026-02-19 12:01 backlog-guard added mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v26
- 2026-02-19 12:01 backlog-guard added mainline-dod-prod-smoke-200-200-v26
- 2026-02-19 12:01 backlog-guard added backend-nextjs-postgres-platform-hardening-v9
- 2026-02-19 12:01 activated frontend-uiux-funds-hub-step-card-hierarchy-v8 (lane fallback)
- 2026-02-19 12:11 activated frontend-uiux-dashboard-information-architecture-v8 (lane fallback)
- 2026-02-19 12:21 activated backend-engine-service-contract-hardening-v8 (lane fallback)
- 2026-02-19 12:31 activated mainline-dod-reads-writes-postgres-contract-compatible-with-current-ui-v26 (lane fallback)
- 2026-02-19 12:40 backlog-guard completed stale feature-funds-hub-batch-edit-weights-v0
- 2026-02-19 13:03 backlog-guard added feature-dashboard-guided-empty-state-v0
- 2026-02-19 13:10 llm-autofill added feature-funds-hub-trade-execution-checklist-v0
- 2026-02-19 13:31 activated feature-dashboard-guided-empty-state-v0
- 2026-02-19 13:41 backlog-guard added feature-interaction-keyboard-shortcuts-v0
- 2026-02-19 13:41 activated feature-funds-hub-trade-execution-checklist-v0
- 2026-02-19 13:51 backlog-guard added mainline-goal-keep-next-js-as-the-only-public-backend-for-with-postgres-persistence-v0
- 2026-02-19 13:51 activated feature-interaction-keyboard-shortcuts-v0
- 2026-02-19 14:01 backlog-guard added mainline-goal-increase-user-visible-delivery-ui-polish-interaction-flow-and-practical-operator-features-v0
- 2026-02-19 14:01 activated mainline-goal-keep-next-js-as-the-only-public-backend-for-with-postgres-persistence-v0
- 2026-02-19 14:11 backlog-guard added mainline-goal-keep-daa-workflow-reliable-while-improving-speed-to-action-for-daily-operations-v0
- 2026-02-19 14:11 activated mainline-goal-increase-user-visible-delivery-ui-polish-interaction-flow-and-practical-operator-features-v0 (lane fallback)
- 2026-02-19 14:21 backlog-guard added mainline-dod-each-active-milestone-pr-includes-at-least-one-user-visible-functional-change-v0
- 2026-02-19 14:21 activated mainline-goal-keep-daa-workflow-reliable-while-improving-speed-to-action-for-daily-operations-v0 (lane fallback)
- 2026-02-19 14:31 backlog-guard added mainline-dod-and-both-improve-operator-efficiency-for-the-targeted-scenario-v0
- 2026-02-19 14:31 activated mainline-dod-each-active-milestone-pr-includes-at-least-one-user-visible-functional-change-v0 (lane fallback)
- 2026-02-19 14:41 backlog-guard added mainline-dod-backend-api-changes-preserve-contract-compatibility-and-pass-ci-build-test-typecheck-v0
- 2026-02-19 14:41 activated mainline-dod-and-both-improve-operator-efficiency-for-the-targeted-scenario-v0 (lane fallback)
- 2026-02-19 14:51 backlog-guard added mainline-dod-prod-smoke-remains-green-200-200-v0
- 2026-02-19 14:51 activated mainline-dod-backend-api-changes-preserve-contract-compatibility-and-pass-ci-build-test-typecheck-v0 (lane fallback)
- 2026-02-19 15:01 activated mainline-dod-prod-smoke-remains-green-200-200-v0 (lane fallback)
- 2026-02-19 17:32 backlog-guard added feature-live-execution-timeline-v0
- 2026-02-19 17:32 activated feature-live-execution-timeline-v0
- 2026-02-19 17:34 backlog-guard added feature-self-serve-run-debugger-v0
- 2026-02-19 17:34 activated feature-self-serve-run-debugger-v0
- 2026-02-19 17:34 backlog-guard added feature-inline-detection-review-workspace-v0
- 2026-02-19 17:36 activated feature-inline-detection-review-workspace-v0
- 2026-02-19 17:40 backlog-guard added feature-daa-command-palette-v0
- 2026-02-19 17:43 activated feature-daa-command-palette-v0
- 2026-02-19 17:50 backlog-guard added feature-funds-hub-smart-defaults-v0
- 2026-02-19 17:52 activated feature-funds-hub-smart-defaults-v0
- 2026-02-19 18:00 backlog-guard added feature-run-history-anomaly-highlights-v0
- 2026-02-19 18:02 activated feature-run-history-anomaly-highlights-v0
- 2026-02-19 18:10 backlog-guard added feature-dashboard-ops-alert-center-v0
- 2026-02-19 18:12 activated feature-dashboard-ops-alert-center-v0
- 2026-02-19 19:20 backlog-guard added feature-policy-impact-simulator-v0
- 2026-02-19 19:20 activated feature-policy-impact-simulator-v0
- 2026-02-19 19:30 backlog-guard added feature-portfolio-drift-alerts-v0
- 2026-02-19 19:30 activated feature-portfolio-drift-alerts-v0
- 2026-02-19 19:40 backlog-guard added feature-rebalance-whatif-lab-v0
- 2026-02-19 19:40 activated feature-rebalance-whatif-lab-v0
- 2026-02-19 19:50 backlog-guard added feature-run-incident-playbooks-v0
- 2026-02-19 19:50 activated feature-run-incident-playbooks-v0
- 2026-02-19 20:00 backlog-guard added feature-watchlist-signal-inbox-v0
- 2026-02-19 20:00 activated feature-watchlist-signal-inbox-v0
- 2026-02-19 20:10 backlog-guard added feature-step-readiness-score-v0
- 2026-02-19 20:10 activated feature-step-readiness-score-v0
- 2026-02-19 20:20 backlog-guard added feature-execution-cost-preview-v0
- 2026-02-19 20:20 activated feature-execution-cost-preview-v0
- 2026-02-19 20:30 backlog-guard added feature-operator-shift-handover-v0
- 2026-02-19 20:30 activated feature-operator-shift-handover-v0
- 2026-02-19 20:40 activated feature-cross-market-ledger-risk-view-v0
- 2026-02-19 20:43 activated feature-human-factor-scoreboard-v0
- 2026-02-19 20:52 activated feature-analyst-logic-consistency-alerts-v0
- 2026-02-19 21:01 activated feature-qat-weight-adjusted-targets-v0
- 2026-02-19 21:11 activated feature-rebalance-scenario-a-b-gates-v0
