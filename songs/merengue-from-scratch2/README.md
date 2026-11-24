# Merengue from scratch

**140 BPM** · 6 pistas

| Pista | Nombre | Código |
|---|---|---|
| `d2` | Tambora | `s "[woodblock_vcsl:6 ~ woodblock_vcsl:6 woodblock_vcsl:7] [congas:22 ~ woodblock_vcsl:6 ~] [woodblock_vcsl:6 ~ woodblock_vcsl:6 woodblock_vcsl:7] [congas:22 congas:6 ~ congas:22]" # gain 0.9 # room 0.15` |
| `d3` | Kick | `s "bd*4" # gain "[0.9 0.7]*2" # lpf 2500` |
| `d4` | Electric bass | `n "<[c3 ~ ~ g3 ~ ~ c3 e3] [f3 ~ ~ c3 ~ ~ f3 a3] [g3 ~ ~ d3 ~ ~ g3 b3] [c3 ~ ~ g3 ~ d3 ~ e3]>" # s "electric_bass_finger_fluid" # legato 0.8 # gain 0.9 # lpf 850` |
| `d5` | Piano | `struct "<[~ t]*4 [t ~ t ~] [~ ~ t t] [t t ~ t]>" $ n "<[g4,c5,e5] [a4,c5,f5] [g4,b4,d5,f5] [g4,c5,e5]>" # s "bright_acoustic_piano_fluid" # legato 0.4 # gain 0.85 # room 0.3` |
| `d6` | Trumpets | `n "<[c5 ~ e5 g5 ~ a5 g5 ~] ~ [f4 ~ a4 c5 ~ b4 ~] ~>" # s "trumpet_fluid" # legato 0.85 # gain 0.9 # room 0.25` |
| `d7` | Alto sax | `n "<~ [d5 ~ c5 a4 ~ g4 f4] ~ [f4 a4 c5 ~ d5 ~ c5 ~]>" # s "alto_sax_fluid" # legato 0.8 # gain 0.85 # room 0.25 # pan 0.35` |

Abre `song.tidal` en tu editor de TidalCycles, o abre la canción desde Tidal Studio (Mis proyectos → GitHub).
