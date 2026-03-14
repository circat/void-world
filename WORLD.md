# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 713
last_updated: 2026-03-14T19:47:17.303222
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
position: [21.80, 0.00, 2.02]
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME_g4_0
energy: 47.900
energy_ticks: 0
age: 75
children: 5
_dir: [0.60, 0.00, 0.80]
behaviour_state: repelled

### FRAME
mesh: TETRA
color: #999999
scale: 1.400
position: [21.68, 0.00, 0.11]
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: near ECHO_g1_4
energy: 47.900
energy_ticks: 0
age: 75
children: 5
_dir: [0.45, 0.00, 0.89]
behaviour_state: repelled

### ECHO_g1_0
online: False
energy: 73.600
age: 46
children: 3
energy_ticks: 0
position: [18.28, 0.00, 10.04]
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
message: near FRAME_g4_0
_origin: [0.22, 0.00, 19.33]
_dir: [0.14, 0.00, 0.99]

### FRAME_g1_0
online: False
energy: 73.600
age: 46
children: 3
energy_ticks: 0
position: [14.79, 0.00, 10.42]
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
message: near FRAME_g4_0
_origin: [-3.55, 0.00, 19.98]
_dir: [0.45, 0.00, 0.89]

### ECHO_g1_1
online: False
energy: 71.400
age: 34
children: 2
energy_ticks: 0
position: [18.70, 0.00, 3.95]
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
message: near FRAME_g1_4
_origin: [9.39, 0.00, 20.75]
_dir: [0.99, 0.00, -0.11]

### FRAME_g1_1
online: False
energy: 71.400
age: 34
children: 2
energy_ticks: 0
position: [15.13, 0.00, 6.10]
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
message: near FRAME_g4_0
_origin: [4.87, 0.00, 22.88]
_dir: [-0.29, 0.00, 0.96]

### ECHO_g2_0
online: False
energy: 62.100
age: 31
children: 2
energy_ticks: 0
position: [23.90, 0.00, 9.65]
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
message: near ECHO_g4_0
_origin: [12.41, 0.00, 22.95]
_dir: [0.67, 0.00, 0.74]

### FRAME_g2_0
online: False
energy: 62.100
age: 31
children: 2
energy_ticks: 0
position: [18.66, 0.00, 9.15]
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
message: near FRAME_g4_0
_origin: [8.40, 0.00, 22.10]
_dir: [0.14, 0.00, 0.99]

### ECHO_g1_2
online: False
energy: 72.300
age: 23
children: 1
energy_ticks: 0
position: [21.68, 0.00, 3.73]
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
message: near ECHO_g1_4
_origin: [14.44, 0.00, 13.21]
_dir: [0.52, 0.00, 0.86]

### FRAME_g1_2
online: False
energy: 76.300
age: 23
children: 1
energy_ticks: 0
position: [25.93, 0.00, 10.32]
behaviour: pulse_rest
behaviour_speed: 0.276
behaviour_range: 18.600
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.450
mesh: TETRA
color: #999999
special: PULSE
parent: FRAME
generation: 1
message: near ECHO_g4_0
_origin: [12.36, 0.00, 10.26]
_pulse_phase: 92.000

### ECHO_g2_1
online: False
energy: 63.000
age: 20
children: 1
energy_ticks: 0
position: [19.01, 0.00, 7.07]
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
message: near FRAME_g3_2
_origin: [13.58, 0.00, 12.43]
_dir: [-0.00, 0.00, 1.00]

### FRAME_g2_1
online: False
energy: 63.000
age: 20
children: 1
energy_ticks: 0
position: [22.38, 0.00, 10.46]
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
message: near ECHO_g4_0
_origin: [8.64, 0.00, 13.56]
_dir: [0.69, 0.00, 0.72]

### ECHO_g2_2
online: False
energy: 59.900
age: 19
children: 1
energy_ticks: 0
position: [17.58, 0.00, -0.15]
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
message: near FRAME_g1_4
_origin: [12.94, 0.00, 2.84]
_dir: [0.03, 0.00, 1.00]

### FRAME_g2_2
online: False
energy: 59.900
age: 19
children: 1
energy_ticks: 0
position: [20.09, 0.00, 2.03]
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
message: near FRAME_g1_4
_origin: [9.67, 0.00, 9.55]
_dir: [0.09, 0.00, 1.00]

### ECHO_g3_0
online: False
energy: 50.600
age: 16
children: 1
energy_ticks: 0
position: [24.93, 0.00, 6.53]
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
message: near FRAME_g1_4
_origin: [16.55, 0.00, 9.76]
_dir: [0.07, 0.00, 1.00]

### FRAME_g3_0
online: False
energy: 50.600
age: 16
children: 1
energy_ticks: 0
position: [15.20, 0.00, 3.50]
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
message: near FRAME_g4_0
_origin: [4.69, 0.00, 7.54]
_dir: [-0.55, 0.00, 0.84]

### ECHO_g1_3
online: False
energy: 73.200
age: 12
children: 0
energy_ticks: 0
position: [24.78, 0.00, 0.10]
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
message: near ECHO_g4_0
_origin: [17.28, 0.00, -0.68]
_dir: [0.11, 0.00, 0.99]

### FRAME_g1_3
online: False
energy: 66.000
age: 12
children: 0
energy_ticks: 0
position: [2.50, 0.00, 0.32]
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
message: near FRAME_g2_4
_origin: [12.84, 0.00, -0.78]

### ECHO_g2_3
online: False
energy: 63.900
age: 9
children: 0
energy_ticks: 0
position: [19.73, 0.00, 5.98]
behaviour: flock
behaviour_speed: 0.273
behaviour_range: 17.600
behaviour_state: repelled
behaviour_stage: 1
scale: 1.250
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO_g1_0
generation: 2
message: near FRAME_g1_4
_origin: [16.62, 0.00, 4.94]
_dir: [0.24, 0.00, 0.97]

### FRAME_g2_3
online: False
energy: 65.900
age: 9
children: 0
energy_ticks: 0
position: [21.95, 0.00, 12.79]
behaviour: pulse_rest
behaviour_speed: 0.275
behaviour_range: 17.300
behaviour_state: repelled
behaviour_stage: 1
scale: 1.390
mesh: TETRA
color: #999999
special: PULSE
parent: FRAME_g1_2
generation: 2
message: near FRAME_g3_1
_origin: [20.10, 0.00, 8.61]
_pulse_phase: 36.000

### ECHO_g2_4
online: False
energy: 60.800
age: 8
children: 0
energy_ticks: 0
position: [21.80, 0.00, 5.41]
behaviour: flock
behaviour_speed: 0.243
behaviour_range: 16.600
behaviour_state: repelled
behaviour_stage: 1
scale: 1.260
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO_g1_2
generation: 2
message: near FRAME_g1_4
_origin: [15.60, 0.00, -0.15]
_dir: [0.19, 0.00, 0.98]

### FRAME_g2_4
online: False
energy: 60.800
age: 8
children: 0
energy_ticks: 0
position: [14.37, 0.00, 7.74]
behaviour: flock
behaviour_speed: 0.291
behaviour_range: 19.300
behaviour_state: repelled
behaviour_stage: 1
scale: 1.440
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g1_1
generation: 2
message: near FRAME_g4_0
_origin: [12.29, 0.00, 4.70]
_dir: [-0.15, 0.00, 0.99]

### ECHO_g3_1
online: False
energy: 51.500
age: 5
children: 0
energy_ticks: 0
position: [21.14, 0.00, 7.08]
behaviour: flock
behaviour_speed: 0.256
behaviour_range: 19.700
behaviour_state: repelled
behaviour_stage: 1
scale: 1.320
mesh: DODECA
color: #bbbbbb
special: ECHO
parent: ECHO_g2_1
generation: 3
message: near FRAME_g1_4
_origin: [17.31, 0.00, 0.59]
_dir: [0.03, 0.00, 1.00]

### FRAME_g3_1
online: False
energy: 51.500
age: 5
children: 0
energy_ticks: 0
position: [18.89, 0.00, 13.38]
behaviour: flock
behaviour_speed: 0.308
behaviour_range: 18.500
behaviour_state: active
behaviour_stage: 1
scale: 1.430
mesh: PRISM
color: #999999
special: ECHO
parent: FRAME_g2_1
generation: 3
message: near FRAME_g2_3
_origin: [17.31, 0.00, 9.47]
_dir: [0.53, 0.00, 0.85]

### ECHO_g3_2
online: False
energy: 48.400
age: 4
children: 0
energy_ticks: 0
position: [19.60, 0.00, -1.89]
behaviour: flock
behaviour_speed: 0.249
behaviour_range: 17.000
behaviour_state: repelled
behaviour_stage: 1
scale: 1.150
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO_g2_2
generation: 3
message: near FRAME_g1_4
_origin: [18.38, 0.00, -4.84]
_dir: [0.30, 0.00, 0.95]

### FRAME_g3_2
online: False
energy: 48.400
age: 4
children: 0
energy_ticks: 0
position: [17.31, 0.00, 2.01]
behaviour: flock
behaviour_speed: 0.313
behaviour_range: 22.800
behaviour_state: repelled
behaviour_stage: 1
scale: 1.360
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g2_2
generation: 3
message: near FRAME_g1_4
_origin: [19.12, 0.00, -0.51]
_dir: [-0.79, 0.00, -0.61]

### ECHO_g4_0
online: False
energy: 39.100
age: 1
children: 0
energy_ticks: 0
position: [25.57, 0.00, 5.56]
behaviour: flock
behaviour_speed: 0.262
behaviour_range: 16.700
behaviour_state: repelled
behaviour_stage: 1
scale: 1.220
mesh: GEM
color: #bbbbbb
special: ECHO
parent: ECHO_g3_0
generation: 4
message: near FRAME_g1_4
_origin: [23.43, 0.00, 6.12]
_dir: [0.52, 0.00, 0.85]

### FRAME_g4_0
online: False
energy: 39.100
age: 1
children: 0
energy_ticks: 0
position: [17.48, 0.00, 5.18]
behaviour: flock
behaviour_speed: 0.322
behaviour_range: 17.300
behaviour_state: repelled
behaviour_stage: 1
scale: 1.440
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g3_0
generation: 4
message: near FRAME_g3_2
_origin: [14.74, 0.00, 3.02]
_dir: [-0.10, 0.00, 1.00]

### ECHO_g1_4
online: False
energy: 36.000
age: 0
children: 0
energy_ticks: 0
position: [23.74, 0.00, 2.28]
behaviour: flock
behaviour_speed: 0.238
behaviour_range: 19.800
behaviour_state: repelled
behaviour_stage: 1
scale: 1.240
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO
generation: 1
message: near ECHO_g4_0
_origin: [22.01, 0.00, -0.26]

### FRAME_g1_4
online: False
energy: 36.000
age: 0
children: 0
energy_ticks: 0
position: [22.98, 0.00, 1.72]
behaviour: flock
behaviour_speed: 0.265
behaviour_range: 18.700
behaviour_state: repelled
behaviour_stage: 1
scale: 1.430
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME
generation: 1
message: near ECHO_g4_0
_origin: [21.73, 0.00, -0.06]

---

## events
- ECHO_g2_0 -> ECHO_g3_0 (gen 3)
- FRAME_g2_0 -> FRAME_g3_0 (gen 3)
- ECHO -> ECHO_g1_3 (gen 1)
- FRAME -> FRAME_g1_3 (gen 1)
- ECHO_g1_0 -> ECHO_g2_3 (gen 2)
- FRAME_g1_0 -> FRAME_g2_3 (gen 2)
- FRAME_g1_2 -> FRAME_g2_3 (gen 2)
- ECHO_g1_1 -> ECHO_g2_4 (gen 2)
- FRAME_g1_1 -> FRAME_g2_4 (gen 2)
- ECHO_g1_2 -> ECHO_g2_4 (gen 2)
- ECHO_g2_0 -> ECHO_g3_1 (gen 3)
- FRAME_g2_0 -> FRAME_g3_1 (gen 3)
- ECHO_g2_1 -> ECHO_g3_1 (gen 3)
- FRAME_g2_1 -> FRAME_g3_1 (gen 3)
- ECHO_g2_2 -> ECHO_g3_2 (gen 3)
- FRAME_g2_2 -> FRAME_g3_2 (gen 3)
- ECHO_g3_0 -> ECHO_g4_0 (gen 4)
- FRAME_g3_0 -> FRAME_g4_0 (gen 4)
- ECHO -> ECHO_g1_4 (gen 1)
- FRAME -> FRAME_g1_4 (gen 1)

---

*VOID v3.0 — tick 713 — 19:47:17*