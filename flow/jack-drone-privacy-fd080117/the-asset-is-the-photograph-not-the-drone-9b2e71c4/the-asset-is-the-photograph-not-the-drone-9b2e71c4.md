---
id: the-asset-is-the-photograph-not-the-drone-9b2e71c4
stage: problem_recovery
kernel: prime
temporal: false
mutagen_lineage: [breakout, addition-by-subtraction]
next: doppl
scores: { judge: 4, human: null, n: 0 }
doppelgangers: 0
---

# The Asset Is the Photograph, Not the Drone

prev_id: [[jack-drone-privacy-fd080117]]

## Trace

### Case study · synopsis

A celebrity's offshore yacht relied on being out of ordinary sight; that privacy assumption fails from above as paparazzi deploy drones.

## Discovery

### Jamming is illegal and indiscriminate

FCC Jammer Enforcement bars any private RF-jamming remedy (no business/residence exemption, fines to $112,500/incident), and a jammer in port-adjacent water hits emergency comms and aircraft, not just the target. → [[yacht-drone-privacy-7c1f4a02#^jamming-illegal-and-indiscriminate]]

### Detection is already solved

Passive RF detection (Drone Defence AeroSentry Marine, DroneShield RfAI) picks up the drone and its controller out to ~2 km, 360°, before it reaches the vessel — the warning window exists. → [[yacht-drone-privacy-7c1f4a02#^passive-rf-detection-lead-time]]

### Killing the link does not erase the footage

On ~3 s of link loss a drone fails safe to Return-to-Home and flies back to its operator; the camera records independent of the control link, so anything shot before line-of-sight is already lost. → [[yacht-drone-privacy-7c1f4a02#^rth-keeps-the-footage]]

### The value is the identifiable subject

Tabloid economics are recognition-bound: the payday is a clear shot of a known person, and a frame without an identifiable subject has near-zero commercial value. → [[yacht-drone-privacy-7c1f4a02#^value-is-the-identifiable-subject]]

## Growth — Problem recovery

### Surface complaint

Paparazzi drones are invading the owner's privacy, so the job is to stop the drones approaching the yacht.

### Deleted assumption

The threat is the drone as a physical object, so the response must neutralize the aircraft — shoot it down, jam its link, or intercept it.

### Hidden variable

Detection already wins the warning window; what is actually scarce and controllable is whether the drone departs with a *usable, identifiable* photograph. Every aircraft-directed option is either illegal (RF jamming), uncontrollable (projectile or net debris over busy water), or simply too late — a drone that loses its link still returns home with whatever its independently-recording camera already captured.

### Actual problem

Stop the drone from leaving with a commercially usable photograph of the identifiable owner — using the existing detection lead time — without a visible, illegal, or night-ruining intervention.

### Candidate response

Look in the detection window, not the airspace: the territory to search is responses that change what the drone can *capture* — exposure, sightlines, crew procedure, discreet signaling — rather than anything aimed at the aircraft. Which of those actually wins is the next stage's question, not this one's.

### Skin in the Game

- Talk to a maritime security lead about what a crew actually does in the seconds after a drone alert, and whether owner and guests will reliably respond to a subtle cue rather than a klaxon.
- Price the real cost asymmetry: a false alarm that stops the party every time a dot appears, versus one missed identifiable frame.
- Run the cheapest falsifying check first — measure detection range and drone closing speed against the time it takes exposed people to clear sightlines.

### Sprouts

- Discreet signaling as a wedge — a prompt to move that does not read as an alarm.
- Exposure and sightlines as a designable surface on deck.
- Graduated alert tiers as a guard against alarm fatigue.

### Evaluation

#### Novelty +4

Reframes off the consensus "neutralize the drone" story to "neutralize the photograph," relocating the entire problem from airspace to behavior.

#### Grounding +4

Anchored in FCC jamming law, real passive-detection ranges, documented Return-to-Home camera behavior, and the recognition-bound paparazzi value model; the seam between footage and identifiable subject is concrete and testable.

#### Falsifiability +3

Falsifier named: if footage value does *not* hinge on identifiability — context-only deck shots still sell — or if exposed people cannot reliably clear sightlines inside the warning window, the frame is wrong.

#### Cost-efficiency +3

The recovered problem points at responses that reuse detection the owner can already buy and cost mostly procedure, not kinetic hardware or regulatory risk — though confirming it is tractable still needs field contact.

#### Relevance +5

Directly serves the owner's actual brief — keep the night private, effortless, and uninterrupted — rather than winning a fight with an aircraft.

## Path

next: doppl
