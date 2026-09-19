# Current status after the 10 Shahrivar historical cut-off

This note keeps the historical backfill stable while recording later work. It is intentionally concise and public-safe.

## G5B2 - authoritative on-chain health validation

The candidate pipeline was rechecked against authoritative market parameters, borrower position state, and oracle data. The purpose was to replace assumed or discovery-only values with independently verified state. A liquidation call probe still returned an input/eligibility rejection, so the result was recorded as validation progress, not execution success.

## G5B3 - near-liquidation ranking

A broader Base candidate set was processed and a watch-oriented ranking was produced. The first displayed health values were obviously mis-scaled. That output is retained as a diagnostic incident, not a claim. The correction path is validated normalization and rerun evidence.

## G5C - economic proof and accounting

The project then moved from “which positions are close?” to “can debt, interest, collateral, cost, sizing, and route feasibility be reconciled precisely enough for a paper-profit decision?” The current planned sequence is exact accounting, paper profit, and then a bounded simulation/evidence loop.

## Public status

- Candidate discovery and on-chain verification: **SUPPORTED**.
- Health/risk ranking: **SUPPORTED with a corrected-normalization history**.
- Paper economic proof: **IN PROGRESS**.
- Autonomous atomic simulation/evidence bridge: **BLOCKED / next gate**.
- Live execution and realized profit: **NOT_PROVEN**.

