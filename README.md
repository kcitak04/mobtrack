# DATTRACK

A mobile music tracker in the spirit of the classic Amiga trackers, in one self-contained HTML file.
Built for Chrome on Android in landscape, and it also runs in desktop Chrome.

- 8 stereo tracks (SYNTH or SAMPLE kit tracks), patterns of 16–256 rows, tracker-style effects (0xy … Fxx), 4 automation lanes, note length and swing per row
- Sampler: load or record, waveform editor, loops with crossfade, slicing, warp (BEATS / MMC / RE-PITCH), 2 LFOs, bit/rate crush
- Synths: BASS (acid, glide, accent), 4-op FM (8 algorithms), PAD (supersaw/wavetable + chorus), LEAD (PWM, sync)
- Mixer: per-track EQ, compressor, insert effect, reverb and delay sends; master fader, 2 master inserts, EQ, compressor, limiter
- Sample Lab: 31 offline processes (spectral, waveset, granular, texture, formant, spatial)
- Files: `.mtk` projects with samples included; export to WAV, AIFF, FLAC or Ogg Opus (16/24/32-bit, 44.1–96 kHz, stems); `.MOD` import/export; autosave in the browser

Audio runs in an AudioWorklet driven by a lookahead scheduler.

## Install on Android

- **APK:** download `DATTRACK.apk` from the [latest release](https://github.com/kcitak04/mobtrack/releases/latest) and open it.
- **Web app:** open https://kcitak04.github.io/mobtrack/ in Chrome, then **INSTALL APP** in the PREF tab or Chrome menu ⋮ → **Install app**.

Both run full screen and work offline.

## Use

Tap **TAP TO START**, then **?** for the controls and the effect list.
`tracker.html` also opens straight from disk in desktop Chrome.

Songs, samples and autosaves stay on your device and are never uploaded anywhere.

## Licenses

All app code is original. The Android app includes AndroidX WebKit and AndroidX Core (The Android Open Source Project / Google LLC) under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).
