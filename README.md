**Live Demo:** https://constantine-s-an.github.io/Nebula-Weaver/

# Nebula Weaver

Interactive WebGL starfield/nebula experience with bilingual UI, supernova bursts, and cursor-guided particle flow—all in a single HTML file.

## Features
- 15k animated particles with attraction/repulsion and velocity-based color shift.
- Cursor/touch steering plus click/long-press supernova bursts.
- Bilingual UI toggle (中文 / EN) for titles and instructions.
- Pure client-side: CDN Three.js (r128), no build or extra assets.
- Responsive canvas with fog, radial gradient sprites, and drag-based motion.

## Controls
- Move mouse/touch: guide the particle stream.
- Click or long-press (away from UI buttons): trigger a supernova-style explosion.
- Language button (top-right): toggle English/Chinese UI copy.

## Run Locally
1) Clone: `git clone https://github.com/Constantine-S-AN/Nebula-Weaver.git`
2) Serve (recommended): `cd Nebula-Weaver && python3 -m http.server 8000`
3) Open `http://localhost:8000` (or open `index.html` directly for a quick preview).

## Notes
- All visuals live in `index.html`; the only external dependency is CDN Three.js.
- After the first load, your browser cache can keep it working offline.
- Tweak particle count, colors, and forces via the `CONFIG` object in `index.html`.
- To adjust performance on low-power devices, lower `particleCount` or `particleSize`.
