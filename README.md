# 🕯️ Interactive Loft Room Landing Page

<p align="center">
  <img src="https://img.shields.io/badge/HTML-Single%20File-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS-Pure%20CSS%20Only-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JS-Web%20Audio%20API-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Dependencies-Zero-ef4444?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Bundle%20Size-%3C 40KB-a855f7?style=for-the-badge" />
</p>

<p align="center">
  <strong>A cinematic, interactive loft room built entirely in one HTML file.</strong><br/>
  No frameworks. No images. No build tools. Just flip the switch.
</p>

<p align="center">
  <a href="#-quick-start">Get Started</a> ·
  <a href="#️-customisation-guide">Customise It</a> ·
  <a href="#-how-it-works">How It Works</a> ·
  <a href="#-contributing">Contribute</a>
</p>

---

## 📖 Table of Contents

- [What Is This?](#-what-is-this)
- [Features](#-features)
- [Live Demo](#-live-demo)
- [Quick Start](#-quick-start)
- [Customisation Guide](#️-customisation-guide)
  - [Change the Text](#1--change-the-heading--subtitle)
  - [Change the Title](#2--change-the-browser-tab-title)
  - [Change the Wall Art Label](#3--change-the-wall-art-label)
  - [Change the Music Label](#4--change-the-music-label)
  - [Change the Color Palette](#5--change-the-color-palette)
  - [Change the Fonts](#6--change-the-fonts)
  - [Rearrange Furniture](#7--rearrange-furniture)
  - [Change the Canvas Size](#8--change-the-canvas-size)
  - [Swap or Disable Music](#9--swap-or-disable-music)
  - [Edit the Portrait Overlay](#10--edit-the-portrait-overlay)
  - [Add a Call-to-Action Button](#11--add-a-call-to-action-button)
  - [Change the Switch Behavior](#12--change-the-switch-behavior)
- [File Structure](#-file-structure)
- [How It Works](#-how-it-works)
- [Browser Support](#-browser-support)
- [Deployment Guide](#-deployment-guide)
- [Use Case Ideas](#-use-case-ideas)
- [FAQ](#-faq)
- [Contributing](#-contributing)
- [Roadmap](#️-roadmap)
- [License](#-license)
- [Credits](#-credits)

---

## 🖼️ What Is This?

**Abinya 3.0** is a fully self-contained single HTML file that renders a detailed, atmospheric loft room scene using only CSS and vanilla JavaScript. There are no external assets, no frameworks, no build process, and no backend — just one file you can open in any browser.

It is designed to be used as a **website landing page** — particularly for:

- 🎓 Hackathons and tech events
- 🌐 Personal portfolio intro screens  
- 🚀 Product launch teasers
- 🎨 Creative showcases and art projects
- 🏢 Company or team intro pages

The room comes alive when you click the wall switch. Lights glow, the floor reflects warmth, ambient music begins to play, and your custom text fades into view.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🏠 **Full Loft Room Scene** | Ceiling, back wall, side walls, wainscot panels, molding - all in pure CSS |
| 🪵 **3D Perspective Floor** | Wood planks that recede toward the horizon using CSS `rotateX` perspective - no WebGL |
| 💡 **Interactive Light Switch** | Realistic rocker switch with physical tilt animation, LED indicator, and full lighting toggle |
| 🌡️ **Dynamic Lighting System** | 12+ elements change simultaneously - bulb glow, floor pool, wall bloom, shade glow, table lamp |
| 🪑 **Tufted Leather Armchair** | Fully CSS-rendered with tufting buttons, padded seat, armrests and legs |
| 📚 **Bookshelf with Books & Plant** | Three shelves of varied books, small plant with leaves and terracotta pot |
| 🪔 **Side Table with Lamp** | Working table lamp that activates with the main lights |
| 🪟 **Window with Curtains** | Dark glass pane with cross mullions, curtain rod, and draped green curtains |
| 🖼️ **Framed Wall Art** | Abstract CSS painting in an ornate dark wood frame with artist label |
| 🎵 **Procedural Ambient Music** | Synthesised pads and melody via Web Audio API - zero audio files |
| 📱 **Mobile Landscape Mode** | Portrait triggers a beautiful "rotate your phone" screen; landscape fills perfectly |
| 🎞️ **Film Grain Overlay** | SVG fractal noise at 4% opacity for a cinematic, analogue feel |
| 🔤 **Elegant Typography** | Cormorant Garamond (serif) + DM Mono (mono) loaded from Google Fonts |
| ⚡ **Zero Dependencies** | One HTML file, under 40KB, no npm, no build step, no servers |

---

## 🎥 Live Demo

Clone the repo and open `index.html` directly in your browser:

```bash
git clone https://github.com/your-username/abinya-loft.git
cd abinya-loft
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

> **No server required.** Google Fonts will load if you have an internet connection. The room itself works fully offline.

---

## 🚀 Quick Start

### Option A — Use as-is

1. Download `index.html`
2. Open it in a browser
3. Click the switch on the right wall

### Option B — Clone & Customise

```bash
# Clone
git clone https://github.com/your-username/abinya-loft.git
cd abinya-loft

# Edit the file
code index.html     # or any text editor

# Preview
open index.html
```

### Option C — Fork on GitHub

1. Click **Fork** in the top right of this page
2. Edit `index.html` directly in GitHub's editor  
3. Enable GitHub Pages (Settings → Pages → main branch)
4. Your landing page is live in ~60 seconds

---

## 🛠️ Customisation Guide

Everything lives inside a single `index.html` file. Use your browser's developer tools (`F12`) or any text editor to find and edit the sections below.

---

### 1. 📝 Change the Heading & Subtitle

Search for `light-text` in the file. You'll find:

```html
<div class="light-text">
  <h2>The Ideas Are Warming Up…</h2>
  <p>Innovation · Creativity · Engineering Excellence</p>
</div>
```

**Replace** the `<h2>` with your event name, product name, or personal tagline.  
**Replace** the `<p>` with your subtitle, dates, or a short description.

**Examples:**
```html
<!-- Hackathon -->
<h2>HackFest 2025</h2>
<p>48 hours · 200 hackers · infinite possibilities</p>

<!-- Personal portfolio -->
<h2>Hi, I'm Priya.</h2>
<p>designer · developer · dreamer</p>

<!-- Product launch -->
<h2>Something is coming.</h2>
<p>launching march 2025 · stay tuned</p>
```

The heading uses italic Cormorant Garamond at 24px with a warm amber glow. The subtitle uses DM Mono at 9px with letter-spacing. Both fade in smoothly when the lights turn on.

---

### 2. 🏷️ Change the Browser Tab Title

At the very top of the file:

```html
<title>Abinya 3.0</title>
```

Change `Abinya 3.0` to your project or event name.

---

### 3. 🖼️ Change the Wall Art Label

The framed artwork on the right wall has a small label beneath it:

```html
<div class="art-label">Abinya 3.0</div>
```

Change this to your version number, studio name, or any short text. It appears in tiny monospace uppercase font when the lights are on.

---

### 4. 🎵 Change the Music Label

The small music indicator in the bottom-left shows a label when music plays:

```html
<span class="music-label">Nocturne</span>
```

Change `Nocturne` to match your vibe — `Ambient`, `Lo-fi`, `v2.0`, your event hashtag, anything short.

---

### 5. 🎨 Change the Color Palette

The room is built with rich dark browns and warm amber lighting. Here are the key colors to find-and-replace for a custom theme:

#### Key Color Reference

| Element | Color (Off) | Color (On) | CSS Class |
|---|---|---|---|
| Light glow / text | — | `#ffd060` | `.bulb.on`, `.light-text h2` |
| Ceiling | `#0e0c09` | `#1e1a10` | `.ceiling` |
| Back wall | `#1e1912` | `#30261a` | `.wall` |
| Side walls | `#090806` | `#141009` | `.left-wall` |
| Floor planks | `#2a1d0f` | (brighter) | `.floor-planks` |
| Leather chair | `#4c3622` | — | `.chair-back` |
| Curtains | `#1e2a1a` | — | `.curtain` |
| Switch plate | `#cec5a4` | — | `.switch-plate` |

#### Example: Blue Night Theme

Replace amber values with cool blue throughout:

```css
/* Find these → Replace with */
rgba(255,200,60, ...)  →  rgba(60,140,255, ...)
rgba(255,215,70, ...)  →  rgba(80,160,255, ...)
#ffd060                →  #60aaff
```

#### Example: Emerald Theme

```css
rgba(255,200,60, ...)  →  rgba(60,220,120, ...)
#ffd060                →  #50e090
```

---

### 6. 🔤 Change the Fonts

Two fonts load from Google Fonts at the top of the `<head>`:

```html
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;1,300&family=DM+Mono:wght@300&display=swap" rel="stylesheet">
```

- **Cormorant Garamond** — the elegant italic heading
- **DM Mono** — monospace labels, switch text, music label

**To swap fonts:**

1. Visit [fonts.google.com](https://fonts.google.com) and pick your fonts
2. Copy the new `<link>` tag and replace the one above
3. Update the CSS rules:

```css
/* Main heading */
.light-text h2 { font-family: 'Your Serif Font', serif; }

/* Labels and subtext */
.light-text p,
.music-label,
.art-label     { font-family: 'Your Mono Font', monospace; }
```

**To use system fonts only (no Google Fonts):**

```css
.light-text h2 { font-family: Georgia, 'Times New Roman', serif; }
.light-text p  { font-family: 'Courier New', Courier, monospace; }
```

Remove the `<link>` tag from the `<head>` and the page will load with zero external requests.

---

### 7. 🪑 Rearrange Furniture

Every furniture piece is absolutely positioned within the room. The floor line is at `bottom: 26%`. You can freely move items left or right.

```css
/* Bookshelf — default: left side */
.bookshelf {
  left: 10%;      /* ← adjust this to move left/right */
  bottom: 26%;    /* keep this to stay on the floor */
}

/* Armchair — default: right side */
.armchair {
  right: 11%;     /* ← adjust this */
  bottom: 26%;
}

/* Side table — auto-positioned next to armchair */
.side-table {
  right: calc(11% + 156px);   /* ← 156px is the armchair width */
  bottom: 26%;
}

/* Rug — centred by default */
.rug {
  left: 50%;
  transform: translateX(-50%);  /* keeps it centred */
  bottom: 26%;
}
```

> **Tip:** If you move the armchair, update the side table's `right` value to `calc(NEW_RIGHT% + 156px)` so it stays adjacent.

---

### 8. 📐 Change the Canvas Size

The room is designed at **1440 × 600 px**. This gives a wide cinematic aspect ratio. To change it:

**Step 1** — Update the CSS:
```css
.room {
  width:  1440px;   /* ← your new width  */
  height: 600px;    /* ← your new height */
}
```

**Step 2** — Update the JavaScript scale function to match:
```javascript
function scaleRoom() {
  const scale = Math.min(stage.clientWidth / 1440, stage.clientHeight / 600);
  //                                         ^^^^                       ^^^
  //                           must match your new CSS dimensions above
  room.style.transform = `scale(${scale})`;
}
```

**Recommended ratios:**

| Use Case | Width | Height | Ratio |
|---|---|---|---|
| Current (default) | 1440px | 600px | 2.4:1 |
| Widescreen cinema | 1920px | 800px | 2.4:1 |
| Standard laptop | 1280px | 720px | 16:9 |
| Square / Instagram | 800px | 800px | 1:1 |

---

### 9. 🎵 Swap or Disable Music

#### Disable music completely

Find the `startMusic()` and `stopMusic()` functions in the `<script>` tag, and replace them with empty functions:

```javascript
function startMusic() {}
function stopMusic()  {}
```

You can also remove the music bars UI from the HTML:

```html
<!-- Remove or comment out this block -->
<div class="music-ui">
  ...
</div>
```

#### Use your own audio file

Replace the `startMusic()` and `stopMusic()` functions with:

```javascript
let bgAudio = null;

function startMusic() {
  bgAudio = new Audio('your-track.mp3');  // place file next to index.html
  bgAudio.loop   = true;
  bgAudio.volume = 0;
  bgAudio.play().catch(() => {}); // catch autoplay errors gracefully

  // Fade in over 3 seconds
  let v = 0;
  const fade = setInterval(() => {
    v = Math.min(0.8, v + 0.016);
    bgAudio.volume = v;
    if (v >= 0.8) clearInterval(fade);
  }, 50);
}

function stopMusic() {
  if (!bgAudio) return;
  let v = bgAudio.volume;
  const fade = setInterval(() => {
    v = Math.max(0, v - 0.02);
    bgAudio.volume = v;
    if (v <= 0) { bgAudio.pause(); bgAudio.currentTime = 0; clearInterval(fade); }
  }, 60);
}
```

Then place `your-track.mp3` (or `.ogg`, `.wav`) in the same folder as `index.html`.

> **Free ambient music sources:** [freemusicarchive.org](https://freemusicarchive.org), [pixabay.com/music](https://pixabay.com/music), [incompetech.com](https://incompetech.com)

#### Keep procedural music but change the chord

The current music plays a **Cm9 chord** (C minor 9). The pad frequencies are defined near the top of the music section:

```javascript
const PAD = [
  {f: 130.81, v: 0.055},  // C3  — root
  {f: 155.56, v: 0.048},  // Eb3 — minor third
  {f: 196.00, v: 0.052},  // G3  — fifth
  {f: 233.08, v: 0.040},  // Bb3 — minor seventh
  {f: 293.66, v: 0.032},  // D4  — ninth
  {f: 349.23, v: 0.025},  // F4  — eleventh
  {f: 392.00, v: 0.020},  // G4  — upper fifth
  {f: 466.16, v: 0.015},  // Bb4 — upper seventh
];
```

Change `f` values to any frequencies you like. A few useful root notes:

| Note | Frequency |
|---|---|
| C3 | 130.81 Hz |
| D3 | 146.83 Hz |
| E3 | 164.81 Hz |
| F3 | 174.61 Hz |
| G3 | 196.00 Hz |
| A3 | 220.00 Hz |

---

### 10. 📱 Edit the Portrait Overlay

When a phone is held in portrait orientation, this overlay appears:

```html
<div class="rotate-overlay" id="rotateOverlay">
  <div class="rotate-icon">
    <!-- SVG phone + rotation arrow icon -->
  </div>
  <h2>rotate your phone</h2>
  <p>landscape mode · for best experience</p>
</div>
```

Customise the text, or add your logo above the heading:

```html
<h2>rotate your phone</h2>
<p>HackFest 2025 · landscape mode required</p>
```

To change the overlay background:
```css
.rotate-overlay {
  background: linear-gradient(160deg, #0a0806 0%, #1a1410 100%);
  /* ↑ change to any color or gradient */
}
```

To **allow portrait mode** (if you don't need the lock), remove or comment out these CSS rules:

```css
/* Delete or comment these two media query blocks */
@media (orientation:portrait) {
  .rotate-overlay { display: flex; }
  .stage         { display: none; }
}
@media (orientation:landscape) {
  .rotate-overlay { display: none !important; }
  .stage         { display: flex; }
}
```

---

### 11. 🔲 Add a Call-to-Action Button

When the lights turn on, you may want a button to appear — a link to your project, registration form, or portfolio. 

Add this inside the `.wall` div, after the `.light-text` div:

```html
<div class="cta-button">
  <a href="https://your-link.com" target="_blank">Register Now →</a>
</div>
```

Add this CSS:

```css
.cta-button {
  position: absolute;
  bottom: 22%;
  left: 50%;
  transform: translateX(-50%) translateY(10px);
  opacity: 0;
  transition: opacity 0.9s ease 1s, transform 0.9s ease 1s;
  pointer-events: none;
  z-index: 25;
}
.room.on .cta-button {
  opacity: 1;
  transform: translateX(-50%) translateY(0);
  pointer-events: all;
}
.cta-button a {
  font-family: 'DM Mono', monospace;
  font-size: 11px;
  letter-spacing: 3px;
  text-transform: uppercase;
  color: #ffd060;
  text-decoration: none;
  border: 1px solid rgba(255, 208, 96, 0.4);
  padding: 10px 24px;
  border-radius: 2px;
  transition: background 0.3s ease, border-color 0.3s ease;
}
.cta-button a:hover {
  background: rgba(255, 208, 96, 0.08);
  border-color: rgba(255, 208, 96, 0.8);
}
```

---

### 12. ⚡ Change the Switch Behavior

By default, the switch toggles between on and off states. You can hook into this for custom actions.

Find the click listener in the `<script>` section:

```javascript
rocker.addEventListener('click', () => {
  isOn = !isOn;
  if (isOn) {
    // ← ADD YOUR CUSTOM "ON" LOGIC HERE
    // e.g., show a modal, start a countdown, redirect after delay
    room.classList.add('on');
    ...
  } else {
    // ← ADD YOUR CUSTOM "OFF" LOGIC HERE
    room.classList.remove('on');
    ...
  }
});
```

**Example: redirect to another page after lights come on:**

```javascript
if (isOn) {
  room.classList.add('on');
  rocker.classList.add('on');
  // ... existing light code ...
  startMusic();

  // Redirect after 3 seconds
  setTimeout(() => {
    window.location.href = 'https://your-main-site.com';
  }, 3000);
}
```

**Example: start a countdown timer:**

```javascript
if (isOn) {
  // ... existing code ...
  startCountdown(); // your custom function
}
```

---

## 📁 File Structure

```
abinya-loft/
│
├── index.html       ← The entire project lives here
├── README.md        ← This documentation
└── LICENSE          ← MIT License
```

That's the whole project. One HTML file, under 40 KB.

---

## 🏗️ How It Works

### Architecture Overview

```
┌─────────────────────────────────────────────────────────┐
│                         .stage                          │
│    (fixed viewport container, centres the room)        │
│                                                         │
│  ┌──────────────────────────────────────────────────┐  │
│  │                      .room                       │  │
│  │         (1440 × 600 px, scaled via JS)           │  │
│  │                                                   │  │
│  │  .ceiling          ████████████████████  0–18%   │  │
│  │  .lamp-assembly    ████ z-index:50 ████           │  │
│  │  .wall             ████████████████████  18–74%  │  │
│  │    └── .window                                    │  │
│  │    └── .wall-art                                  │  │
│  │    └── .light-text                                │  │
│  │    └── .music-ui                                  │  │
│  │  .left-wall        █  9% wide                     │  │
│  │  .right-wall       █  9% wide (switch inside)     │  │
│  │  .bookshelf        absolute, bottom:26%           │  │
│  │  .armchair         absolute, bottom:26%           │  │
│  │  .side-table       absolute, bottom:26%           │  │
│  │  .rug              absolute, bottom:26%           │  │
│  │  .floor            ████████████████████  74–100% │  │
│  │    └── .floor-planks  (3D perspective)            │  │
│  │    └── .floor-pool    (light glow)                │  │
│  │  .grain            fixed, z-index:100, 4% opacity │  │
│  └──────────────────────────────────────────────────┘  │
└─────────────────────────────────────────────────────────┘
```

### Responsive Scaling

The room is a **fixed-pixel design** scaled to fit any screen. Rather than using `%` or `vw` units for furniture (which would cause layout drift), everything is designed at full 1440×600 and then scaled uniformly:

```javascript
function scaleRoom() {
  const scale = Math.min(
    stage.clientWidth  / 1440,
    stage.clientHeight / 600
  );
  room.style.transform = `scale(${scale})`;
}
window.addEventListener('resize', scaleRoom);
```

This is the same technique used by game engines for pixel-perfect UI — the design never reflows, just scales.

### 3D Floor Without WebGL

The perspective floor uses a single CSS transform trick:

```css
.floor-planks {
  position: absolute;
  bottom: 0;
  left:  -60%;   /* extend beyond container width */
  right: -60%;
  height: 340%;  /* extend well above the container */

  transform: perspective(240px) rotateX(62deg);
  transform-origin: bottom center;
}
```

By making the element much **wider and taller** than its container, then rotating it toward the viewer on the X axis, the parallel plank lines converge toward a vanishing point at the top — creating true perspective depth without any 3D library.

### Lighting System — 12 Simultaneous Transitions

The entire lighting system is driven by a single CSS class toggle. JavaScript adds or removes `.on` from the `.room` element, and CSS handles every transition:

```javascript
room.classList.toggle('on'); // this one line triggers everything
```

CSS selectors react to this class across the entire element tree:

```css
/* Example — wall changes colour */
.wall             { background: #1e1912; transition: background 1.2s ease; }
.room.on .wall    { background: #30261a; }

/* Example — floor brightens */
.floor-planks                { filter: brightness(1); }
.room.on .floor-planks       { filter: brightness(2.1) saturate(1.3); }

/* Example — light pool appears */
.floor-pool                  { opacity: 0; transition: opacity 1.4s ease; }
.room.on .floor-pool         { opacity: 1; }
```

All 12+ transitions run simultaneously and are GPU-accelerated (only `filter`, `opacity`, `background`, `box-shadow` and `transform` are animated).

### Pendant Lamp — Always on Top

The lamp has `z-index: 50` as a direct child of `.room`, placed **after** the wall div in the HTML. This means it renders on top of the wall art, bookshelf, and all other elements — just like a real lamp hanging from the ceiling:

```html
<div class="room">
  <div class="ceiling">...</div>
  <div class="lamp-assembly" style="z-index:50">  ← renders last (on top)
    ...bulb, shade, cord...
  </div>
  <div class="wall">
    <div class="wall-art">...</div>   ← z-index:6, behind lamp
  </div>
  ...
</div>
```

### Ambient Music — How the Synthesis Works

The music system uses the [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API) to build a synthesiser entirely in JavaScript:

```
 8 Oscillators (Cm9 chord voicing)
      ↓ each with:
      • Frequency LFO  → slow pitch vibrato
      • Amplitude LFO  → slow tremolo
      ↓
 Low-pass filter  (cutoff: 1400Hz)
      ↓                    ↘
 Direct signal         Convolution Reverb (5-second impulse)
      ↓                    ↓
        Master Gain Node  ← fade in/out
              ↓
        Audio Output
              +
 Melody oscillator (pentatonic, triangle wave)
 → plays one note every 1.6–3.4 seconds
 → own LPF → Master Gain
```

The reverb is created procedurally: a buffer of decaying random noise becomes the impulse response for `createConvolver()`. No audio files, no samples — the reverb is computed on the fly.

### Portrait Detection — Pure CSS

No JavaScript is used to detect orientation. The CSS media query handles everything:

```css
@media (orientation: portrait) {
  .rotate-overlay { display: flex; } /* show overlay */
  .stage          { display: none;  } /* hide room    */
}
@media (orientation: landscape) {
  .rotate-overlay { display: none !important; } /* hide overlay */
  .stage          { display: flex; }            /* show room    */
}
```

The phone icon animates with a simple CSS keyframe that tilts -90° and back on a 2.2s loop:

```css
@keyframes rockit {
  0%  { transform: rotate(0deg);   }
  30% { transform: rotate(-90deg); }  /* tilt to landscape */
  60% { transform: rotate(-90deg); }  /* hold */
  80% { transform: rotate(0deg);   }  /* return */
  100%{ transform: rotate(0deg);   }
}
```

---

## 🌐 Browser Support

| Browser | Version | Support | Notes |
|---|---|---|---|
| Chrome | 90+ | ✅ Full | Recommended |
| Firefox | 88+ | ✅ Full | |
| Safari | 14+ | ✅ Full | Requires user tap before audio |
| Edge | 90+ | ✅ Full | |
| Mobile Chrome | Latest | ✅ Landscape only | |
| Mobile Safari | 14+ | ✅ Landscape only | |
| Samsung Internet | 14+ | ✅ Full | |
| Opera | 76+ | ✅ Full | |
| IE 11 | — | ❌ Not supported | CSS transforms not compatible |

> **Audio note:** All modern browsers require a user interaction (a click or tap) before audio can play. This project handles this naturally — music only starts when the user clicks the wall switch.

---

## 🚢 Deployment Guide

### GitHub Pages (Free, Recommended)

```
1. Fork this repository
2. Go to: Settings → Pages
3. Source: Deploy from a branch
4. Branch: main  /  Folder: / (root)
5. Click Save
6. Wait ~60 seconds
7. Visit: https://YOUR-USERNAME.github.io/REPO-NAME
```

### Netlify (Free, Drag & Drop)

1. Visit [netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop the `index.html` file (or the whole folder)
3. Netlify gives you an instant live URL
4. Optionally connect a custom domain in Netlify settings

### Vercel (Free)

```bash
npm i -g vercel
vercel deploy
# Follow the prompts — live in ~30 seconds
```

### Cloudflare Pages (Free)

1. Push to a GitHub repo
2. Go to Cloudflare Pages → Create a project
3. Connect your GitHub repo
4. No build command needed — just set output directory to `/`

### Self-hosted / VPS

```bash
# Nginx — serve the file directly
server {
  listen 80;
  server_name yourdomain.com;
  root /var/www/abinya;
  index index.html;
}

# Or just use Python for quick local testing
python3 -m http.server 8080

# Or Node.js
npx serve .
```

### Custom Domain

After deploying to GitHub Pages, Netlify, or Vercel, add your custom domain through their DNS settings. All three platforms support custom domains on free plans.

---

## 🎯 Use Case Ideas

| Idea | What to Change |
|---|---|
| **Hackathon landing** | Heading → event name, subtitle → dates/tagline, add a Register button |
| **Tech conference** | Heading → conference name, add countdown timer in JS |
| **Personal portfolio** | Heading → your name + role, subtitle → stack/skills, switch → link to portfolio PDF |
| **Product teaser** | Heading → product name, subtitle → "coming soon · [date]", music off |
| **Startup intro** | Heading → company tagline, CTA button → links to app or signup |
| **Artist portfolio** | Change color palette to monochrome, heading → artist name |
| **Game jam page** | Dark theme perfect as-is, add game logo as CSS element |
| **University project** | Show as interactive demo, heading → project title |
| **Wedding / event invite** | Warm tones already set, heading → event name + date |
| **Retro / arcade theme** | Change colors to neon green/cyan, swap fonts to monospace only |

---

## ❓ FAQ

**Q: Does this work offline?**  
A: Yes, fully — except Google Fonts will fall back to system fonts. The room, music, and all interactions work with no internet connection.

**Q: Can I add images to the room?**  
A: Yes. Use `<img>` tags with `position: absolute` inside the `.room` div, with `bottom: 26%` to place them on the floor line. Set a `z-index` between 9 and 49 so they render behind the lamp.

**Q: Why doesn't the music play on mobile?**  
A: Browsers require a user gesture before audio. On mobile, tap the switch — if audio still doesn't play on Safari, make sure your device is not in silent mode.

**Q: Can I add video to the window?**  
A: Yes! Replace the `.window-frame` background with a `<video>` element playing a looping night scene. Set `position: absolute; inset: 0; width: 100%; height: 100%; object-fit: cover` on the video.

**Q: How do I make the switch start in the "on" position?**  
A: Change the initial state in the JavaScript:

```javascript
let isOn = true; // was false

// Then immediately after the rocker event listener, add:
room.classList.add('on');
rocker.classList.add('on');
led.style.background = 'rgba(60,220,60,0.88)';
led.style.boxShadow  = '0 0 7px rgba(60,255,60,0.75)';
bulb.classList.add('on');
// Note: don't call startMusic() here — audio needs a user gesture first
```

**Q: Can I use this commercially?**  
A: Yes. The MIT license permits commercial use, modification, and distribution. Attribution is appreciated but not required.

**Q: Why is the room 1440 × 600 and not 16:9?**  
A: The 2.4:1 cinematic ratio was chosen intentionally — it fills widescreen monitors beautifully and feels like a movie frame. On 16:9 screens it scales down with letterboxing above and below, which adds to the cinematic feel. You can change it to 1280×720 (16:9) if you prefer — see [Change the Canvas Size](#8--change-the-canvas-size).

**Q: How do I add my own furniture or decorations?**  
A: Add new `<div>` elements inside `.room`, position them with `position: absolute; bottom: 26%` for floor-level items, and style with CSS. Add a `.room.on .your-element { filter: brightness(1) }` state for the lit version.

---

## 🤝 Contributing

Contributions are warmly welcome! Here's how to get involved:

### Good First Issues

- [ ] Add a **second furniture layout** variant (e.g., modern/minimal)
- [ ] Add **CSS-only stars** visible through the window at night
- [ ] Add a **typewriter animation** on the heading text
- [ ] Add **rain on the window glass** using CSS animation
- [ ] Add a **countdown timer** component
- [ ] Add an **optional CTA section** that expands below when lights turn on
- [ ] Create a **color theme switcher** with CSS custom properties
- [ ] Add a **cat silhouette** sleeping on the armchair 🐱

### How to Contribute

```bash
# 1. Fork the repository on GitHub

# 2. Clone your fork
git clone https://github.com/YOUR-USERNAME/abinya-loft.git
cd abinya-loft

# 3. Create a branch for your feature
git checkout -b feature/add-cat-on-chair

# 4. Make your changes to index.html
# 5. Test in Chrome, Firefox, and Safari
# 6. Test on mobile (landscape mode)

# 7. Commit with a descriptive message
git commit -m "feat: add sleeping cat on armchair with CSS animation"

# 8. Push to your fork
git push origin feature/add-cat-on-chair

# 9. Open a Pull Request on GitHub
```

### Contribution Guidelines

- Keep everything in a single `index.html` file — no build tools or separate assets unless truly necessary
- Test in at least Chrome and Firefox before submitting
- Keep the total file size under 60 KB
- Follow the existing CSS naming convention (`.kebab-case`)
- Comment non-obvious CSS tricks so others can learn from them
- If adding a new interactive feature, ensure it works via keyboard as well as mouse

### Code Style

```css
/* ══ SECTION NAME ══ */
.element {
  property: value;         /* comment if non-obvious */
}
.room.on .element { property: new-value; }  /* lit state on same line */
```

---

## 🗺️ Roadmap

### Version 3.1
- [ ] CSS custom properties (variables) for easy one-place color theming
- [ ] Keyboard accessibility (Tab to switch, Enter/Space to toggle)
- [ ] `prefers-reduced-motion` media query to disable animations

### Version 3.2
- [ ] Second room theme: Modern Minimal (white walls, concrete floor)
- [ ] Day/night toggle with sunrise gradient through the window
- [ ] Optional countdown timer component

### Version 4.0
- [ ] Multiple rooms selectable via a menu
- [ ] User-configurable text via URL hash parameters
- [ ] CSS-only winter version with snow through the window

---

## 📄 License

```
MIT License

Copyright (c) 2025 Abinya 3.0 Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

---

## 🙏 Credits

**Core technologies:**
- [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API) — procedural music synthesis
- [CSS Transforms](https://developer.mozilla.org/en-US/docs/Web/CSS/transform) — 3D floor perspective effect
- [SVG Filters](https://developer.mozilla.org/en-US/docs/Web/SVG/Element/filter) — film grain overlay

**Fonts:**
- [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) by Christian Thalmann — Google Fonts
- [DM Mono](https://fonts.google.com/specimen/DM+Mono) by Colophon Foundry — Google Fonts

**Inspiration:**
- The warmth of a lamp-lit room on a cold night
- The feeling of walking into a space where ideas happen

---

<p align="center">
  <strong>Built with ♥ and a single HTML file</strong>
</p>

<p align="center">
  If this helped you, consider giving it a ⭐ on GitHub
</p>

<p align="center">
  <a href="#-quick-start">↑ Back to top</a>
</p>
