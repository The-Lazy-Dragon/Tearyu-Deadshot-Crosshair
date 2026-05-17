<div align="center">

```
 _____                       
|_   _|                      
  | | ___  __ _ _ __ _   _ū  
  | |/ _ \/ _` | '__| | | |  
  | |  __/ (_| | |  | |_| |  
  \_/\___|\__,_|_|   \__, |  
                      __/ |  
                     |___/   
```

# 怠竜 Tearyū's Deadshot Crosshair

**A crosshair extension for deadshot.io. No Tampermonkey. No BS.**

[![Made by The Lazy Dragon](https://img.shields.io/badge/Made%20by-The%20Lazy%20Dragon%20怠竜-ff153f?style=flat-square)](https://github.com/The-Lazy-Dragon)
[![Chrome Extension](https://img.shields.io/badge/Type-Chrome%20Extension-00fff7?style=flat-square)](#)
[![No Framework](https://img.shields.io/badge/Framework-None%20Needed-3a486a?style=flat-square)](#)
[![Crosshair Shapes](https://img.shields.io/badge/Shapes-15+-712637?style=flat-square)](#-crosshair-shapes)
[![Custom Images](https://img.shields.io/badge/Custom%20Images-Supported-00fff7?style=flat-square)](#-custom-images)
[![Version](https://img.shields.io/badge/Version-2.0-ff153f?style=flat-square)](#)

*"just use the default crosshair bro" — someone with terrible aim*

---

</div>

## ⚡ What is this?

A crosshair extension to be added thru your Chrome Extensions for deadshot.io, that you can customise as per your needs, so u don't fucking need Tampermonkey. Custom Images ARE NOW SUPPORTED. More features may come, if I feel like it.

So yeah. Just a crosshair.

---

## 🚀 How to Install

> Takes like 30 seconds.

**1.** Hit the green **`Code`** button on this page → **`Download ZIP`** → extract it

**2.** Open Chrome and head to:
```
Extensions → Manage Extensions
```
*(or just slam `chrome://extensions` into the address bar)*

**3.** Flip on **Developer Mode** — toggle in the top right corner

**4.** Hit **Load unpacked** → select the `deadshot-extension` folder you just extracted

**5.** Go to [deadshot.io](https://deadshot.io) — your crosshair is already there

> If you update the files later, just hit the 🔄 refresh icon on the extension card and reload the game tab.

---

## 🎮 Controls

Seven panels on the right side of your screen. Click the buttons or use the keys:

| Key | Panel | What it does |
|-----|-------|-------------|
| `\` | ✛ Style | Crosshair type, master on/off, psychedelic mode |
| `O` | 🎨 Colors | Main color, outline color, opacity |
| `.` | ⚙ Details | Outline, center dot, dot size, circle radius |
| `I` | ┼ Arms | Toggle individual arms on/off |
| `/` | ⇔ Dims | Length, thickness, gap |
| `P` | 🖼 Images | All 4 custom image modes |
| `` ` `` | 📊 HUD | FPS, ping, key tracker, overlay color, preview toggle |
| `U` | — | Hide / Show the entire sidebar |

Panels are **draggable** — grab anywhere that isn't a control and move it wherever.  
The **preview box** is also draggable — pick it up and put it wherever it doesn't bother you.  
Settings **auto-save** to your browser. They survive page reloads.

---

## ✨ Crosshair Shapes

15+ vector shapes across 5 categories. Mix with custom images however you want.

| Category | Styles |
|----------|--------|
| **Cross** | Cross (no dot) · Cross + Dot |
| **Circle** | Circle · Circle + Cross · Circle + Cross + Dot |
| **Dot** | Dot only |
| **Diamond** | Diamond · Diamond + Dot · Diamond + Cross |
| **Square** | Square · Square + Dot · Square + Cross ⊕ · Square + Cross + Dot · Square + X (diagonal) · Square + X + Dot |

---

## 🖼 Custom Images

Upload PNG, JPG, or SVG. Transparent backgrounds are preserved and render clean. All 4 modes work **simultaneously** — stack them however you want.

### Mode 1 — Full Crosshair Image
Replaces the entire vector crosshair with your image. Drop in any crosshair PNG and it just works. Size and opacity sliders. Optional spin with speed control.

### Mode 2 — Custom Dot
Replaces or adds to the center dot. Any image. Optional spin.

### Mode 3 — Custom Arms
Tiles an image along each arm instead of drawing a line. Tile size and spacing adjustable. Respects which arms are enabled in the Arms panel.

### Mode 4 — Orbit Border
Stamps a repeating image around the center in a **circle, oval, or square** pattern. Think eggs spinning in a circle. Or skulls. Or whatever you upload.
- **Count** — how many icons
- **Radius** — how far from the center
- **Orbit** — rotate the whole formation around the center
- **Self spin** — each icon spins on its own axis independently

Images are stored as base64 in your browser. They persist between sessions without needing to re-upload.

---

## 🍄 Psychedelic Mode

Found in the **Style** panel. The crosshair, outline, and all HUD overlays start smoothly cycling through the entire color spectrum in real time. Like you're on shrooms but you can still headshot people. Runs on the GPU via CSS hue-rotate — no JS canvas repaints. Speed is adjustable. Potato PC approved.

---

## 📊 HUD Overlays

All sit top-left. Toggle each one independently from the HUD panel.

- **Live FPS** — updates every second
- **Live Ping** — estimated, refreshes every 2s
- **Key Tracker** — WASD · LMB · RMB · Shift · Space · R · F
- **Overlay Color** — recolor all of the above to any color you want
- **Preview Box** — always-visible crosshair preview, toggleable and draggable

---

## 📂 What's in the ZIP

```
deadshot-extension/
├── manifest.json     — Chrome extension config
├── crosshair.js      — All the code, one file
├── icon16.png
├── icon48.png
└── icon128.png
```

---

## 📋 Changelog

### v2.0 — The Image Update
- 🖼 **Mode 1** — Full PNG/JPG/SVG crosshair. Replaces vector entirely. Transparent backgrounds preserved.
- 🎯 **Mode 2** — Custom dot image. Optional spin.
- 💫 **Mode 3** — Custom arm tiles. Tiled along each arm instead of a line.
- 🌀 **Mode 4** — Orbit border. Repeating images in a circle, oval, or square. Can orbit, stay still, or spin on their own axis. (eggs spinning in a circle. u know what it is.)
- All 4 modes work simultaneously on top of each other and on top of the vector crosshair
- Single shared canvas — no layer stacking, potato-safe
- rAF animation loop only runs when something is actually animating. Static = zero CPU.
- Images stored as base64 in localStorage — persist between sessions
- New **Images** panel (`P` key)

### v1.1.2
- 🎨 Rewrote psychedelic mode — now runs on the GPU via CSS `hue-rotate` animation
- Zero JS canvas repaints while psychedelic is active
- Speed slider updates animation duration in real time
- Tested on a potato PC. Runs fine. v1.1.1 could not say the same.

### v1.1.1
- 🐛 Fixed psychedelic mode tanking game performance — throttled from 60fps to 20fps
- Preview box no longer animates when you're not looking at it
- Overlay color updates via CSS variable instead of hammering the DOM
- *The one I'm not proud of*

### v1.1
- 🍄 Added **Psychedelic Mode** — full spectrum color cycling on crosshair + HUD
- 🎨 Added **Overlay Color** picker — recolor FPS, ping, and key tracker
- 👁 Added **Preview toggle** — hide the preview box from HUD panel
- 🖱 Made the **preview box draggable**

### v1.0
- Initial release — crosshair engine, 15+ shapes, sidebar UI, HUD overlays, key tracker

---

## ⚠ Known Stuff

- Chrome only. No Firefox support, don't ask.
- Works on `deadshot.io` and `www.deadshot.io` only.
- Large image files will bloat your localStorage. Keep uploads reasonable.

---

## 🐉 About the Dev

**The Lazy Dragon** · `怠竜 Tearyū`

BSc IT student who builds things way more complex than they need to be and calls it a crosshair.

- GitHub: [@The-Lazy-Dragon](https://github.com/The-Lazy-Dragon)
- Discord: `this.isnt.craig_`
- Reddit: `u/Red_DevilAS07`

### Also check out:
**[NavalStrike](https://github.com/The-Lazy-Dragon/NavalStrike)** — Battleship. But neon. But with 25 ship classes, 35 achievements, a Konami code, procedural audio, and hard AI that actually hurts. One `.html` file.

**[Lazy Dragon's TicTacToe](https://github.com/The-Lazy-Dragon/lazy-dragons-tictactoe)** — It's TicTacToe. But neon. But with achievements, a dev console, and an unbeatable minimax AI. Also one `.html` file.

---

<div align="center">

**⭐ Star the repo if your aim improved**

*Built with zero frameworks and questionable life choices — actually built this because deadshot.io's default crosshair was pissing me off*

</div>
