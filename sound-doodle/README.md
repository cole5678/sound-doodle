# Sound Doodle

A single-file browser toy for drawing sound. Pick a color and draw on the canvas — each stroke becomes music.

- **Height** controls pitch (higher on screen = higher note)
- **Left/right position** controls stereo pan
- **Color** picks the instrument timbre (sine, triangle, sawtooth, or square wave)

Notes are drawn from a major pentatonic scale, so anything you doodle comes out sounding pleasant. Hit **Replay** to watch and hear your drawing played back in the order you drew it, or **Clear** to start over.

## Running it

No build step or dependencies — just open [`index.html`](index.html) in a browser.

```bash
open sound-doodle/index.html   # macOS
start sound-doodle/index.html  # Windows
```
