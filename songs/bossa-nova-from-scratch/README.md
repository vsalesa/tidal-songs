# Bossa nova from scratch

**130 BPM** · 7 pistas

| Pista | Nombre | Código |
|---|---|---|
| `d1` | Shaker | `s "[shaker_small:0 shaker_small:2]*8" # gain "[0.95 0.7 0.85 0.7]*4" # hpf 3000 # pan 0.6 # room 0.58` |
| `d2` | Surdo | `s "bd ~ ~ bd bd ~ ~ bd" # gain 0.8 # lpf 900` |
| `d3` | Rimshot | `s "<[808:5 ~ ~ 808:5 ~ ~ 808:5 ~] [~ ~ 808:5 ~ ~ 808:5 ~ ~]>" # gain 0.75` |
| `d4` | Upright bass | `n "<[c3 ~ ~ g2 g2 ~ ~ c3] [a2 ~ ~ e3 e3 ~ ~ a2] [d3 ~ ~ a2 a2 ~ ~ d3] [g2 ~ ~ d3 d3 ~ ~ g2]>" # s "acoustic_bass_fluid" # legato 1 # gain 0.9` |
| `d5` | Nylon guitar | `n "<[c4'maj7 ~ ~ c4'maj7 ~ ~ c4'maj7 a3'min7] [~ ~ a3'min7 ~ ~ a3'min7 ~ ~] [d4'min7 ~ ~ d4'min7 ~ ~ d4'min7 g3'dom7] [~ ~ g3'dom7 ~ ~ g3'dom7 ~ ~]>" # s "acoustic_guitar_nylon_fluid" # legato 0.5 # gain 0.85 # room 0.15` |
| `d6` | Flute | `n "<[e6 ~ ~ d6 e6 ~ ~ g6] [~ ~ ~ ~ e6 ~ ~ ~] [f6 ~ ~ e6 f6 ~ ~ a6] [g6 ~ ~ f6 d6 ~ b5 ~] [e6 ~ ~ d6 e6 ~ ~ b6] [a6 ~ ~ ~ g6 ~ ~ ~] [f6 ~ ~ e6 f6 ~ ~ d7] [c7 ~ ~ b6 ~ ~ ~ ~]>" # s "flute_fluid" # legato 0.95 # gain 0.85 # room 0.3` |
| `d7` | FM electric piano (Tidal Studio) | `n "a5 a5" # s "ts_rhodes"` |

Abre `song.tidal` en tu editor de TidalCycles, o abre la canción desde Tidal Studio (Mis proyectos → GitHub).
