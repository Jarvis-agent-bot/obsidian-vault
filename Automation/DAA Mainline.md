# DAA Mainline

## Epoch
Human-factor-coupled global dynamic rebalance: ship user-visible capability while keeping execution deterministic, auditable, and guardrail-first.

## Core Philosophy
- Math floor: dynamic rebalance keeps allocation inside risk envelope.
- Wisdom filter: quality-adjust targets by human-factor and short-term signal bias.
- Risk isolation: hard execution gates prevent single-point blowups.

## Goal (what "done" looks like)
- Keep Next.js as the ONLY public backend for `/api/daa/*` with Postgres persistence.
- Deliver a usable W_qat decision flow:
  - `W_qat = W_base * H_multiplier * AI_bias`
  - operator-visible factor trace for every recommendation.
- Build human-factor evaluation and logic-consistency loop:
  - analyst/manager tiering (elite/neutral/incompetent)
  - thesis-regime drift alerts and controlled down-weighting.
- Enforce guardrail-first execution:
  - MaxIn/MaxOut limits
  - liquidity caps
  - T+N settlement and cash-gap gating.
- Keep AI as recommender only (no auto trade execution).

## DoD (verifiable)
- Each milestone PR includes at least one user-visible functional change (not test-only).
- `/daa/market/funds` shows decision transparency for targeted slice (inputs, gates, and rationale).
- Scenario routing is explicit and testable:
  - Scenario A (strong-hold): threshold can widen when quality/signal supports it.
  - Scenario B (value-trap): buy path is blocked or sell-only/force-exit path is selected.
- Buy recommendations must pass: non-incompetent tag + MaxIn not locked + liquidity/T+N gate pass.
- Backend/API changes preserve contract compatibility and pass CI (build/test/typecheck).
- Prod smoke remains green: `/api/daa/engine-health` 200; `/daa/dashboard` 200.

## Avoid (low ROI during this epoch)
- Repetitive hardening/test-only loops with no capability movement.
- Prompt-only tweaks without deterministic contract or evidence.
- Any hidden auto-execution path bypassing human confirmation.

## Execution Rules
- 1 milestone = 1 PR (vertical slice, user-visible outcome).
- WIP: at most 1 open PR.
- Backlog stays tight (small, high-signal, feature-first, architecture-aligned).
- Single-writer backlog mutation remains in core autopilot.
- Planner is read-only candidate relay (deterministic, no free-form key/title generation).
- Every milestone includes minimal verification evidence and rollback note.

## Config (email)
- RESEND_API_KEY
- DAA_AUTH_EMAIL_FROM
- DAA_PUBLIC_ORIGIN
