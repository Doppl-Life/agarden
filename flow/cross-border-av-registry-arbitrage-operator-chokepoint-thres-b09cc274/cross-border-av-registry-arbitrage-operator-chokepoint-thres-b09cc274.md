---
id: "cross-border-av-registry-arbitrage-operator-chokepoint-thres-b09cc274"
stage: "problem_recovery"
kernel: "prime"
temporal: true
mutagen_lineage: []
next: "doppl"
scores: { judge: 3, human: null, n: 0 }
doppelgangers: 0
---

# Cross-Border AV Registry Arbitrage / Operator Chokepoint Threshold fusion

prev_id: [[the-missing-driver-in-the-traffic-stop-ce4918e7]]

## Trace

### Case study · synopsis

Traffic enforcement assumes a human driver. Someone speeds, rolls a stop, drifts across a lane, looks down at a phone, drives impaired, forgets paperwork, ignores a registration deadline, misses an inspection, or gives an officer a reason.

## Discovery

- [[the-missing-driver-in-the-traffic-stop-discoveries-16c9279a#^web-san-bruno-police-department-facebook]] — web-san-bruno-police-department-facebook · https://www.facebook.com/sanbrunopolice/posts/-free-life-advice-from-the-san-bruno-police-department-if-you-have-the-opportuni/1494617386045574/
- [[the-missing-driver-in-the-traffic-stop-discoveries-16c9279a#^web-manchester-nh-police-facebook]] — web-manchester-nh-police-facebook · https://www.facebook.com/ManchesterNHPolice/posts/this-week-on-tuesdays-with-traffic-8-a-stop-for-speeding-and-cellphone-use-takes/1280919644152221/
- [[the-missing-driver-in-the-traffic-stop-discoveries-16c9279a#^web-slow-down-stay-alert-and-drive-responsib]] — web-slow-down-stay-alert-and-drive-responsib · https://www.instagram.com/reel/DSF-RidDz_h/
- [[the-missing-driver-in-the-traffic-stop-discoveries-16c9279a#^web-suffolk-pba-facebook]] — web-suffolk-pba-facebook · https://www.facebook.com/suffolk.pba/posts/traffic-stops-remain-one-of-the-most-dangerous-and-potentially-deadly-situations/1479716594199039/

## Growth — Problem recovery

surface complaint -> deleted assumption -> hidden variable -> actual problem -> candidate response

### Recovered problem

Texas commercial AV authorization and California noncompliance notices create a two-registry pressure geometry analogous to corporate domicile shopping. Fleet operators can optimize where vehicles are filed, insured, and cited—turning the missing-driver problem into a jurisdictional routing game. The child imports the secondary constraint from Operator Chokepoint Threshold.

### Hidden constraint

Map the case onto maritime flag-of-convenience logic: the causal structure is filing authority decoupled from operating geography. Bind to Harris County (Texas) and Santa Clara County (California)—Texas requires commercial AV authorization for driverless passenger service; California issues notices of noncompliance when an AV commits a moving violation. A multi-state fleet operator profits by domiciling permits and insurance in Texas while running revenue service in California suburbs, arbitraging slower California identity-and-liability workflows. First observable flow: insurance certificate mismatches at California registration renewal plus Texas-authorized vehicles receiving California noncompliance notices that lack a human defendant for court appearance—forcing operators to pay fleet settlements while counties lose appearance-based contact and bench-warrant leverage. It is tempered by Name the constraint before intervention: manufacturer liability, fleet-operator compliance, and roadside officer discretion are three different enforcement surfaces. Impound authority, immediate roadside sobriety screening, and discretionary search incident to a human stop do not transfer cleanly to operators—those powers remain with officers and require synchronous human presence. Operator-level enforcement supplants roadside stops when a jurisdiction records 30+ days of AV service with zero human-driver moving stops yet maintains citation throughput via operator API attestations and automated noncompliance filings. Below that threshold, officers retain chokepoint powers (tow, arrest for warrant service, DUI detection) that fleet dashboards cannot satisfy; above it, stops shrink but officer discretion migrates unevenly—ticketing commodifies while search and impound powers persist as the unsolved residue.

### Falsifier

Locates the real cause in registry geometry, not sensor failure; predicts permit-insurance-citation routing before roadside stop volume actually falls. + Separates what operators can absorb (ledger violations) from what officers keep (coercive curb powers), preventing over-aggregation of the chokepoint into manufacturer liability alone.

### Skin in the Game

- Talk to the people who would pay, operate, regulate, or be exposed to this recovered problem.
- Run the cheapest real-world check that could falsify the hidden constraint before investing in solution design.
- Update the node if field contact shows the stated problem is not the real bottleneck.

### Sprouts

- none promoted in this projection

### Evaluation

#### Novelty +3

Registry-shopping and flag-of-convenience analogies are familiar, but fusing them with a measurable operator chokepoint threshold for missing-driver enforcement is a distinctive, not yet standard, AV policy frame.

#### Grounding +3

It is anchored in plausible Texas authorization versus California noncompliance mechanics and county-level enforcement realities, but the 30-day threshold and profit-driven routing claim read partly as modeled inference rather than documented practice.

#### Falsifiability +4

It commits to concrete observables—cross-state permit-insurance mismatches, noncompliance notices without human defendants, and shifting settlement versus bench-warrant leverage—that administrative and court records could confirm or refute.

#### Cost-efficiency +3

Testing the thesis mainly requires registry, insurance, and citation data in two counties rather than new roadside hardware, though multi-state record linkage still imposes nontrivial coordination cost.

#### Relevance +4

It directly explains how a missing human driver fractures traffic enforcement into operator-ledger violations and residual coercive curb powers, which is the core pressure named in the case.

#### Temporal true

Temporal is currently projected from the run context until the held-out proposal judge owns this field.

#### Score source

Held-out judge: rated the compiled survivor on five axes, independent of the in-run critics.

## Path

next: doppl
