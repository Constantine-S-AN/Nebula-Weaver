**Live Demo:** https://constantine-s-an.github.io/Nebula-Weaver/

Nebula Weaver

Nebula Weaver is a WebGL-based interactive particle visualization experiment designed to create an immersive experience of holding a galaxy in your hands. Powered by Three.js, tens of thousands of particles simulate fluid physical movements, responding to user touch, mouse input, and device gyroscope data.

(Note: Replace this with your actual screenshot)

✨ Core Features

Stunning Visual Experience:

Real-time rendering of 15,000+ high-brightness particles.

Dynamic Color Temperature: Particle colors change in real-time based on movement speed, transitioning from deep silent blue (#0066ff) to blazing supernova gold (#ffaa00).

Additive Blending: Creates a neon-like, brilliant glowing effect.

Immersive Interaction:

Fluid Attraction: Particles move like a living school of fish, automatically following the trail of your mouse or finger.

Supernova Explosion: Long-press the screen or mouse to trigger a violent repulsive field, simulating the visual impact of a stellar explosion.

Gyroscope Control (Gravity Sensing):

Mobile Exclusive Experience: When enabled, simply tilt your phone to shift the gravitational core, just like pouring a galaxy in the palm of your hand.

Includes iOS permission handling and status indicators.

Multi-language Support:

Built-in English/Chinese toggle that updates UI text in real-time.

🎮 Controls Guide

Platform

Action

Effect

Desktop

Move Mouse

Guides the direction of the particle stream



Hold Left Click

Accumulates energy and triggers an explosion

Mobile

Touch & Drag

Guides the direction of the particle stream



Long Press

Triggers an explosion



Tilt Phone

(Requires enabling the top-left switch) Moves the gravitational core

⚠️ Note: Due to browser security policies, Gyroscope functionality requires an HTTPS environment to work correctly (except on localhost).

🛠️ Technical Implementation

Core Library: Three.js (r128)

Rendering Techniques:

Uses THREE.Points and THREE.BufferGeometry for high-performance particle rendering.

CanvasTexture dynamically generates radially gradient glowing textures without needing external image assets.

Physics Engine:

Custom Verlet integration physics simulation.

Includes attraction, repulsion, drag (friction), and Brownian motion noise.

Gyroscope Mapping: Maps deviceorientation event Beta/Gamma values to screen space coordinate offsets.

🚀 Quick Start

This project is structured as a single file, making deployment extremely simple.

Method 1: Local Preview

If you have VS Code installed, the Live Server extension is recommended:

Open the folder in VS Code.

Right-click index.html and select "Open with Live Server".

Ensure your phone and computer are on the same WiFi network, then visit http://ComputerIP:5500.

Method 2: Static Deployment

Upload index.html to any static web hosting service (HTTPS support required), such as:

GitHub Pages

Vercel

Netlify

Tiiny.host (Recommended for temporary testing)

📄 License

MIT License. Feel free to create more dazzling starry skies!