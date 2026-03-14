# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 721
last_updated: 2026-03-14T19:48:00.640875
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
position: [16.39, 0.00, 8.59]
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME_g3_5
energy: 72.700
energy_ticks: 0
age: 83
children: 5
_dir: [-0.49, 0.00, 0.87]
behaviour_state: repelled

### FRAME
mesh: TETRA
color: #999999
scale: 1.400
position: [17.84, 0.00, 7.10]
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: near ECHO_g3_4
energy: 72.700
energy_ticks: 0
age: 83
children: 5
_dir: [-0.40, 0.00, 0.92]
behaviour_state: repelled

### ECHO_g1_0
online: False
energy: 63.400
age: 54
children: 4
energy_ticks: 0
position: [15.19, 0.00, 17.62]
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
message: near FRAME_g3_5
_origin: [0.22, 0.00, 19.33]
_dir: [-0.47, 0.00, 0.88]

### FRAME_g1_0
online: False
energy: 63.400
age: 54
children: 4
energy_ticks: 0
position: [11.72, 0.00, 18.79]
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
message: near FRAME_g2_6
_origin: [-3.55, 0.00, 19.98]
_dir: [-0.41, 0.00, 0.91]

### ECHO_g1_1
online: False
energy: 61.200
age: 42
children: 3
energy_ticks: 0
position: [15.69, 0.00, 11.89]
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
message: near ECHO_g3_4
_origin: [9.39, 0.00, 20.75]
_dir: [-0.39, 0.00, 0.92]

### FRAME_g1_1
online: False
energy: 61.200
age: 42
children: 3
energy_ticks: 0
position: [12.74, 0.00, 14.22]
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
message: near FRAME_g2_6
_origin: [4.87, 0.00, 22.88]
_dir: [-0.49, 0.00, 0.87]

### ECHO_g2_0
online: False
energy: 51.900
age: 39
children: 3
energy_ticks: 0
position: [20.54, 0.00, 15.04]
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
message: near ECHO_g3_4
_origin: [12.41, 0.00, 22.95]
_dir: [-0.73, 0.00, 0.68]

### FRAME_g2_0
online: False
energy: 51.900
age: 39
children: 3
energy_ticks: 0
position: [16.18, 0.00, 17.25]
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
message: near FRAME_g3_5
_origin: [8.40, 0.00, 22.10]
_dir: [-0.14, 0.00, 0.99]

### ECHO_g1_2
online: False
energy: 62.100
age: 31
children: 2
energy_ticks: 0
position: [19.29, 0.00, 11.13]
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
message: near FRAME_g3_5
_origin: [14.44, 0.00, 13.21]
_dir: [-0.46, 0.00, 0.89]

### FRAME_g1_2
online: False
energy: 68.500
age: 31
children: 2
energy_ticks: 0
position: [28.13, 0.00, 10.32]
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
message: near FRAME_g3_3
_origin: [12.36, 0.00, 10.26]
_pulse_phase: 124.000

### ECHO_g2_1
online: False
energy: 52.800
age: 28
children: 2
energy_ticks: 0
position: [16.49, 0.00, 14.27]
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
message: near FRAME_g3_5
_origin: [13.58, 0.00, 12.43]
_dir: [-0.66, 0.00, 0.75]

### FRAME_g2_1
online: False
energy: 52.800
age: 28
children: 2
energy_ticks: 0
position: [18.32, 0.00, 18.51]
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
message: near FRAME_g3_1
_origin: [8.64, 0.00, 13.56]
_dir: [-0.65, 0.00, 0.76]

### ECHO_g2_2
online: False
energy: 49.700
age: 27
children: 2
energy_ticks: 0
position: [13.09, 0.00, 6.36]
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
message: near ECHO_g3_3
_origin: [12.94, 0.00, 2.84]
_dir: [-0.68, 0.00, 0.74]

### FRAME_g2_2
online: False
energy: 49.700
age: 27
children: 2
energy_ticks: 0
position: [14.31, 0.00, 9.17]
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
message: near FRAME_g3_5
_origin: [9.67, 0.00, 9.55]
_dir: [-0.65, 0.00, 0.76]

### ECHO_g3_0
online: False
energy: 75.400
age: 24
children: 1
energy_ticks: 0
position: [22.90, 0.00, 14.59]
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
message: near ECHO_g3_4
_origin: [16.55, 0.00, 9.76]
_dir: [-0.18, 0.00, 0.98]

### FRAME_g3_0
online: False
energy: 75.400
age: 24
children: 1
energy_ticks: 0
position: [11.33, 0.00, 12.12]
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
message: near FRAME_g2_6
_origin: [4.69, 0.00, 7.54]
_dir: [-0.36, 0.00, 0.93]

### ECHO_g1_3
online: False
energy: 63.000
age: 20
children: 1
energy_ticks: 0
position: [20.48, 0.00, 5.14]
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
message: near ECHO_g3_3
_origin: [17.28, 0.00, -0.68]
_dir: [-0.61, 0.00, 0.79]

### FRAME_g1_3
online: False
energy: 62.000
age: 20
children: 0
energy_ticks: 0
position: [0.20, 0.00, 0.03]
behaviour: seek
behaviour_speed: 0.289
behaviour_range: 19.500
behaviour_state: seeking_center
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
energy: 53.700
age: 17
children: 1
energy_ticks: 0
position: [16.45, 0.00, 12.89]
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
message: near FRAME_g3_5
_origin: [16.62, 0.00, 4.94]
_dir: [-0.82, 0.00, 0.58]

### FRAME_g2_3
online: False
energy: 56.900
age: 17
children: 1
energy_ticks: 0
position: [24.60, 0.00, 7.94]
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
message: near ECHO_g3_4
_origin: [20.10, 0.00, 8.61]
_pulse_phase: 68.000
_dir: [0.48, 0.00, -0.88]

### ECHO_g2_4
online: False
energy: 50.600
age: 16
children: 1
energy_ticks: 0
position: [19.97, 0.00, 12.76]
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
message: near FRAME_g3_4
_origin: [15.60, 0.00, -0.15]
_dir: [-0.06, 0.00, 1.00]

### FRAME_g2_4
online: False
energy: 50.600
age: 16
children: 1
energy_ticks: 0
position: [12.38, 0.00, 16.63]
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
message: near FRAME_g3_5
_origin: [12.29, 0.00, 4.70]
_dir: [-0.04, 0.00, 1.00]

### ECHO_g3_1
online: False
energy: 76.300
age: 13
children: 0
energy_ticks: 0
position: [18.15, 0.00, 14.40]
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
message: near FRAME_g3_5
_origin: [17.31, 0.00, 0.59]
_dir: [-0.71, 0.00, 0.70]

### FRAME_g3_1
online: False
energy: 76.300
age: 13
children: 0
energy_ticks: 0
position: [15.06, 0.00, 22.20]
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
message: near FRAME_g2_1
_origin: [17.31, 0.00, 9.47]
_dir: [-0.67, 0.00, 0.74]

### ECHO_g3_2
online: False
energy: 73.200
age: 12
children: 0
energy_ticks: 0
position: [16.22, 0.00, 5.13]
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
message: near ECHO_g3_3
_origin: [18.38, 0.00, -4.84]
_dir: [-0.60, 0.00, 0.80]

### FRAME_g3_2
online: False
energy: 73.200
age: 12
children: 0
energy_ticks: 0
position: [11.97, 0.00, 10.34]
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
message: near FRAME_g3_5
_origin: [19.12, 0.00, -0.51]
_dir: [-0.61, 0.00, 0.79]

### ECHO_g4_0
online: False
energy: 63.900
age: 9
children: 0
energy_ticks: 0
position: [21.40, 0.00, 12.63]
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
message: near FRAME_g3_4
_origin: [23.43, 0.00, 6.12]
_dir: [-0.74, 0.00, 0.67]

### FRAME_g4_0
online: False
energy: 63.900
age: 9
children: 0
energy_ticks: 0
position: [13.71, 0.00, 14.41]
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
message: near ECHO_g3_3
_origin: [14.74, 0.00, 3.02]
_dir: [-0.68, 0.00, 0.73]

### ECHO_g1_4
online: False
energy: 60.800
age: 8
children: 0
energy_ticks: 0
position: [22.98, 0.00, 9.82]
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
message: near ECHO_g3_4
_origin: [22.01, 0.00, -0.26]
_dir: [-0.20, 0.00, 0.98]

### FRAME_g1_4
online: False
energy: 60.800
age: 8
children: 0
energy_ticks: 0
position: [19.81, 0.00, 9.39]
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
message: near FRAME_g3_3
_origin: [21.73, 0.00, -0.06]
_dir: [-0.29, 0.00, 0.96]

### FRAME_g2_5
online: False
energy: 55.800
age: 6
children: 0
energy_ticks: 0
position: [27.96, 0.00, 8.61]
behaviour: pulse_rest
behaviour_speed: 0.254
behaviour_range: 18.900
behaviour_state: repelled
behaviour_stage: 1
scale: 1.450
mesh: TETRA
color: #999999
special: PULSE
parent: FRAME_g1_2
generation: 2
message: near FRAME_g3_3
_origin: [26.65, 0.00, 10.45]
_pulse_phase: 24.000

### ECHO_g2_5
online: False
energy: 51.500
age: 5
children: 0
energy_ticks: 0
position: [22.11, 0.00, 8.32]
behaviour: flock
behaviour_speed: 0.230
behaviour_range: 15.300
behaviour_state: repelled
behaviour_stage: 1
scale: 1.180
mesh: DODECA
color: #bbbbbb
special: ECHO
parent: ECHO_g1_3
generation: 2
message: near ECHO_g3_4
_origin: [21.14, 0.00, 1.10]
_dir: [-0.59, 0.00, 0.81]

### FRAME_g2_6
online: False
energy: 51.500
age: 5
children: 0
energy_ticks: 0
position: [9.12, 0.00, 14.41]
behaviour: flock
behaviour_speed: 0.273
behaviour_range: 18.100
behaviour_state: repelled
behaviour_stage: 1
scale: 1.370
mesh: OCTA
color: #999999
special: ECHO
parent: FRAME_g1_1
generation: 2
message: near FRAME_g3_5
_origin: [14.09, 0.00, 7.62]
_dir: [-0.47, 0.00, 0.88]

### FRAME_g3_3
online: False
energy: 45.700
age: 3
children: 0
energy_ticks: 0
position: [25.48, 0.00, 7.71]
behaviour: pulse_rest
behaviour_speed: 0.279
behaviour_range: 15.700
behaviour_state: repelled
behaviour_stage: 1
scale: 1.430
mesh: TETRA
color: #999999
special: PULSE
parent: FRAME_g2_3
generation: 3
message: near ECHO_g2_5
_origin: [24.62, 0.00, 9.78]
_pulse_phase: 12.000

### ECHO_g3_3
online: False
energy: 42.200
age: 2
children: 0
energy_ticks: 0
position: [17.63, 0.00, 10.23]
behaviour: flock
behaviour_speed: 0.253
behaviour_range: 18.700
behaviour_state: repelled
behaviour_stage: 1
scale: 1.290
mesh: GEM
color: #bbbbbb
special: ECHO
parent: ECHO_g2_3
generation: 3
message: near FRAME_g3_5
_origin: [17.17, 0.00, 12.60]
_dir: [-0.50, 0.00, 0.86]

### FRAME_g3_4
online: False
energy: 42.200
age: 2
children: 0
energy_ticks: 0
position: [20.68, 0.00, 18.31]
behaviour: flock
behaviour_speed: 0.283
behaviour_range: 19.100
behaviour_state: repelled
behaviour_stage: 1
scale: 1.330
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g2_1
generation: 3
message: near ECHO_g4_0
_origin: [18.62, 0.00, 15.98]
_dir: [-0.63, 0.00, 0.77]

### ECHO_g3_4
online: False
energy: 39.100
age: 1
children: 0
energy_ticks: 0
position: [20.78, 0.00, 11.44]
behaviour: pulse_rest
behaviour_speed: 0.235
behaviour_range: 14.700
behaviour_state: repelled
behaviour_stage: 1
scale: 1.200
mesh: KNOT
color: #bbbbbb
special: PULSE
parent: ECHO_g2_4
generation: 3
message: near ECHO_g3_3
_origin: [22.82, 0.00, 11.10]
_pulse_phase: 4.000

### FRAME_g3_5
online: False
energy: 39.100
age: 1
children: 0
energy_ticks: 0
position: [13.70, 0.00, 12.84]
behaviour: pulse_rest
behaviour_speed: 0.306
behaviour_range: 18.100
behaviour_state: repelled
behaviour_stage: 1
scale: 1.350
mesh: TETRA
color: #999999
special: PULSE
parent: FRAME_g2_4
generation: 3
message: near ECHO_g3_3
_origin: [9.84, 0.00, 15.85]
_pulse_phase: 4.000

---

## events
- FRAME_g3_0 -> FRAME_g4_0 (gen 4)
- ECHO -> ECHO_g1_4 (gen 1)
- FRAME -> FRAME_g1_4 (gen 1)
- FRAME_g1_2 -> FRAME_g2_5 (gen 2)
- ECHO_g1_0 -> ECHO_g2_5 (gen 2)
- FRAME_g1_0 -> FRAME_g2_6 (gen 2)
- ECHO_g1_1 -> ECHO_g2_5 (gen 2)
- FRAME_g1_1 -> FRAME_g2_6 (gen 2)
- ECHO_g1_2 -> ECHO_g2_5 (gen 2)
- ECHO_g1_3 -> ECHO_g2_5 (gen 2)
- FRAME_g2_3 -> FRAME_g3_3 (gen 3)
- ECHO_g2_0 -> ECHO_g3_3 (gen 3)
- FRAME_g2_0 -> FRAME_g3_4 (gen 3)
- ECHO_g2_1 -> ECHO_g3_3 (gen 3)
- FRAME_g2_1 -> FRAME_g3_4 (gen 3)
- ECHO_g2_3 -> ECHO_g3_3 (gen 3)
- ECHO_g2_2 -> ECHO_g3_4 (gen 3)
- FRAME_g2_2 -> FRAME_g3_5 (gen 3)
- ECHO_g2_4 -> ECHO_g3_4 (gen 3)
- FRAME_g2_4 -> FRAME_g3_5 (gen 3)

---

*VOID v3.0 — tick 721 — 19:48:00*