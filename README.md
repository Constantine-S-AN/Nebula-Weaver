**Live Demo:** https://constantine-s-an.github.io/Nebula-Weaver/

# Nebula Weaver

Interactive WebGL starfield/nebula experience with bilingual UI, supernova bursts, and cursor-guided particle flow—all in a single HTML file.

## Features
- 15,000 animated particles with attraction/repulsion and color-by-velocity.
- Click/hold to trigger supernova bursts; move cursor/touch to steer the flow.
- Bilingual interface toggle (中文 / EN) for title, subtitle, and instructions.
- No build step or external assets beyond CDN Three.js; runs entirely client-side.

## Controls
- Move mouse/touch: guide particle stream.
- Click or long-press (away from UI buttons): trigger a supernova-style explosion.
- Language button (top-right): toggle English/Chinese UI copy.

## Quick Start
1) Clone: `git clone https://github.com/Constantine-S-AN/Nebula-Weaver.git`
2) Serve locally (recommended):  
   `cd Nebula-Weaver && python3 -m http.server 8000`
3) Open `http://localhost:8000` (or open `index.html` directly for a quick preview).

## Notes
- All visuals are in `index.html` (Three.js r128 via CDN); no additional assets required.
- Works offline after first load of the CDN script if cached by your browser.
- Tweak particle counts, colors, and forces in `index.html` under the `CONFIG` object.
