# MOBTRACK

A mobile music tracker in the spirit of ProTracker / OctaMED, in one self-contained HTML file.
Built for Chrome on Android in landscape, and it also runs in desktop Chrome.

- 8 stereo tracks, patterns of 16–256 rows, ProTracker-style effects (0xy … Fxx)
- Sampler: load or record, waveform editor, loops with crossfade, slicing, filter, 2 LFOs, bit/rate crush
- Synths: BASS (acid, glide, accent), 4-op FM (8 algorithms), PAD (supersaw/wavetable + chorus), LEAD (PWM, sync)
- Mixer: per-track EQ, compressor, reverb and delay sends; master EQ, compressor, limiter
- Files: `.mtk` projects with samples included, WAV export (offline render), ProTracker `.MOD` import/export, autosave in the browser

Audio runs in an AudioWorklet driven by a lookahead scheduler.

## Install on Android

1. Open https://kcitak04.github.io/mobtrack/ in Chrome.
2. Tap **INSTALL APP** in the FILE tab, or Chrome menu ⋮ → **Install app**.
3. Launch **MOBTRACK** from the app drawer. It runs full screen and works offline.

The installed app updates itself the next time it starts online.

## Use

Tap **TAP TO START**, then **?** for the controls and the effect list.
The page also runs in desktop Chrome, and `tracker.html` opens straight from disk.

Songs, samples and autosaves stay on your device and are never uploaded anywhere.
