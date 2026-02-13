# DAA Tasks

## Now
- [ ] (auto) Nothing active

## Backlog


Planning note: priority = top to bottom. Keep each task ~1 PR.

Funds hub epic (human note): make `/daa/market/funds` the primary hub and expose the shortest workflow path.

Dynamic rebalancing core (main objective)

Real data + UI refactor (top priority)



Funds hub / dynamic rebalance (ops & E2E)









## Done

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
## Log

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
