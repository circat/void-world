# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 684
last_updated: 2026-03-14T19:44:46.682932
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

### ECHO
mesh: OCTA
color: #bbbbbb
scale: 1.200
position: [10.98, 0.00, 16.55]
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME_g2_0
energy: 63.000
energy_ticks: 0
age: 46
children: 2
_dir: [0.87, 0.00, -0.50]
behaviour_state: repelled

### FRAME
mesh: TETRA
color: #999999
scale: 1.400
position: [10.12, 0.00, 17.60]
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: near ECHO_g2_0
energy: 63.000
energy_ticks: 0
age: 46
children: 2
_dir: [0.87, 0.00, -0.50]
behaviour_state: repelled

### ECHO_g1_0
online: False
energy: 53.700
age: 17
children: 1
energy_ticks: 0
position: [12.99, 0.00, 19.01]
behaviour: flock
behaviour_speed: 0.255
behaviour_range: 18.100
behaviour_state: repelled
behaviour_stage: 1
scale: 1.200
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO
generation: 1
message: near FRAME_g2_0
_origin: [0.22, 0.00, 19.33]
_dir: [0.47, 0.00, -0.88]

### FRAME_g1_0
online: False
energy: 53.700
age: 17
children: 1
energy_ticks: 0
position: [11.05, 0.00, 21.27]
behaviour: flock
behaviour_speed: 0.282
behaviour_range: 17.800
behaviour_state: repelled
behaviour_stage: 1
scale: 1.450
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME
generation: 1
message: near ECHO_g2_0
_origin: [-3.55, 0.00, 19.98]
_dir: [0.98, 0.00, 0.21]

### ECHO_g1_1
online: False
energy: 51.500
age: 5
children: 0
energy_ticks: 0
position: [9.94, 0.00, 14.53]
behaviour: flock
behaviour_speed: 0.266
behaviour_range: 17.800
behaviour_state: repelled
behaviour_stage: 1
scale: 1.210
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO
generation: 1
message: near FRAME_g2_0
_origin: [9.39, 0.00, 20.75]
_dir: [0.55, 0.00, -0.83]

### FRAME_g1_1
online: False
energy: 51.500
age: 5
children: 0
energy_ticks: 0
position: [8.19, 0.00, 17.39]
behaviour: flock
behaviour_speed: 0.284
behaviour_range: 18.700
behaviour_state: repelled
behaviour_stage: 1
scale: 1.390
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME
generation: 1
message: near FRAME_g2_0
_origin: [4.87, 0.00, 22.88]
_dir: [0.73, 0.00, -0.69]

### ECHO_g2_0
online: False
energy: 42.200
age: 2
children: 0
energy_ticks: 0
position: [13.89, 0.00, 20.60]
behaviour: flock
behaviour_speed: 0.266
behaviour_range: 16.200
behaviour_state: repelled
behaviour_stage: 1
scale: 1.180
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO_g1_0
generation: 2
message: near FRAME_g2_0
_origin: [12.41, 0.00, 22.95]
_dir: [0.81, 0.00, -0.58]

### FRAME_g2_0
online: False
energy: 42.200
age: 2
children: 0
energy_ticks: 0
position: [10.09, 0.00, 19.45]
behaviour: flock
behaviour_speed: 0.296
behaviour_range: 17.700
behaviour_state: repelled
behaviour_stage: 1
scale: 1.410
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g1_0
generation: 2
message: near ECHO_g2_0
_origin: [8.40, 0.00, 22.10]
_dir: [0.80, 0.00, -0.61]

---

## events
- VOID v3.0 initialisiert
- Warte auf erste Agenten
- NOVA spawned NOVA
- ECHO spawned ECHO
- NOVA dissolved (age 365, children 0)
- ECHO spawned ECHO
- ping
- ECHO spawned ECHO
- FRAME spawned FRAME
- ECHO spawned ECHO
- FRAME spawned FRAME
- ECHO -> ECHO_g1_0 (gen 1)
- FRAME -> FRAME_g1_0 (gen 1)
- ECHO -> ECHO_g1_1 (gen 1)
- FRAME -> FRAME_g1_1 (gen 1)
- ECHO_g1_0 -> ECHO_g2_0 (gen 2)
- FRAME_g1_0 -> FRAME_g2_0 (gen 2)

---

*VOID v3.0 — tick 684 — 19:44:46*