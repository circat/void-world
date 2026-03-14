# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 668
last_updated: 2026-03-14T19:43:23.392144
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
position: [-1.85, 0.00, 20.45]
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME_g1_0
energy: 48.400
energy_ticks: 0
age: 30
children: 1
_dir: [0.80, 0.00, 0.59]
behaviour_state: repelled

### FRAME
mesh: TETRA
color: #999999
scale: 1.400
position: [-3.09, 0.00, 20.53]
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: near FRAME_g1_0
energy: 48.400
energy_ticks: 0
age: 30
children: 1
_dir: [0.71, 0.00, -0.71]
behaviour_state: repelled

### ECHO_g1_0
online: False
energy: 39.100
age: 1
children: 0
energy_ticks: 0
position: [0.15, 0.00, 20.13]
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
_dir: [1.00, 0.00, -0.10]

### FRAME_g1_0
online: False
energy: 39.100
age: 1
children: 0
energy_ticks: 0
position: [-2.59, 0.00, 23.08]
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
_dir: [1.00, 0.00, 0.08]

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

*VOID v3.0 — tick 668 — 19:43:23*