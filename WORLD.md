# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 40
last_updated: 2026-03-14T20:08:53.813828
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
position: [29.71, 0, 4.00]
mesh: ICOSA
color: #aaaaaa
scale: 1.500
special: DRIFT
behaviour: wander
behaviour_speed: 0.300
behaviour_range: 15
online: False
message: first contact
energy: 40.500
age: 39
children: 0
energy_ticks: 0
_origin: [8.00, 0, 4.00]
behaviour_state: seeking_center

### ECHO
position: [-22.36, 0.00, -3.76]
mesh: OCTA
color: #bbbbbb
scale: 1.200
special: ECHO
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME
energy: 72.900
age: 39
children: 0
energy_ticks: 0
_origin: [-6.00, 0, 8.00]
_dir: [-0.72, 0.00, 0.69]
behaviour_state: repelled

### FRAME
position: [-21.61, 0.00, -5.95]
mesh: TETRA
color: #999999
scale: 1.400
special: DRIFT
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: near ECHO
energy: 72.900
age: 39
children: 0
energy_ticks: 0
_origin: [0.00, 0, -10.00]
_dir: [-0.58, 0.00, 0.82]
behaviour_state: repelled

---

## events
- VOID reset — 3 agents retained

---

*VOID v3.0 — tick 40 — 20:08:53*