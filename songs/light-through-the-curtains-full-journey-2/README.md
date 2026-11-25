# Light Through the Curtains — Full Journey

**76 BPM** · ambient · 12 pistas

| Pista | Nombre | Código |
|---|---|---|
| `d1` | Heartbeat Kick | `s "bd ~ ~ ~ ~ ~ ~ ~" # gain 0.07 # room 0.75 # size 0.85` |
| `d2` | d2 | `mask "<t!24 f!24>" $ n "<a3 c4 g3 e3> ~ ~ ~ <c5 e4 a4 g4> ~ ~ ~ <e5 a4 c5 g4> ~ ~ ~ <a5 e5 c6 g5> ~ <e6 c6 a5 e5> ~" # s "salamander_grand" # room 0.8 # size 0.9 # gain 0.6 # legato 1.1` |
| `d3` | Open Window | `s "birds" # gain 0.03 # room 0.6 # size 0.7 # speed 0.6` |
| `d4` | Morning Bass | `mask "<t!40 f!8>" $ n "a2 ~ ~ ~ ~ ~ ~ ~" # s "steinway_b" # lpf 380 # gain 0.1 # room 0.6 # size 0.85 # legato 1.2` |
| `d5` | Brushed Guitar | `mask "<t!40 f!8>" $ n "e4 ~ ~ a4 ~ ~ <c5 ~> ~" # s "ts_pluck" # room 0.6 # size 0.7 # gain 0.7 # legato 0.8 # delay 0.15 # delaytime 0.3 # delayfeedback 0.3` |
| `d6` | Wind Swell | `mask "<t!40 f!8>" $ whenmod 16 12 (# gain 0.5) $ s "wind" # gain 0.015 # room 0.7 # size 0.8 # speed 0.5` |
| `d7` | d7 | `mask "<f!8 t!32 f!8>" $ n "~ <e5 d5 c5 b4 a4 b4 d5 e5> ~ ~ <g5 a5 f5 e5 g5 f5 a5 g5> ~ <e5 g5 a5 c6 b5 a5 g5 e5> ~" # s "vibraphone_soft" # room 0.85 # size 0.9 # gain 1.0 # legato 1.1` |
| `d8` | Warm Pad | `mask "<f!16 t!24 f!8>" $ n "<[a3,c4,e4] [a3,c4,e4] [g3,b3,d4] [a3,c4,e4]>" # s "pad_2_warm_fluid" # legato 1.5 # lpf 1000 # room 0.9 # size 0.95 # gain 0.06` |
| `d9` | d9 | `mask "<f!24 t!24>" $ n "~ <c5 e5 g5 a4 g4 e4 c5 e5> <a4 g4 b4 e4 g4 a4 b4 c5> ~ <e5 d5 f5 g5 e4 f4 g4 a4> ~ [<c5 e5> <b4 g4> <a4 c5> <g4 b4>] ~" # s "salamander_grand" # room 0.8 # size 0.9 # gain 0.65 # legato 1.0` |
| `d10` | Cello Answer | `mask "<f!12 t!28 f!8>" $ n "e3 ~ ~ ~ g3 ~ ~ ~" # s "vsco_cellos_arco" # room 0.85 # size 0.95 # gain 0.9 # legato 1.4` |
| `d11` | Horn Breath | `mask "<f!20 t!20 f!8>" $ n "a3 ~ ~ ~ ~ ~ ~ ~" # s "french_horn_fluid" # room 0.9 # size 0.95 # gain 0.4 # legato 1.8` |
| `d12` | New Age Pad (high) | `mask "<f!16 t!32 f!0>" $ n "<[a4,e5] [g4,d5] [a4,c5] [e4,b4]>" # s "pad_1_new_age_fluid" # legato 2.0 # room 0.9 # size 0.95 # gain 0.055 # lpf 2200` |

Abre `song.tidal` en tu editor de TidalCycles, o abre la canción desde Tidal Studio (Mis proyectos → GitHub).
