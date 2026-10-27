# Quantum Gourami Audio Game

A small ear-training game starring a celestial gourami. Pick what you want to train, then pick how you want to play.

**Sound**
- **Frequency:** a soft sine tone somewhere between 50 Hz and 15 kHz, laid out by octaves like an EQ.
- **Tempo:** a tiny 808-style drum machine (kick, snare, hat) synthesized in the browser, playing a random groove (rock, bachata, house, boom bap, dembow, trap, bossa, breakbeat) at a random 60–180 BPM. Half-time and double-time guesses count.

**Mode**
- **Training:** swim to the height that matches what you hear before the time bar runs out. Ten rounds, each faster.
- **Arcade:** two nebulas drift in, each labeled with a frequency or a tempo. Eat the one that matches. Dodge asteroids and black holes, grab star snacks, keep your three lives. The choices get closer and space gets faster as you level up.

**Character**
- **Gourami:** power move pulls stardust and stars in.
- **Angel:** power move glides behind asteroids.
- **Betta:** power move smashes through asteroids.

Hold the power move (Space, or ✦ on phones) in Arcade. It drains while held and recharges when you let go. Nothing survives a black hole.

Controls: ↑ / ↓ (or W / S) to swim, drag or tap to steer, Space to lock in early in Training or for the power move in Arcade. Works on phones. Use headphones at a low volume; the top end is piercing.

## Run it locally

A single self-contained `index.html`, no build step:

```sh
open index.html
# or
python3 -m http.server 8000   # then visit http://localhost:8000
```

High scores are shared across every device through a public [npoint.io](https://www.npoint.io) JSON bin, and also kept in each player's browser so the boards still work offline. The menu shows a total play count from [Abacus](https://abacus.jasoncameron.dev), a free counter service; if it's unreachable, the game works without it.

Made by Anish Ghosh, vibecoded with Claude Code.
