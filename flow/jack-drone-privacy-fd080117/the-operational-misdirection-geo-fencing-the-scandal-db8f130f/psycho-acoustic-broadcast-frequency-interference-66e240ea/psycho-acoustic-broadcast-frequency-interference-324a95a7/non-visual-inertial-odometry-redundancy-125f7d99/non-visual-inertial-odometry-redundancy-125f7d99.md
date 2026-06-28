---
id: non-visual-inertial-odometry-redundancy-125f7d99
stage: problem_recovery
kernel: prime
temporal: false
next: doppl
scores: { judge: 2, human: null, n: 0 }
doppelgangers: 0
---

# Non-Visual Inertial Odometry Redundancy

prev_id: [[psycho-acoustic-broadcast-frequency-interference-324a95a7]]

## Trace
### Case study · synopsis

Utilizing a low-power, directional acoustic transmitter that broadcasts specific, ultra-low frequency (infrasound) tones below the threshold of conscious hearing but known to affect human equilibrium and peripheral vision. This causes subtle disorientation or 'visual flicker' in drone camera lenses operating on optical stabilization algorithms.

## Discovery
### Finding 1

Military-grade Inertial Navigation System (INS) principles. → [[physics-inertial-navigation-0c3b4f4a#^non-visual-inertial-odometry]]

### Finding 2

Aerodynamics research on low-frequency air resistance. → [[physics-inertial-navigation-0c3b4f4a#^non-visual-inertial-odometry]]

## Growth — Problem recovery
### Surface complaint
Infrasound causes visual flicker in drone optical stabilization.
### Deleted assumption
That the primary source of positional data must be the camera's visual input (VIO).
### Hidden variable
The inherent coupling between low-frequency atmospheric disturbances and inertial measurement unit (IMU) drift rates.
### Actual problem
Over-reliance on Visual Inertial Odometry (VIO), which is highly susceptible to environmental noise that mimics positional change.
### Candidate response
Implement a redundant, self-contained navigation system based solely on relative inertial measurements (accelerometers and gyroscopes) calibrated against known atmospheric models. This 'Blind IMU' would track position changes independent of optical confirmation, using differential pressure readings to correct for drift caused by external forces like the infrasound.
### Skin in the Game
- High-grade Fiber Optic Gyroscopes (FOG)
- Atmospheric drag modeling
- Differential pressure correction loops
### Sprouts
- Navigation in complete GPS denial environments.
- Improved stability for deep submersible applications.
### Evaluation
#### Novelty +4
89% of language absent from the seed; 2 dependency markers.
#### Grounding +3
2 evidence item(s); 3 causal markers; 0 hedge(s).
#### Falsifiability +3
Bridged from the falsifiability measurement (checkable markers, claims, evidence).
#### Cost-efficiency +0
Judge-only axis — defaults to 0 under the deterministic bridge.
#### Relevance +0
Judge-only axis — defaults to 0 under the deterministic bridge.
## Path
next: doppl
