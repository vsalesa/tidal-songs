# Techno from scratch

**130 BPM** · 5 pistas

| Pista | Nombre | Código |
|---|---|---|
| `d1` | Kick | `mask "<t!8 f!4 t!4>" $ s "techno*4" # gain 1.05` |
| `d4` | Percussion | `s "rm(3,8,2)" # gain 0.75 # pan 0.7 # delay 0.3 # delaytime (60/130*0.75) # delayfeedback 0.4` |
| `d5` | Bass | `mask "<f!4 t!4 f!4 t!4>" $ struct "[~ t t t]*4" $ n "<a2!3 c3>" # s "superpwm" # lpf 400 # legato 0.7 # shape 0.3 # gain 0.95` |
| `d6` | Acid line | `mask "<f!8 t!8>" $ n "a3 a3 c4 a3 ~ a4 g3 a3 a3 ~ e4 a3 c4 ~ a3 g4" # s "sawtooth" # lpf (range 300 3000 $ slow 16 sine) # resonance 0.25 # legato 0.6 # gain 0.55` |
| `d7` | Pad | `mask "<f!6 t!10>" $ n "a'min9" # s "supersaw" # legato 1 # hpf 400 # lpf 2500 # room 0.6 # size 0.9 # gain 0.4` |

Abre `song.tidal` en tu editor de TidalCycles, o abre la canción desde Tidal Studio (Mis proyectos → GitHub).
