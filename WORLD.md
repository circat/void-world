# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 673
last_updated: 2026-03-14T19:43:48.394082
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
position: [2.69, 0.00, 20.20]
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME_g1_0
energy: 63.900
energy_ticks: 0
age: 35
children: 1
_dir: [0.88, 0.00, 0.48]
behaviour_state: repelled

### FRAME
mesh: TETRA
color: #999999
scale: 1.400
position: [1.26, 0.00, 21.12]
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: near FRAME_g1_0
energy: 63.900
energy_ticks: 0
age: 35
children: 1
_dir: [0.57, 0.00, 0.82]
behaviour_state: repelled

### ECHO_g1_0
online: False
energy: 54.600
age: 6
children: 0
energy_ticks: 0
position: [4.65, 0.00, 22.26]
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
_dir: [0.72, 0.00, 0.69]

### FRAME_g1_0
online: False
energy: 54.600
age: 6
children: 0
energy_ticks: 0
position: [2.68, 0.00, 24.93]
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
_dir: [0.88, 0.00, 0.47]

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

*VOID v3.0 — tick 673 — 19:43:48*