# DAA System Smoke Test — 2026-02-13

Base URL (prod): https://exwxyzi.cn
Test runner: OpenClaw (manual curl-style probes)

## Executive Summary

- Engine connectivity (Next.js -> nginx `/daa-api/*` -> Python engine): PASS (`/api/daa/engine-health` 200)
- Step5 simulate endpoint (Next.js proxy -> Python): PASS (`/api/daa/rebalance/simulate` 200)
- Market data (server-side routes):
  - Yahoo RSS: PASS (200)
  - Xueqiu quote: PASS (200, token configured)
  - TwitterData tokenInfo: PASS (200, token redacted)
- Core rebalance endpoint (pure TS core logic): FAIL in prod (`/api/daa/rebalance/core` returned 404 HTML)
- Market digest endpoint (intended for VPS-local cron): FAIL (`/api/daa/analysis/market-digest` returned 500 `fetch failed`)
- Funds Hub upstream (third-party public endpoints used by UI JSONP): PASS (basic HTTP 200 headers)

## Detailed Results

### 1) Engine Health

- Request: `GET /api/daa/engine-health`
- Status: 200
- Body (snippet): `{ "ok": true, "service": "daa-engine", "version": "0.1.0" }`
- Meaning: nginx `/daa-api/*` routing is working and the Python engine is reachable.

### 2) Market — Yahoo Finance RSS (No Token)

- Request: `GET /api/daa/market/yahoo/rss?symbol=AAPL`
- Status: 200
- Meaning: server-side fetch to Yahoo RSS is OK.

### 3) Market — Xueqiu Realtime Quote (Token Required)

- Request: `GET /api/daa/market/xueqiu/quotec?symbol=SH000001`
- Status: 200
- Meaning: `XUEQIU_TOKEN` is configured on the server and upstream is reachable.

### 4) Market — TwitterData Token Info (Token Required)

- Request: `GET /api/daa/market/twitter/token-info`
- Status: 200
- Body note: token is returned as `REDACTED` by design (good).
- Meaning: `TWITTERDATA_TOKEN` is configured and upstream is reachable.

### 5) Rebalance (Step5) — Simulate (Python Engine)

- Request: `POST /api/daa/rebalance/simulate`
- Status: 200
- Sample response observed:
  - `orders`: BUY SPY (1500), SELL QQQ (1500)
  - `explain.policy`: `v0 heuristic`
- Meaning: Step5 simulate API is alive end-to-end.
- Note: engine is still v0 heuristic (does not consider existing positions; no portfolio-level optimization).

### 6) Rebalance (Core) — Deterministic TS Logic

- Request: `POST /api/daa/rebalance/core`
- Status: 404 (HTML page)
- Meaning: prod deployment currently does NOT expose this route (either not deployed yet, or routing/build mismatch).
- Impact: core algorithm can exist in repo, but the prod API for it is missing, so UI cannot rely on it.

### 7) Analysis — Market Digest (VPS-local cron endpoint)

- Request: `GET /api/daa/analysis/market-digest`
- Status: 500 (`fetch failed`)
- Meaning: as deployed, this endpoint is not usable. It is intended to run only on VPS-local `127.0.0.1` and internally calls other market endpoints.
- Next step: debug why internal fetch fails (origin/host assumptions, proxy headers, network, or runtime restrictions).

### 8) Funds Hub — Third-party Upstreams (UI JSONP style)

These are not Next.js API routes; they are public endpoints used by the Funds Hub page.

- `https://fundgz.1234567.com.cn/js/000001.js` -> HTTP 200
- `https://qt.gtimg.cn/q=jj000001` -> HTTP 200
- `https://fundf10.eastmoney.com/FundArchivesDatas.aspx?...` -> HTTP 200

Meaning: basic upstream availability is OK, but stability/format drift risk remains (unofficial endpoints).

## Conclusions (What Is "Real" vs "Scaffold" Today)

- Real (prod): Python engine connectivity, Step5 simulate, Yahoo/Xueqiu/TwitterData server-side fetch.
- Not fully real yet:
  - Step1 backtest uses mock price series provider.
  - Step4 baseline signals flow is still designed for manual price-series input (per docs).
  - Execution live adapter is still placeholder (paper mode only).
  - Core rebalance API route missing in prod.
  - Market digest endpoint broken in prod.

## TODO Candidates Derived From This Smoke Test

1) Fix prod: expose `/api/daa/rebalance/core` (route exists in repo but 404 in prod).
2) Fix prod: `/api/daa/analysis/market-digest` (should be VPS-local and reliable for cron usage).
3) Crypto v0: OKX integration (server-side market data), normalize into existing market event/price schema.
4) Data layer v1: unify asset model (funds + HK/US equities + gold + crypto) so rebalancing works across categories.
5) UI/UX: after data layer is stable, integrate into a single "one-click" workflow (import holdings -> fetch data -> propose -> explain -> paper execution log).
