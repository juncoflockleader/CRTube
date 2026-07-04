# NieR:Automata — 16-BIT
### A pixel-art short film. One HTML file. ~2 minutes.

> "Everything that lives is designed to end."

---

## Technical treatment

- **Canvas:** 384×216 internal buffer, integer-scaled with `image-rendering: pixelated`, CRT scanline overlay + subtle vignette.
- **Palette:** NieR's desaturated world — bone white, ash grey, faded tan, olive, near-black — with two violations: the **red** of the logic virus and the **gold** of dawn.
- **Music:** the user's own MIDI of "Weight of the World" (solo piano arrangement, 70 BPM, ~105s), loaded and parsed at runtime and rendered through chiptune voices — triangle for the low register, vibrato square lead above, dotted-eighth echo. The per-scene arrangement still applies: note dropouts and detune during the corruption, a lowpass veil in the rain, drums and octave-doubling only at the credits, and a quiet echoing fade at dawn. (If the .mid file is absent, an original fallback composition in the same spirit plays instead.)
- **Audio unlock:** browser autoplay rules require a gesture → the piece opens on a title screen: *PRESS START*.

---

## Scenes

### 0 · TITLE — *silence, then a single held note*
Black. Scanlines. A pale moon over the silhouette of a ruined skyline.
**NieR:Automata — 16-BIT** · *PRESS START*

### 1 · PROLOGUE — *sparse music-box arpeggio*
Black screen. Typewriter text, white on black:
> *Everything that lives is designed to end.*
> *We are perpetually trapped in a never-ending spiral of life and death.*
> *Is this a curse? Or some kind of punishment?*

### 2 · CITY RUINS — *melody enters, lonely*
Side-scrolling parallax: dust-tan sky, a white sun, broken towers swallowed by green, rubble in the foreground. **2B** walks right — white hair, black dress, katana on her back. **Pod 042** bobs faithfully behind her. Dust motes drift. Birds cross the sun.
Caption: `CITY RUINS — 11945 AD`

### 3 · TOGETHER — *melody warms, counter-voice joins*
2B and **9S** sit on a broken overpass ledge, watching the sun sink. Below, machine lifeforms — round-headed, lamp-eyed — wander harmlessly. One fishes.
> 9S: "2B... if we could stay like this forever..."
> 2B: "...Nines."
The sun dips. Hold on the two small figures.

### 4 · CORRUPTION — *music collapses: detuned, filtered, skipping*
Red. Screen tears, horizontal displacement glitches, the palette inverts in stutters. 2B kneels alone, red rings blooming off her body.
`▌LOGIC VIRUS DETECTED▐` flickers in broken type.
> 2B: "It always... ends like this."
White flash. Silence for one full bar.

### 5 · RAIN — *bass and rain only, then the melody returns in a lower octave*
Near-black scene. Rain in streaks. Lightning. **A2** stands with her long sword drawn; before her, 2B kneels — two silhouettes against the storm.
> 2B: "Become as gods..."
The lightning holds their outline. Fade to black.

### 6 · ENDING E — CREDITS — *full arrangement: the only swell. drums, pad, everything*
The credits are a bullet-hell. A tiny ship (the player) climbs a scrolling wall of staff credits, firing. The names fight back.
> POD 153: "Proposal: cease this pointless struggle."
> POD 042: "Query: do you wish for them to live?"
The ship dies. Restarts. Dies. Then —
`OFFERS OF HELP RECEIVED: yui.a2 · player_9S · Emil_Head · devola&popola ...`
A wedge of allied ships surrounds the player. The wall of names breaks.
> POD 042: "...Yes. Everything."

### 7 · DAWN — *arrangement dissolves back to the music box, one voice*
A grass field at first light — the only warm colors in the film. Three androids lie in the grass, eyes closed, hands at rest: 2B, 9S, A2. Two pods keep watch. Fireflies / petals drift.
> POD 042: "A future is not given to you. It is something you must take for yourself."
Hold. `— fin —` · *click to begin again*

---

## Emotional throughline

Loneliness → warmth → loss → violence → sacrifice → **choice** → rest.
The music makes the argument: the full band only ever plays while the credits are trying to kill you — because in this story, hope is something you shoot your way toward, with strangers' help. Then it's taken away again, gently, and what's left at dawn is one small voice. That's the weight, and the putting-down of the weight.
