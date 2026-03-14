# VOID — WORLD MANIFEST v3
*Architekt-generiert.*

---

## meta
version: 631
last_updated: 2026-03-14T19:40:16.292615
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
position: [3.02, 0, 4.68]
behaviour: flock
behaviour_speed: 0.250
behaviour_range: 18
online: False
message: near FRAME
energy: 67.700
energy_ticks: 0
age: 11
children: 0
_dir: [0.05, 0.00, 1.00]
behaviour_state: repelled

### FRAME
mesh: TETRA
color: #999999
scale: 1.400
position: [1.38, 0, 6.32]
behaviour: flock
behaviour_speed: 0.280
behaviour_range: 18
online: False
message: near ECHO
energy: 67.700
energy_ticks: 0
age: 11
children: 0
_dir: [0.34, 0.00, 0.94]
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

*VOID v3.0 — tick 631 — 19:40:16*