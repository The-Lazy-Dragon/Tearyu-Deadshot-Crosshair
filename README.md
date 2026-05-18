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
## Android Edition

**The crosshair app for deadshot.io. Native Android. No browser extensions needed.**

[![Made by The Lazy Dragon](https://img.shields.io/badge/Made%20by-The%20Lazy%20Dragon%20怠竜-ff153f?style=flat-square)](https://github.com/The-Lazy-Dragon)
[![Platform](https://img.shields.io/badge/Platform-Android-00fff7?style=flat-square)](#)
[![Min SDK](https://img.shields.io/badge/Android-8.0%2B-3a486a?style=flat-square)](#)
[![Version](https://img.shields.io/badge/Version-1.0-ff153f?style=flat-square)](#)
[![Free](https://img.shields.io/badge/Price-Free-00ff88?style=flat-square)](#)

*The browser extension, but as an app. Same crosshair. Same features. No Tampermonkey. No Kiwi Browser. Just install and play.*

---

</div>

## ⚡ What is this?

A native Android app that loads deadshot.io in a full-screen WebView with the crosshair injected directly into the page. Toggle it on and off from the bottom bar. Customise it from inside the app. Free, no ads, sideloadable from GitHub.

Based on the [browser extension](https://github.com/The-Lazy-Dragon/Tearyu-Deadshot-Crosshair/tree/main) — same crosshair engine, all the same features.

---

## 📲 Install the APK

### Option 1 — Just download it (easiest)

**1.** Go to the [Releases](https://github.com/The-Lazy-Dragon/Tearyu-Deadshot-Crosshair/releases) tab of this repo

**2.** Download `怠竜-deadshot.apk` from the latest release

**3.** Transfer it to your phone if needed (or download directly on your phone)

**4.** On your phone: **Settings → Apps → Special app access → Install unknown apps** → enable it for your file manager or browser

**5.** Tap the APK → Install → done

---

### Option 2 — Build it yourself

> You need **Android Studio** installed. Download it at [developer.android.com/studio](https://developer.android.com/studio). Open it once and let it finish downloading the SDK before you start.

**1.** Clone this branch:
```bash
git clone --branch android https://github.com/The-Lazy-Dragon/Tearyu-Deadshot-Crosshair.git
cd tearyu-deadshot-crosshair
```

**2.** Open **Android Studio** → **Open** → select the cloned folder

**3.** Wait for Gradle sync to finish — progress bar at the bottom. Takes 2–3 minutes the first time.

**4.** Go to:
```
Build → Build Bundle(s) / APK(s) → Build APK(s)
```

**5.** APK is at:
```
app/build/outputs/apk/debug/app-debug.apk
```

**6.** Transfer it to your phone → tap to install.

> You can rename the APK to whatever you want. Android reads the app name from inside the file, not the filename.

---

## 📲 What's in the App

**Splash screen** — 怠竜 branded, 1.8 seconds, looks clean.

**Main screen:**
- Full-screen deadshot.io WebView
- Detects if you're on deadshot.io — if you navigate away it tells you and gives you a button to go back
- **Crosshair toggle** — big button at the bottom, tap to enable/disable the crosshair
- **Settings button** — opens the crosshair editor panel in-game without you having to press any keys
- **About button** — top right, opens the about screen

**On first launch:** asks for Draw Over Other Apps permission. Tap OK and enable it in settings. If you skip it the crosshair still works inside the app — you only need that permission if you want the crosshair visible while using other apps simultaneously.

---

## ✨ Crosshair Features

Everything from the browser extension is in here — same JS engine, same settings, same everything:

- 15+ vector crosshair shapes — Cross, Circle, Diamond, Square, Dot and combos
- Custom images — PNG/JPG/SVG for full crosshair, dot, arms, orbit border
- Orbit border — repeating images in a circle/oval/square, single image mode
- Spin and breathe motion on the vector crosshair
- Hit marker flash on tap
- Dot types — Circle, Square, Diamond, H-line, V-line
- 5 preset slots with export/import codes
- Psychedelic mode — full GPU CSS hue-rotate, potato-safe
- HUD overlays — FPS, ping, key tracker, custom color
- Draggable preview box
- All settings auto-save

---

## 📂 Project Structure

```
tearyu-deadshot-android/
├── app/
│   ├── src/main/
│   │   ├── java/com/lazydragons/tearyu/
│   │   │   ├── SplashActivity.java      — splash screen
│   │   │   ├── MainActivity.java        — main WebView + crosshair injection
│   │   │   ├── AboutActivity.java       — about screen
│   │   │   └── OverlayService.java      — placeholder for future system overlay
│   │   ├── res/
│   │   │   ├── layout/                  — XML layouts
│   │   │   ├── values/                  — colors, strings, themes
│   │   │   ├── mipmap-*/               — launcher icons
│   │   │   └── raw/crosshair.js        — the crosshair engine
│   │   └── AndroidManifest.xml
│   └── build.gradle
├── gradle/
├── build.gradle
└── settings.gradle
```

---

## ⚠ Known Stuff

- Android 8.0+ (API 26) required
- Needs internet to load deadshot.io — it's a WebView app, not an offline game
- Keyboard shortcuts from the browser extension (`\`, `O`, `.` etc.) don't work on mobile — use the Settings button instead
- Chrome extension version also works on Android via **Kiwi Browser** if you prefer that

---

## 🌐 Also Available As

**Browser Extension** — works on Chrome (desktop), Kiwi Browser (Android), Orion (iOS).
→ **[main branch](https://github.com/The-Lazy-Dragon/Tearyu-Deadshot-Crosshair/tree/main)**

---

## 🐉 About the Dev

**The Lazy Dragon** · `怠竜 Tearyū`

BSc IT student who builds things way more complex than they need to be.

- GitHub: [@The-Lazy-Dragon](https://github.com/The-Lazy-Dragon)
- Discord: `this.isnt.craig_`

### Also check out:
**[NavalStrike](https://github.com/The-Lazy-Dragon/NavalStrike)** — Battleship. But neon. But with 25 ship classes, 35 achievements, a Konami code, procedural audio, and hard AI that actually hurts. One `.html` file.

**[Lazy Dragon's TicTacToe](https://github.com/The-Lazy-Dragon/lazy-dragons-tictactoe)** — TicTacToe. But neon. But with achievements, a dev console, and an unbeatable minimax AI. Also one `.html` file.

---

<div align="center">

**⭐ Star the repo if your aim improved**

*Built with zero frameworks and questionable life choices*

</div>
