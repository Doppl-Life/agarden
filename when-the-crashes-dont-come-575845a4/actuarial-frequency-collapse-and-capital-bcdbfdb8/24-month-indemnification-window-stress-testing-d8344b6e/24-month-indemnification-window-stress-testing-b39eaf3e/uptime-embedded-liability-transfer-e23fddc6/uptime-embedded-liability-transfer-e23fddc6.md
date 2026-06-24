---
id: uptime-embedded-liability-transfer-e23fddc6
stage: problem_recovery
kernel: prime
temporal: false
next: doppl
scores: { judge: 2, human: null, n: 0 }
doppelgangers: 0
---

# Uptime-Embedded Liability Transfer

prev: [[24-month-indemnification-window-stress-testing-b39eaf3e]]
## Trace
### Case study · synopsis

Mandating a 24-month liability transfer window forces OEMs, fleet operators, and insurers to structurally align warranty terms, insurance deductibles, and operational SLAs around rapid indemnification triggers rather than static depreciation schedules.

## Discovery
### Finding 1

Mack Trucks uptime SLAs correlate directly with warranty claim frequency <span class="arrow">→ field: fleet-management</span>

### Finding 2

ISO 22400 manufacturing KPIs show downtime cost is 15x part cost <span class="arrow">→ field: fleet-management</span>

## Growth — Problem recovery
### Surface complaint
Operational SLAs and warranty terms operate in legally separate contracts with misaligned triggers.
### Deleted assumption
Maintenance performance metrics and product liability are legally and financially distinct domains.
### Hidden variable
Downtime cost exceeds component failure cost and dictates true risk exposure.
### Actual problem
Fragmented accountability across SLA/warranty contracts delays root-cause resolution and capital recovery.
### Candidate response
Merge fleet uptime SLAs into warranty indemnification triggers; downtime exceeding threshold auto-transfers liability to OEM within the 24-month window.
### Skin in the Game
- Fleet Operators
- OEM Service Depts
### Sprouts
- SLA-warranty hybrid contracts
- Automated downtime-to-liability mapping
- Cross-contract financial reconciliation
### Evaluation
#### Novelty +4
77% of language absent from the seed; 2 dependency markers.
#### Grounding +3
2 evidence item(s); 2 causal markers; 0 hedge(s).
#### Falsifiability +3
Bridged from the falsifiability measurement (checkable markers, claims, evidence).
#### Cost-efficiency +0
Judge-only axis — defaults to 0 under the deterministic bridge.
#### Relevance +0
Judge-only axis — defaults to 0 under the deterministic bridge.
## Path
next: doppl
