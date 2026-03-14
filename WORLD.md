# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 681
last_updated: 2026-03-14T19:44:30.952231
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
position: [8.69, 0.00, 18.26]
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME_g1_1
energy: 53.700
energy_ticks: 0
age: 43
children: 2
_dir: [0.99, 0.00, -0.16]
behaviour_state: repelled

### FRAME
mesh: TETRA
color: #999999
scale: 1.400
position: [7.53, 0.00, 19.38]
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: near ECHO_g1_1
energy: 53.700
energy_ticks: 0
age: 43
children: 2
_dir: [1.00, 0.00, -0.05]
behaviour_state: repelled

### ECHO_g1_0
online: False
energy: 79.400
age: 14
children: 0
energy_ticks: 0
position: [10.97, 0.00, 21.14]
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
_dir: [0.90, 0.00, -0.43]

### FRAME_g1_0
online: False
energy: 79.400
age: 14
children: 0
energy_ticks: 0
position: [9.85, 0.00, 21.75]
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
_dir: [0.92, 0.00, -0.40]

### ECHO_g1_1
online: False
energy: 42.200
age: 2
children: 0
energy_ticks: 0
position: [7.63, 0.00, 16.62]
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
_dir: [0.87, 0.00, -0.50]

### FRAME_g1_1
online: False
energy: 42.200
age: 2
children: 0
energy_ticks: 0
position: [5.31, 0.00, 18.99]
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
_dir: [0.98, 0.00, -0.19]

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

*VOID v3.0 — tick 681 — 19:44:30*