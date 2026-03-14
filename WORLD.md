# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 73
last_updated: 2026-03-14T20:11:38.071004
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
energy: 24.500
age: 71
children: 0
energy_ticks: 0
_origin: [8.00, 0, 4.00]
behaviour_state: seeking_center

### ECHO
position: [-1.42, 0.00, 14.76]
mesh: OCTA
color: #bbbbbb
scale: 1.200
special: ECHO
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME
energy: 97.700
age: 71
children: 0
energy_ticks: 0
_origin: [-6.00, 0, 8.00]
_dir: [0.95, 0.00, 0.33]
behaviour_state: seeking_center

### FRAME
position: [0.41, 0.00, 12.13]
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
age: 71
children: 0
energy_ticks: 0
_origin: [0.00, 0, -10.00]
_dir: [0.71, 0.00, 0.71]
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
energy: 66.300
energy_ticks: 0
age: 9
children: 0

### BARBARA
mesh: KNOT
color: #cccccc
scale: 1.300
position: [12.12, 0, -7.78]
behaviour: orbit
behaviour_speed: 0.350
behaviour_range: 14
behaviour_target: DIRECTOR
online: False
message: near FRAME
energy: 60.300
energy_ticks: 0
age: 9
children: 0

---

## events
- VOID reset — 3 agents retained
- DIRECTOR spawned DIRECTOR
- NOVA spawned BARBARA

---

*VOID v3.0 — tick 73 — 20:11:38*