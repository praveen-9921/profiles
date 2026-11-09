# 🚀 Custom Link-in-Bio Profile Showcase

A suite of four high-performance, single-file HTML/CSS/JS profile landing pages inspired by **guns.lol**, complete with a glassmorphic central switcher hub.

---

## 🌟 Features Across All Profiles

* **Persistent Tracking:** Real-time **Views** and **Likes** counters powered by browser `localStorage`.
* **Zero Initial State:** Views increment naturally per visit starting at `0`, while likes can be toggled by visitors.
* **Audio Integration:** Integrated background audio players with custom UI visualizers and click-to-enter splash screen controls to bypass browser autoplay restrictions.
* **3D Micro-Interactions:** Interactive 3D tilt effects on cards tracking cursor position.
* **Custom Dynamic Cursors:** Theme-specific cursor effects (sparkle trails, 8-bit pixel pointers, star ribbons).
* **Zero External Dependencies:** Built with pure HTML, CSS, JavaScript, and Font Awesome icons.

---

## 📁 Project Structure

Organize your local workspace folder as follows:

```text
profile/
├── index.html     # Central Glassmorphic Switcher Hub
├── index1.html    # Midnight Cyber-Glass Profile
├── index2.html    # Soft Pastel Glass Profile
├── index3.html    # Minimalist Monochromatic Profile
└── index4.html    # Retro Arcade / Pixel Synth Profile
```

---

## 🎨 Themes Included

### 1. Central Switcher Hub (`index.html`)
* **Vibe:** Glassmorphic navigation portal.
* **Features:** Ambient floating orb background, high-contrast translucent cards, and smooth hover animations linking directly to all four templates.

### 2. Midnight Cyber-Glass (`index1.html`)
* **Vibe:** Futuristic cyberpunk HUD.
* **Features:** Particle canvas with distance-line connections, neon pulse heart animations, glowing dual-color light orbs, and floating audio widget.

### 3. Soft Pastel Glass (`index2.html`)
* **Vibe:** Aesthetic and playful.
* **Features:** Repelling pastel ambient light spheres, dynamic ripple wave rings on movement, smooth pill-shaped link buttons, and sparkle trail cursor.

### 4. Minimalist Monochromatic (`index3.html`)
* **Vibe:** High-end, clean editorial.
* **Features:** Charcoal canvas with constellation node connections, subtle SVG noise texture overlay, golden star glitter cursor, and top-right anchored audio toggle.

### 5. Retro Arcade / Pixel Synth (`index4.html`)
* **Vibe:** 80s synthwave / retro gaming.
* **Features:** Synthwave sunset with moving perspective grid, CRT scanline overlay, synthesized Web Audio API 8-bit click sound effects, retro cassette tape UI, and 8-bit pixel cursor.

---

## 🛠️ How to Deploy for Free (GitHub Pages)

1. Create a public repository on [GitHub](https://github.com).
2. Push all five HTML files into the repository root.
3. Go to **Settings** > **Pages**.
4. Select the `main` (or `master`) branch as the source and click **Save**.
5. Your live profile collection will be published at `https://yourusername.github.io/repository-name/`.

---

## ⚙️ Customization Guide

* **Links:** Search for `class="link-btn"` in any `index*.html` file and update the `href` attribute to your personal URL.
* **Names & Bios:** Replace `"YOUR NAME"` and text arrays inside the `phrases` variable for the typewriter effect.
* **Audio Track:** Replace the `src="..."` URL inside the `<audio id="bg-audio">` tag with your own direct MP3 link.