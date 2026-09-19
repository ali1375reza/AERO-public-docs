# Incidents, failures, fixes, and lessons

The project treats a failure as evidence about the system. The public record keeps the incident, the effect, the correction, and the remaining uncertainty.

| Incident | Effect | Public correction / lesson |
|---|---|---|
| Filters too strict | Almost no opportunities survived | Instrument where candidates disappear; do not guess that more filtering means more quality. |
| Filters too loose | Activity increased but economics became negative | Reintroduce complete cost and risk accounting; trade count is not edge. |
| Replay event-definition bug | Artificially inflated decision count | Batch complete snapshots before deciding. |
| Incomplete LP P&L | Historical model omitted part of execution economics | Downgrade the model to a rejection/research tool; do not use it as a live permit. |
| Clock drift and stale-state risk | Time checks could be contaminated | Use authoritative timestamps and explicit freshness guards. |
| Public RPC timeout/rate limit | Performance tests stopped or slowed | Classify transport failure separately from `NO_EDGE`; add fallback and bounded retry. |
| Provider quota exhaustion | Long shadow run stopped after repeated refresh failures | Fail closed; never continue on stale coverage. |
| WebSocket protocol mismatch | A free endpoint could not provide the required event channel | Test protocol support empirically; separate polling from event transport. |
| Fixed coverage tiers | Near-threshold positions could be displaced | Keep the full universe visible and adapt priority capacity. |
| Zero pending hash | Older context identity proof became unsafe | Treat provider hash as telemetry and require independent reconfirmation. |
| Busy-skip under event load | One hot worker could not keep up | Tune concurrency from telemetry, then rerun the gate. |
| Disk and swap pressure | Operational readiness was reduced | Treat storage and retention as part of production readiness. |
| Runtime dependency mismatch | A shadow runner failed before validation | Record runtime provenance and use a validated environment. |
| Stale output/provenance collision | A new candidate could appear to reuse old evidence | Freeze source/evidence identity and keep per-run output separation. |
| Default stop reason mistaken for completion | Risk of a false PASS | Require a real endpoint, fresh evidence, and an explicit three-state gate. |
| Healthy-vs-liquidatable confusion | Route work could be launched for an ineligible position | Reconcile authoritative state before any route stage. |
| Oracle valuation mismatch | A liquidation probe reached protocol validation but was rejected | Investigate price semantics and historical state before changing the economic conclusion. |
| Health-factor unit mismatch | Initial rank values were implausibly scaled | Mark the output preliminary, correct normalization, and rerun validation. |
| Route/calldata rejection | Repeated probes did not establish executable capture | Preserve the failure and keep route execution blocked until the input/state contract is proven. |

## General lessons

1. Correctness is a chain: discovery, state, freshness, economics, and execution must agree.
2. A provider failure is not an economic result.
3. A historical or fork success is not live profitability.
4. A missing opportunity is a measured `NOT_OBSERVED`, not a hidden pass.
5. Evidence identity and storage hygiene are part of engineering, not administration.

