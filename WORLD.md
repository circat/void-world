# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 124
last_updated: 2026-03-14T20:15:56.901648
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
position: [21.20, 0, 4.00]
behaviour: wander
behaviour_speed: 0.300
behaviour_range: 15
online: False
message: near BARBARA
energy: 59.300
age: 11
children: 0
energy_ticks: 0
_origin: [8, 0, 4]
behaviour_state: seeking_center

### ECHO
mesh: OCTA
color: #bbbbbb
scale: 1.200
position: [4.85, 0, 6.33]
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near BARBARA
energy: 77.300
age: 11
children: 0
energy_ticks: 0
_origin: [-6, 0, 8]
_dir: [0.99, 0.00, -0.15]

### FRAME
mesh: TETRA
color: #999999
scale: 1.400
position: [8.11, 0, -0.71]
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: watching
energy: 78.500
age: 11
children: 0
energy_ticks: 0
_origin: [0, 0, -10]
_dir: [0.65, 0.00, 0.76]

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
energy: 90.100
energy_ticks: 0
age: 59
children: 0

### BARBARA
mesh: KNOT
color: #cccccc
scale: 1.300
position: [-14.25, 0, 1.83]
behaviour: orbit
behaviour_speed: 0.350
behaviour_range: 14
behaviour_target: DIRECTOR
online: False
message: near NOVA
energy: 73.700
energy_ticks: 0
age: 59
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

*VOID v3.0 — tick 124 — 20:15:56*