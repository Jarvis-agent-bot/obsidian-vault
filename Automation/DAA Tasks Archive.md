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
