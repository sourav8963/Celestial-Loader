# Celestial Loader 🚀✨

> A visually stunning, highly detailed cosmic loading screen featuring realistic celestial mechanics, procedural SVG textures, and an interactive HTML5 Canvas deep space background. 

This project is a single-file, zero-dependency (aside from Tailwind CSS via CDN) web animation that simulates a rocket's journey while a realistic Earth orbits a burning Sun. It's perfect for use as a creative loading screen for web applications, portfolios, or games.

---

## 🌟 Features

* **Procedural Celestial Bodies:** * **The Sun:** Smoldering plasma turbulence created using CSS radial gradients and SVG `<feTurbulence>`.
  * **The Earth:** Features a precise 29% land ratio generated via thresholding on seamlessly stitched noise, topped with independently moving cloud layers.
  * **The Moon:** Highly detailed, pockmarked crater noise that accurately orbits the Earth.
* **Realistic Orbital Mechanics:** The Earth orbits the Sun, and the Moon orbits the Earth using synced CSS animations and JavaScript calculations linked to the loading progress.
* **Deep Space Canvas:** * **Dynamic Particles:** Generates stars, drifting spatial dust, and dynamic sun sparks.
  * **Smart Meteors:** Features procedurally generated "uneven rock" meteors with fiery trails that are programmed with a "safe zone" to avoid colliding with the Earth and Moon.
  * **Fast Shooting Stars:** Occasional fast-moving streaks across the deep black background.
* **Animated Progress Bar:** * Features a highly detailed, custom SVG rocket with animated fire exhaust.
  * Leaves behind a dynamic "cloudy trail" powered by SVG displacement maps (`<feDisplacementMap>`).
  * Smooth 20-second simulated loading sequence.

---

## 🛠️ Technologies Used

* **HTML5:** Semantic structure and `<canvas>` integration.
* **Tailwind CSS:** Utility-first styling (imported via CDN for rapid layout alignment).
* **Vanilla CSS3:** Advanced `@keyframes`, `mix-blend-mode`, and complex layered styling for planetary bodies.
* **Vanilla JavaScript:** Frame-by-frame Canvas rendering, particle physics, and progress bar timekeeping.
* **SVG Filters:** Heavy use of `<feTurbulence>`, `<feColorMatrix>`, and `<feGaussianBlur>` to generate realistic terrain and weather patterns natively without external image assets.

---

## 🚀 Getting Started

Since this is a standalone file, no complex build tools or package managers are required.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/celestial-loader.git](https://github.com/yourusername/celestial-loader.git)
