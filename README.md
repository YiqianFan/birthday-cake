# Birthday Cake - Night Sky Wish

An interactive birthday cake webpage with a dreamy night sky theme. Blow out the candles by dragging, and watch wishes float across the screen.

## Features

- **Drag-to-blow interaction** — hold and drag across the cake to extinguish candles (works on both touch and mouse)
- **Three-stage blow-out** — candles struggle, shrink, then emit canvas-drawn smoke wisps
- **Canvas particle system** — sparks, shooting stars, fireworks, confetti, and fireflies, all managed through an 800-particle object pool for smooth 60fps performance
- **Night sky atmosphere** — crescent moon, drifting clouds, aurora-like background gradients, and twinkling stars
- **Wish text** — after blowing out candles, blessing messages fade in and out at the bottom of the screen
- **Relight** — press the button to relight candles and blow again

## Quick Start

No build step required. Open `index.html` in any modern browser:

```
# clone the repo
git clone https://github.com/YiqianFan/birthday-cake.git
cd birthday-cake

# open in browser
open index.html
```

Or visit the live demo: https://yiqianfan.github.io/birthday-cake/

## Tech Stack

- Pure HTML + CSS + JavaScript (zero dependencies)
- Canvas 2D for particle rendering
- CSS animations for static decorative elements (stars, moon, clouds, candle flames)
- Object pool pattern for particle recycling (no DOM creation/destruction during animation)

## License

MIT
