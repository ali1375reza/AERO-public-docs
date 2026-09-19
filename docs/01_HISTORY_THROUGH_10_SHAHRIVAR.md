# Project history through 10 Shahrivar 1405

**Calendar cut-off:** 10 Shahrivar 1405 / 2026-09-01

This is a public narrative reconstructed from the supplied daily records and handoff dossiers. It deliberately compresses implementation detail and keeps only the facts needed to understand progress, failure, and readiness.

## Phase 0 - Day Zero

The project started as a small-capital DeFi research effort. Directional trading and yield ideas were tested first. The decisive lesson was economic: more signals or more trades do not create an edge when cost, funding, slippage, reward conversion, or uncertainty consume the return.

## Phase 1 - AERO-LAB research foundation

The early AERO-LAB generations moved from read-only data collection to strict backtesting, risk scanning, forward shadow, cohort comparison, replay, calibration, and operational safety. A major replay defect was discovered: rows from one complete state snapshot were being treated as independent events. Batching the snapshot before making a decision restored methodological credibility.

The foundation also introduced the distinction between:

- a model that looks attractive on historical or synthetic data;
- a shadow decision that survives current-state checks;
- an actual realized result.

## Phase 2 - FAST_ROTATION_50

The short-horizon yield branch tested 24/48/72-hour rotation ideas with a small shared budget. Calibration and holdout results were explicitly kept in forward-shadow status. The branch was stopped because gas, slippage, reward conversion, uncertainty, and incomplete LP accounting consumed too much of the available edge. The decision was to pivot rather than weaken risk gates.

## Phase 3 - ATOMIC_HUNTER_50 foundations

ATOMIC_HUNTER_50 reframed the opportunity as an atomic or short-window event. The public milestones progressed from a Morpho watcher and an auction watcher to risk/economic gates, exact final validation, an evidence layer, historical Full-TX replay, multi-market stress, real-state workers, dynamic sizing, a route/economic gate, and a fail-safe/dedup/audit guard.

The public conclusion at this point was not “profitable bot.” It was that historical mechanics and a disciplined shadow decision chain could be tested without signing or broadcasting.

## Phase 4 - cbXRP and multi-market shadow line

The next generations concentrated on exact state, route/economics, event timing, coverage, and provider behavior. Several important corrections were made:

- pending event context was separated from authoritative state;
- bounded synchronization was introduced when event and HTTP views were not aligned;
- fixed hot/warm coverage tiers were replaced by adaptive coverage after a rank-miss risk was found;
- performance timeouts were separated from economic rejection;
- provider fallback and fail-closed refresh rules were added.

The long-wait shadow run demonstrated stable event handling for hours but observed no real economic trigger. It stopped when provider capacity was exhausted, which was treated as an operational failure and not as a profit or logic success.

## Phase 5 - v0.37 and v0.38 transport redesign

Fork stress work showed that two independent route paths could execute against controlled historical/current state. That was a mechanics result, not live capture evidence.

The next transport generation removed dependence on a single provider. Public HTTP polling, sealed full refresh, alternate provider paths, and an event-driven provider were compared. A short stage-1 gate passed with no lane failures and materially lower busy-skip after measured concurrency tuning. The longer burn-in remained a separate gate.

The all-zero pending-hash behavior of some providers invalidated an older context-proof assumption. The project retained the provider value as telemetry and introduced a separate fingerprint/reconfirmation concept. A real candidate reconfirmation was still outstanding.

## Phase 6 - Opportunity Census and Parallel Capture Architecture

While the reference soak ran, a read-only opportunity census tested whether the reference market represented the whole opportunity supply. The answer was no: historical evidence suggested that other markets deserved evaluation. A separate multi-market capture branch was built, tested, frozen, and closed without modifying the reference baseline.

The branch showed:

- market-state triggers can be detected without relying only on price movement;
- exact health checks can be combined with a shadow decision core;
- a no-opportunity snapshot must correctly produce zero route attempts;
- historical route evidence supports research priority but not realized profit.

## Phase 7 - 27 to 31 Mordad and 1 Shahrivar

The records for 27-28 Mordad focused on the final technical gate, evidence freezing, provenance, and a safe handoff from the reference soak to the next candidate. The main operational lessons were to require a real endpoint, not a default stop reason; keep output identity separate between runs; avoid unsafe interactive shell behavior; and treat disk/swap pressure as readiness risks.

By 29 Mordad the Integrated Candidate had passed its public verification layers and observed state-change triggers, while no liquidatable row appeared in the recorded snapshot. Route and economic stages therefore remained unopened by design.

The 30 Mordad record moved into L0 funded-shadow runtime validation. A runtime dependency mismatch was found and corrected by using the validated project environment. Initial and extended shadow cycles passed, with signing and broadcast disabled.

The 31 Mordad record documented the transition toward an L1 controlled single-shot decision point. Manual approval was required, automatic execution remained disabled, and a previous evidence label was corrected so that the documented decision chain matched the actual stage.

The 1 Shahrivar summary recorded the broader architecture: watcher, borrower/state reading, health and oracle validation, trigger pipeline, exact confirmation, safety layer, parallel capture, yield research, forward shadow, long-duration validation, and L0 candidate preparation. It also recorded the recurring risks: provider instability, reconnects, false triggers, event/state mismatch, and execution safety.

## Position at the 10 Shahrivar cut-off

At the public cut-off, AERO was a mature pre-live, evidence-disciplined research stack. Candidate detection, exact state validation, economic modelling, safety controls, and evidence recording had meaningful support. Live competitive capture, signed transactions, broadcast, and realized profit remained unproven.

The next responsible step was not to add features indiscriminately. It was to close accounting and evidence gaps, then advance through controlled gates.

