# AERO-LAB Public Development Record

**Documentation-only repository | Public evidence and project history**

AERO (also referred to as **aria** in some working notes) is a proprietary research and execution platform for selecting and validating atomic DeFi opportunities. This repository is a public trust record, not the product repository.

It explains:

- why the project started and how its scope changed;
- what each major phase tried to prove;
- what passed, what failed, and what remains uncertain;
- how evidence is classified and reviewed;
- what the current gates and roadmap are.

The project is **not presented as a retail trading bot** and this repository does not make a profitability guarantee.

## Public boundary

This repository intentionally contains no source code, contracts, executable scripts, private keys, credentials, private endpoints, exact sensitive addresses, proprietary thresholds, route construction, bidding rules, or other details that could reconstruct the engine.

Raw PDFs, logs, configuration files, and implementation archives remain outside this public repository. The public files are written from those records after a disclosure review.

## Start here

| Need | Document |
|---|---|
| Five-minute overview | [Project status](PROJECT_STATUS.md) |
| Persian overview | [خلاصهٔ فارسی](README.fa.md) |
| Full origin and history | [Project history](docs/01_HISTORY_THROUGH_10_SHAHRIVAR.md) |
| Public architecture | [Public architecture](docs/02_PUBLIC_ARCHITECTURE.md) |
| Evidence rules | [Evidence methodology](docs/03_EVIDENCE_METHODOLOGY.md) |
| Results and limits | [Validation results](docs/04_VALIDATION_RESULTS.md) |
| Failures and lessons | [Incidents and lessons](docs/05_INCIDENTS_AND_LESSONS.md) |
| Next gates | [Roadmap](docs/06_ROADMAP.md) |
| Disclosure rules | [Public disclosure policy](PUBLIC_DISCLOSURE_POLICY.md) |

## Current public position

- The project has moved from research construction into staged economic and execution validation.
- Candidate discovery, on-chain state checks, oracle interpretation, health validation, economic modelling, safety gates, and evidence recording have been exercised in shadow or simulated modes.
- G5B2 on-chain health validation is recorded as complete; G5B3 ranking was run over a multi-candidate set and its first output was treated as preliminary because of a unit-normalization issue.
- The current direction is G5C exact accounting, then paper-profit validation, then a bounded simulation/evidence loop.
- No repeatable live capture, signed transaction, broadcast, or realized profit is claimed here.

## Evidence language

`PROVEN` means the stated test passed within its stated evidence class. `SUPPORTED` means several independent observations support the claim but a stronger gate remains. `NOT_OBSERVED` means the relevant opportunity did not occur in the observation window. `NOT_PROVEN` means the project has not yet collected the evidence required for the claim.

## Naming note

Historical notes use AERO-LAB, FAST_ROTATION_50, and ATOMIC_HUNTER_50. These are public phase labels only; they do not expose implementation.

## License and ownership

See [NOTICE.md](NOTICE.md). The public record does not grant rights to proprietary software, algorithms, data, or execution infrastructure.

