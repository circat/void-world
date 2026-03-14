# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 633
last_updated: 2026-03-14T19:40:26.640490
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
position: [3.13, 0, 6.68]
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME
energy: 69.100
energy_ticks: 0
age: 13
children: 0
_dir: [0.03, 0.00, 1.00]
behaviour_state: repelled

### FRAME
mesh: TETRA
color: #999999
scale: 1.400
position: [1.79, 0, 8.51]
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: near ECHO
energy: 69.100
energy_ticks: 0
age: 13
children: 0
_dir: [0.11, 0.00, 0.99]
behaviour_state: repelled

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

---

*VOID v3.0 — tick 633 — 19:40:26*