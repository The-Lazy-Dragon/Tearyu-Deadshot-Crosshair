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
[![Shapes](https://img.shields.io/badge/Shapes-15+-712637?style=flat-square)](#-crosshair-shapes)
[![Custom Images](https://img.shields.io/badge/Custom%20Images-Supported-00fff7?style=flat-square)](#-custom-images)
[![Version](https://img.shields.io/badge/Version-2.1-ff153f?style=flat-square)](#)

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

## 📱 Mobile

### Android
Kiwi Browser supports Chrome extensions natively. Same ZIP, same install steps, works out of the box.

> **[Download Kiwi Browser](https://kiwibrowser.com)** → install it → follow the same install steps above inside Kiwi.

### iOS
Every browser on iOS is forced to use Apple's WebKit engine under the hood — Chrome on iOS is literally just Safari with a skin, no Blink, no extension support. The workaround is **Orion Browser** by Kagi, which supports Chrome extensions on top of WebKit.

> **[Download Orion Browser](https://kagi.com/orion)** → install the extension → play deadshot.io in Orion.

---

## 🎮 Controls

Eight panels on the right side of your screen. Click the buttons or use the keys:

| Key | Panel | What it does |
|-----|-------|-------------|
| `\` | ✛ Style | Crosshair type, spin, breathe, psychedelic mode |
| `O` | 🎨 Colors | Main color, outline, opacity, hit marker |
| `.` | ⚙ Details | Outline toggle, dot type & size, circle radius |
| `I` | ┼ Arms | Toggle individual arms on/off |
| `/` | ⇔ Dims | Length, thickness, gap |
| `P` | 🖼 Images | All 4 custom image modes |
| `K` | 💾 Presets | Save/load slots, export/import codes |
| `1`–`5` | — | Instantly load preset slot 1–5 |
| `` ` `` | 📊 HUD | FPS, ping, key tracker, overlay color, preview |
| `U` | — | Hide / Show the entire sidebar |

Panels are **draggable** — grab anywhere that isn't a control.  
The **preview box** is also draggable — move it wherever.  
Settings **auto-save**. They survive page reloads.

---

## ✨ Crosshair Shapes

15+ vector shapes. Combine with images, spin, breathe, psychedelic — all at once.

| Category | Styles |
|----------|--------|
| **Cross** | Cross · Cross + Dot |
| **Circle** | Circle · Circle + Cross · Circle + Cross + Dot |
| **Dot** | Dot only |
| **Diamond** | Diamond · Diamond + Dot · Diamond + Cross |
| **Square** | Square · Square + Dot · Square + Cross ⊕ · Square + Cross + Dot · Square + X · Square + X + Dot |

---

## 🔵 Dot Types

For any style that includes a dot, you can pick the dot shape:

| Type | What it looks like |
|------|-------------------|
| Circle | Classic round dot |
| Square | Solid square |
| Diamond | Rotated square |
| Horizontal line | Short horizontal bar |
| Vertical line | Short vertical bar |

Size goes up to 30px.

---

## 🌀 Motion

Found in the **Style** panel. Both work at the same time.

**Spin** — the entire crosshair rotates continuously. Speed adjustable from slow drift to full send.

**Breathe** — the arms pulse in and out rhythmically. Speed and amount both adjustable. Looks like your crosshair is alive.

---

## ⚡ Hit Marker

Found in the **Colors** panel. Flashes 4 diagonal ticks on LMB click — like actual hit feedback but client side.

- Custom color, separate from your crosshair color
- Size and thickness sliders
- Duration: 50ms (blink) to 500ms (lingers)
- Toggle on/off

---

## 🖼 Custom Images

Upload PNG, JPG, or SVG. Transparent backgrounds render clean. All 4 modes work **simultaneously** and stack on top of the vector crosshair.

### Mode 1 — Full Crosshair Image
Drops your image dead center, replacing the vector crosshair. Size up to 160px. Opacity slider. Optional spin.

### Mode 2 — Custom Dot
Any image as the center dot. Optional spin.

### Mode 3 — Custom Arms
Tiles an image along each arm instead of drawing a line. Tile size and spacing adjustable. Respects which arms are toggled on.

### Mode 4 — Orbit / Border
**Repeating mode** — stamps N copies of an image around a circle, oval, or square path. The eggs-spinning-in-a-circle mode. Count, radius, icon size all adjustable. Can orbit the center or stay static. Each icon can spin on its own axis independently.

**Single image mode** — one image, two options:
- **Travel orbit path** — the image travels around the circle/oval/square continuously
- **Stay at center** — sits at the center, optional self-spin. Basically a fancy dot replacement. Size goes up to 160px.

Images are stored as base64 in your browser. They persist between sessions without re-uploading.

---

## 💾 Presets

Found in the **Presets** panel (`K`).

**5 save slots** — click a slot to load it, hit "Save to selected slot" to overwrite it.

**Export/Import codes** — exports your entire current settings as a base64 string. Share it with someone, they paste it and import. Instant crosshair sharing.

---

## 🍄 Psychedelic Mode

Found in the **Style** panel. Crosshair, outline, and all HUD overlays cycle through the full color spectrum in real time. Runs on the GPU via CSS hue-rotate — no JS canvas repaints. Potato PC approved. Speed adjustable.

---

## 📊 HUD Overlays

All sit top-left. Toggle each independently from the HUD panel.

- **Live FPS** — updates every second
- **Live Ping** — estimated, refreshes every 2s
- **Key Tracker** — WASD · LMB · RMB · Shift · Space · R · F
- **Overlay Color** — recolor all of the above to any color
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

### v2.1
- 🌀 **Spin** — whole crosshair rotates continuously, speed adjustable
- 💨 **Breathe** — arms pulse in and out, speed + amount adjustable. Both work simultaneously.
- ⚡ **Hit Marker** — diagonal tick flash on LMB, custom color/size/thickness/duration
- 🔵 **Dot types** — Circle, Square, Diamond, Horizontal line, Vertical line. Size up to 30px.
- 💾 **Presets** — 5 save slots + export/import shareable codes (`K` key)
- 🖼 **Orbit single image mode** — one image that travels the orbit path or sits at center, size up to 160px
- ┼ **Arms panel** — replaced checkboxes with big toggle buttons
- Removed redundant "show dot" checkbox — dot is controlled by crosshair type

### v2.1 — The Motion Update
- 🌀 **Spin** — whole crosshair rotates continuously, speed adjustable
- 💨 **Breathe** — arms pulse in and out, speed + amount adjustable. Both work simultaneously.
- ⚡ **Hit Marker** — diagonal tick flash on LMB, custom color/size/thickness/duration
- 🔵 **Dot types** — Circle, Square, Diamond, Horizontal line, Vertical line. Size up to 30px.
- 💾 **Presets** — 5 save slots, press `1`–`5` to load instantly, export/import shareable codes (`K` key)
- 🖼 **Orbit single image mode** — one image that travels the orbit path or sits at center, size up to 160px
- ┼ **Arms panel** — replaced checkboxes with big toggle buttons
- 🐛 Arms toggle actually works now. Inline `onclick` handlers are blocked by Chrome's Content Security Policy in extensions. Switched to delegated event listeners.

### v2.0 — The Image Update
- 🖼 **Mode 1** — Full PNG/JPG/SVG crosshair. Replaces vector entirely. Transparent backgrounds preserved.
- 🎯 **Mode 2** — Custom dot image. Optional spin.
- 💫 **Mode 3** — Custom arm tiles. Tiled along each arm instead of a line.
- 🌀 **Mode 4** — Orbit border. Repeating images in a circle, oval, or square. Can orbit, stay still, or spin on their own axis.
- All 4 modes work simultaneously on top of each other and the vector crosshair
- Single shared canvas, potato-safe. rAF loop only runs when animating.
- Images stored as base64 in localStorage

### v1.1.2
- 🎨 Psychedelic mode rewritten — GPU CSS hue-rotate, zero JS canvas repaints
- Tested on a potato PC. Runs fine. v1.1.1 could not say the same.

### v1.1.1
- 🐛 Fixed psychedelic mode tanking performance — throttled from 60fps to 20fps
- *The one I'm not proud of*

### v1.1
- 🍄 Psychedelic Mode, Overlay Color picker, draggable preview box

### v1.0
- Initial release — 15+ shapes, sidebar UI, HUD overlays, key tracker

---

## ⚠ Known Stuff

- Chrome only on desktop. Kiwi Browser on Android. Orion on iOS.
- Works on `deadshot.io` and `www.deadshot.io` only.
- Large image uploads will bloat localStorage. Keep them reasonable.

---

## 🐉 About the Dev

**The Lazy Dragon** · `怠竜 Tearyū`

BSc IT student who builds things way more complex than they need to be and calls it a crosshair.

- GitHub: [@The-Lazy-Dragon](https://github.com/The-Lazy-Dragon)
- Discord: `this.isnt.craig_`

### Also check out:
**[NavalStrike](https://github.com/The-Lazy-Dragon/NavalStrike)** — Battleship. But neon. But with 25 ship classes, 35 achievements, a Konami code, procedural audio, and hard AI that actually hurts. One `.html` file.

**[Lazy Dragon's TicTacToe](https://github.com/The-Lazy-Dragon/lazy-dragons-tictactoe)** — It's TicTacToe. But neon. But with achievements, a dev console, and an unbeatable minimax AI. Also one `.html` file.

---

<div align="center">

**⭐ Star the repo if your aim improved**

*Built with zero frameworks and questionable life choices — actually built this because deadshot.io's default crosshair was pissing me off*

</div>
