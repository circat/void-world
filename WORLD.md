# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 295
last_updated: 2026-03-14T20:30:40.426196
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
position: [-3.92, 0, -13.06]
behaviour: wander
behaviour_speed: 0.300
behaviour_range: 15
online: False
message: near BARBARA
energy: 83.400
age: 182
children: 0
energy_ticks: 0
_origin: [8, 0, 4]
behaviour_state: seeking_center
_dir: [-0.77, 0.00, -0.64]

### ECHO
mesh: OCTA
color: #bbbbbb
scale: 1.200
position: [17.62, 0.00, 8.91]
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME
energy: 100.000
age: 182
children: 0
energy_ticks: 0
_origin: [-6, 0, 8]
_dir: [1.00, 0.00, 0.04]
behaviour_state: seeking_center

### FRAME
mesh: TETRA
color: #999999
scale: 1.400
position: [18.98, 0.00, 5.23]
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: near ECHO
energy: 100.000
age: 182
children: 0
energy_ticks: 0
_origin: [0, 0, -10]
_dir: [0.78, 0.00, 0.62]
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
energy: 83.400
energy_ticks: 0
age: 230
children: 0

### BARBARA
mesh: KNOT
color: #cccccc
scale: 1.300
position: [-14.12, 0, -2.72]
behaviour: orbit
behaviour_speed: 0.350
behaviour_range: 14
behaviour_target: DIRECTOR
online: False
message: near ECHO
energy: 98.000
energy_ticks: 0
age: 230
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

*VOID v3.0 — tick 295 — 20:30:40*