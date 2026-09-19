# Validation results and boundaries

## Results supported by the historical record

### Research and replay

- Early research became repeatable enough to compare hypotheses rather than rely on isolated scripts.
- A major event-definition error in replay was found and corrected.
- Historical Full-TX and fork work reproduced past mechanics and helped separate mechanical validity from economic validity.

### Multi-market shadow

- The opportunity census showed that the reference market was not the whole market universe.
- Multi-market state and trigger surfaces were exercised.
- Exact health checks and shadow decision rules operated together.
- In windows with no liquidatable position, zero route attempts was the correct fail-closed outcome.

### Transport and coverage

- Coverage gaps caused by fixed priority tiers were identified and addressed with adaptive ranking and refresh.
- Provider fallbacks and chunking strategies improved resilience.
- A short v0.38 stage-1 gate passed with no recorded lane failures; the longer burn-in remained separate.
- Provider context semantics were revised after zero pending hashes made an older identity assumption unsafe.

### L0/L1 shadow preparation

- Funded-shadow preparation, evidence manifests, runtime boundaries, and controlled-decision review were recorded.
- Initial and extended shadow cycles passed in the documented window.
- Manual approval remained required; signing and broadcast were disabled.

### G5 line after the historical cut-off

- G5B2 on-chain health validation confirmed that candidate discovery must be reconciled with authoritative market, oracle, and position state.
- G5B3 processed a broader candidate set and produced a watch-oriented ranking. The first displayed health values were implausibly scaled, so the result was marked preliminary and the normalization path was corrected.
- G5C shifted the focus from “is this position close?” to “is the debt, interest, collateral, cost, and execution accounting precise enough for a paper-profit decision?”

## Explicitly not proven

- repeated live liquidation or auction capture;
- competitive first-capture performance;
- signed or broadcast production transactions;
- a stable series of realized net profit;
- indefinite future coverage recall;
- a commercial license market or customer demand.

