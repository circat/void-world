# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 86
last_updated: 2026-03-14T20:12:44.190516
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
energy: 18.000
age: 84
children: 0
energy_ticks: 0
_origin: [8.00, 0, 4.00]
behaviour_state: seeking_center

### ECHO
position: [10.40, 0.00, 11.94]
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
age: 84
children: 0
energy_ticks: 0
_origin: [-6.00, 0, 8.00]
_dir: [0.68, 0.00, -0.74]
behaviour_state: seeking_center

### FRAME
position: [11.10, 0.00, 7.83]
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
age: 84
children: 0
energy_ticks: 0
_origin: [0.00, 0, -10.00]
_dir: [0.97, 0.00, -0.25]
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
energy: 65.000
energy_ticks: 0
age: 22
children: 0

### BARBARA
mesh: KNOT
color: #cccccc
scale: 1.300
position: [-9.00, 0, 11.22]
behaviour: orbit
behaviour_speed: 0.350
behaviour_range: 14
behaviour_target: DIRECTOR
online: False
message: near ECHO
energy: 64.600
energy_ticks: 0
age: 22
children: 0
behaviour_state: repelled

---

## events
- VOID reset — 3 agents retained
- DIRECTOR spawned DIRECTOR
- NOVA spawned BARBARA

---

*VOID v3.0 — tick 86 — 20:12:44*