# 🌈 SPECTRUM

**Bring color back to a world of gray.**

A calm, luminous browser game built for the **June Solstice Game Jam 2026** with a Pride-forward theme and a Juneteenth spirit of freedom, color, remembrance, and joy.

You play a tiny mote of light moving through a sleeping gray world. Everywhere you glide, color wakes up. Dormant buds bloom. The air brightens. The meter fills. When enough color returns, the whole world opens into a rainbow finale. 🏳️‍🌈✨🌞

## 🎮 Play

Play it here:

👉 **https://dacameragirl.github.io/Spectrum/**

Or open `index.html` in any modern browser. No install, no build, no dependencies.

## 🕹️ Controls

- 🖱️ **Mouse / touch:** the light glides toward your pointer.
- ⌨️ **WASD / arrow keys:** move by keyboard.
- 🌱 **Bloom buds:** glide over the breathing gray buds.
- 🌈 **Fill the color meter:** reach **100% colored** to trigger the finale.
- 🎵 **♪ / M:** toggle sound.

## ✨ Theme

SPECTRUM is about color returning where it was muted.

- 🌈 **Pride:** visibility, softness, glow, self-expression, and chosen color.
- 🖤❤️💚💛 **Juneteenth:** liberation, memory, resilience, and the joy of becoming free.
- 🌞 **June Solstice:** light at its longest, warmth spreading, a world waking up.
- 🌸 **Blooming:** small acts of movement creating permanent change.

The game is gentle on purpose: no combat, no score pressure, no punishment. Just movement, color, sound, and a world becoming brighter because you touched it.

## 🌺 What Happens In Game

1. 🩶 The world starts gray and quiet.
2. ✨ Your light leaves glowing rainbow trails.
3. 🌱 Gray buds pulse and wait.
4. 🌼 Touching a bud makes it bloom.
5. 🎶 Each bloom plays a note.
6. 🌈 The color meter climbs.
7. 🎆 At 100%, the world erupts into a rainbow finale.

## 🧠 How It Works

- 🎨 A hidden `paint` canvas stores every stroke, so color stays permanent while the world redraws each frame.
- 💡 Strokes use additive blending with `globalCompositeOperation = 'lighter'`, so color reads as light instead of ink.
- 📊 Coverage is measured by shrinking the paint layer to a tiny thumbnail and counting lit pixels.
- 🎵 A small Web Audio score plays pentatonic notes on each bloom, rising as the finale gets closer.
- 🧩 Everything lives in one self-contained `index.html` file.

## 🛠️ Tech

- Vanilla JavaScript
- HTML5 Canvas
- Web Audio
- No dependencies
- No build step
- GitHub Pages deployment

## 📁 Files

- `index.html`: the whole game.
- `README.md`: this page.
- `LICENSE`: All Rights Reserved license.

## 🔒 License

Copyright (c) 2026 Angela Hudson. All Rights Reserved.

Viewing this public repository does **not** grant permission to use, copy, modify, publish, distribute, sell, sublicense, or create derivative works from this software without prior written permission.

See [LICENSE](LICENSE) for the full terms.

---

Made by **Angela Hudson** · June Solstice Game Jam 2026 · Pride + Juneteenth color bloom edition 🌈🌞🌺
