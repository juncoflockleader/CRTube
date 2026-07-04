# CRTube

A tiny fake video site hosting pixel-art tribute films, rendered live on a
384×216 canvas with chiptune covers sequenced through the Web Audio API.

**Watch:** https://juncoflockleader.github.io/CRTube/

## The films

- **NieR:Automata — 16-BIT** ([watch.html](watch.html), script in [SCRIPT.md](SCRIPT.md))
  Seven scenes from 2B's story, ending in a bullet-hell credits sequence and a dawn.
- **Final Fantasy X — 16-BIT** ([watch-ffx.html](watch-ffx.html), script in [SCRIPT-FFX.md](SCRIPT-FFX.md))
  Zanarkand, the pilgrimage, the Sending, and a farewell in pyreflies.
- **NieR Replicant — 16-BIT · Kainé** ([watch-kaine.html](watch-kaine.html), script in [SCRIPT-KAINE.md](SCRIPT-KAINE.md))
  The Aerie, the giant Shade, five years of stone, and an escape at full sprint.
- **Persona 4 — 16-BIT · Yukiko** ([watch-p4.html](watch-p4.html), script in [SCRIPT-P4.md](SCRIPT-P4.md))
  The Midnight Channel, Inaba in the fog, a laughing fit by the river, and a spring train.

## How it works

Everything is pure front-end — three self-contained HTML files, no build step,
no dependencies, no server. Each film embeds a MIDI rendition (base64), parses
it at runtime with a ~100-line MIDI parser, and plays it through hand-rolled
chiptune voices: triangle bass, vibrato square lead, echo delay. Scene-aware
arrangement effects (lowpass veils, note dropouts, octave shimmer) react to
the story. All visuals are procedural canvas pixels; the CRT look is CSS.

Flashing/strobe effects are deliberately avoided throughout for
photosensitivity safety.

## Running locally

Open `index.html` in a browser. That's it — `file://` works.

## Credits & disclaimer

An unofficial, non-commercial fan tribute. NieR:Automata, NieR Replicant, and
Final Fantasy X, their characters, and their music belong to Square Enix;
Persona 4 and its music belong to Atlus/SEGA. Original compositions by
Keiichi Okabe ("Weight of the World", "Kainé / Escape"), Nobuo Uematsu
("To Zanarkand"), and Shoji Meguro (Persona 4). Staff names shown in the
credits sequence are factual credits of the original games. If you own these
rights and want something taken down, open an issue.
