# flamenco

**98 BPM** · 9 pistas

| Pista | Nombre | Código |
|---|---|---|
| `d1` | Claves | `n "[0 ~] [0 0]" # s "claves" # gain 0.8` |
| `d2` | Nylon Guitar | `note "<[a3,c4,e4] [g3,b3,d4] [f3,a3,c4] [e3,gs3,b3,d4]>" # s "acoustic_guitar_nylon_fluid" # legato 0.85 # gain 0.95` |
| `d3` | Bass | `note "<a2 g2 f2 e2>" # s "acoustic_bass_fluid" # legato 0.8 # gain 1.0` |
| `d4` | Melody random | `every 4 (fast 1.4 . (# gain 1.05)) $ every 7 (slow 1.5 . (# gain 0.75)) $ slow 5 $ randcat [note "[e5 d5 c5 b4 a4 ~ b4 c5 d5 e5 fs5 e5 d5 c5 b4 a4 gs4 a4 b4 c5 d5 e5 ~]" # s "acoustic_guitar_nylon_fluid" # legato 0.65 # gain 0.9 # room 0.2, note "[a5 g5 f5 e5 d5 c5 b4 a4 ~ b4 c5 d5 e5 d5 c5 b4 ~ a4 gs4 a4 b4 c5 ~]" # s "acoustic_guitar_nylon_fluid" # legato 0.62 # gain 0.9 # room 0.2, note "[a4 b4 c5 d5 e5 d5 c5 b4 a4 ~ gs4 a4 b4 c5 d5 e5 fs5 g5 a5 g5 f5 e5 d5 ~]" # s "acoustic_guitar_nylon_fluid" # legato 0.65 # gain 0.88 # room 0.2, note "[e5 d5 c5 b4 ~ a4 ~ gs4 a4 b4 c5 ~ d5 e5 d5 c5 b4 ~ a4 gs4 a4 b4 ~]" # s "acoustic_guitar_nylon_fluid" # legato 0.68 # gain 0.9 # room 0.2, note "[[a5 g5 f5] e5 d5 ~ c5 b4 a4 ~ gs4 a4 b4 c5 d5 ~ e5 fs5 e5 ~ d5 c5 b4 ~]" # s "acoustic_guitar_nylon_fluid" # legato 0.65 # gain 0.88 # room 0.2]` |
| `d5` | Shaker | `n "0*8" # s "claps_vcsl"` |
| `d6` | Harmonics | `n "<a5 e5>" # s "guitar_harmonics_fluid" # gain 0.3 # room 0.5 # size 0.7` |
| `d7` | Palmas vivas | `sometimesBy 0.35 (slow 1.5) $ degradeBy 0.12 $ n "<[0 0 ~ 0 0 0 0 ~ 0 0 ~ [0 0 0 0 0 0 0 0]] [0 ~ 0 ~ 0 ~ 0 ~] [0 0 ~ 0 0 0 0 ~ 0 0 ~ [0 0 0 0 0 0 0 0]] [0 0 0 0 0 0 ~ 0 0 0 0 0 0 0 0 ~]>" # s "cajon" # speed 0.78 # gain (range 0.6 1.0 rand) # room (range 0.12 0.3 rand)` |
| `d8` | Cajón | `sometimesBy 0.25 (slow 1.5) $ n "<[0 ~ 1 ~] [0 ~ 2 ~] [0 2 1 2] [0 2 ~ 1 2 ~ 1 ~ 1 ~ 1 ~]>" # s "cajon" # speed 0.75 # gain (range 0.65 1.0 rand) # room (range 0.15 0.25 rand)` |
| `d9` | Counter always | `note "<[~ a4 ~ c5 ~ e5 ~@2] [~ g4 ~ b4 ~ d5 ~@2] [~ f4 ~ a4 ~ c5 ~@2] [~ e4 ~ gs4 ~ b4 ~@2]>" # s "acoustic_guitar_nylon_musyng" # legato 0.8 # gain 0.5 # room 0.3 # pan 0.4` |

La partitura (melodía, acordes y bajo) está en `song.musicxml`: ábrela en MuseScore.

Abre `song.tidal` en tu editor de TidalCycles, o abre la canción desde Tidal Studio (Mis proyectos → GitHub).
