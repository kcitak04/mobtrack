# MOBTRACK

A mobile music tracker in the spirit of ProTracker / OctaMED, in one self-contained HTML file.
Built for Chrome on Android in landscape, and it also runs in desktop Chrome.

- 8 stereo tracks, patterns of 16–256 rows, ProTracker-style effects (0xy … Fxx)
- Sampler: load or record, waveform editor, loops with crossfade, slicing, filter, 2 LFOs, bit/rate crush
- Synths: BASS (acid, glide, accent), 4-op FM (8 algorithms), PAD (supersaw/wavetable + chorus), LEAD (PWM, sync)
- Mixer: per-track EQ, compressor, reverb and delay sends; master EQ, compressor, limiter
- Files: `.mtk` projects with samples included, WAV export (offline render), ProTracker `.MOD` import/export, autosave in the browser

Audio runs in an AudioWorklet driven by a lookahead scheduler.

## Use

Open the GitHub Pages URL in Chrome, rotate to landscape and tap **TAP TO START**. Tap **?** for the controls and the effect list.

Songs, samples and autosaves stay on your device and are never uploaded anywhere.
