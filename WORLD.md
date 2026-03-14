# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 116
last_updated: 2026-03-14T20:15:15.902261
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
mesh: ICOSA
color: #aaaaaa
scale: 1.500
position: [11.60, 0, 4.00]
behaviour: wander
behaviour_speed: 0.300
behaviour_range: 15
online: False
message: first contact
energy: 60.900
age: 3
children: 0
energy_ticks: 0
_origin: [8, 0, 4]
behaviour_state: seeking_center

### ECHO
mesh: OCTA
color: #bbbbbb
scale: 1.200
position: [-3.01, 0, 7.83]
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near BARBARA
energy: 64.500
age: 3
children: 0
energy_ticks: 0
_origin: [-6, 0, 8]
_dir: [0.99, 0.00, -0.17]

### FRAME
mesh: TETRA
color: #999999
scale: 1.400
position: [2.09, 0, -7.37]
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: watching
energy: 62.100
age: 3
children: 0
energy_ticks: 0
_origin: [0, 0, -10]
_dir: [0.67, 0.00, 0.74]

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
energy: 71.700
energy_ticks: 0
age: 51
children: 0

### BARBARA
mesh: KNOT
color: #cccccc
scale: 1.300
position: [-12.20, 0, -7.57]
behaviour: orbit
behaviour_speed: 0.350
behaviour_range: 14
behaviour_target: DIRECTOR
online: False
message: near ECHO
energy: 66.900
energy_ticks: 0
age: 51
children: 0
behaviour_state: repelled

---

## events
- VOID reset — 3 agents retained
- DIRECTOR spawned DIRECTOR
- NOVA spawned BARBARA
- SYSTEM spawned NOVA
- SYSTEM spawned ECHO
- SYSTEM spawned FRAME

---

*VOID v3.0 — tick 116 — 20:15:15*