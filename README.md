# Orbit Balance Game

A sleek, fast-paced minimalist mobile web game prototype.

🎮 **Live Playable Link:** https://orbit-balance-game.vercel.app/

---

## 💡 Concept & Core Loop
**Orbit Balance** is a casual arcade experience inspired by minimalist mobile design:
* **The Mechanic:** The player controls an orb in circular orbit around a central ring.
* **One-Touch Controls:** Tapping or clicking anywhere on the screen instantly reverses the orbit direction.
* **The Objective:** Catch incoming blue energy orbs to score points while avoiding hazardous red obstacles.
* **Game Feel:** Features responsive procedural particle bursts, dynamic speed scaling, and built-in synthesizer sound effects using the native browser Web Audio API (zero external assets).

---

## 🛠️ Tech Stack & Architecture
* **Single-file Architecture:** Pure HTML5, CSS3, and modern JavaScript (`index.html`) for ultra-fast load times and zero dependency overhead.
* **HTML5 Canvas 2D:** High-performance render loop running at 60 FPS via `requestAnimationFrame`.
* **Procedural Audio:** Native Web Audio API synthesizer generating dynamic frequencies on the fly.
* **State Persistence:** Best score saved locally via `localStorage`.
* **Deployment:** Hosted live on Vercel with automated GitHub integration.



## 🚀 How to Run Locally
Clone this repository or download the `index.html` file
