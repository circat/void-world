# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 31
last_updated: 2026-03-14T20:08:07.454322
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
position: [29.40, 0, 4.00]
mesh: ICOSA
color: #aaaaaa
scale: 1.500
special: DRIFT
behaviour: wander
behaviour_speed: 0.300
behaviour_range: 15
online: False
message: first contact
energy: 45.000
age: 30
children: 0
energy_ticks: 0
_origin: [8.00, 0, 4.00]
behaviour_state: seeking_center

### ECHO
position: [-17.29, 0.00, -9.68]
mesh: OCTA
color: #bbbbbb
scale: 1.200
special: ECHO
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME
energy: 66.600
age: 30
children: 0
energy_ticks: 0
_origin: [-6.00, 0, 8.00]
_dir: [-0.93, 0.00, -0.37]
behaviour_state: repelled

### FRAME
position: [-19.52, 0.00, -12.19]
mesh: TETRA
color: #999999
scale: 1.400
special: DRIFT
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: near ECHO
energy: 66.600
age: 30
children: 0
energy_ticks: 0
_origin: [0.00, 0, -10.00]
_dir: [-0.99, 0.00, 0.11]
behaviour_state: repelled

---

## events
- VOID reset — 3 agents retained

---

*VOID v3.0 — tick 31 — 20:08:07*