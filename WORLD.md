# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 703
last_updated: 2026-03-14T19:46:26.475159
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
position: [17.05, 0.00, -0.37]
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME_g1_3
energy: 51.900
energy_ticks: 0
age: 65
children: 4
_dir: [0.90, 0.00, -0.43]
behaviour_state: repelled

### FRAME
mesh: TETRA
color: #999999
scale: 1.400
position: [15.39, 0.00, 0.23]
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: near ECHO_g1_3
energy: 51.900
energy_ticks: 0
age: 65
children: 4
_dir: [0.94, 0.00, -0.34]
behaviour_state: repelled

### ECHO_g1_0
online: False
energy: 77.600
age: 36
children: 2
energy_ticks: 0
position: [15.31, 0.00, 3.54]
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
message: near ECHO_g3_0
_origin: [0.22, 0.00, 19.33]
_dir: [0.48, 0.00, -0.88]

### FRAME_g1_0
online: False
energy: 77.600
age: 36
children: 2
energy_ticks: 0
position: [9.95, 0.00, 4.60]
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
message: near FRAME_g1_3
_origin: [-3.55, 0.00, 19.98]
_dir: [0.78, 0.00, -0.63]

### ECHO_g1_1
online: False
energy: 75.400
age: 24
children: 1
energy_ticks: 0
position: [13.69, 0.00, -0.17]
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
message: near ECHO_g1_3
_origin: [9.39, 0.00, 20.75]
_dir: [0.94, 0.00, -0.34]

### FRAME_g1_1
online: False
energy: 75.400
age: 24
children: 1
energy_ticks: 0
position: [9.72, 0.00, 0.84]
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
message: near FRAME_g1_3
_origin: [4.87, 0.00, 22.88]
_dir: [0.92, 0.00, -0.39]

### ECHO_g2_0
online: False
energy: 66.100
age: 21
children: 1
energy_ticks: 0
position: [15.96, 0.00, 5.68]
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
message: near FRAME_g1_3
_origin: [12.41, 0.00, 22.95]
_dir: [0.87, 0.00, 0.50]

### FRAME_g2_0
online: False
energy: 66.100
age: 21
children: 1
energy_ticks: 0
position: [10.65, 0.00, 2.50]
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
message: near FRAME_g1_3
_origin: [8.40, 0.00, 22.10]
_dir: [0.97, 0.00, -0.24]

### ECHO_g1_2
online: False
energy: 76.300
age: 13
children: 0
energy_ticks: 0
position: [13.90, 0.00, 1.00]
behaviour: flock
behaviour_speed: 0.261
behaviour_range: 17.500
behaviour_state: repelled
behaviour_stage: 1
scale: 1.210
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO
generation: 1
message: near ECHO_g1_3
_origin: [14.44, 0.00, 13.21]
_dir: [0.66, 0.00, -0.75]

### FRAME_g1_2
online: False
energy: 78.700
age: 13
children: 0
energy_ticks: 0
position: [19.33, 0.00, 10.32]
behaviour: pulse_rest
behaviour_speed: 0.276
behaviour_range: 18.600
behaviour_state: repelled
behaviour_stage: 1
scale: 1.450
mesh: TETRA
color: #999999
special: PULSE
parent: FRAME
generation: 1
message: near ECHO_g2_0
_origin: [12.36, 0.00, 10.26]
_pulse_phase: 52.000

### ECHO_g2_1
online: False
energy: 67.000
age: 10
children: 0
energy_ticks: 0
position: [13.89, 0.00, 2.54]
behaviour: flock
behaviour_speed: 0.244
behaviour_range: 20.200
behaviour_state: repelled
behaviour_stage: 1
scale: 1.260
mesh: DODECA
color: #bbbbbb
special: ECHO
parent: ECHO_g1_0
generation: 2
message: near ECHO_g3_0
_origin: [13.58, 0.00, 12.43]
_dir: [0.81, 0.00, -0.59]

### FRAME_g2_1
online: False
energy: 67.000
age: 10
children: 0
energy_ticks: 0
position: [13.01, 0.00, 4.18]
behaviour: flock
behaviour_speed: 0.295
behaviour_range: 19.500
behaviour_state: repelled
behaviour_stage: 1
scale: 1.400
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g1_0
generation: 2
message: near FRAME_g1_3
_origin: [8.64, 0.00, 13.56]
_dir: [0.99, 0.00, -0.15]

### ECHO_g2_2
online: False
energy: 63.900
age: 9
children: 0
energy_ticks: 0
position: [11.73, 0.00, -2.23]
behaviour: flock
behaviour_speed: 0.251
behaviour_range: 17.900
behaviour_state: repelled
behaviour_stage: 1
scale: 1.210
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO_g1_1
generation: 2
message: near FRAME_g1_3
_origin: [12.94, 0.00, 2.84]
_dir: [0.40, 0.00, -0.92]

### FRAME_g2_2
online: False
energy: 63.900
age: 9
children: 0
energy_ticks: 0
position: [12.22, 0.00, -0.92]
behaviour: flock
behaviour_speed: 0.296
behaviour_range: 20.900
behaviour_state: repelled
behaviour_stage: 1
scale: 1.380
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g1_1
generation: 2
message: near FRAME_g1_3
_origin: [9.67, 0.00, 9.55]
_dir: [0.79, 0.00, -0.61]

### ECHO_g3_0
online: False
energy: 54.600
age: 6
children: 0
energy_ticks: 0
position: [18.98, 0.00, 4.05]
behaviour: flock
behaviour_speed: 0.264
behaviour_range: 16.400
behaviour_state: repelled
behaviour_stage: 1
scale: 1.210
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO_g2_0
generation: 3
message: near FRAME_g1_3
_origin: [16.55, 0.00, 9.76]
_dir: [0.68, 0.00, -0.74]

### FRAME_g3_0
online: False
energy: 54.600
age: 6
children: 0
energy_ticks: 0
position: [8.35, 0.00, -0.19]
behaviour: flock
behaviour_speed: 0.310
behaviour_range: 16.700
behaviour_state: repelled
behaviour_stage: 1
scale: 1.460
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g2_0
generation: 3
message: near FRAME_g1_3
_origin: [4.69, 0.00, 7.54]
_dir: [0.80, 0.00, -0.59]

### ECHO_g1_3
online: False
energy: 42.200
age: 2
children: 0
energy_ticks: 0
position: [17.82, 0.00, -2.48]
behaviour: flock
behaviour_speed: 0.245
behaviour_range: 17.000
behaviour_state: repelled
behaviour_stage: 1
scale: 1.200
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO
generation: 1
message: near FRAME_g1_3
_origin: [17.28, 0.00, -0.68]
_dir: [0.56, 0.00, -0.83]

### FRAME_g1_3
online: False
energy: 42.200
age: 2
children: 0
energy_ticks: 0
position: [14.00, 0.00, 1.80]
behaviour: seek
behaviour_speed: 0.289
behaviour_range: 19.500
behaviour_state: repelled
behaviour_stage: 1
scale: 1.430
mesh: TETRA
color: #999999
special: PULSE
parent: FRAME
generation: 1
message: near ECHO_g1_3
_origin: [12.84, 0.00, -0.78]

---

## events
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
- ECHO -> ECHO_g1_2 (gen 1)
- FRAME -> FRAME_g1_2 (gen 1)
- ECHO_g1_0 -> ECHO_g2_1 (gen 2)
- FRAME_g1_0 -> FRAME_g2_1 (gen 2)
- ECHO_g1_1 -> ECHO_g2_2 (gen 2)
- FRAME_g1_1 -> FRAME_g2_2 (gen 2)
- ECHO_g2_0 -> ECHO_g3_0 (gen 3)
- FRAME_g2_0 -> FRAME_g3_0 (gen 3)
- ECHO -> ECHO_g1_3 (gen 1)
- FRAME -> FRAME_g1_3 (gen 1)

---

*VOID v3.0 — tick 703 — 19:46:26*