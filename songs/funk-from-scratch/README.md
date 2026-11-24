# Funk from scratch

**104 BPM** · 6 pistas

| Pista | Nombre | Código |
|---|---|---|
| `d1` | Kick | `s "bd ~ ~ bd ~ ~ ~ ~ ~ ~ bd ~ ~ bd ~ ~" # gain 1` |
| `d2` | Snare | `s "~ ~ ~ ~ sn ~ ~ sn ~ sn ~ ~ sn ~ ~ sn" # gain "0 0 0 0 1 0 0 0.35 0 0.35 0 0 1 0 0 0.4"` |
| `d3` | Hi-hats | `s "hh*16" # gain "[0.9 0.5 0.7 0.5]*4"` |
| `d4` | Bass | `mask "<f!2 t!14>" $ n "<[e3 ~ e4 ~ ~ e3 ~ d4 ~ e3 ~ g3 ~ a3 b3 ~] [a3 ~ a4 ~ ~ a3 ~ g4 ~ a3 ~ c4 ~ cs4 d4 ~]>" # s "superpwm" # lpf 1500 # legato 0.5 # gain 0.95` |
| `d5` | Guitar | `mask "<f!4 t!12>" $ struct "~ t ~ t ~ ~ t ~ ~ t ~ t ~ ~ t ~" $ note "<e'min7 a4'dom9>" # s "gtr" # legato 0.4 # hpf 500 # gain 0.75 # pan 0.35` |
| `d6` | Horns | `mask "<f!8 t!8>" $ n "<[~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ [d6,g6] ~ [d6,g6] ~] [~ ~ ~ ~ ~ ~ ~ ~ [e6,g6] ~ [e6,g6] ~ ~ ~ [g6,cs7] ~]>" # s "supertrumpet" # legato 0.5 # gain 0.7` |

Abre `song.tidal` en tu editor de TidalCycles, o abre la canción desde Tidal Studio (Mis proyectos → GitHub).
