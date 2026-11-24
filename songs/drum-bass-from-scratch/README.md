# Drum & bass from scratch

**174 BPM** · 7 pistas

| Pista | Nombre | Código |
|---|---|---|
| `d1` | Kick | `mask "<f!4 t!12>" $ s "bd ~ ~ ~ ~ ~ ~ ~ ~ ~ bd ~ ~ ~ ~ ~" # gain 1` |
| `d2` | Snare | `mask "<f!4 t!12>" $ s "~ sn ~ sn" # gain 1 # shape 0.2` |
| `d3` | Hi-hats | `mask "<f!2 t!14>" $ s "hh*8" # gain "[0.7 0.5]*4"` |
| `d4` | Chopped break | `mask "<f!8 t!8>" $ s "amencutup*16" # n (irand 32) # gain 0.6 # hpf 1500` |
| `d5` | Bass | `mask "<f!4 t!12>" $ n "<[d3@6 f3@2] [bf2@6 a2@2] [f2@8] [c3@6 e3@2]>" # s "supersaw" # lpf 500 # legato 1 # gain 0.8` |
| `d6` | Pad | `n "<d'min bf4'maj f4'maj c'maj>" # s "supersaw" # lpf 1800 # legato 1 # gain 0.4 # room 0.6 # size 0.9` |
| `d7` | Piano | `mask "<t!4 f!4 t!8>" $ n "<[a6 ~ ~ f6 ~ ~ d6 ~] [~ ~ ~ ~ f6 ~ e6 d6] [c6 ~ ~ a5 ~ ~ c6 ~] [e6 ~ ~ ~ g6 ~ e6 ~]>" # s "superpiano" # gain 0.6 # room 0.4 # delay 0.35 # delaytime (60/174*0.75) # delayfeedback 0.4` |

Abre `song.tidal` en tu editor de TidalCycles, o abre la canción desde Tidal Studio (Mis proyectos → GitHub).
