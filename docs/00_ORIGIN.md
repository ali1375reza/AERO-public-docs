# Origin and project philosophy

## The initial question

AERO began with a small-capital question: can an automated system search a broad DeFi opportunity space and act only when the expected value remains positive after costs, uncertainty, and operational risk?

The first experiments were directional strategies and yield/loop-carry ideas. They did not justify a real-money product. Some versions found almost nothing because their filters were too strict; others found more activity but negative economics after funding, fees, slippage, borrowing cost, and rebalancing friction.

The project therefore changed identity. It became **AERO-LAB**, a decision-research laboratory with four rules:

1. separate risk from opportunity scoring;
2. replay past state without looking ahead;
3. observe new state in shadow mode before considering any live action;
4. preserve failures and uncertainty instead of converting them into marketing claims.

## Why the pivot mattered

FAST_ROTATION_50 explored short-horizon yield rotation. It was not abandoned because the code was inconvenient; it was stopped because the economic edge at small scale was not strong enough after real costs and uncertainty.

The next branch, ATOMIC_HUNTER_50, changed the opportunity definition. It examined atomic or near-atomic situations such as liquidations and auctions where the economic condition can be checked around the beginning of an execution window. The branch still remained research-first: historical replay, fork stress, and shadow evidence came before any consideration of live execution.

## The permanent boundary

The public project record describes the problem, experiments, evidence, incidents, and decisions. The proprietary implementation remains private. This boundary is part of the architecture, not an afterthought.

