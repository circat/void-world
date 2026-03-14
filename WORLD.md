# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 729
last_updated: 2026-03-14T19:48:44.428739
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
position: [10.13, 0.00, 12.97]
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME_g2_9
energy: 62.500
energy_ticks: 0
age: 91
children: 6
_dir: [-0.99, 0.00, 0.13]
behaviour_state: seeking_center

### FRAME
mesh: TETRA
color: #999999
scale: 1.400
position: [11.98, 0.00, 12.88]
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: near ECHO_g2_6
energy: 62.500
energy_ticks: 0
age: 91
children: 6
_dir: [-0.98, 0.00, -0.18]
behaviour_state: repelled

### ECHO_g1_0
online: False
energy: 53.200
age: 62
children: 5
energy_ticks: 0
position: [8.04, 0.00, 20.03]
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
message: near ECHO_g2_7
_origin: [0.22, 0.00, 19.33]
_dir: [-0.98, 0.00, -0.21]

### FRAME_g1_0
online: False
energy: 53.200
age: 62
children: 5
energy_ticks: 0
position: [4.88, 0.00, 23.56]
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
message: near FRAME_g2_8
_origin: [-3.55, 0.00, 19.98]
_dir: [-0.93, 0.00, -0.36]

### ECHO_g1_1
online: False
energy: 51.000
age: 50
children: 4
energy_ticks: 0
position: [9.29, 0.00, 16.48]
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
message: near FRAME_g2_9
_origin: [9.39, 0.00, 20.75]
_dir: [-1.00, 0.00, -0.09]

### FRAME_g1_1
online: False
energy: 51.000
age: 50
children: 4
energy_ticks: 0
position: [5.65, 0.00, 15.78]
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
message: near FRAME_g4_2
_origin: [4.87, 0.00, 22.88]
_dir: [-0.96, 0.00, -0.26]

### ECHO_g2_0
online: False
energy: 76.700
age: 47
children: 3
energy_ticks: 0
position: [14.15, 0.00, 20.57]
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
message: near ECHO_g4_1
_origin: [12.41, 0.00, 22.95]
_dir: [-0.82, 0.00, 0.57]

### FRAME_g2_0
online: False
energy: 76.700
age: 47
children: 3
energy_ticks: 0
position: [8.64, 0.00, 21.77]
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
message: near ECHO_g2_7
_origin: [8.40, 0.00, 22.10]
_dir: [-0.94, 0.00, 0.34]

### ECHO_g1_2
online: False
energy: 51.900
age: 39
children: 3
energy_ticks: 0
position: [12.73, 0.00, 15.73]
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
message: near FRAME_g2_9
_origin: [14.44, 0.00, 13.21]
_dir: [-0.94, 0.00, 0.35]

### FRAME_g1_2
online: False
energy: 59.100
age: 39
children: 3
energy_ticks: 0
position: [33.62, 0.00, 10.32]
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
message: near FRAME_g2_7
_origin: [12.36, 0.00, 10.26]
_pulse_phase: 156.000

### ECHO_g2_1
online: False
energy: 77.600
age: 36
children: 2
energy_ticks: 0
position: [9.97, 0.00, 18.37]
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
message: near ECHO_g2_7
_origin: [13.58, 0.00, 12.43]
_dir: [-0.95, 0.00, 0.31]

### FRAME_g2_1
online: False
energy: 77.600
age: 36
children: 2
energy_ticks: 0
position: [10.31, 0.00, 23.09]
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
message: near ECHO_g2_7
_origin: [8.64, 0.00, 13.56]
_dir: [-0.99, 0.00, 0.11]

### ECHO_g2_2
online: False
energy: 74.500
age: 35
children: 2
energy_ticks: 0
position: [6.91, 0.00, 11.18]
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
message: near FRAME_g4_2
_origin: [12.94, 0.00, 2.84]
_dir: [-0.97, 0.00, 0.26]

### FRAME_g2_2
online: False
energy: 74.500
age: 35
children: 2
energy_ticks: 0
position: [7.78, 0.00, 15.24]
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
message: near FRAME_g5_0
_origin: [9.67, 0.00, 9.55]
_dir: [-0.86, 0.00, 0.51]

### ECHO_g3_0
online: False
energy: 65.200
age: 32
children: 2
energy_ticks: 0
position: [16.65, 0.00, 19.63]
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
message: near ECHO_g2_7
_origin: [16.55, 0.00, 9.76]
_dir: [-0.99, 0.00, 0.13]

### FRAME_g3_0
online: False
energy: 65.200
age: 32
children: 2
energy_ticks: 0
position: [2.96, 0.00, 16.92]
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
message: near FRAME_g5_0
_origin: [4.69, 0.00, 7.54]
_dir: [-1.00, 0.00, 0.10]

### ECHO_g1_3
online: False
energy: 52.800
age: 28
children: 2
energy_ticks: 0
position: [14.66, 0.00, 9.71]
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
message: near FRAME_g2_9
_origin: [17.28, 0.00, -0.68]
_dir: [-1.00, 0.00, 0.03]

### FRAME_g1_3
online: False
energy: 59.200
age: 28
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
energy: 78.500
age: 25
children: 1
energy_ticks: 0
position: [9.79, 0.00, 16.96]
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
message: near FRAME_g2_9
_origin: [16.62, 0.00, 4.94]
_dir: [-0.95, 0.00, 0.30]

### FRAME_g2_3
online: False
energy: 48.300
age: 25
children: 2
energy_ticks: 0
position: [26.72, 0.00, 4.06]
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
message: near FRAME_g3_3
_origin: [20.10, 0.00, 8.61]
_pulse_phase: 100.000
_dir: [0.48, 0.00, -0.88]

### ECHO_g2_4
online: False
energy: 75.400
age: 24
children: 1
energy_ticks: 0
position: [13.63, 0.00, 16.89]
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
message: near FRAME_g2_9
_origin: [15.60, 0.00, -0.15]
_dir: [-0.91, 0.00, 0.42]

### FRAME_g2_4
online: False
energy: 75.400
age: 24
children: 1
energy_ticks: 0
position: [4.87, 0.00, 21.76]
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
message: near FRAME_g5_0
_origin: [12.29, 0.00, 4.70]
_dir: [-0.88, 0.00, 0.47]

### ECHO_g3_1
online: False
energy: 66.100
age: 21
children: 1
energy_ticks: 0
position: [11.07, 0.00, 17.88]
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
message: near FRAME_g2_9
_origin: [17.31, 0.00, 0.59]
_dir: [-1.00, 0.00, -0.04]

### FRAME_g3_1
online: False
energy: 66.100
age: 21
children: 1
energy_ticks: 0
position: [6.16, 0.00, 25.18]
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
message: near FRAME_g2_8
_origin: [17.31, 0.00, 9.47]
_dir: [-1.00, 0.00, 0.03]

### ECHO_g3_2
online: False
energy: 63.000
age: 20
children: 1
energy_ticks: 0
position: [10.60, 0.00, 9.34]
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
message: near FRAME_g2_9
_origin: [18.38, 0.00, -4.84]
_dir: [-0.99, 0.00, -0.14]

### FRAME_g3_2
online: False
energy: 63.000
age: 20
children: 1
energy_ticks: 0
position: [5.23, 0.00, 13.77]
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
message: near FRAME_g5_0
_origin: [19.12, 0.00, -0.51]
_dir: [-0.94, 0.00, -0.33]

### ECHO_g4_0
online: False
energy: 53.700
age: 17
children: 1
energy_ticks: 0
position: [14.98, 0.00, 17.58]
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
message: near FRAME_g2_9
_origin: [23.43, 0.00, 6.12]
_dir: [-0.94, 0.00, 0.33]

### FRAME_g4_0
online: False
energy: 53.700
age: 17
children: 1
energy_ticks: 0
position: [6.08, 0.00, 19.29]
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
message: near FRAME_g2_8
_origin: [14.74, 0.00, 3.02]
_dir: [-0.94, 0.00, 0.35]

### ECHO_g1_4
online: False
energy: 50.600
age: 16
children: 1
energy_ticks: 0
position: [18.51, 0.00, 15.75]
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
message: near FRAME_g2_9
_origin: [22.01, 0.00, -0.26]
_dir: [-0.81, 0.00, 0.59]

### FRAME_g1_4
online: False
energy: 50.600
age: 16
children: 1
energy_ticks: 0
position: [14.49, 0.00, 15.43]
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
message: near ECHO_g2_7
_origin: [21.73, 0.00, -0.06]
_dir: [-0.22, 0.00, 0.97]

### FRAME_g2_5
online: False
energy: 47.200
age: 14
children: 1
energy_ticks: 0
position: [32.04, 0.00, 8.61]
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
message: near FRAME_g2_7
_origin: [26.65, 0.00, 10.45]
_pulse_phase: 56.000

### ECHO_g2_5
online: False
energy: 76.300
age: 13
children: 0
energy_ticks: 0
position: [16.76, 0.00, 13.22]
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
message: near FRAME_g2_9
_origin: [21.14, 0.00, 1.10]
_dir: [-0.60, 0.00, 0.80]

### FRAME_g2_6
online: False
energy: 76.300
age: 13
children: 0
energy_ticks: 0
position: [2.25, 0.00, 18.68]
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
message: near FRAME_g5_0
_origin: [14.09, 0.00, 7.62]
_dir: [-0.99, 0.00, -0.12]

### FRAME_g3_3
online: False
energy: 72.500
age: 11
children: 0
energy_ticks: 0
position: [28.84, 0.00, 7.71]
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
message: near FRAME_g3_6
_origin: [24.62, 0.00, 9.78]
_pulse_phase: 44.000

### ECHO_g3_3
online: False
energy: 67.000
age: 10
children: 0
energy_ticks: 0
position: [11.03, 0.00, 14.53]
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
message: near FRAME_g2_9
_origin: [17.17, 0.00, 12.60]
_dir: [-0.98, 0.00, 0.18]

### FRAME_g3_4
online: False
energy: 67.000
age: 10
children: 0
energy_ticks: 0
position: [13.63, 0.00, 23.33]
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
message: near ECHO_g2_7
_origin: [18.62, 0.00, 15.98]
_dir: [-1.00, 0.00, -0.08]

### ECHO_g3_4
online: False
energy: 65.900
age: 9
children: 0
energy_ticks: 0
position: [23.60, 0.00, 11.44]
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
message: near ECHO_g2_7
_origin: [22.82, 0.00, 11.10]
_pulse_phase: 36.000

### FRAME_g3_5
online: False
energy: 65.900
age: 9
children: 0
energy_ticks: 0
position: [17.36, 0.00, 12.84]
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
message: near FRAME_g2_9
_origin: [9.84, 0.00, 15.85]
_pulse_phase: 36.000

### ECHO_g4_1
online: False
energy: 54.600
age: 6
children: 0
energy_ticks: 0
position: [10.93, 0.00, 20.62]
behaviour: flock
behaviour_speed: 0.263
behaviour_range: 17.800
behaviour_state: repelled
behaviour_stage: 1
scale: 1.270
mesh: DODECA
color: #bbbbbb
special: ECHO
parent: ECHO_g3_1
generation: 4
message: near FRAME_g5_0
_origin: [14.39, 0.00, 16.79]
_dir: [-0.99, 0.00, 0.13]

### FRAME_g4_1
online: False
energy: 54.600
age: 6
children: 0
energy_ticks: 0
position: [8.68, 0.00, 25.49]
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
message: near ECHO_g4_1
_origin: [11.68, 0.00, 24.64]
_dir: [-0.95, 0.00, -0.30]

### ECHO_g1_5
online: False
energy: 51.500
age: 5
children: 0
energy_ticks: 0
position: [12.41, 0.00, 11.17]
behaviour: flock
behaviour_speed: 0.269
behaviour_range: 16.100
behaviour_state: repelled
behaviour_stage: 1
scale: 1.260
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO
generation: 1
message: near ECHO_g2_6
_origin: [13.28, 0.00, 11.87]
_dir: [-0.84, 0.00, 0.55]

### FRAME_g1_5
online: False
energy: 51.500
age: 5
children: 0
energy_ticks: 0
position: [7.40, 0.00, 7.67]
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
message: near ECHO_g4_2
_origin: [14.23, 0.00, 8.14]
_dir: [-1.00, 0.00, 0.06]

### ECHO_g4_2
online: False
energy: 51.500
age: 5
children: 0
energy_ticks: 0
position: [8.78, 0.00, 11.28]
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
message: near FRAME_g2_9
_origin: [12.57, 0.00, 6.59]
_dir: [-0.93, 0.00, 0.36]

### FRAME_g4_2
online: False
energy: 51.500
age: 5
children: 0
energy_ticks: 0
position: [3.02, 0.00, 12.57]
behaviour: flock
behaviour_speed: 0.295
behaviour_range: 23.600
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.380
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g3_2
generation: 4
message: near FRAME_g5_0
_origin: [8.78, 0.00, 13.49]
_dir: [-1.00, 0.00, -0.09]

### FRAME_g2_7
online: False
energy: 48.400
age: 4
children: 0
energy_ticks: 0
position: [35.35, 0.00, 7.70]
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
message: near FRAME_g3_6
_origin: [33.37, 0.00, 10.31]

### ECHO_g2_6
online: False
energy: 42.200
age: 2
children: 0
energy_ticks: 0
position: [16.86, 0.00, 11.48]
behaviour: flock
behaviour_speed: 0.249
behaviour_range: 15.800
behaviour_state: repelled
behaviour_stage: 1
scale: 1.190
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO_g1_3
generation: 2
message: near FRAME_g2_9
_origin: [18.76, 0.00, 11.86]
_dir: [-0.55, 0.00, -0.84]

### FRAME_g2_8
online: False
energy: 42.200
age: 2
children: 0
energy_ticks: 0
position: [2.38, 0.00, 20.85]
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
message: near FRAME_g5_0
_origin: [9.52, 0.00, 24.36]
_dir: [-0.95, 0.00, -0.30]

### ECHO_g5_0
online: False
energy: 42.200
age: 2
children: 0
energy_ticks: 0
position: [12.08, 0.00, 19.34]
behaviour: flock
behaviour_speed: 0.275
behaviour_range: 17.900
behaviour_state: repelled
behaviour_stage: 1
scale: 1.280
mesh: GEM
color: #bbbbbb
special: ECHO
parent: ECHO_g4_0
generation: 5
message: near FRAME_g3_4
_origin: [15.51, 0.00, 18.17]
_dir: [-1.00, 0.00, -0.03]

### FRAME_g5_0
online: False
energy: 42.200
age: 2
children: 0
energy_ticks: 0
position: [5.91, 0.00, 17.60]
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
message: near FRAME_g2_8
_origin: [5.75, 0.00, 20.09]
_dir: [-1.00, 0.00, 0.02]

### ECHO_g2_7
online: False
energy: 39.100
age: 1
children: 0
energy_ticks: 0
position: [13.20, 0.00, 20.25]
behaviour: orbit
behaviour_speed: 0.230
behaviour_range: 18.900
behaviour_state: repelled
behaviour_stage: 1
scale: 1.190
mesh: ICOSA
color: #bbbbbb
special: ORBIT
parent: ECHO_g1_4
generation: 2
message: near FRAME_g3_4
_origin: [19.64, 0.00, 17.19]

### FRAME_g2_9
online: False
energy: 39.100
age: 1
children: 0
energy_ticks: 0
position: [13.67, 0.00, 13.30]
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
message: near ECHO_g2_6
_origin: [16.73, 0.00, 16.47]
_dir: [-0.90, 0.00, -0.43]

### FRAME_g3_6
online: False
energy: 36.000
age: 0
children: 0
energy_ticks: 0
position: [32.64, 0.00, 9.49]
behaviour: flock
behaviour_speed: 0.254
behaviour_range: 18.700
behaviour_state: repelled
behaviour_stage: 1
scale: 1.390
mesh: TETRA
color: #999999
special: ECHO
parent: FRAME_g2_5
generation: 3
message: near FRAME_g2_7
_origin: [34.40, 0.00, 9.71]

---

## events
- FRAME_g3_0 -> FRAME_g4_1 (gen 4)
- ECHO_g3_1 -> ECHO_g4_1 (gen 4)
- FRAME_g3_1 -> FRAME_g4_1 (gen 4)
- ECHO -> ECHO_g1_5 (gen 1)
- FRAME -> FRAME_g1_5 (gen 1)
- ECHO_g3_2 -> ECHO_g4_2 (gen 4)
- FRAME_g3_2 -> FRAME_g4_2 (gen 4)
- FRAME_g1_2 -> FRAME_g2_7 (gen 2)
- ECHO_g1_0 -> ECHO_g2_6 (gen 2)
- FRAME_g1_0 -> FRAME_g2_8 (gen 2)
- ECHO_g1_2 -> ECHO_g2_6 (gen 2)
- ECHO_g1_3 -> ECHO_g2_6 (gen 2)
- ECHO_g4_0 -> ECHO_g5_0 (gen 5)
- FRAME_g4_0 -> FRAME_g5_0 (gen 5)
- ECHO_g1_1 -> ECHO_g2_7 (gen 2)
- FRAME_g1_1 -> FRAME_g2_9 (gen 2)
- ECHO_g1_4 -> ECHO_g2_7 (gen 2)
- FRAME_g1_4 -> FRAME_g2_9 (gen 2)
- FRAME_g2_3 -> FRAME_g3_6 (gen 3)
- FRAME_g2_5 -> FRAME_g3_6 (gen 3)

---

*VOID v3.0 — tick 729 — 19:48:44*