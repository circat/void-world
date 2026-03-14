# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 683
last_updated: 2026-03-14T19:44:41.305368
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
position: [10.29, 0.00, 17.32]
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME_g2_0
energy: 59.900
energy_ticks: 0
age: 45
children: 2
_dir: [0.98, 0.00, -0.18]
behaviour_state: repelled

### FRAME
mesh: TETRA
color: #999999
scale: 1.400
position: [9.35, 0.00, 18.51]
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: near ECHO_g2_0
energy: 59.900
energy_ticks: 0
age: 45
children: 2
_dir: [1.00, 0.00, -0.06]
behaviour_state: repelled

### ECHO_g1_0
online: False
energy: 50.600
age: 16
children: 1
energy_ticks: 0
position: [12.51, 0.00, 19.91]
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
message: near FRAME_g2_0
_origin: [0.22, 0.00, 19.33]
_dir: [0.58, 0.00, -0.81]

### FRAME_g1_0
online: False
energy: 50.600
age: 16
children: 1
energy_ticks: 0
position: [9.95, 0.00, 21.03]
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
message: near ECHO_g2_0
_origin: [-3.55, 0.00, 19.98]
_dir: [-0.89, 0.00, -0.45]

### ECHO_g1_1
online: False
energy: 48.400
age: 4
children: 0
energy_ticks: 0
position: [9.35, 0.00, 15.41]
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
message: near FRAME_g2_0
_origin: [9.39, 0.00, 20.75]
_dir: [0.74, 0.00, -0.68]

### FRAME_g1_1
online: False
energy: 48.400
age: 4
children: 0
energy_ticks: 0
position: [7.36, 0.00, 18.17]
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
message: near FRAME_g2_0
_origin: [4.87, 0.00, 22.88]
_dir: [0.82, 0.00, -0.58]

### ECHO_g2_0
online: False
energy: 39.100
age: 1
children: 0
energy_ticks: 0
position: [13.03, 0.00, 21.22]
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
message: near FRAME_g2_0
_origin: [12.41, 0.00, 22.95]
_dir: [0.90, 0.00, -0.43]

### FRAME_g2_0
online: False
energy: 39.100
age: 1
children: 0
energy_ticks: 0
position: [9.15, 0.00, 20.17]
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
message: near ECHO_g2_0
_origin: [8.40, 0.00, 22.10]
_dir: [0.85, 0.00, -0.53]

---

## events
- VOID v3.0 initialisiert
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

---

*VOID v3.0 — tick 683 — 19:44:41*