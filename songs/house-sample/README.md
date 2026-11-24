# house-sample

**70 BPM** · 7 pistas

| Pista | Nombre | Código |
|---|---|---|
| `d1` | Kick drum | `mask "<t f>" $ every 4 (fast 3) $ s "[bd ~ bd ~]*2" # room 0.55` |
| `d2` | Melody arpy | `slow 2 $ every 3 rev $ jux rev $ n "<[c5 e5 ~ g5 ~ a5 ~ ~] [e5 ~ d5 g5 ~ a5 ~ c5]>" # s "arpy" # room 0.9 # size 0.95 # legato 2 # gain 0.8 # delay 0.4 # delaytime 0.75 # delayfeedback 0.45 # room 1` |
| `d3` | Pad | `slow 4 $ n "<c'maj7 g'min>" # s "superpiano" # room 0.97 # size 0.99 # legato 5.0 # gain 0.45 # lpf 1000` |
| `d4` | Counter melody | `slow 3 $ n "<a4 ~ ~ e5 ~ ~ g4 ~>" # s "arpy" # room 0.85 # size 0.9 # legato 1.8 # gain 0.55 # delay 0.3 # delaytime 0.5 # delayfeedback 0.35 # pan 0.3` |
| `d5` | Claps on 2 and 4 | `s "~ cp ~ cp" # room 0.33` |
| `d6` | Air texture | `degradeBy 0.65 $ slow 3 $ s "wind ~ ~ ~ wind ~ ~ ~" # room 0.25 # size 0.99 # gain 0.9 # lpf 1200 # speed 0.6 # pan (slow 6 sine)` |
| `d7` | Space layer | `degradeBy 0.9 $ slow 4 $ s "space" # room 0.99 # size 0.99 # gain 0.3 # lpf 700 # speed 0.4` |

Abre `song.tidal` en tu editor de TidalCycles, o abre la canción desde Tidal Studio (Mis proyectos → GitHub).
