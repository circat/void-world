# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 669
last_updated: 2026-03-14T19:43:28.254395
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
position: [-0.85, 0.00, 20.21]
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME_g1_0
energy: 51.500
energy_ticks: 0
age: 31
children: 1
_dir: [0.99, 0.00, 0.16]
behaviour_state: repelled

### FRAME
mesh: TETRA
color: #999999
scale: 1.400
position: [-1.94, 0.00, 20.04]
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: near FRAME_g1_0
energy: 51.500
energy_ticks: 0
age: 31
children: 1
_dir: [0.99, 0.00, -0.11]
behaviour_state: repelled

### ECHO_g1_0
online: False
energy: 42.200
age: 2
children: 0
energy_ticks: 0
position: [1.16, 0.00, 20.30]
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
_dir: [0.99, 0.00, 0.17]

### FRAME_g1_0
online: False
energy: 42.200
age: 2
children: 0
energy_ticks: 0
position: [-1.47, 0.00, 23.18]
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
_dir: [1.00, 0.00, 0.09]

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

*VOID v3.0 — tick 669 — 19:43:28*