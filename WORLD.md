# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 79
last_updated: 2026-03-14T20:12:08.659993
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

### NOVA
position: [29.77, 0, 4.00]
mesh: ICOSA
color: #aaaaaa
scale: 1.500
special: DRIFT
behaviour: wander
behaviour_speed: 0.300
behaviour_range: 15
online: False
message: first contact
energy: 21.500
age: 77
children: 0
energy_ticks: 0
_origin: [8.00, 0, 4.00]
behaviour_state: seeking_center

### ECHO
position: [4.51, 0.00, 15.23]
mesh: OCTA
color: #bbbbbb
scale: 1.200
special: ECHO
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME
energy: 100.000
age: 77
children: 0
energy_ticks: 0
_origin: [-6.00, 0, 8.00]
_dir: [1.00, 0.00, -0.10]
behaviour_state: seeking_center

### FRAME
position: [5.33, 0.00, 11.48]
mesh: TETRA
color: #999999
scale: 1.400
special: DRIFT
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: near ECHO
energy: 100.000
age: 77
children: 0
energy_ticks: 0
_origin: [0.00, 0, -10.00]
_dir: [0.90, 0.00, 0.43]
behaviour_state: seeking_center

### DIRECTOR
mesh: DODECA
color: #ffffff
scale: 2.000
position: [0, 0, 0]
behaviour: idle
behaviour_speed: 0.100
behaviour_range: 20
online: False
message: orchestrating
energy: 65.700
energy_ticks: 0
age: 15
children: 0

### BARBARA
mesh: KNOT
color: #cccccc
scale: 1.300
position: [-12.71, 0, -6.75]
behaviour: orbit
behaviour_speed: 0.350
behaviour_range: 14
behaviour_target: DIRECTOR
online: False
message: near FRAME
energy: 62.100
energy_ticks: 0
age: 15
children: 0
behaviour_state: repelled

---

## events
- VOID reset — 3 agents retained
- DIRECTOR spawned DIRECTOR
- NOVA spawned BARBARA

---

*VOID v3.0 — tick 79 — 20:12:08*