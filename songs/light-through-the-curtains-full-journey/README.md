# Light Through the Curtains — Full Journey (e597cab)

**76 BPM** · ambient · 14 pistas

| Pista | Nombre | Código |
|---|---|---|
| `d1` | Chillout Beat | `stack [s "808bd ~ ~ ~ ~ 808bd ~ ~" # gain 1.25, s "~ ~ rm ~ ~ ~ rm ~" # gain 1.1 # room 0.4, s "hh*8" # gain (range 0.85 1.05 $ fast 2 sine) # hpf 4000 # pan 0.6]` |
| `d2` | Childhood Piano (early) | `mask "<t!24 f!24>" $ n "a3 ~ ~ ~ c5 ~ ~ ~ e5 ~ ~ ~ a5 ~ e6 ~" # s "salamander_grand" # room 0.8 # size 0.9 # gain 0.6 # legato 1.1` |
| `d3` | Open Window | `s "birds" # gain 0.03 # room 0.6 # size 0.7 # speed 0.6` |
| `d4` | Morning Bass | `mask "<t!40 f!8>" $ n "a2 ~ ~ ~ ~ ~ ~ ~" # s "steinway_b" # lpf 380 # gain 0.1 # room 0.6 # size 0.85 # legato 1.2` |
| `d5` | Brushed Guitar | `mask "<t!40 f!8>" $ n "e4 ~ ~ a4 ~ ~ <c5 ~> ~" # s "ts_pluck" # room 0.6 # size 0.7 # gain 0.7 # legato 0.8 # delay 0.15 # delaytime 0.3 # delayfeedback 0.3` |
| `d6` | Wind Swell | `mask "<t!40 f!8>" $ whenmod 16 12 (# gain 0.5) $ s "wind" # gain 0.015 # room 0.7 # size 0.8 # speed 0.5` |
| `d7` | d7 | `mask "<f!8 t!32 f!8>" $ n "~ <e5 d5 c5 b4> ~ ~ <g5 a5 f5 e5> ~ <e5 g5 a5 c6> ~" # s "vibraphone_soft" # room 0.85 # size 0.9 # gain 1.0 # legato 1.1` |
| `d8` | Warm Pad | `mask "<f!16 t!24 f!8>" $ n "<[a3,c4,e4] [a3,c4,e4] [g3,b3,d4] [a3,c4,e4]>" # s "pad_2_warm_fluid" # legato 1.5 # lpf 1000 # room 0.9 # size 0.95 # gain 0.06` |
| `d9` | d9 | `mask "<f!24 t!24>" $ n "~ <c5 e5 g5 a4> <a4 g4 b4 e4> ~ <e5 d5 f5 g5> ~ [<c5 e5> <b4 g4>] ~" # s "salamander_grand" # room 0.8 # size 0.9 # gain 0.65 # legato 1.0` |
| `d10` | Cello Answer | `mask "<f!12 t!28 f!8>" $ n "e3 ~ ~ ~ g3 ~ ~ ~" # s "vsco_cellos_arco" # room 0.85 # size 0.95 # gain 0.9 # legato 1.4` |
| `d11` | Horn Breath | `mask "<f!20 t!20 f!8>" $ n "a3 ~ ~ ~ ~ ~ ~ ~" # s "french_horn_fluid" # room 0.9 # size 0.95 # gain 0.4 # legato 1.8` |
| `d12` | Voice Oohs (bar 29) | `mask "<f!16>" $ n "a4 ~ ~ ~ e5 ~ ~ ~" # s "voice_oohs_fluid" # room 0.9 # size 0.95 # gain 1.45 # legato 1.6 # lpf 450` |
| `d15` | Electronic FX | `stack [mask "<f!2 t!2 f!12>" $ n "~ a5 ~ ~ e6 ~ ~ ~" # s "ts_bell" # gain 1.2 # room 0.5 # size 0.8 # delay 0.5 # delaytime 0.592 # delayfeedback 0.55 # pan (range 0.15 0.85 $ slow 4 sine), mask "<f!8 t!2 f!6>" $ degradeBy 0.35 $ n "a4 e5 a5 e5 c5 a5 e5 g5" # s "ts_acid" # lpf (range 700 3000 $ slow 8 sine) # resonance 0.2 # gain 1.1 # room 0.5 # delay 0.35 # delaytime 0.592 # delayfeedback 0.4, mask "<f!12 t!4>" $ n "[a4,e5]*8" # s "ts_juno" # legato 0.6 # lpf (range 400 5000 $ slow 4 saw) # gain 0.95 # room 0.7 # size 0.85]` |
| `d16` | Voice Oohs (combined choir) | `stack [n "<a3 f3 g3 a3>" # s "voice_oohs_fluid" # legato 2.0 # room 0.9 # size 0.95 # gain 0.55 # lpf 1800 # pan 0.35, n "<e4 c4 d4 e4>" # s "voice_oohs_fluid" # legato 2.0 # room 0.9 # size 0.95 # gain 0.5 # lpf 2400 # pan 0.65, mask "<f!2 t!2 f!4>" $ n "<c5 a4 b4 e5>" # s "voice_oohs_fluid" # legato 1.8 # room 0.9 # size 0.95 # gain 0.9 # lpf 3500, mask "<f!4 t!2 f!2>" $ n "<[e4 c4] [c4 a3] [d4 b3] [c4 e4]>" # s "voice_oohs_fluid" # legato 1.6 # room 0.8 # size 0.9 # gain 0.75 # lpf 2800 # pan 0.25, mask "<f!6 t!2>" $ n "~ ~ <b4 g4 a4 b4> ~" # s "voice_oohs_fluid" # legato 2.0 # room 0.95 # size 0.98 # gain 1.0 # lpf 3500 # delay 0.4 # delaytime 0.592 # delayfeedback 0.45]` |

La partitura (melodía, acordes y bajo) está en `song.musicxml`: ábrela en MuseScore.

Abre `song.tidal` en tu editor de TidalCycles, o abre la canción desde Tidal Studio (Mis proyectos → GitHub).
