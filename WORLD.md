# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 26
last_updated: 2026-03-14T20:07:41.370771
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
position: [28.91, 0, 4.00]
mesh: ICOSA
color: #aaaaaa
scale: 1.500
special: DRIFT
behaviour: wander
behaviour_speed: 0.300
behaviour_range: 15
online: False
message: first contact
energy: 47.500
age: 25
children: 0
energy_ticks: 0
_origin: [8.00, 0, 4.00]
behaviour_state: seeking_center

### ECHO
position: [-13.99, 0.00, -8.84]
mesh: OCTA
color: #bbbbbb
scale: 1.200
special: ECHO
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME
energy: 63.100
age: 25
children: 0
energy_ticks: 0
_origin: [-6.00, 0, 8.00]
_dir: [-0.82, 0.00, -0.57]
behaviour_state: repelled

### FRAME
position: [-14.56, 0, -11.16]
mesh: TETRA
color: #999999
scale: 1.400
special: DRIFT
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: near ECHO
energy: 63.100
age: 25
children: 0
energy_ticks: 0
_origin: [0.00, 0, -10.00]
_dir: [-0.94, 0.00, -0.35]
behaviour_state: repelled

---

## events
- VOID reset — 3 agents retained

---

*VOID v3.0 — tick 26 — 20:07:41*