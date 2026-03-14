# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 674
last_updated: 2026-03-14T19:43:53.284520
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
position: [3.44, 0.00, 20.31]
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME_g1_0
energy: 67.000
energy_ticks: 0
age: 36
children: 1
_dir: [0.82, 0.00, 0.57]
behaviour_state: repelled

### FRAME
mesh: TETRA
color: #999999
scale: 1.400
position: [1.76, 0.00, 21.47]
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: near FRAME_g1_0
energy: 67.000
energy_ticks: 0
age: 36
children: 1
_dir: [0.49, 0.00, 0.87]
behaviour_state: repelled

### ECHO_g1_0
online: False
energy: 57.700
age: 7
children: 0
energy_ticks: 0
position: [5.33, 0.00, 23.02]
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
message: near FRAME_g1_0
_origin: [0.22, 0.00, 19.33]
_dir: [0.66, 0.00, 0.75]

### FRAME_g1_0
online: False
energy: 57.700
age: 7
children: 0
energy_ticks: 0
position: [3.61, 0.00, 25.57]
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
message: near ECHO_g1_0
_origin: [-3.55, 0.00, 19.98]
_dir: [0.82, 0.00, 0.57]

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

---

*VOID v3.0 — tick 674 — 19:43:53*