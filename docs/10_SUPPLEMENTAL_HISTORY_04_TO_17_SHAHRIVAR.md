# Supplemental history and evidence review: 4–17 Shahrivar 1405

**Public review date:** 28 Shahrivar 1405 / 2026-09-19  
**Repository role:** documentation-only, public-safe record  
**Evidence posture:** Shadow or read-only unless explicitly stated otherwise

## Coverage note

Ten additional private PDFs were reviewed after the first public backfill. They contain overlapping records from 4–10 Shahrivar, a recovery-grade checkpoint labeled 15 Shahrivar, a 16 Shahrivar economic milestone, and a short report dated September 17 whose stated window ends September 16. The packet does **not** provide a separate event log for every day through 28 Shahrivar.

This document therefore records only supported conclusions from the supplied packet. It does not invent missing daily events, and it does not replace the later G5B2/G5C status already recorded in this repository.

## Chronology

### 4–7 Shahrivar: gated reliability and read-only executor work

- The earlier G0–G4 foundations were treated as closed within their stated evidence classes.
- Read-only historical executor replay closed three representative smoke cases, including a forensic split-route replay. This demonstrated replay and encoding conformance, not independent live route discovery.
- A corrected five-minute Shadow reliability burn passed after a sequence of memory, bookkeeping, semantic-response, quarantine, retry, and pacing corrections.
- An exact two-hour soak had started at the document cutoff but was still running. The document explicitly did not call it a final pass.
- Historical economics were marked as a selected-winner sample with survivorship bias. They were never presented as AERO win rate or realized income.
- No key was used, no transaction was signed or broadcast, and production policy remained disabled.

### 8–10 Shahrivar: expanded market shadow and WebSocket isolation

- The route-planning and historical-smoke work was expanded to three additional markets. Six out of six bounded historical smoke cases passed after fixture and type corrections, while the system remained fail-closed on zero or invalid inputs.
- An isolated five-market runtime was assembled without changing the production market configuration.
- The isolated universe reached 17,855 seeded borrowers. A total of 11,059 active positions were revalidated at one pinned validation head with zero decode, semantic, or position-read errors in the reported run.
- A ten-minute real Shadow canary completed with zero fatal errors. It observed no candidate or decision in that short window; this is recorded as `NOT_OBSERVED`, not as an economic failure or success.
- A differential investigation separated a stable low-level head subscription from an unstable higher-level block-watching fetch path. A runner-level raw-head patch then passed a three-minute canary with 60 observed heads, zero subscription errors, zero watchdog takeovers, and zero fatal errors.
- A 12-hour five-market economic-and-latency capture was started with a ready universe of approximately 18,350 borrowers. The packet was captured while that run was still collecting data, so no final economic conclusion is claimed from it.

### Recovery checkpoint labeled 15 Shahrivar

- Recovery work reconstructed the project after loss of conversational context without rewriting the engineering history.
- The recovered operating mode remained Shadow only: signing, broadcasting, and real-capital execution were disabled.
- A trace-concurrency guard, lower chain-read pressure, endpoint quarantine, bounded retry/backoff, and checkpointed backfill were treated as reliability measures. They were not presented as proof of production competitiveness.
- Backfill and RPC stability were still open gates. Route coverage and simulation/trace reliability remained partial or blocked in the recovery document.
- The recovery record added an explicit security rule: credentials and private runtime details must stay outside public records and be rotated privately if exposure is suspected.

### 16 Shahrivar: exact-state economic validation

- The economic validation line moved from API-level observation toward fixed-block, on-chain state verification.
- Raw state fields needed for later economic reconciliation were added to the evidence concept, including borrowed amount, collateral, oracle value, and risk-limit information. Only the public conclusion is retained here; implementation fields and identifiers are intentionally omitted.
- Historical replay still encountered provider limits and rate limits. A critical sample remained validation evidence, not liquidation proof.
- The economic simulator was not yet enabled in this milestone, and a forensic replay remained required before stronger economic claims.

### Latest dated short report in the packet

The latest short report is titled **AERO Project Documentation – September 17** and says its progress window ends September 16. It records:

- the G4-to-G5 transition;
- stabilization of the runner, health monitoring, candidate and pool discovery;
- WebSocket head flow, heartbeat/liveness monitoring, and RPC error handling;
- continuing rate-limit, endpoint-quarantine, multicall-pressure, and simulation-readiness issues;
- improvements in work-budget control, chain-read pressure, recovery logic, zero-liquidity filtering, logging, and observability;
- a next step of 6–24 hours of monitoring for stability, consistency, error rates, and simulation readiness.

This short report is preserved as a dated source statement. The repository's later G5B2/G5C status remains the authoritative current position.

## Public position at the 28 Shahrivar review date

The current repository status, which is later than some of the supplied source windows, records:

- G5B2 authoritative on-chain health validation as recorded complete;
- G5B3 multi-candidate ranking as a preliminary result whose first health display required unit-normalization correction;
- G5C exact accounting and paper-profit preparation as the active direction;
- bounded simulation/evidence and longer-duration evidence as later gates;
- no public claim of signing, broadcast, repeatable live capture, or realized profit.

This section is a status snapshot, not a claim that the older PDFs contain daily evidence for every date through 28 Shahrivar.

## Consolidated public judgment

### Supported by the packet

- Shadow safety and the separation of observation from execution.
- Candidate, market, oracle, and borrower-state validation in the stated runs.
- Deterministic economic calculation and evidence recording as research capabilities.
- A five-market shadow runtime and a low-level head-flow path that passed its stated short canary.
- A documented chain of incidents, corrections, and remaining uncertainty.

### Still not proven

- Repeatable competitive route capture.
- Stable production-like simulation success across a meaningful sample.
- Competitive end-to-end latency against other actors.
- Signed or broadcast production transactions.
- Realized net profit or a commercial performance series.

## Lessons added to the public record

1. A previous block is not always the exact state immediately before a transaction; transaction position within a block matters.
2. A successful read must be recorded as successfully checked. Otherwise closed or zero positions can re-enter the due queue and create memory pressure.
3. Provider capacity, semantic validity, and chain latency are different failure classes and need separate evidence.
4. A quarantine system must fail closed when every endpoint is unavailable; silent empty chunks create false confidence.
5. A short canary with zero candidates is an observation-window result, not proof that the market has no opportunity.
6. Runtime evidence and audit-wrapper failures must be separated so a reporting defect cannot be mistaken for a runtime defect.
7. Public documentation should preserve negative results while removing implementation details that could rebuild or operate the private engine.

## Disclosure boundary

The reviewed PDFs include implementation excerpts, private paths, exact identifiers, endpoint details, and other internal material. None of those are copied here. The public repository retains only the historical conclusion, aggregate evidence, failure mode, correction, and limitation. Raw PDFs remain outside the public repository.
