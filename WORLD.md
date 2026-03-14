# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 733
last_updated: 2026-03-14T19:49:05.581754
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
position: [6.35, 0.00, 12.43]
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near ECHO_g3_5
energy: 74.900
energy_ticks: 0
age: 95
children: 6
_dir: [-0.93, 0.00, -0.36]
behaviour_state: seeking_center

### FRAME
mesh: TETRA
color: #999999
scale: 1.400
position: [7.98, 0.00, 11.98]
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: near ECHO_g3_5
energy: 74.900
energy_ticks: 0
age: 95
children: 6
_dir: [-0.86, 0.00, -0.51]
behaviour_state: repelled

### ECHO_g1_0
online: False
energy: 65.600
age: 66
children: 5
energy_ticks: 0
position: [4.23, 0.00, 18.70]
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
message: near FRAME_g3_7
_origin: [0.22, 0.00, 19.33]
_dir: [-0.88, 0.00, -0.47]

### FRAME_g1_0
online: False
energy: 65.600
age: 66
children: 5
energy_ticks: 0
position: [1.15, 0.00, 21.29]
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
message: near FRAME_g3_8
_origin: [-3.55, 0.00, 19.98]
_dir: [-0.86, 0.00, -0.50]

### ECHO_g1_1
online: False
energy: 63.400
age: 54
children: 4
energy_ticks: 0
position: [5.29, 0.00, 15.29]
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
message: near FRAME_g3_7
_origin: [9.39, 0.00, 20.75]
_dir: [-1.00, 0.00, -0.10]

### FRAME_g1_1
online: False
energy: 63.400
age: 54
children: 4
energy_ticks: 0
position: [1.76, 0.00, 13.76]
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
message: near FRAME_g3_8
_origin: [4.87, 0.00, 22.88]
_dir: [-0.82, 0.00, -0.57]

### ECHO_g2_0
online: False
energy: 54.100
age: 51
children: 4
energy_ticks: 0
position: [10.62, 0.00, 18.89]
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
message: near ECHO_g5_0
_origin: [12.41, 0.00, 22.95]
_dir: [-0.76, 0.00, -0.65]

### FRAME_g2_0
online: False
energy: 54.100
age: 51
children: 4
energy_ticks: 0
position: [4.76, 0.00, 19.23]
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
message: near FRAME_g3_7
_origin: [8.40, 0.00, 22.10]
_dir: [-0.66, 0.00, -0.76]

### ECHO_g1_2
online: False
energy: 64.300
age: 43
children: 3
energy_ticks: 0
position: [8.77, 0.00, 14.53]
behaviour: flock
behaviour_speed: 0.261
behaviour_range: 17.500
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.210
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO
generation: 1
message: near FRAME_g3_7
_origin: [14.44, 0.00, 13.21]
_dir: [-0.91, 0.00, -0.41]

### FRAME_g1_2
online: False
energy: 72.300
age: 43
children: 3
energy_ticks: 0
position: [34.62, 0.00, 10.32]
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
message: near FRAME_g4_3
_origin: [12.36, 0.00, 10.26]
_pulse_phase: 172.000

### ECHO_g2_1
online: False
energy: 55.000
age: 40
children: 3
energy_ticks: 0
position: [6.30, 0.00, 17.84]
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
message: near FRAME_g3_7
_origin: [13.58, 0.00, 12.43]
_dir: [-0.94, 0.00, -0.33]

### FRAME_g2_1
online: False
energy: 55.000
age: 40
children: 3
energy_ticks: 0
position: [6.05, 0.00, 21.17]
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
_dir: [-0.82, 0.00, -0.57]

### ECHO_g2_2
online: False
energy: 51.900
age: 39
children: 3
energy_ticks: 0
position: [3.58, 0.00, 10.02]
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
message: near FRAME_g5_0
_origin: [12.94, 0.00, 2.84]
_dir: [-0.54, 0.00, -0.84]

### FRAME_g2_2
online: False
energy: 51.900
age: 39
children: 3
energy_ticks: 0
position: [4.76, 0.00, 14.34]
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
message: near ECHO_g3_5
_origin: [9.67, 0.00, 9.55]
_dir: [0.18, 0.00, -0.98]

### ECHO_g3_0
online: False
energy: 77.600
age: 36
children: 2
energy_ticks: 0
position: [12.47, 0.00, 19.15]
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
message: near ECHO_g3_6
_origin: [16.55, 0.00, 9.76]
_dir: [-0.99, 0.00, -0.17]

### FRAME_g3_0
online: False
energy: 77.600
age: 36
children: 2
energy_ticks: 0
position: [-0.76, 0.00, 14.08]
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
message: near FRAME_g3_8
_origin: [4.69, 0.00, 7.54]
_dir: [-0.70, 0.00, -0.71]

### ECHO_g1_3
online: False
energy: 65.200
age: 32
children: 2
energy_ticks: 0
position: [11.12, 0.00, 8.25]
behaviour: flock
behaviour_speed: 0.245
behaviour_range: 17.000
behaviour_state: seeking_center
behaviour_stage: 1
scale: 1.200
mesh: OCTA
color: #bbbbbb
special: ECHO
parent: ECHO
generation: 1
message: near FRAME_g2_9
_origin: [17.28, 0.00, -0.68]
_dir: [-0.82, 0.00, -0.57]

### FRAME_g1_3
online: False
energy: 65.600
age: 32
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
energy: 55.900
age: 29
children: 2
energy_ticks: 0
position: [6.00, 0.00, 15.71]
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
message: near FRAME_g3_7
_origin: [16.62, 0.00, 4.94]
_dir: [-0.98, 0.00, 0.18]

### FRAME_g2_3
online: False
energy: 61.500
age: 29
children: 2
energy_ticks: 0
position: [27.78, 0.00, 2.12]
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
message: near FRAME_g2_5
_origin: [20.10, 0.00, 8.61]
_pulse_phase: 116.000
_dir: [0.48, 0.00, -0.88]

### ECHO_g2_4
online: False
energy: 52.800
age: 28
children: 2
energy_ticks: 0
position: [10.12, 0.00, 15.48]
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
message: near ECHO_g3_6
_origin: [15.60, 0.00, -0.15]
_dir: [-0.79, 0.00, -0.61]

### FRAME_g2_4
online: False
energy: 52.800
age: 28
children: 2
energy_ticks: 0
position: [1.64, 0.00, 18.62]
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
message: near FRAME_g3_8
_origin: [12.29, 0.00, 4.70]
_dir: [-0.48, 0.00, -0.88]

### ECHO_g3_1
online: False
energy: 78.500
age: 25
children: 1
energy_ticks: 0
position: [7.30, 0.00, 16.38]
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
message: near FRAME_g3_7
_origin: [17.31, 0.00, 0.59]
_dir: [-0.82, 0.00, -0.57]

### FRAME_g3_1
online: False
energy: 78.500
age: 25
children: 1
energy_ticks: 0
position: [2.44, 0.00, 22.25]
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
_dir: [-0.73, 0.00, -0.68]

### ECHO_g3_2
online: False
energy: 75.400
age: 24
children: 1
energy_ticks: 0
position: [6.90, 0.00, 8.15]
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
message: near ECHO_g3_5
_origin: [18.38, 0.00, -4.84]
_dir: [-0.89, 0.00, -0.46]

### FRAME_g3_2
online: False
energy: 75.400
age: 24
children: 1
energy_ticks: 0
position: [1.27, 0.00, 11.09]
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
_dir: [-0.95, 0.00, -0.31]

### ECHO_g4_0
online: False
energy: 66.100
age: 21
children: 1
energy_ticks: 0
position: [11.10, 0.00, 16.09]
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
message: near ECHO_g3_6
_origin: [23.43, 0.00, 6.12]
_dir: [-0.89, 0.00, -0.46]

### FRAME_g4_0
online: False
energy: 66.100
age: 21
children: 1
energy_ticks: 0
position: [1.95, 0.00, 16.76]
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
message: near FRAME_g3_8
_origin: [14.74, 0.00, 3.02]
_dir: [-0.94, 0.00, -0.34]

### ECHO_g1_4
online: False
energy: 63.000
age: 20
children: 1
energy_ticks: 0
position: [14.81, 0.00, 16.62]
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
message: near ECHO_g2_5
_origin: [22.01, 0.00, -0.26]
_dir: [-0.98, 0.00, 0.22]

### FRAME_g1_4
online: False
energy: 63.000
age: 20
children: 1
energy_ticks: 0
position: [11.12, 0.00, 13.27]
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
message: near ECHO_g3_6
_origin: [21.73, 0.00, -0.06]
_dir: [-0.67, 0.00, -0.74]

### FRAME_g2_5
online: False
energy: 60.000
age: 18
children: 1
energy_ticks: 0
position: [31.53, 0.00, 5.59]
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
_pulse_phase: 72.000
_dir: [-0.17, 0.00, -0.99]

### ECHO_g2_5
online: False
energy: 53.700
age: 17
children: 1
energy_ticks: 0
position: [13.25, 0.00, 13.09]
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
message: near ECHO_g3_6
_origin: [21.14, 0.00, 1.10]
_dir: [-0.92, 0.00, -0.40]

### FRAME_g2_6
online: False
energy: 53.700
age: 17
children: 1
energy_ticks: 0
position: [-0.15, 0.00, 15.93]
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
message: near ECHO_g3_5
_origin: [14.09, 0.00, 7.62]
_dir: [-0.82, 0.00, -0.58]

### FRAME_g3_3
online: False
energy: 50.700
age: 15
children: 1
energy_ticks: 0
position: [31.08, 0.00, 7.71]
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
message: near FRAME_g3_6
_origin: [24.62, 0.00, 9.78]
_pulse_phase: 60.000

### ECHO_g3_3
online: False
energy: 79.400
age: 14
children: 0
energy_ticks: 0
position: [7.14, 0.00, 13.92]
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
message: near ECHO_g3_5
_origin: [17.17, 0.00, 12.60]
_dir: [-0.93, 0.00, -0.36]

### FRAME_g3_4
online: False
energy: 79.400
age: 14
children: 0
energy_ticks: 0
position: [9.66, 0.00, 22.32]
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
message: near ECHO_g5_0
_origin: [18.62, 0.00, 15.98]
_dir: [-0.79, 0.00, -0.61]

### ECHO_g3_4
online: False
energy: 78.700
age: 13
children: 0
energy_ticks: 0
position: [26.42, 0.00, 11.44]
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
message: near FRAME_g3_6
_origin: [22.82, 0.00, 11.10]
_pulse_phase: 52.000

### FRAME_g3_5
online: False
energy: 78.700
age: 13
children: 0
energy_ticks: 0
position: [21.02, 0.00, 12.84]
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
message: near ECHO_g3_6
_origin: [9.84, 0.00, 15.85]
_pulse_phase: 52.000

### ECHO_g4_1
online: False
energy: 67.000
age: 10
children: 0
energy_ticks: 0
position: [7.16, 0.00, 18.77]
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
message: near FRAME_g5_0
_origin: [14.39, 0.00, 16.79]
_dir: [-0.91, 0.00, -0.42]

### FRAME_g4_1
online: False
energy: 67.000
age: 10
children: 0
energy_ticks: 0
position: [5.04, 0.00, 22.59]
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
message: near FRAME_g3_7
_origin: [11.68, 0.00, 24.64]
_dir: [-0.81, 0.00, -0.58]

### ECHO_g1_5
online: False
energy: 63.900
age: 9
children: 0
energy_ticks: 0
position: [8.84, 0.00, 9.95]
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
message: near ECHO_g3_5
_origin: [13.28, 0.00, 11.87]
_dir: [-0.94, 0.00, -0.34]

### FRAME_g1_5
online: False
energy: 63.900
age: 9
children: 0
energy_ticks: 0
position: [2.83, 0.00, 6.79]
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
message: near ECHO_g3_5
_origin: [14.23, 0.00, 8.14]
_dir: [-0.98, 0.00, -0.22]

### ECHO_g4_2
online: False
energy: 63.900
age: 9
children: 0
energy_ticks: 0
position: [5.39, 0.00, 10.08]
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
message: near ECHO_g3_5
_origin: [12.57, 0.00, 6.59]
_dir: [-0.88, 0.00, -0.47]

### FRAME_g4_2
online: False
energy: 63.900
age: 9
children: 0
energy_ticks: 0
position: [-1.28, 0.00, 10.67]
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
message: near ECHO_g3_5
_origin: [8.78, 0.00, 13.49]
_dir: [-0.85, 0.00, -0.53]

### FRAME_g2_7
online: False
energy: 60.800
age: 8
children: 0
energy_ticks: 0
position: [39.67, 0.00, 7.70]
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
energy: 54.600
age: 6
children: 0
energy_ticks: 0
position: [13.18, 0.00, 10.06]
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
message: near ECHO_g3_6
_origin: [18.76, 0.00, 11.86]
_dir: [-0.89, 0.00, -0.46]

### FRAME_g2_8
online: False
energy: 54.600
age: 6
children: 0
energy_ticks: 0
position: [-1.76, 0.00, 19.71]
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
_dir: [-0.86, 0.00, -0.52]

### ECHO_g5_0
online: False
energy: 54.600
age: 6
children: 0
energy_ticks: 0
position: [8.07, 0.00, 17.77]
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
message: near FRAME_g5_0
_origin: [15.51, 0.00, 18.17]
_dir: [-0.76, 0.00, -0.64]

### FRAME_g5_0
online: False
energy: 54.600
age: 6
children: 0
energy_ticks: 0
position: [2.77, 0.00, 15.62]
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
message: near FRAME_g3_8
_origin: [5.75, 0.00, 20.09]
_dir: [-1.00, 0.00, -0.03]

### ECHO_g2_7
online: False
energy: 44.300
age: 5
children: 0
energy_ticks: 0
position: [-23.03, 0.00, 7.34]
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
energy: 51.500
age: 5
children: 0
energy_ticks: 0
position: [9.97, 0.00, 11.35]
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
_dir: [-0.86, 0.00, -0.51]

### FRAME_g3_6
online: False
energy: 48.400
age: 4
children: 0
energy_ticks: 0
position: [28.61, 0.00, 9.72]
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
message: near FRAME_g4_3
_origin: [34.40, 0.00, 9.71]
_dir: [-0.99, 0.00, -0.11]

### ECHO_g3_5
online: False
energy: 45.300
age: 3
children: 0
energy_ticks: 0
position: [3.44, 0.00, 12.18]
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
message: near FRAME_g5_0
_origin: [6.64, 0.00, 16.09]
_dir: [-0.86, 0.00, -0.51]

### FRAME_g3_7
online: False
energy: 45.300
age: 3
children: 0
energy_ticks: 0
position: [8.57, 0.00, 20.11]
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
message: near FRAME_g4_1
_origin: [7.32, 0.00, 21.36]
_dir: [-0.81, 0.00, -0.59]

### ECHO_g3_6
online: False
energy: 42.200
age: 2
children: 0
energy_ticks: 0
position: [15.86, 0.00, 14.37]
behaviour: flock
behaviour_speed: 0.229
behaviour_range: 16.300
behaviour_state: repelled
behaviour_stage: 1
scale: 1.150
mesh: DODECA
color: #bbbbbb
special: ECHO
parent: ECHO_g2_5
generation: 3
message: near ECHO_g2_6
_origin: [16.12, 0.00, 10.66]
_dir: [-0.85, 0.00, -0.53]

### FRAME_g3_8
online: False
energy: 42.200
age: 2
children: 0
energy_ticks: 0
position: [-2.29, 0.00, 17.16]
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
message: near FRAME_g5_0
_origin: [-1.29, 0.00, 17.01]
_dir: [-0.93, 0.00, -0.38]

### FRAME_g4_3
online: False
energy: 39.100
age: 1
children: 0
energy_ticks: 0
position: [31.66, 0.00, 8.45]
behaviour: pulse_rest
behaviour_speed: 0.278
behaviour_range: 17.200
behaviour_state: repelled
behaviour_stage: 1
scale: 1.390
mesh: OCTA
color: #999999
special: PULSE
parent: FRAME_g3_3
generation: 4
message: near FRAME_g3_6
_origin: [30.33, 0.00, 8.33]
_pulse_phase: 4.000

---

## events
- ECHO_g4_0 -> ECHO_g5_0 (gen 5)
- FRAME_g4_0 -> FRAME_g5_0 (gen 5)
- ECHO_g1_1 -> ECHO_g2_7 (gen 2)
- FRAME_g1_1 -> FRAME_g2_9 (gen 2)
- ECHO_g1_4 -> ECHO_g2_7 (gen 2)
- FRAME_g1_4 -> FRAME_g2_9 (gen 2)
- FRAME_g2_3 -> FRAME_g3_6 (gen 3)
- FRAME_g2_5 -> FRAME_g3_6 (gen 3)
- ECHO_g2_1 -> ECHO_g3_5 (gen 3)
- FRAME_g2_1 -> FRAME_g3_7 (gen 3)
- ECHO_g2_3 -> ECHO_g3_5 (gen 3)
- ECHO_g2_0 -> ECHO_g3_6 (gen 3)
- FRAME_g2_0 -> FRAME_g3_8 (gen 3)
- ECHO_g2_2 -> ECHO_g3_6 (gen 3)
- FRAME_g2_2 -> FRAME_g3_8 (gen 3)
- ECHO_g2_4 -> ECHO_g3_6 (gen 3)
- FRAME_g2_4 -> FRAME_g3_8 (gen 3)
- ECHO_g2_5 -> ECHO_g3_6 (gen 3)
- FRAME_g2_6 -> FRAME_g3_8 (gen 3)
- FRAME_g3_3 -> FRAME_g4_3 (gen 4)

---

*VOID v3.0 — tick 733 — 19:49:05*