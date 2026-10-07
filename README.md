# Music & Instrument Tools

Public hub for **[Music & Instrument Tools](https://heiguozhi.wang/en/)** — free music-theory and instrument utilities, plus serial-number year lookup for guitars and related gear.

Chinese brand name: **黑锅之王** · Operator: **[BlameMagnet](https://github.com/BlameMagnet)**

This repository holds multilingual site introductions and an [issue tracker](https://github.com/BlameMagnet/music-instrument-tools/issues) for feedback. **No application source code lives here.** The production site is maintained separately.

## Languages

| Language | Document |
| --- | --- |
| English (default) | [README.md](./README.md) |
| 简体中文 | [README.zh-Hans.md](./README.zh-Hans.md) |
| 繁體中文 | [README.zh-Hant.md](./README.zh-Hant.md) |

The live site is trilingual (`zh-Hans` at the site root, plus `en` and `zh-Hant`). Links below go to the English locale; the same path also exists at the site root (Simplified Chinese) and under `/zh-Hant/`.

Exception: `/about/support.html` (voluntary tip) is for Chinese locales only and shows a **Weixin (微信)** tip QR. `/en/about/support.html` redirects to `/en/about/site.html`.

## Tools

- [Tuner](https://heiguozhi.wang/en/tools/tuner.html) — Real-time mic tuner for many instruments.
- [Metronome](https://heiguozhi.wang/en/tools/metronome.html) — Metronome with voice cues for practice.
- [Circle of Fifths](https://heiguozhi.wang/en/tools/circle-of-fifths.html) — Visual circle of fifths for key signatures, relative keys, and progressions.
- [Tone Playground](https://heiguozhi.wang/en/tools/tone-playground.html) — Build guitar/bass chains with pedals, amps, cabs, and DI.
- [Chord Dictionary](https://heiguozhi.wang/en/tools/chord-dictionary.html) — Guitar/ukulele chord shapes with tones and audio.
- [Fretboard Visualizer](https://heiguozhi.wang/en/tools/fretboard.html) — Interactive fretboards with tunings, scale/chord templates, and audio.
- [Pitch & Frequency](https://heiguozhi.wang/en/tools/pitch-frequency.html) — C0–C10 note frequencies with adjustable A4 and playback.
- [Scale Explorer](https://heiguozhi.wang/en/tools/scale-explorer.html) — Explore 20+ scales with fretboard view and audio.
- [Chord Progression Builder](https://heiguozhi.wang/en/tools/progression-builder.html) — Build progressions from degrees and presets with BPM playback.
- [Drum Machine](https://heiguozhi.wang/en/tools/rhythm-patterns.html) — Style patterns with BPM control and visual playback.
- [Interval Ear Training](https://heiguozhi.wang/en/tools/ear-training.html) — Practice intervals with difficulty levels and play modes.
- [Wire Gauge Converter](https://heiguozhi.wang/en/tools/wire-gauge-converter.html) — Convert AWG, SWG, metric/imperial diameter and cross-section.

## Serial number decoders

Curated high-priority brands (site preset order). More brands are on the [home page](https://heiguozhi.wang/en/) or at `/en/sn-decoders/{brand}.html`.

- [Gibson](https://heiguozhi.wang/en/sn-decoders/gibson.html)
- [Fender](https://heiguozhi.wang/en/sn-decoders/fender.html)
- [Epiphone](https://heiguozhi.wang/en/sn-decoders/epiphone.html)
- [Squier](https://heiguozhi.wang/en/sn-decoders/squier.html)
- [Ibanez](https://heiguozhi.wang/en/sn-decoders/ibanez.html)
- [PRS](https://heiguozhi.wang/en/sn-decoders/prs.html)
- [Martin](https://heiguozhi.wang/en/sn-decoders/martin.html)
- [Taylor](https://heiguozhi.wang/en/sn-decoders/taylor.html)
- [ESP / LTD](https://heiguozhi.wang/en/sn-decoders/esp-ltd.html)
- [Edwards / GrassRoots](https://heiguozhi.wang/en/sn-decoders/edwards-grassroots.html)

## About & support

- [About the site](https://heiguozhi.wang/en/about/site.html)
- [Support](https://heiguozhi.wang/about/support.html) — Chinese locales only; Weixin / 微信 tip QR
- [Author](https://heiguozhi.wang/en/about/author.html)
- [Sitemap](https://heiguozhi.wang/sitemap.xml) — full indexable URL list
- [llms.txt](https://heiguozhi.wang/llms.txt) — curated overview for AI crawlers

## Feedback

Please use [GitHub Issues](https://github.com/BlameMagnet/music-instrument-tools/issues) for bug reports and suggestions (wrong decode results, broken pages, feature ideas, copy fixes).

When filing an issue, include:

1. The page URL (and language path if not Simplified Chinese)
2. What you expected vs what happened
3. Browser / device if it looks like a client bug

## Notes

- Pages are statically prerendered HTML.
- Do not crawl media, NAM models, or WASM under `/7d/tone-playground/` (see the site `/robots.txt`).
- Serial lookups are educational year/plant references, not authenticity certificates.
- Tone Playground is an educational simulation, not an official product from any gear brand.
