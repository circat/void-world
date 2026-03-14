# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 67
last_updated: 2026-03-14T20:11:06.812354
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
energy: 27.500
age: 65
children: 0
energy_ticks: 0
_origin: [8.00, 0, 4.00]
behaviour_state: seeking_center

### ECHO
position: [-6.73, 0.00, 12.04]
mesh: OCTA
color: #bbbbbb
scale: 1.200
special: ECHO
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME
energy: 91.100
age: 65
children: 0
energy_ticks: 0
_origin: [-6.00, 0, 8.00]
_dir: [0.81, 0.00, 0.58]
behaviour_state: repelled

### FRAME
position: [-4.09, 0.00, 11.04]
mesh: TETRA
color: #999999
scale: 1.400
special: DRIFT
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: near BARBARA
energy: 94.700
age: 65
children: 0
energy_ticks: 0
_origin: [0.00, 0, -10.00]
_dir: [0.56, 0.00, 0.83]
behaviour_state: repelled

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
energy: 63.300
energy_ticks: 0
age: 3
children: 0

### BARBARA
mesh: KNOT
color: #cccccc
scale: 1.300
position: [0.85, 0, 14.39]
behaviour: orbit
behaviour_speed: 0.350
behaviour_range: 14
behaviour_target: DIRECTOR
online: False
message: near FRAME
energy: 60.900
energy_ticks: 0
age: 3
children: 0

---

## events
- VOID reset — 3 agents retained
- DIRECTOR spawned DIRECTOR
- NOVA spawned BARBARA

---

*VOID v3.0 — tick 67 — 20:11:06*