# ramayan-audio

Pre-rendered Hindi narration (Divya voice — AI4Bharat **Indic-Parler-TTS**) for
[jvoltci.github.io/ramayan](https://jvoltci.github.io/ramayan).

Served via **jsDelivr** (`https://cdn.jsdelivr.net/gh/jvoltci/ramayan-audio@main/`) so the audio
stays out of the main site repo. Layout: `<kanda>-<sarga>-<verse>.opus` + a per-sarga
`<kanda>-<sarga>.json` manifest (`{verses:[{v,file,dur}]}`). Opus ~24 kbps.

Audio CC-BY-NC 4.0. Text: Gītā Press, Gorakhpur.
