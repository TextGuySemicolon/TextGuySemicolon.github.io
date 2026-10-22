# Audio credits: ambank

All sounds and music in this folder are licensed from **Artlist** and were edited (trimmed, faded,
mono 44.1 kHz 128 kbps mp3, loudness ladder per `playbook/SFX-DIRECTION.md`). Raw downloads are not stored in this repo.

SFX v2 (2026-10-20): every slot plays at relative gain 1.0 (`audio.volume.sfx`); the loudness ladder is baked into
the files. Playback rules live in the theme JSON `audio.mix`. Drop-offs (miss) are silent by design.
Music plays at `audio.volume.music` (0.32) and dips 5 dB under GO / TIME'S UP / win.

## SFX v2

| File | Slot | Artlist title | Creator | Pack | Artlist URL |
|---|---|---|---|---|---|
| `click.mp3` | `sfx.click` | General Button | SoundCrib | Bright UI Vol 2 | https://artlist.io/sfx/pack/bright-ui-vol-2/8932 |
| `countdown-tick.mp3` | `sfx.countdownTick` | Xylophone Single Clean Note | Alan Dalcastagne | Soothing Instruments | TODO: Artlist sound/pack URL (Soothing Instruments) |
| `go.mp3` | `sfx.go` | Chimes Achievement 01 | SoundCrib | Bright UI Vol 2 | https://artlist.io/sfx/pack/bright-ui-vol-2/8932 |
| `catch-30.mp3` | `sfx.catchItem (+30)` | Positive Pick 01 | SoundCrib | Bright UI Vol 2 | https://artlist.io/sfx/pack/bright-ui-vol-2/8932 |
| `catch-50.mp3` | `sfx.catchCoin (+50)` | Positive Pick 02 | SoundCrib | Bright UI Vol 2 | https://artlist.io/sfx/pack/bright-ui-vol-2/8932 |
| `catch-coin.mp3` | `sfx.catchCoin (+50, AmBank logo coin)` — client "ka-ching" (R1 #8); replaces catch-50 | Game Coin Collector - Coin Pick Up | SoundCrib | https://artlist.io/sfx/track/game-coin-collector---coin-pick-up/135796 (first 400 ms, 120 ms fade, HPF 120 / LPF 9k, -21.4 dB loudest-400ms, already C7 2093 Hz so no pitch shift) |
| `catch-bad.mp3` | `sfx.catchBad` | Negative Button Click | SoundCrib | Bright UI Vol 2 | https://artlist.io/sfx/pack/bright-ui-vol-2/8932 |
| `timer-tick.mp3` | `sfx.timerTick` | Select Click 03 | SoundCrib | Bright UI Vol 2 | https://artlist.io/sfx/pack/bright-ui-vol-2/8932 |
| `times-up.mp3` | `sfx.timesUp` | Task Completed Positive | SoundCrib | Bright UI Vol 2 | https://artlist.io/sfx/pack/bright-ui-vol-2/8932 |
| `score-tick.mp3` | `sfx.scoreTick` | Select Confirmation | SoundCrib | Bright UI Vol 2 | https://artlist.io/sfx/pack/bright-ui-vol-2/8932 |
| `win.mp3` | `sfx.win` | Chimes Achievement 02 | SoundCrib | Bright UI Vol 2 | https://artlist.io/sfx/pack/bright-ui-vol-2/8932 |
| `qr-done.mp3` | `(spare, no slot yet)` | General Button 03 | SoundCrib | Bright UI Vol 2 | https://artlist.io/sfx/pack/bright-ui-vol-2/8932 |

## Music

| File | Slot | Artlist title | Creator | Edit | Licence |
|---|---|---|---|---|---|
| `music-menu.mp3` | `music.menu` | My Bebe - Instrumental version | Captain Joz | 24-bar loop from 34.47 s (47.93 s, ~120.2 BPM), 1 s crossfade, ~-16 LUFS | Licensed via Artlist |
| `music-game.mp3` | `music.game` | Pretty Pretty - Instrumental version | Ariel Shalom | 24-bar loop from 52.94 s (45.7 s, ~126.0 BPM), 1 s crossfade, ~-16 LUFS | Licensed via Artlist |
