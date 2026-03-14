# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 679
last_updated: 2026-03-14T19:44:20.577969
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
position: [7.05, 0.00, 19.33]
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME_g1_1
energy: 47.500
energy_ticks: 0
age: 41
children: 2
_dir: [0.91, 0.00, -0.41]
behaviour_state: repelled

### FRAME
mesh: TETRA
color: #999999
scale: 1.400
position: [5.63, 0.00, 20.42]
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: near FRAME_g1_1
energy: 47.500
energy_ticks: 0
age: 41
children: 2
_dir: [0.95, 0.00, -0.31]
behaviour_state: repelled

### ECHO_g1_0
online: False
energy: 73.200
age: 12
children: 0
energy_ticks: 0
position: [9.16, 0.00, 22.07]
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
message: near ECHO_g1_1
_origin: [0.22, 0.00, 19.33]
_dir: [0.44, 0.00, -0.90]

### FRAME_g1_0
online: False
energy: 73.200
age: 12
children: 0
energy_ticks: 0
position: [8.02, 0.00, 23.01]
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
message: near ECHO_g1_1
_origin: [-3.55, 0.00, 19.98]
_dir: [0.57, 0.00, -0.82]

### ECHO_g1_1
online: False
energy: 36.000
age: 0
children: 0
energy_ticks: 0
position: [5.78, 0.00, 17.66]
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
message: near FRAME_g1_1
_origin: [9.39, 0.00, 20.75]

### FRAME_g1_1
online: False
energy: 36.000
age: 0
children: 0
energy_ticks: 0
position: [3.08, 0.00, 19.46]
behaviour: flock
behaviour_speed: 0.284
behaviour_range: 18.700
behaviour_state: active
behaviour_stage: 1
scale: 1.390
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME
generation: 1
message: near ECHO_g1_1
_origin: [4.87, 0.00, 22.88]

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

---

*VOID v3.0 — tick 679 — 19:44:20*