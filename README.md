# // JUKO ENGINE //

A neon-glitch dialogue **GIF generator** in a single HTML page.

Type some text and it renders as glitchy, zalgo-corrupted neon — then export it as an animated GIF.

## Features

- **Classic green glitch** by default (leet swaps, glitch characters, zalgo, neon glow, white flicker).
- **Per-part or whole-dialogue styling** via a tiny markup system — style a selection or the entire text:
  - Solid **color** (any hex).
  - Animated **rainbow**.
  - 12 tweakable **text animations**: wave, bounce, shake, jitter, wobble, pulse, float, spin, drift, quake, swing.
  - **Steady** regions that opt out of the glitch.
- Tags are insertable from the toolbar or by hand: `[c=#ff0000]…[/c]`, `[rb]…[/rb]`, `[a=wave]…[/a]`, `[stable]…[/stable]` (they nest).
- Tweak sliders: glitch intensity, zalgo, animation speed/amount, rainbow speed/spread, glow, frame count.
- **GIF preview**, download, and best-effort copy-to-clipboard.

## Usage

Just open `index.html` in a browser. No build step, no server.

## Built with

- [gifshot](https://github.com/yahoo/gifshot) for GIF encoding (bundled).
