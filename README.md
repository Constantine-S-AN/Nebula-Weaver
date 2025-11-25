**Live Demo:** https://constantine-s-an.github.io/Nebula-Weaver/

# Nebula Weaver

Interactive, bilingual WebGL nebula—15k particles with cursor-guided flow and supernova bursts, all in one HTML.

## What’s Inside
- 15k particles with attraction/repulsion, drag, and velocity-tinted color.
- Cursor/touch steering; click/long-press triggers a supernova burst.
- Bilingual UI toggle (中文 / EN) for titles and instructions.
- Pure client-side: CDN Three.js (r128); no build, no extra assets.
- Responsive canvas, fog, radial-sprite particles; single-file setup.

## Controls
- Move mouse/touch: guide the stream.
- Click or long-press (away from the lang button): fire a supernova.
- Language button (top-right): toggle English/Chinese UI text.

## Run Locally
1) Clone: `git clone https://github.com/Constantine-S-AN/Nebula-Weaver.git`
2) Serve (recommended): `cd Nebula-Weaver && python3 -m http.server 8000`
3) Open `http://localhost:8000` (or double-click `index.html` to preview).

## Mobile
- Works on modern mobile browsers; touch controls mirror mouse (drag to steer, tap/long-press to burst).
- For lower-power devices, reduce `particleCount`/`particleSize` in `CONFIG` to keep frame rates smooth.
- If the CDN is blocked, load once on Wi‑Fi to cache Three.js, then re-open offline.

## Customize
- All logic lives in `index.html`; Three.js comes from the CDN.
- Tune performance in the `CONFIG` object (e.g., `particleCount`, `particleSize`).
- After the first load, cached CDN assets let it keep working offline.
