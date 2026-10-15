# Quantum Gourami Frequency Training

A small ear-training game. A soft sine tone plays somewhere between 50 Hz and 15 kHz; swim the celestial gourami to the height that matches it before the time bar runs out. Ten rounds, each faster than the last. Scoring is by how many octaves you miss by: within 1/12 octave is Perfect, within 1/3 octave is Close.

Controls: ↑ / ↓ (or W / S) to swim, drag or tap to steer, Space to lock in early. Use headphones at a low volume; the top end is piercing.

## Run it locally

It's a single self-contained `index.html` with no build step. Open it in a browser:

```sh
open index.html
```

or serve the folder:

```sh
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Publish on GitHub Pages

1. Create a GitHub repo and push this folder.
2. In the repo: Settings → Pages → Deploy from branch → `main`, folder `/ (root)`.

High scores are saved in each player's browser.

Made by Anish Ghosh, vibecoded with Claude CLI.
