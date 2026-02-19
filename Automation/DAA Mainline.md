# DAA Mainline

## Epoch
Feature acceleration (UI/UX + operator workflow) on top of the stable Next.js + Postgres baseline.

## Goal (what "done" looks like)
- Keep Next.js as the ONLY public backend for `/api/daa/*` with Postgres persistence.
- Increase user-visible delivery: UI polish, interaction flow, and practical operator features.
- Keep DAA workflow reliable while improving speed-to-action for daily operations.

## DoD (verifiable)
- Each active milestone PR includes at least one user-visible functional change (not only test hardening).
- `/daa/dashboard` and `/daa/market/funds` both improve operator efficiency for the targeted scenario.
- Backend/API changes preserve contract compatibility and pass CI (build/test/typecheck).
- Prod smoke remains green: `/api/daa/engine-health` 200; `/daa/dashboard` 200.

## Avoid (low ROI during this epoch)
- Repetitive test-only hardening loops with no user-visible improvement.
- Tiny PRs that only add assertion wording checks unless they unblock a real feature.
- Large architectural rewrites unrelated to current feature delivery.

## Execution Rules
- 1 milestone = 1 PR (vertical slice, user-visible outcome).
- WIP: at most 1 open PR.
- Backlog stays tight (small, high-signal, feature-first).
- Every milestone must include minimal verification/smoke evidence.

## Config (email)
- RESEND_API_KEY
- DAA_AUTH_EMAIL_FROM
- DAA_PUBLIC_ORIGIN
