# Reggaeton from scratch

**92 BPM** · 7 pistas

| Pista | Nombre | Código |
|---|---|---|
| `d1` | 808 kick | `mask "<f!4 t!4 f!2 t!6>" $ s "808bd:7*4" # gain 1` |
| `d2` | Dembow snare | `mask "<f!4 t!4 f!2 t!6>" $ s "[~ ~ ~ sn] [~ ~ sn ~] [~ ~ ~ sn] <[~ ~ sn ~] [~ ~ sn ~] [~ ~ sn ~] [sn sn sn sn]>" # gain 0.5 # nudge (-0.015)` |
| `d3` | Hi-hats | `mask "<t!8 f!2 t!6>" $ s "hh*8" # gain "[0.55 0.8]*4" # pan 0.6` |
| `d4` | 808 sub | `mask "<f!4 t!4 f!2 t!6>" $ struct "t ~ ~ t ~ ~ t ~" $ n "<a2 f2 c3 g2>" # s "ts_sub" # legato 0.6 # gain 0.95` |
| `d5` | Pad | `n "<[a4,c5,e5] [a4,c5,f5] [g4,c5,e5] [g4,b4,d5]>" # s "pad_2_warm_fluid" # legato 1 # gain 0.8 # lpf 2500 # room 0.3` |
| `d6` | Guitar (hook) | `mask "<t!4 f!4 t!8>" $ n "<[e6 ~ ~ c6 ~ ~ a5 ~] [c6 ~ ~ a5 ~ ~ f5 ~] [e6 ~ ~ g6 ~ ~ e6 ~] [d6 ~ ~ b5 ~ ~ g5 ~]>" # s "acoustic_guitar_nylon_fluid" # gain 0.9 # delay 0.3 # delaytime (60/92/2) # delayfeedback 0.35` |
| `d7` | Vocal chops | `mask "<f!10 t!6>" $ n "<[~ ~ e5 ~ ~ e5 ~ ~] [~ ~ c5 ~ ~ c5 ~ ~] [~ ~ e5 ~ ~ g5 ~ ~] [~ ~ d5 ~ ~ b4 ~ ~]>" # s "voice_oohs_fluid" # legato 0.5 # gain 0.3 # room 0.3 # pan 0.4` |

Abre `song.tidal` en tu editor de TidalCycles, o abre la canción desde Tidal Studio (Mis proyectos → GitHub).
