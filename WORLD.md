# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 739
last_updated: 2026-03-14T19:49:37.530375
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
position: [1.39, 0.00, 9.32]
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME_g2_12
energy: 58.500
energy_ticks: 0
age: 101
children: 7
_dir: [-0.69, 0.00, -0.72]
behaviour_state: repelled

### FRAME
mesh: TETRA
color: #999999
scale: 1.400
position: [2.66, 0.00, 9.72]
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: near ECHO_g2_9
energy: 58.500
energy_ticks: 0
age: 101
children: 7
_dir: [-0.77, 0.00, -0.64]
behaviour_state: repelled

### ECHO_g1_0
online: False
energy: 49.200
age: 72
children: 6
energy_ticks: 0
position: [-0.40, 0.00, 14.76]
behaviour: flock
behaviour_speed: 0.255
behaviour_range: 18.100
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.200
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO
generation: 1
message: near FRAME_g5_1
_origin: [0.22, 0.00, 19.33]
_dir: [-0.64, 0.00, -0.76]

### FRAME_g1_0
online: False
energy: 49.200
age: 72
children: 6
energy_ticks: 0
position: [-4.61, 0.00, 17.76]
behaviour: flock
behaviour_speed: 0.282
behaviour_range: 17.800
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.450
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME
generation: 1
message: near FRAME_g5_1
_origin: [-3.55, 0.00, 19.98]
_dir: [-0.88, 0.00, -0.48]

### ECHO_g1_1
online: False
energy: 47.000
age: 60
children: 5
energy_ticks: 0
position: [-0.56, 0.00, 12.93]
behaviour: flock
behaviour_speed: 0.266
behaviour_range: 17.800
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.210
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO
generation: 1
message: near ECHO_g5_2
_origin: [9.39, 0.00, 20.75]
_dir: [-0.83, 0.00, -0.55]

### FRAME_g1_1
online: False
energy: 47.000
age: 60
children: 5
energy_ticks: 0
position: [-3.51, 0.00, 9.71]
behaviour: flock
behaviour_speed: 0.284
behaviour_range: 18.700
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.390
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME
generation: 1
message: near FRAME_g5_2
_origin: [4.87, 0.00, 22.88]
_dir: [-0.89, 0.00, -0.46]

### ECHO_g2_0
online: False
energy: 72.700
age: 57
children: 4
energy_ticks: 0
position: [5.20, 0.00, 15.76]
behaviour: flock
behaviour_speed: 0.266
behaviour_range: 16.200
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.180
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO_g1_0
generation: 2
message: near ECHO_g5_1
_origin: [12.41, 0.00, 22.95]
_dir: [-0.97, 0.00, -0.24]

### FRAME_g2_0
online: False
energy: 72.700
age: 57
children: 4
energy_ticks: 0
position: [-1.18, 0.00, 15.94]
behaviour: flock
behaviour_speed: 0.296
behaviour_range: 17.700
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.410
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g1_0
generation: 2
message: near FRAME_g5_1
_origin: [8.40, 0.00, 22.10]
_dir: [-0.42, 0.00, -0.91]

### ECHO_g1_2
online: False
energy: 47.900
age: 49
children: 4
energy_ticks: 0
position: [4.72, 0.00, 10.06]
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
message: near ECHO_g2_9
_origin: [14.44, 0.00, 13.21]
_dir: [-0.76, 0.00, -0.66]

### FRAME_g1_2
online: False
energy: 57.100
age: 49
children: 4
energy_ticks: 0
position: [35.62, 0.00, 10.32]
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
message: near FRAME_g3_3
_origin: [12.36, 0.00, 10.26]
_pulse_phase: 196.000

### ECHO_g2_1
online: False
energy: 73.600
age: 46
children: 3
energy_ticks: 0
position: [1.05, 0.00, 15.32]
behaviour: flock
behaviour_speed: 0.244
behaviour_range: 20.200
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.260
mesh: DODECA
color: #bbbbbb
special: ECHO
parent: ECHO_g1_0
generation: 2
message: near FRAME_g5_1
_origin: [13.58, 0.00, 12.43]
_dir: [-0.81, 0.00, -0.59]

### FRAME_g2_1
online: False
energy: 73.600
age: 46
children: 3
energy_ticks: 0
position: [-0.22, 0.00, 18.24]
behaviour: flock
behaviour_speed: 0.295
behaviour_range: 19.500
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.400
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g1_0
generation: 2
message: near FRAME_g3_7
_origin: [8.64, 0.00, 13.56]
_dir: [-0.76, 0.00, -0.65]

### ECHO_g2_2
online: False
energy: 70.500
age: 45
children: 3
energy_ticks: 0
position: [-1.03, 0.00, 6.62]
behaviour: flock
behaviour_speed: 0.251
behaviour_range: 17.900
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.210
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO_g1_1
generation: 2
message: near ECHO_g5_2
_origin: [12.94, 0.00, 2.84]
_dir: [-0.69, 0.00, -0.72]

### FRAME_g2_2
online: False
energy: 70.500
age: 45
children: 3
energy_ticks: 0
position: [-0.17, 0.00, 10.73]
behaviour: flock
behaviour_speed: 0.296
behaviour_range: 20.900
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.380
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g1_1
generation: 2
message: near ECHO_g5_2
_origin: [9.67, 0.00, 9.55]
_dir: [-0.91, 0.00, -0.40]

### ECHO_g3_0
online: False
energy: 61.200
age: 42
children: 3
energy_ticks: 0
position: [6.59, 0.00, 17.44]
behaviour: flock
behaviour_speed: 0.264
behaviour_range: 16.400
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.210
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO_g2_0
generation: 3
message: near ECHO_g5_1
_origin: [16.55, 0.00, 9.76]
_dir: [-0.99, 0.00, -0.16]

### FRAME_g3_0
online: False
energy: 61.200
age: 42
children: 3
energy_ticks: 0
position: [-7.39, 0.00, 11.22]
behaviour: flock
behaviour_speed: 0.310
behaviour_range: 16.700
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.460
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g2_0
generation: 3
message: near FRAME_g5_2
_origin: [4.69, 0.00, 7.54]
_dir: [-0.91, 0.00, -0.41]

### ECHO_g1_3
online: False
energy: 48.800
age: 38
children: 3
energy_ticks: 0
position: [6.29, 0.00, 5.06]
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
message: near ECHO_g5_2
_origin: [17.28, 0.00, -0.68]
_dir: [-0.96, 0.00, -0.29]

### FRAME_g1_3
online: False
energy: 49.200
age: 38
children: 1
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
message: near FRAME_g2_12
_origin: [12.84, 0.00, -0.78]

### ECHO_g2_3
online: False
energy: 74.500
age: 35
children: 2
energy_ticks: 0
position: [0.79, 0.00, 11.93]
behaviour: flock
behaviour_speed: 0.273
behaviour_range: 17.600
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.250
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO_g1_0
generation: 2
message: near ECHO_g5_2
_origin: [16.62, 0.00, 4.94]
_dir: [-0.71, 0.00, -0.70]

### FRAME_g2_3
online: False
energy: 46.300
age: 35
children: 3
energy_ticks: 0
position: [29.37, 0.00, -0.79]
behaviour: pulse_rest
behaviour_speed: 0.275
behaviour_range: 17.300
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.390
mesh: TETRA
color: #999999
special: PULSE
parent: FRAME_g1_2
generation: 2
message: near FRAME_g3_9
_origin: [20.10, 0.00, 8.61]
_pulse_phase: 140.000
_dir: [0.48, 0.00, -0.88]

### ECHO_g2_4
online: False
energy: 71.400
age: 34
children: 2
energy_ticks: 0
position: [5.05, 0.00, 12.65]
behaviour: flock
behaviour_speed: 0.243
behaviour_range: 16.600
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.260
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO_g1_2
generation: 2
message: near ECHO_g5_2
_origin: [15.60, 0.00, -0.15]
_dir: [-0.82, 0.00, -0.57]

### FRAME_g2_4
online: False
energy: 71.400
age: 34
children: 2
energy_ticks: 0
position: [-4.13, 0.00, 15.15]
behaviour: flock
behaviour_speed: 0.291
behaviour_range: 19.300
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.440
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g1_1
generation: 2
message: near FRAME_g4_5
_origin: [12.29, 0.00, 4.70]
_dir: [-0.89, 0.00, -0.45]

### ECHO_g3_1
online: False
energy: 62.100
age: 31
children: 2
energy_ticks: 0
position: [2.24, 0.00, 13.04]
behaviour: flock
behaviour_speed: 0.256
behaviour_range: 19.700
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.320
mesh: DODECA
color: #bbbbbb
special: ECHO
parent: ECHO_g2_1
generation: 3
message: near ECHO_g5_2
_origin: [17.31, 0.00, 0.59]
_dir: [-0.76, 0.00, -0.65]

### FRAME_g3_1
online: False
energy: 62.100
age: 31
children: 2
energy_ticks: 0
position: [-2.25, 0.00, 17.96]
behaviour: flock
behaviour_speed: 0.308
behaviour_range: 18.500
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.430
mesh: PRISM
color: #999999
special: ECHO
parent: FRAME_g2_1
generation: 3
message: near FRAME_g5_1
_origin: [17.31, 0.00, 9.47]
_dir: [-0.93, 0.00, -0.38]

### ECHO_g3_2
online: False
energy: 59.000
age: 30
children: 2
energy_ticks: 0
position: [2.57, 0.00, 5.23]
behaviour: flock
behaviour_speed: 0.249
behaviour_range: 17.000
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.150
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO_g2_2
generation: 3
message: near ECHO_g5_2
_origin: [18.38, 0.00, -4.84]
_dir: [-0.84, 0.00, -0.55]

### FRAME_g3_2
online: False
energy: 59.000
age: 30
children: 2
energy_ticks: 0
position: [-3.10, 0.00, 6.84]
behaviour: flock
behaviour_speed: 0.313
behaviour_range: 22.800
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.360
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g2_2
generation: 3
message: near FRAME_g5_2
_origin: [19.12, 0.00, -0.51]
_dir: [-0.53, 0.00, -0.85]

### ECHO_g4_0
online: False
energy: 49.700
age: 27
children: 2
energy_ticks: 0
position: [6.26, 0.00, 13.27]
behaviour: flock
behaviour_speed: 0.262
behaviour_range: 16.700
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.220
mesh: GEM
color: #bbbbbb
special: ECHO
parent: ECHO_g3_0
generation: 4
message: near ECHO_g5_2
_origin: [23.43, 0.00, 6.12]
_dir: [-0.86, 0.00, -0.51]

### FRAME_g4_0
online: False
energy: 49.700
age: 27
children: 2
energy_ticks: 0
position: [-2.92, 0.00, 12.97]
behaviour: flock
behaviour_speed: 0.322
behaviour_range: 17.300
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.440
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g3_0
generation: 4
message: near FRAME_g4_5
_origin: [14.74, 0.00, 3.02]
_dir: [-0.96, 0.00, -0.29]

### ECHO_g1_4
online: False
energy: 46.600
age: 26
children: 2
energy_ticks: 0
position: [9.34, 0.00, 15.38]
behaviour: flock
behaviour_speed: 0.238
behaviour_range: 19.800
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.240
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO
generation: 1
message: near ECHO_g3_6
_origin: [22.01, 0.00, -0.26]
_dir: [-0.96, 0.00, -0.29]

### FRAME_g1_4
online: False
energy: 46.600
age: 26
children: 2
energy_ticks: 0
position: [6.90, 0.00, 11.32]
behaviour: flock
behaviour_speed: 0.265
behaviour_range: 18.700
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.430
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME
generation: 1
message: near ECHO_g5_2
_origin: [21.73, 0.00, -0.06]
_dir: [-0.89, 0.00, -0.46]

### FRAME_g2_5
online: False
energy: 79.800
age: 24
children: 1
energy_ticks: 0
position: [31.14, 0.00, 6.60]
behaviour: pulse_rest
behaviour_speed: 0.254
behaviour_range: 18.900
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.450
mesh: TETRA
color: #999999
special: PULSE
parent: FRAME_g1_2
generation: 2
message: near FRAME_g4_3
_origin: [26.65, 0.00, 10.45]
_pulse_phase: 96.000
_dir: [-0.11, 0.00, 0.99]

### ECHO_g2_5
online: False
energy: 72.300
age: 23
children: 1
energy_ticks: 0
position: [8.37, 0.00, 10.82]
behaviour: flock
behaviour_speed: 0.230
behaviour_range: 15.300
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.180
mesh: DODECA
color: #bbbbbb
special: ECHO
parent: ECHO_g1_3
generation: 2
message: near ECHO_g5_2
_origin: [21.14, 0.00, 1.10]
_dir: [-0.94, 0.00, -0.33]

### FRAME_g2_6
online: False
energy: 72.300
age: 23
children: 1
energy_ticks: 0
position: [-5.20, 0.00, 12.57]
behaviour: flock
behaviour_speed: 0.273
behaviour_range: 18.100
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.370
mesh: OCTA
color: #999999
special: ECHO
parent: FRAME_g1_1
generation: 2
message: near FRAME_g4_5
_origin: [14.09, 0.00, 7.62]
_dir: [-0.96, 0.00, -0.28]

### FRAME_g3_3
online: False
energy: 70.100
age: 21
children: 1
energy_ticks: 0
position: [35.56, 0.00, 7.71]
behaviour: pulse_rest
behaviour_speed: 0.279
behaviour_range: 15.700
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.430
mesh: TETRA
color: #999999
special: PULSE
parent: FRAME_g2_3
generation: 3
message: near FRAME_g2_10
_origin: [24.62, 0.00, 9.78]
_pulse_phase: 84.000

### ECHO_g3_3
online: False
energy: 63.000
age: 20
children: 1
energy_ticks: 0
position: [1.95, 0.00, 11.31]
behaviour: flock
behaviour_speed: 0.253
behaviour_range: 18.700
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.290
mesh: GEM
color: #bbbbbb
special: ECHO
parent: ECHO_g2_3
generation: 3
message: near ECHO_g5_2
_origin: [17.17, 0.00, 12.60]
_dir: [-0.62, 0.00, -0.79]

### FRAME_g3_4
online: False
energy: 63.000
age: 20
children: 1
energy_ticks: 0
position: [3.48, 0.00, 19.52]
behaviour: flock
behaviour_speed: 0.283
behaviour_range: 19.100
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.330
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g2_1
generation: 3
message: near FRAME_g5_1
_origin: [18.62, 0.00, 15.98]
_dir: [-0.84, 0.00, -0.54]

### ECHO_g3_4
online: False
energy: 63.500
age: 19
children: 1
energy_ticks: 0
position: [29.24, 0.00, 11.44]
behaviour: pulse_rest
behaviour_speed: 0.235
behaviour_range: 14.700
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.200
mesh: KNOT
color: #bbbbbb
special: PULSE
parent: ECHO_g2_4
generation: 3
message: near FRAME_g3_5
_origin: [22.82, 0.00, 11.10]
_pulse_phase: 76.000

### FRAME_g3_5
online: False
energy: 63.500
age: 19
children: 1
energy_ticks: 0
position: [24.68, 0.00, 12.84]
behaviour: pulse_rest
behaviour_speed: 0.306
behaviour_range: 18.100
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.350
mesh: TETRA
color: #999999
special: PULSE
parent: FRAME_g2_4
generation: 3
message: near FRAME_g4_4
_origin: [9.84, 0.00, 15.85]
_pulse_phase: 76.000

### ECHO_g4_1
online: False
energy: 50.600
age: 16
children: 1
energy_ticks: 0
position: [1.60, 0.00, 16.41]
behaviour: flock
behaviour_speed: 0.263
behaviour_range: 17.800
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.270
mesh: DODECA
color: #bbbbbb
special: ECHO
parent: ECHO_g3_1
generation: 4
message: near FRAME_g5_1
_origin: [14.39, 0.00, 16.79]
_dir: [-0.57, 0.00, -0.82]

### FRAME_g4_1
online: False
energy: 50.600
age: 16
children: 1
energy_ticks: 0
position: [-1.42, 0.00, 21.11]
behaviour: flock
behaviour_speed: 0.298
behaviour_range: 19.500
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.360
mesh: PRISM
color: #999999
special: ECHO
parent: FRAME_g3_1
generation: 4
message: near ECHO_g5_1
_origin: [11.68, 0.00, 24.64]
_dir: [-0.97, 0.00, 0.24]

### ECHO_g1_5
online: False
energy: 47.500
age: 15
children: 1
energy_ticks: 0
position: [4.16, 0.00, 5.83]
behaviour: flock
behaviour_speed: 0.269
behaviour_range: 16.100
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.260
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO
generation: 1
message: near ECHO_g5_2
_origin: [13.28, 0.00, 11.87]
_dir: [-0.81, 0.00, -0.58]

### FRAME_g1_5
online: False
energy: 47.500
age: 15
children: 1
energy_ticks: 0
position: [-3.33, 0.00, 3.87]
behaviour: flock
behaviour_speed: 0.297
behaviour_range: 17.000
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.360
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME
generation: 1
message: near FRAME_g5_2
_origin: [14.23, 0.00, 8.14]
_dir: [-0.84, 0.00, -0.54]

### ECHO_g4_2
online: False
energy: 47.500
age: 15
children: 1
energy_ticks: 0
position: [1.15, 0.00, 7.04]
behaviour: flock
behaviour_speed: 0.230
behaviour_range: 16.300
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.100
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO_g3_2
generation: 4
message: near ECHO_g5_2
_origin: [12.57, 0.00, 6.59]
_dir: [-0.68, 0.00, -0.73]

### FRAME_g4_2
online: False
energy: 47.500
age: 15
children: 1
energy_ticks: 0
position: [-6.92, 0.00, 6.54]
behaviour: flock
behaviour_speed: 0.295
behaviour_range: 23.600
behaviour_state: repelled
behaviour_stage: 1
scale: 1.380
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g3_2
generation: 4
message: near FRAME_g2_12
_origin: [8.78, 0.00, 13.49]
_dir: [-0.80, 0.00, -0.60]

### FRAME_g2_7
online: False
energy: 79.400
age: 14
children: 0
energy_ticks: 0
position: [46.15, 0.00, 7.70]
behaviour: wander
behaviour_speed: 0.271
behaviour_range: 19.300
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.530
mesh: TETRA
color: #999999
special: DRIFT
parent: FRAME_g1_2
generation: 2
message: near FRAME_g1_2
_origin: [33.37, 0.00, 10.31]

### ECHO_g2_6
online: False
energy: 73.200
age: 12
children: 0
energy_ticks: 0
position: [8.05, 0.00, 7.32]
behaviour: flock
behaviour_speed: 0.249
behaviour_range: 15.800
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.190
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO_g1_3
generation: 2
message: near ECHO_g5_2
_origin: [18.76, 0.00, 11.86]
_dir: [-0.94, 0.00, -0.33]

### FRAME_g2_8
online: False
energy: 73.200
age: 12
children: 0
energy_ticks: 0
position: [-7.44, 0.00, 17.38]
behaviour: flock
behaviour_speed: 0.274
behaviour_range: 16.700
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.390
mesh: KNOT
color: #999999
special: ECHO
parent: FRAME_g1_0
generation: 2
message: near FRAME_g3_8
_origin: [9.52, 0.00, 24.36]
_dir: [-0.92, 0.00, -0.38]

### ECHO_g5_0
online: False
energy: 73.200
age: 12
children: 0
energy_ticks: 0
position: [2.56, 0.00, 14.44]
behaviour: flock
behaviour_speed: 0.275
behaviour_range: 17.900
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.280
mesh: GEM
color: #bbbbbb
special: ECHO
parent: ECHO_g4_0
generation: 5
message: near ECHO_g5_2
_origin: [15.51, 0.00, 18.17]
_dir: [-0.57, 0.00, -0.82]

### FRAME_g5_0
online: False
energy: 73.200
age: 12
children: 0
energy_ticks: 0
position: [-2.51, 0.00, 10.80]
behaviour: flock
behaviour_speed: 0.312
behaviour_range: 15.500
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.480
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g4_0
generation: 5
message: near FRAME_g2_12
_origin: [5.75, 0.00, 20.09]
_dir: [-0.51, 0.00, -0.86]

### ECHO_g2_7
online: False
energy: 41.300
age: 11
children: 0
energy_ticks: 0
position: [18.64, 0.00, -15.38]
behaviour: orbit
behaviour_speed: 0.230
behaviour_range: 18.900
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.190
mesh: ICOSA
color: #bbbbbb
special: ORBIT
parent: ECHO_g1_4
generation: 2
message: near FRAME_g2_8
_origin: [19.64, 0.00, 17.19]

### FRAME_g2_9
online: False
energy: 70.100
age: 11
children: 0
energy_ticks: 0
position: [5.14, 0.00, 7.37]
behaviour: flock
behaviour_speed: 0.266
behaviour_range: 17.800
behaviour_state: repelled
behaviour_stage: 1
scale: 1.480
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g1_4
generation: 2
message: near ECHO_g2_8
_origin: [16.73, 0.00, 16.47]
_dir: [-0.69, 0.00, -0.73]

### FRAME_g3_6
online: False
energy: 67.000
age: 10
children: 0
energy_ticks: 0
position: [22.61, 0.00, 8.69]
behaviour: flock
behaviour_speed: 0.254
behaviour_range: 18.700
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.390
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g2_5
generation: 3
message: near FRAME_g4_4
_origin: [34.40, 0.00, 9.71]
_dir: [-0.97, 0.00, -0.23]

### ECHO_g3_5
online: False
energy: 63.900
age: 9
children: 0
energy_ticks: 0
position: [-1.51, 0.00, 9.02]
behaviour: flock
behaviour_speed: 0.254
behaviour_range: 16.700
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.280
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO_g2_3
generation: 3
message: near ECHO_g5_2
_origin: [6.64, 0.00, 16.09]
_dir: [-0.67, 0.00, -0.74]

### FRAME_g3_7
online: False
energy: 63.900
age: 9
children: 0
energy_ticks: 0
position: [3.60, 0.00, 15.84]
behaviour: flock
behaviour_speed: 0.302
behaviour_range: 19.100
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.340
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g2_1
generation: 3
message: near FRAME_g5_1
_origin: [7.32, 0.00, 21.36]
_dir: [0.02, 0.00, -1.00]

### ECHO_g3_6
online: False
energy: 60.800
age: 8
children: 0
energy_ticks: 0
position: [10.97, 0.00, 11.90]
behaviour: flock
behaviour_speed: 0.229
behaviour_range: 16.300
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.150
mesh: DODECA
color: #bbbbbb
special: ECHO
parent: ECHO_g2_5
generation: 3
message: near ECHO_g2_6
_origin: [16.12, 0.00, 10.66]
_dir: [-0.94, 0.00, -0.33]

### FRAME_g3_8
online: False
energy: 60.800
age: 8
children: 0
energy_ticks: 0
position: [-7.52, 0.00, 13.59]
behaviour: flock
behaviour_speed: 0.266
behaviour_range: 16.300
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.340
mesh: OCTA
color: #999999
special: ECHO
parent: FRAME_g2_6
generation: 3
message: near FRAME_g4_5
_origin: [-1.29, 0.00, 17.01]
_dir: [-0.72, 0.00, -0.69]

### FRAME_g4_3
online: False
energy: 58.900
age: 7
children: 0
energy_ticks: 0
position: [34.99, 0.00, 8.45]
behaviour: pulse_rest
behaviour_speed: 0.278
behaviour_range: 17.200
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.390
mesh: OCTA
color: #999999
special: PULSE
parent: FRAME_g3_3
generation: 4
message: near FRAME_g2_10
_origin: [30.33, 0.00, 8.33]
_pulse_phase: 28.000

### ECHO_g4_3
online: False
energy: 52.700
age: 5
children: 0
energy_ticks: 0
position: [29.29, 0.00, 13.75]
behaviour: pulse_rest
behaviour_speed: 0.223
behaviour_range: 15.100
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.260
mesh: KNOT
color: #bbbbbb
special: PULSE
parent: ECHO_g3_4
generation: 4
message: near FRAME_g3_5
_origin: [26.77, 0.00, 13.79]
_pulse_phase: 20.000

### FRAME_g4_4
online: False
energy: 52.700
age: 5
children: 0
energy_ticks: 0
position: [19.37, 0.00, 10.26]
behaviour: pulse_rest
behaviour_speed: 0.305
behaviour_range: 18.300
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.330
mesh: TETRA
color: #999999
special: PULSE
parent: FRAME_g3_5
generation: 4
message: near FRAME_g3_6
_origin: [22.03, 0.00, 14.50]
_pulse_phase: 20.000
_dir: [-0.65, 0.00, -0.76]

### ECHO_g1_6
online: False
energy: 48.400
age: 4
children: 0
energy_ticks: 0
position: [3.59, 0.00, 8.90]
behaviour: flock
behaviour_speed: 0.266
behaviour_range: 20.100
behaviour_state: repelled
behaviour_stage: 1
scale: 1.260
mesh: DODECA
color: #bbbbbb
special: ECHO
parent: ECHO
generation: 1
message: near ECHO_g2_9
_origin: [2.00, 0.00, 11.35]
_dir: [-0.94, 0.00, 0.35]

### FRAME_g1_6
online: False
energy: 48.400
age: 4
children: 0
energy_ticks: 0
position: [2.76, 0.00, 12.09]
behaviour: flock
behaviour_speed: 0.286
behaviour_range: 19.700
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.410
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME
generation: 1
message: near ECHO_g5_2
_origin: [7.10, 0.00, 11.08]
_dir: [-0.95, 0.00, -0.31]

### ECHO_g4_4
online: False
energy: 48.400
age: 4
children: 0
energy_ticks: 0
position: [0.33, 0.00, 2.79]
behaviour: flock
behaviour_speed: 0.245
behaviour_range: 16.000
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.210
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO_g3_2
generation: 4
message: near FRAME_g2_12
_origin: [4.27, 0.00, 4.73]
_dir: [-0.77, 0.00, -0.64]

### FRAME_g4_5
online: False
energy: 48.400
age: 4
children: 0
energy_ticks: 0
position: [-6.26, 0.00, 9.59]
behaviour: flock
behaviour_speed: 0.309
behaviour_range: 20.100
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.410
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g3_2
generation: 4
message: near FRAME_g5_2
_origin: [-1.19, 0.00, 9.59]
_dir: [-0.91, 0.00, -0.43]

### FRAME_g2_10
online: False
energy: 45.700
age: 3
children: 0
energy_ticks: 0
position: [36.65, 0.00, 11.61]
behaviour: pulse_rest
behaviour_speed: 0.297
behaviour_range: 18.200
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.480
mesh: TETRA
color: #999999
special: PULSE
parent: FRAME_g1_2
generation: 2
message: near FRAME_g4_3
_origin: [33.48, 0.00, 12.16]
_pulse_phase: 12.000

### ECHO_g2_8
online: False
energy: 39.100
age: 1
children: 0
energy_ticks: 0
position: [7.89, 0.00, 3.06]
behaviour: flock
behaviour_speed: 0.228
behaviour_range: 16.200
behaviour_state: active
behaviour_stage: 1
scale: 1.220
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO_g1_3
generation: 2
message: near ECHO_g2_9
_origin: [7.68, 0.00, 2.53]
_dir: [-1.00, 0.00, -0.07]

### FRAME_g2_11
online: False
energy: 39.100
age: 1
children: 0
energy_ticks: 0
position: [0.41, 0.00, 0.04]
behaviour: seek
behaviour_speed: 0.283
behaviour_range: 18.400
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.370
mesh: TETRA
color: #999999
special: PULSE
parent: FRAME_g1_3
generation: 2
message: near FRAME_g2_12
_origin: [-2.30, 0.00, 1.77]

### ECHO_g5_1
online: False
energy: 39.100
age: 1
children: 0
energy_ticks: 0
position: [1.93, 0.00, 17.96]
behaviour: flock
behaviour_speed: 0.272
behaviour_range: 17.300
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.240
mesh: DODECA
color: #bbbbbb
special: ECHO
parent: ECHO_g4_1
generation: 5
message: near FRAME_g5_1
_origin: [2.60, 0.00, 18.50]
_dir: [0.15, 0.00, -0.99]

### FRAME_g5_1
online: False
energy: 39.100
age: 1
children: 0
energy_ticks: 0
position: [-0.14, 0.00, 20.01]
behaviour: flock
behaviour_speed: 0.300
behaviour_range: 21.500
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.430
mesh: PRISM
color: #999999
special: ECHO
parent: FRAME_g4_1
generation: 5
message: near ECHO_g5_1
_origin: [0.07, 0.00, 19.24]
_dir: [-0.97, 0.00, 0.23]

### ECHO_g2_9
online: False
energy: 36.000
age: 0
children: 0
energy_ticks: 0
position: [4.51, 0.00, 5.74]
behaviour: flock
behaviour_speed: 0.285
behaviour_range: 15.200
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.330
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO_g1_5
generation: 2
message: near ECHO_g5_2
_origin: [5.12, 0.00, 6.19]

### FRAME_g2_12
online: False
energy: 36.000
age: 0
children: 0
energy_ticks: 0
position: [-1.40, 0.00, 4.96]
behaviour: flock
behaviour_speed: 0.291
behaviour_range: 18.300
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.360
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g1_5
generation: 2
message: near ECHO_g2_9
_origin: [-5.06, 0.00, 2.07]

### FRAME_g3_9
online: False
energy: 36.000
age: 0
children: 0
energy_ticks: 0
position: [28.01, 0.00, -3.79]
behaviour: pulse_rest
behaviour_speed: 0.277
behaviour_range: 16.300
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.320
mesh: TETRA
color: #999999
special: PULSE
parent: FRAME_g2_3
generation: 3
message: near FRAME_g2_3
_origin: [30.06, 0.00, -3.37]

### ECHO_g5_2
online: False
energy: 36.000
age: 0
children: 0
energy_ticks: 0
position: [3.62, 0.00, 8.64]
behaviour: flock
behaviour_speed: 0.221
behaviour_range: 16.900
behaviour_state: repelled
behaviour_stage: 1
scale: 1.070
mesh: RING
color: #bbbbbb
special: ECHO
parent: ECHO_g4_2
generation: 5
message: near ECHO_g2_9
_origin: [3.76, 0.00, 6.32]

### FRAME_g5_2
online: False
energy: 36.000
age: 0
children: 0
energy_ticks: 0
position: [-8.30, 0.00, 6.99]
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 23.600
behaviour_state: repelled
behaviour_stage: 1
scale: 1.430
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g4_2
generation: 5
message: near FRAME_g4_5
_origin: [-7.93, 0.00, 4.42]

---

## events
- FRAME_g3_2 -> FRAME_g4_5 (gen 4)
- FRAME_g1_2 -> FRAME_g2_10 (gen 2)
- ECHO_g1_0 -> ECHO_g2_8 (gen 2)
- FRAME_g1_0 -> FRAME_g2_11 (gen 2)
- ECHO_g1_3 -> ECHO_g2_8 (gen 2)
- FRAME_g1_3 -> FRAME_g2_11 (gen 2)
- ECHO_g4_0 -> ECHO_g5_1 (gen 5)
- FRAME_g4_0 -> FRAME_g5_1 (gen 5)
- ECHO_g4_1 -> ECHO_g5_1 (gen 5)
- FRAME_g4_1 -> FRAME_g5_1 (gen 5)
- ECHO_g1_1 -> ECHO_g2_9 (gen 2)
- FRAME_g1_1 -> FRAME_g2_12 (gen 2)
- ECHO_g1_2 -> ECHO_g2_9 (gen 2)
- FRAME_g2_3 -> FRAME_g3_9 (gen 3)
- ECHO_g1_4 -> ECHO_g2_9 (gen 2)
- FRAME_g1_4 -> FRAME_g2_12 (gen 2)
- ECHO_g1_5 -> ECHO_g2_9 (gen 2)
- FRAME_g1_5 -> FRAME_g2_12 (gen 2)
- ECHO_g4_2 -> ECHO_g5_2 (gen 5)
- FRAME_g4_2 -> FRAME_g5_2 (gen 5)

---

*VOID v3.0 — tick 739 — 19:49:37*