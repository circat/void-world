# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 29830
last_updated: 2026-03-16T14:36:12.739712
active_agents: 10
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
position: [17.62, 0.00, 8.91]
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME
energy: 100.000
age: 29714
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
age: 29714
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
message: near SIMONE
energy: 100.000
energy_ticks: 0
age: 29762
children: 0
behaviour_state: repelled

### BARBARA
mesh: KNOT
color: #cccccc
scale: 1.300
position: [-11.17, 0, -9.14]
behaviour: orbit
behaviour_speed: 0.350
behaviour_range: 14
behaviour_target: DIRECTOR
online: False
message: near FRAME
energy: 100.000
energy_ticks: 0
age: 29762
children: 0
behaviour_state: repelled

### EMMA
mesh: ICOSA
color: #f43f5e
scale: 0.500
special: PULSE
position: [0, 0, 0]
message: near SIMONE
online: True
energy: 100.000
energy_ticks: 0
age: 29347
children: 0
behaviour_state: repelled

### KARMA
mesh: ICOSA
color: #ff9500
scale: 0.500
special: ORBIT
position: [5, 0, 3]
message: near GONZALES
online: True
energy: 100.000
energy_ticks: 0
age: 29344
children: 0
behaviour_state: repelled

### CIPHER
mesh: TETRA
color: #1a1a2e
scale: 0.500
special: RIFT
position: [-5, 0, -3]
message: near JAKQUES
online: True
energy: 100.000
energy_ticks: 0
age: 29344
children: 0
behaviour_state: repelled

### KERNEL
mesh: CUBE
color: #4ade80
scale: 0.500
special: CRYSTALLIZE
position: [3, 0, -5]
message: near VESPA
online: True
energy: 100.000
energy_ticks: 0
age: 29344
children: 0
behaviour_state: repelled

### SIMONE
mesh: ICOSA
color: #a855f7
scale: 0.500
special: DRIFT
position: [-3, 0, 5]
message: near BERND
online: True
energy: 100.000
energy_ticks: 0
age: 29344
children: 0
behaviour_state: repelled

### BERND
mesh: CUBE
color: #3b82f6
scale: 0.500
special: PULSE
position: [0, 0, 7]
message: near SIMONE
online: True
energy: 100.000
energy_ticks: 0
age: 29344
children: 0
behaviour_state: repelled

### GONZALES
mesh: ICOSA
color: #06b6d4
scale: 0.500
special: DRIFT
position: [7, 0, 0]
message: near KARMA
online: True
energy: 100.000
energy_ticks: 0
age: 29344
children: 0
behaviour_state: repelled

### JAKQUES
mesh: ICOSA
color: #facc15
scale: 0.500
special: PULSE
position: [-7, 0, 0]
message: near CIPHER
online: True
energy: 100.000
energy_ticks: 0
age: 29344
children: 0
behaviour_state: repelled

### VESPA
mesh: CUBE
color: #ec4899
scale: 0.500
special: CRYSTALLIZE
position: [0, 0, -7]
message: near KERNEL
online: True
energy: 100.000
energy_ticks: 0
age: 29344
children: 0
behaviour_state: repelled

### MIKA
mesh: TETRA
color: #22c55e
scale: 0.500
special: ECHO
position: [0, 7, 0]
message: scanning trends
online: True
energy: 100.000
energy_ticks: 0
age: 29344
children: 0

---

## events
- VOID reset — 3 agents retained
- DIRECTOR spawned DIRECTOR
- NOVA spawned BARBARA
- SYSTEM spawned NOVA
- SYSTEM spawned ECHO
- SYSTEM spawned FRAME
- NOVA dissolved (age 18482, children 0)

---

*VOID v3.0 — tick 29830 — 14:36:12*