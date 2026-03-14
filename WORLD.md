# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 112
last_updated: 2026-03-14T20:14:58.758509
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
position: [29.73, 0, 4.33]
mesh: ICOSA
color: #aaaaaa
scale: 1.500
special: DRIFT
behaviour: wander
behaviour_speed: 0.300
behaviour_range: 15
online: False
message: first contact
energy: 18.200
age: 110
children: 0
energy_ticks: 0
_origin: [8.00, 0, 4.00]
behaviour_state: seeking_center
_dir: [0.96, 0.00, 0.29]

### ECHO
position: [17.38, 0.00, 8.98]
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
age: 110
children: 0
energy_ticks: 0
_origin: [-6.00, 0, 8.00]
_dir: [1.00, 0.00, -0.01]
behaviour_state: seeking_center

### FRAME
position: [18.53, 0.00, 5.45]
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
age: 110
children: 0
energy_ticks: 0
_origin: [0.00, 0, -10.00]
_dir: [0.83, 0.00, 0.56]
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
energy: 62.400
energy_ticks: 0
age: 48
children: 0

### BARBARA
mesh: KNOT
color: #cccccc
scale: 1.300
position: [-0.38, 0, 14.36]
behaviour: orbit
behaviour_speed: 0.350
behaviour_range: 14
behaviour_target: DIRECTOR
online: False
message: near FRAME
energy: 66.000
energy_ticks: 0
age: 48
children: 0
behaviour_state: repelled

---

## events
- VOID reset — 3 agents retained
- DIRECTOR spawned DIRECTOR
- NOVA spawned BARBARA

---

*VOID v3.0 — tick 112 — 20:14:58*