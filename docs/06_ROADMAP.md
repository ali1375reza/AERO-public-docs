# Roadmap and readiness gates

## Completed or substantially supported

- research foundation and evidence discipline;
- historical replay and controlled fork mechanics;
- multi-market shadow architecture;
- exact state/oracle/health validation layers;
- adaptive coverage and provider resilience work;
- L0 funded-shadow preparation and L1 controlled-decision preparation;
- G5B2 on-chain health validation;
- G5B3 preliminary multi-candidate risk ranking.

## Current sequence

### G5C exact accounting

Reconcile protocol state, debt representation, interest accrual, collateral, and economic inputs. The public gate is not “a number appeared”; it is that the accounting agrees across independent views within a declared tolerance and evidence package.

### G5C paper profit

Build a paper-only economic statement that includes the relevant execution costs, sizing, route feasibility, and failure states. It must remain distinct from realized P&L.

### Simulation and evidence loop

Run a bounded simulation/evidence window, preserve every accepted and rejected case, and report coverage, latency, stale-state rejects, provider failures, and economic outcomes.

### Longer-duration validation

Repeat the loop over longer windows, with explicit stop conditions and storage/retention checks. A single quiet window is not proof of capture quality.

### Controlled readiness review

Only after the evidence gates pass should the project consider a separate review of custody, caps, kill switch, failed-transaction budget, monitoring, and manual approval. This repository does not unlock execution.

### Commercialization gate

Commercial claims require a separate evidence package containing repeated realized net results, operational reliability, legal/IP review, and evidence of customer demand. The project’s policy is to require three consecutive positive months before treating profitability as a commercial claim; this is a gate, not a forecast.

## Anti-loop rule

Do not create a new phase merely to create activity. A new version or branch requires a documented defect, a measurable hypothesis, and an exit gate.

