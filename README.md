# SPECTRUM

**Bring color back to a world of gray.**

A calm, luminous browser game built for the **June Solstice Game Jam 2026** (Pride theme).
You play a mote of light. Everywhere you move, you paint glowing rainbow color onto a
gray world. Glide over the dormant buds to make them bloom, fill the color meter, and the
whole world erupts into a rainbow finale. 🏳️‍🌈

## Play
Open `index.html` in any modern browser. No install, no build, no dependencies.

- **Move:** mouse / touch (the light glides toward your pointer), or **WASD / arrow keys**
- **Bloom** the breathing gray buds by gliding over them
- Fill the meter to **100% colored** to trigger the finale
- **♪ / M** toggles sound

## How it works
- A hidden "paint" canvas accumulates every stroke, so your color is permanent while the
  world redraws each frame.
- Strokes use additive blending (`globalCompositeOperation = 'lighter'`) so color reads as
  *light*, not ink.
- Coverage is measured by downscaling the paint layer to a tiny thumbnail and counting lit
  pixels — cheap enough to run continuously.
- A small Web Audio score plays a pentatonic note on each bloom, rising in pitch as you
  near the finale.

## Tech
Single self-contained `index.html` — vanilla JavaScript + HTML5 Canvas + Web Audio.

---
Made by Angela Hudson · June Solstice Game Jam 2026
