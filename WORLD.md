# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 680
last_updated: 2026-03-14T19:44:25.536205
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
position: [7.87, 0.00, 18.77]
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME_g1_1
energy: 50.600
energy_ticks: 0
age: 42
children: 2
_dir: [0.98, 0.00, -0.18]
behaviour_state: repelled

### FRAME
mesh: TETRA
color: #999999
scale: 1.400
position: [6.59, 0.00, 19.89]
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: near ECHO_g1_1
energy: 50.600
energy_ticks: 0
age: 42
children: 2
_dir: [1.00, 0.00, -0.03]
behaviour_state: repelled

### ECHO_g1_0
online: False
energy: 76.300
age: 13
children: 0
energy_ticks: 0
position: [10.05, 0.00, 21.58]
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
_dir: [0.88, 0.00, -0.48]

### FRAME_g1_0
online: False
energy: 76.300
age: 13
children: 0
energy_ticks: 0
position: [8.81, 0.00, 22.20]
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
message: near FRAME_g1_1
_origin: [-3.55, 0.00, 19.98]
_dir: [0.70, 0.00, -0.72]

### ECHO_g1_1
online: False
energy: 39.100
age: 1
children: 0
energy_ticks: 0
position: [6.71, 0.00, 17.15]
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
_dir: [0.88, 0.00, -0.48]

### FRAME_g1_1
online: False
energy: 39.100
age: 1
children: 0
energy_ticks: 0
position: [4.19, 0.00, 19.20]
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
message: near ECHO_g1_1
_origin: [4.87, 0.00, 22.88]
_dir: [0.97, 0.00, -0.23]

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

*VOID v3.0 — tick 680 — 19:44:25*