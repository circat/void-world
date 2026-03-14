# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 694
last_updated: 2026-03-14T19:45:38.423343
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
position: [13.88, 0.00, 7.56]
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME_g2_2
energy: 59.000
energy_ticks: 0
age: 56
children: 3
_dir: [0.19, 0.00, -0.98]
behaviour_state: repelled

### FRAME
mesh: TETRA
color: #999999
scale: 1.400
position: [11.30, 0.00, 8.49]
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: near ECHO_g2_2
energy: 59.000
energy_ticks: 0
age: 56
children: 3
_dir: [-0.34, 0.00, -0.94]
behaviour_state: repelled

### ECHO_g1_0
online: False
energy: 49.700
age: 27
children: 2
energy_ticks: 0
position: [15.13, 0.00, 9.67]
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
message: near FRAME_g2_2
_origin: [0.22, 0.00, 19.33]
_dir: [0.66, 0.00, -0.75]

### FRAME_g1_0
online: False
energy: 49.700
age: 27
children: 2
energy_ticks: 0
position: [10.13, 0.00, 12.82]
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
message: near FRAME_g2_2
_origin: [-3.55, 0.00, 19.98]
_dir: [-0.51, 0.00, 0.86]

### ECHO_g1_1
online: False
energy: 47.500
age: 15
children: 1
energy_ticks: 0
position: [10.87, 0.00, 4.41]
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
message: near FRAME_g2_2
_origin: [9.39, 0.00, 20.75]
_dir: [-0.01, 0.00, -1.00]

### FRAME_g1_1
online: False
energy: 47.500
age: 15
children: 1
energy_ticks: 0
position: [7.95, 0.00, 6.60]
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
message: near FRAME_g2_2
_origin: [4.87, 0.00, 22.88]
_dir: [-0.07, 0.00, -1.00]

### ECHO_g2_0
online: False
energy: 73.200
age: 12
children: 0
energy_ticks: 0
position: [14.07, 0.00, 11.40]
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
message: near FRAME_g2_2
_origin: [12.41, 0.00, 22.95]
_dir: [0.28, 0.00, -0.96]

### FRAME_g2_0
online: False
energy: 73.200
age: 12
children: 0
energy_ticks: 0
position: [7.45, 0.00, 8.96]
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
message: near ECHO_g2_2
_origin: [8.40, 0.00, 22.10]
_dir: [-0.08, 0.00, -1.00]

### ECHO_g1_2
online: False
energy: 48.400
age: 4
children: 0
energy_ticks: 0
position: [9.84, 0.00, 8.42]
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
_dir: [-0.20, 0.00, -0.98]

### FRAME_g1_2
online: False
energy: 49.200
age: 4
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
message: near FRAME_g2_2
_origin: [12.36, 0.00, 10.26]
_pulse_phase: 16.000

### ECHO_g2_1
online: False
energy: 39.100
age: 1
children: 0
energy_ticks: 0
position: [12.50, 0.00, 8.82]
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
message: near FRAME_g2_2
_origin: [13.58, 0.00, 12.43]
_dir: [-0.35, 0.00, -0.94]

### FRAME_g2_1
online: False
energy: 39.100
age: 1
children: 0
energy_ticks: 0
position: [9.99, 0.00, 9.31]
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
message: near ECHO_g2_2
_origin: [8.64, 0.00, 13.56]
_dir: [-0.76, 0.00, -0.65]

### ECHO_g2_2
online: False
energy: 36.000
age: 0
children: 0
energy_ticks: 0
position: [9.53, 0.00, 6.46]
behaviour: flock
behaviour_speed: 0.251
behaviour_range: 17.900
behaviour_state: repelled
behaviour_stage: 1
scale: 1.210
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO_g1_1
generation: 2
message: near FRAME_g2_1
_origin: [12.94, 0.00, 2.84]

### FRAME_g2_2
online: False
energy: 36.000
age: 0
children: 0
energy_ticks: 0
position: [9.71, 0.00, 8.55]
behaviour: flock
behaviour_speed: 0.296
behaviour_range: 20.900
behaviour_state: repelled
behaviour_stage: 1
scale: 1.380
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g1_1
generation: 2
message: near ECHO_g2_1
_origin: [9.67, 0.00, 9.55]

---

## events
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
- ECHO_g1_1 -> ECHO_g2_2 (gen 2)
- FRAME_g1_1 -> FRAME_g2_2 (gen 2)

---

*VOID v3.0 — tick 694 — 19:45:38*