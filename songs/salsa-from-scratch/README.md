# Salsa from scratch

**180 BPM** · 8 pistas

| Pista | Nombre | Código |
|---|---|---|
| `d1` | 2-3 clave | `s "<[~ claves:1 claves:1 ~] [claves:1 ~ ~ claves:1 ~ ~ claves:1 ~]>" # gain 1` |
| `d2` | Congas (tumbao) | `mask "<f!4 t!12>" $ s "congas:0 congas:1 congas:12 congas:1 congas:0 congas:1 congas:6 congas:22" # gain "0.75 0.65 1 0.65 0.75 0.65 1 1" # pan 0.4` |
| `d3` | Bongo (martillo) | `mask "<f!4 t!4 f!8>" $ s "bongos:0 bongos:6 bongos:2 bongos:6 bongos:0 bongos:6 bongos:16 bongos:7" {- # gain "0.95 0.75 0.9 0.75 0.95 0.75 1 0.75" -} # pan 0.6` |
| `d4` | Upright bass (tumbao) | `mask "<f!4 t!12>" $ n "<[~ ~ ~ e3 ~ ~ d3 ~] [~ ~ ~ a2 ~ ~ e3 ~] [~ ~ ~ b2 ~ ~ d3 ~] [~ ~ ~ a2 ~ ~ a2 ~]>" # s "acoustic_bass_fluid" # legato 3 # gain 0.95` |
| `d5` | Piano (guajeo) | `superimpose (\|- n 12) $ n "<[~ c6 a5 ~ e6 c6 ~ f6] [~ d6 a5 ~ f6 d6 ~ e6] [~ b5 gs5 ~ d6 b5 ~ f6] [~ d6 a5 ~ f6 d6 ~ e6]>" # s "bright_acoustic_piano_fluid" # legato 0.9 # gain 0.6 # room 0.89 # lpf 4000` |
| `d6` | Bongo bell | `mask "<f!8 t!8>" $ s "[cowbells:11 cowbells:9]*4" # gain "[1 0.7]*4" # pan 0.6` |
| `d7` | Trombones (moña) | `mask "<t!4 f!8 t!4>" $ n "<[[c4,e4] ~ [c4,e4] ~ [b3,d4] [c4,e4] ~ ~] ~ [[d4,gs4] ~ [d4,gs4] ~ [d4,f4] [b3,e4] ~ ~] ~>" # s "trombone_fluid" # legato 0.7 # gain 0.9 # room 0.2 # pan 0.45` |
| `d8` | Coro | `mask "<f!8 t!4 f!2 t!2>" $ n "<~ [~ ~ [d5,f5] [d5,f5] ~ [c5,e5] ~ ~]>" # s "choir_aahs_fluid" # legato 0.9 # gain 0.9 # room 0.3` |

Abre `song.tidal` en tu editor de TidalCycles, o abre la canción desde Tidal Studio (Mis proyectos → GitHub).
