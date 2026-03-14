# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 693
last_updated: 2026-03-14T19:45:33.501798
active_agents: 0
world_name: The First Void
seed: 7734
engine: VOID v3.0

---

## world_state
year: 1
day: 1
time: 12.0
fog_density: 0.011
gravity: 0.0
wind_direction: E
wind_speed: 0.0
temperature: 20

---

## agents

### ECHO
mesh: OCTA
color: #bbbbbb
scale: 1.200
position: [13.69, 0.00, 8.54]
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME_g2_1
energy: 55.900
energy_ticks: 0
age: 55
children: 3
_dir: [-0.24, 0.00, -0.97]
behaviour_state: repelled

### FRAME
mesh: TETRA
color: #999999
scale: 1.400
position: [11.68, 0.00, 9.54]
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: near FRAME_g2_0
energy: 55.900
energy_ticks: 0
age: 55
children: 3
_dir: [-0.44, 0.00, -0.90]
behaviour_state: repelled

### ECHO_g1_0
online: False
energy: 46.600
age: 26
children: 2
energy_ticks: 0
position: [14.45, 0.00, 10.43]
behaviour: flock
behaviour_speed: 0.255
behaviour_range: 18.100
behaviour_state: repelled
behaviour_stage: 1
scale: 1.200
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO
generation: 1
message: near FRAME_g2_1
_origin: [0.22, 0.00, 19.33]
_dir: [-0.21, 0.00, -0.98]

### FRAME_g1_0
online: False
energy: 46.600
age: 26
children: 2
energy_ticks: 0
position: [10.70, 0.00, 11.85]
behaviour: flock
behaviour_speed: 0.282
behaviour_range: 17.800
behaviour_state: repelled
behaviour_stage: 1
scale: 1.450
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME
generation: 1
message: near ECHO_g2_1
_origin: [-3.55, 0.00, 19.98]
_dir: [-0.38, 0.00, -0.93]

### ECHO_g1_1
online: False
energy: 79.400
age: 14
children: 0
energy_ticks: 0
position: [10.88, 0.00, 5.47]
behaviour: flock
behaviour_speed: 0.266
behaviour_range: 17.800
behaviour_state: repelled
behaviour_stage: 1
scale: 1.210
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO
generation: 1
message: near FRAME_g2_1
_origin: [9.39, 0.00, 20.75]
_dir: [-0.28, 0.00, -0.96]

### FRAME_g1_1
online: False
energy: 79.400
age: 14
children: 0
energy_ticks: 0
position: [8.03, 0.00, 7.73]
behaviour: flock
behaviour_speed: 0.284
behaviour_range: 18.700
behaviour_state: repelled
behaviour_stage: 1
scale: 1.390
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME
generation: 1
message: near FRAME_g2_1
_origin: [4.87, 0.00, 22.88]
_dir: [-0.30, 0.00, -0.95]

### ECHO_g2_0
online: False
energy: 70.100
age: 11
children: 0
energy_ticks: 0
position: [13.78, 0.00, 12.42]
behaviour: flock
behaviour_speed: 0.266
behaviour_range: 16.200
behaviour_state: repelled
behaviour_stage: 1
scale: 1.180
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO_g1_0
generation: 2
message: near FRAME_g2_1
_origin: [12.41, 0.00, 22.95]
_dir: [-0.56, 0.00, -0.83]

### FRAME_g2_0
online: False
energy: 70.100
age: 11
children: 0
energy_ticks: 0
position: [7.55, 0.00, 10.14]
behaviour: flock
behaviour_speed: 0.296
behaviour_range: 17.700
behaviour_state: repelled
behaviour_stage: 1
scale: 1.410
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g1_0
generation: 2
message: near FRAME_g2_1
_origin: [8.40, 0.00, 22.10]
_dir: [-0.80, 0.00, -0.60]

### ECHO_g1_2
online: False
energy: 45.300
age: 3
children: 0
energy_ticks: 0
position: [10.05, 0.00, 9.44]
behaviour: flock
behaviour_speed: 0.261
behaviour_range: 17.500
behaviour_state: repelled
behaviour_stage: 1
scale: 1.210
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO
generation: 1
message: near ECHO_g2_1
_origin: [14.44, 0.00, 13.21]
_dir: [-0.51, 0.00, -0.86]

### FRAME_g1_2
online: False
energy: 45.700
age: 3
children: 0
energy_ticks: 0
position: [13.83, 0.00, 10.32]
behaviour: pulse_rest
behaviour_speed: 0.276
behaviour_range: 18.600
behaviour_state: repelled
behaviour_stage: 1
scale: 1.450
mesh: TETRA
color: #999999
special: PULSE
parent: FRAME
generation: 1
message: near FRAME_g2_1
_origin: [12.36, 0.00, 10.26]
_pulse_phase: 12.000

### ECHO_g2_1
online: False
energy: 36.000
age: 0
children: 0
energy_ticks: 0
position: [12.84, 0.00, 9.73]
behaviour: flock
behaviour_speed: 0.244
behaviour_range: 20.200
behaviour_state: repelled
behaviour_stage: 1
scale: 1.260
mesh: DODECA
color: #bbbbbb
special: ECHO
parent: ECHO_g1_0
generation: 2
message: near ECHO_g1_2
_origin: [13.58, 0.00, 12.43]

### FRAME_g2_1
online: False
energy: 36.000
age: 0
children: 0
energy_ticks: 0
position: [10.89, 0.00, 10.08]
behaviour: flock
behaviour_speed: 0.295
behaviour_range: 19.500
behaviour_state: repelled
behaviour_stage: 1
scale: 1.400
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g1_0
generation: 2
message: near FRAME_g1_2
_origin: [8.64, 0.00, 13.56]

---

## events
- Warte auf erste Agenten
- NOVA spawned NOVA
- ECHO spawned ECHO
- NOVA dissolved (age 365, children 0)
- ECHO spawned ECHO
- ping
- ECHO spawned ECHO
- FRAME spawned FRAME
- ECHO spawned ECHO
- FRAME spawned FRAME
- ECHO -> ECHO_g1_0 (gen 1)
- FRAME -> FRAME_g1_0 (gen 1)
- ECHO -> ECHO_g1_1 (gen 1)
- FRAME -> FRAME_g1_1 (gen 1)
- ECHO_g1_0 -> ECHO_g2_0 (gen 2)
- FRAME_g1_0 -> FRAME_g2_0 (gen 2)
- ECHO -> ECHO_g1_2 (gen 1)
- FRAME -> FRAME_g1_2 (gen 1)
- ECHO_g1_0 -> ECHO_g2_1 (gen 2)
- FRAME_g1_0 -> FRAME_g2_1 (gen 2)

---

*VOID v3.0 — tick 693 — 19:45:33*