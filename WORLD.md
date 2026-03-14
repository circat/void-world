# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 676
last_updated: 2026-03-14T19:44:04.476477
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
position: [4.73, 0.00, 20.57]
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME_g1_0
energy: 73.200
energy_ticks: 0
age: 38
children: 1
_dir: [0.78, 0.00, 0.63]
behaviour_state: repelled

### FRAME
mesh: TETRA
color: #999999
scale: 1.400
position: [2.90, 0.00, 21.87]
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: near FRAME_g1_0
energy: 73.200
energy_ticks: 0
age: 38
children: 1
_dir: [0.69, 0.00, 0.73]
behaviour_state: repelled

### ECHO_g1_0
online: False
energy: 63.900
age: 9
children: 0
energy_ticks: 0
position: [6.99, 0.00, 24.00]
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
message: near FRAME
_origin: [0.22, 0.00, 19.33]
_dir: [0.98, 0.00, 0.20]

### FRAME_g1_0
online: False
energy: 63.900
age: 9
children: 0
energy_ticks: 0
position: [5.79, 0.00, 25.53]
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
message: near FRAME
_origin: [-3.55, 0.00, 19.98]
_dir: [0.96, 0.00, -0.28]

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

*VOID v3.0 — tick 676 — 19:44:04*