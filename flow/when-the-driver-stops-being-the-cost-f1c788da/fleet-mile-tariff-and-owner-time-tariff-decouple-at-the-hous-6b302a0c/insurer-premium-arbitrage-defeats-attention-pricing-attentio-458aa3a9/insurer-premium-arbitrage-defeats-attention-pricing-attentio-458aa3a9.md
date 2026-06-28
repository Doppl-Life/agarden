---
id: "insurer-premium-arbitrage-defeats-attention-pricing-attentio-458aa3a9"
stage: "doppl"
kernel: "prime"
temporal: true
mutagen_lineage: []
next: null
scores: { judge: 3, human: null, n: 0 }
doppelgangers: 0
---

# Insurer-Premium Arbitrage Defeats Attention Pricing / Attention-Reprice Gate Before Loss-Ratio Pass-Through fusion / Corridor-Swap Payoff When Attention-Hour Cost Clears First fusion

prev_id: [[fleet-mile-tariff-and-owner-time-tariff-decouple-at-the-hous-6b302a0c]]

## Trace

### Case study · synopsis

--- id: fsd-mobility-and-time-b23b5a5d stage: case_study name: "When The Driver Stops Being The Cost" next: problem_recovery --- prev_id: null Tesla's Robotaxi rollout is still limited, and supervised FSD still requires an

### Problem recovery · synopsis

Demand, incentives, constraints, and feedback loops split cleanly: fleet-mile pricing ($/mile) and owner-time pricing ($/attention-hour) are separate ledgers that only converge when intervention load hits zero. The non-obvious dependent st.

## Discovery

- [[municipal-bond-3f2a1c08#^fine-revenue-cliff]] — fine-revenue-cliff
- [[claims-adjustment-9d4b7e21#^adjuster-disintermediation]] — adjuster-disintermediation
- [[financial-derivatives-7a1c4e90#^freq-trigger]] — freq-trigger
- [[financial-derivatives-7a1c4e90#^standardized-credit-events]] — standardized-credit-events

## Growth — Doppl

### Claim

Most likely failure: owner-as-insurer-of-last-resort premium in supervised tiers is not a price — it is a cross-subsidy pool fleets will arbitrage by pushing interventions off-ledger. Probing this trap is prerequisite to any viable dual-ledger design. The child imports the secondary constraint from Attention-Reprice Gate Before Loss-Ratio Pass-Through. The child imports the secondary constraint from Corridor-Swap Payoff When Attention-Hour Cost Clears First.

### Implications

- Mechanism: When mile cost falls, operators face incentive to reclassify supervised interventions as 'maintenance events' or route them through captive insurers that recycle premium internally — keeping attention-hour ledger artificially low while loss experience stays on the insurer-of-last-resort tier. Frequency collapse reprices loss ratios slowly (freq-trigger strand risk), so the arbitrage window persists across multiple renewal cycles. Stress-test requirement: any candidate dual-ledger scheme must include intervention-audit hooks tied to NAIC-grade telematics event classes (not self-reported attention logs) and anti-captive clauses before mile/attention split is marketed as convergent. It is tempered by Hard sequencing rule in supervised subscription contracts: (1) per-mile attention surcharge adjusts on telematics-derived intervention-frequency indices quarterly; (2) loss-ratio pass-through to owner-time pricing is locked until step (1) completes two consecutive periods. Fleet-mile ledger absorbs frequency-driven attention cost; owner-time ledger absorbs only residual human-insurance premium after frequency signal stabilizes. Contractually blocks the common failure mode — collapsing ledgers on mile-cost declines while the attention insurer premium is still frequency-unpriced. It is tempered by Fleet routes supervised vehicles away from muni attestation-heavy corridors (fine-revenue-cliff enforcement pressure) toward corridors with OEM direct-settlement coverage and low contested-incidence. Swap economics: avoid attention-hour tariff on high-attestation miles even if $/mile is equal. First corridor where attention-hour cost clears: TX OEM settlement zone with intervention load < gate and no muni attestation surcharge. Fusion with insurer-of-last-resort premium: swap proceeds fund attention-hour hedge (standardized AIE) so premium unsticks without waiting for loss-ratio cycle.
- Claimed delta: Surfaces the dominant failure mode that makes naive ledger separation cosmetic; forces verification layer without which claimed convergence at intervention load zero is unenforceable. + Enforces correct repricing order at contract layer; prevents ~30–50% basis-risk misallocation between mile and attention ledgers during the autonomy transition window. + Finds payoff inversion beyond cheaper miles—corridor swap value equals avoided attention-hour tariff plus released reserve, measurable when swap routes show lower $/attention-hour than stay routes at identical $/mile.
- Parent lineage: child_cand_g0_skeptic_premium_arbitrage_trap_cand_g0_constraint_attention_before_loss + cand_g1_breakthrough_corridor_swap_premium_clear
- Inherited traits: child_cand_g0_skeptic_premium_arbitrage_trap_cand_g0_constraint_attention_before_loss: primary mechanism at 0.512; cand_g1_breakthrough_corridor_swap_premium_clear: constraint and failure-mode pressure at 0.488
- Mutation notes: Combined mechanisms only after separate parent scoring and compatibility check.

### Opportunities

- Use this doppl as the action surface for the recovered problem.
- Test the claimed delta against the falsifier from the problem-recovery node.
- Promote the doppl only if follow-up evidence shows the mechanism creates a real advantage.

### Sprouts

- none promoted in this projection

### Evaluation

#### Novelty +3

The insurer-arbitrage trap plus contractual repricing gate and corridor-swap payoff fuse familiar insurance and routing ideas into a distinctive dual-ledger diagnosis, but none of the core mechanisms are wholly new.

#### Grounding +3

Frequency-loss lag, captive recycling, and telematics event classes are credible industry mechanics, yet the TX corridor example, AIE hedge, and 30–50% basis-risk figure read as asserted rather than evidenced.

#### Falsifiability +4

The proposal names testable observables—telematics-class intervention counts versus self-reported logs, quarterly gate completion, and swap-route $/attention-hour spreads—that could confirm or refute cosmetic ledger separation.

#### Cost-efficiency +2

NAIC-grade audit hooks, anti-captive clauses, and corridor routing add substantial compliance and operations cost, with payoff contingent on the claimed misallocation savings materializing.

#### Relevance +5

It squarely targets why attention stays priced after mile cost falls—unpriced insurer-of-last-resort premium and arbitrage—and encodes the imported frequency-collapse constraint as enforceable contract sequencing.

#### Temporal true

Temporal is currently projected from the run context until the held-out proposal judge owns this field.

#### Score source

Held-out judge: rated the compiled survivor on five axes, independent of the in-run critics.

## Path

null
