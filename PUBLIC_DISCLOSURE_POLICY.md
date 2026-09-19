# Public disclosure policy

## Purpose

The public repository should make the project understandable and auditable without making the proprietary engine reproducible.

## Allowed

- project purpose, phase names, and high-level architecture;
- dated milestones and decision records;
- evidence class and outcome;
- aggregate or qualitative metrics that do not reveal proprietary controls;
- incidents, negative results, fixes, and lessons;
- current status, uncertainty, and roadmap gates;
- hashes of public reports when useful for chronology and integrity.

## Never publish

- source code, bytecode, ABI fragments, selectors, or executable commands;
- contracts, wallet addresses, borrower identifiers, private keys, credentials, or secret-bearing endpoints;
- exact thresholds, weights, sizing grids, fee-bidding rules, route paths, timing constants, or internal schemas;
- private VPS paths, service files, environment files, raw logs, or operational runbooks;
- data that lets a reader reconstruct the execution engine or evade its safety controls.

## Review rule

Every public change must answer four questions:

1. What changed and why?
2. What evidence supports the statement?
3. Which evidence class is it: modeled, historical, shadow, or realized?
4. Could a reader use this detail to rebuild or operate the private engine?

If the answer to the fourth question is yes or uncertain, redact the detail and preserve only the public conclusion.

## Truthfulness rule

Backtests, stress tests, historical replay, and shadow observations are never called realized profit. A missing opportunity is recorded as `NOT_OBSERVED`, not silently converted into a pass or failure. Failed versions remain in the history with their reason and correction.

