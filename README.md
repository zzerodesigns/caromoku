<div align="center">
  <a href="https://zzerodesigns.github.io/caromoku/">
    <img width="1440" height="900" alt="Caromoku Hero" src="./assets/Screenshot%202026-09-07%20at%2022.34.25.png" />
  </a>
</div>

<div align="right"><sub><a href="https://caromoku.ai.studio/">Developed with AI Studio</a></sub></div>

# CAROMOKU: Cờ Caro / Gomoku

**Caromoku** is a unified board game engine bridging Vietnamese **Cờ Caro** and Japanese **Gomoku** within a strict **Single-File Architecture**. The entire application—including customizable rule presets, minimax heuristic AI, zero-allocation HTML5 Canvas rendering, and procedural Web Audio synthesis—is contained completely within a single `index.html` file.

---

## 🕹️ Play Now

### 1. Hosted Version (Web)
Play instantly in your browser via GitHub Pages or Google AI Studio:

# 👉 [zzerodesigns.github.io/caromoku](https://zzerodesigns.github.io/caromoku/) ⚔️
# 🌐 [caromoku.ai.studio](https://caromoku.ai.studio/)

### 2. Peak Performance & Offline Play (Local)
For the most responsive experience and instant input polling, you can **run the game locally** as a standalone file with zero internet connection required.

*   **Latest Build:** Download the raw `index.html` file from the root directory.
*   **Archived Versions:** Go directly to the `/archive/` folder. All previous versions are saved and versioned as standalone files (e.g., `v0.0.1.html`). Download any version and open it directly in your browser.
*   **Commit History (Alternative):** Navigate to any historical commit in the repository, open `index.html` at that point, and download it.

---

## 📸 Screenshots & Visual Modes

<div align="center">
  <img width="1440" height="900" alt="Caromoku Gameplay Overview" src="./assets/Screenshot%202026-09-07%20at%2022.34.48.png" />
  <br/><br/>
  <img width="1440" height="900" alt="Caromoku Dark Board" src="./assets/Screenshot%202026-09-07%20at%2022.34.54.png" />
  <br/><br/>
  <img width="1440" height="900" alt="Caromoku Board Style" src="./assets/Screenshot%202026-09-07%20at%2022.35.02.png" />
  <br/><br/>
  <img width="1440" height="900" alt="Caromoku Grid Presentation" src="./assets/Screenshot%202026-09-07%20at%2022.36.27.png" />
</div>

---

## 🛠️ Project Philosophies & Core Architecture

*   **Zero Dependencies & Single-File Architecture:** Built with pure vanilla HTML5 Canvas, modern JavaScript (ES6+), and CSS. No NPM packages, no build steps, and no bundling tools required to run.
*   **Unified Visual Styles:**
    *   **Gomoku Mode (Intersections):** Rendered on a satin Kaya wood grain board with realistic radial-gradient Black & White slate stones.
    *   **Cờ Caro Mode (Square Cells):** Rendered on a modern slate grid in Dark Theme or authentic graph notebook paper in Light Theme with high-contrast Crimson (X) and Azure (O) marks.
*   **Heuristic Minimax AI Engine:** Built-in intelligent computer opponent with multiple difficulty tiers, utilizing threat pattern detection (open-fours, split-threes, double-threes) and tactical lookaheads without lag or UI blocking.
*   **Procedural Web Audio Synthesis:** Zero external sound files (`.mp3` or `.wav`). All stone clicks, cell stamps, victory fanfares, and interface feedback tones are generated in real-time using the native Web Audio API oscillators and gain envelopes.
*   **Comprehensive Rule Sets:**
    *   **Vietnamese Caro (Two-End Blocked Rule):** 5-in-a-row blocked at both ends does not win; requires an open end or 6+ to claim victory.
    *   **Standard Gomoku:** Exactly 5 in a row wins.
    *   **Free-style Gomoku:** 5 or more continuous stones in a row wins.
    *   **Overline Restricted:** 5 in a row wins; 6+ stones is an overline and does not count as a win.
*   **Configurable Grid Scales:** Seamlessly toggle between **11×11 (Blitz)**, **15×15 (Standard)**, and **19×19 (Pro / Go Scale)** board sizes with automatic star point (Hoshi) positioning.

---

<div align="center">
  <img width="1440" height="900" alt="Caromoku Theme Contrast" src="./assets/Screenshot%202026-09-07%20at%2022.37.06.png" />
  <br/><br/>
  <img width="1440" height="900" alt="Caromoku Options & Settings" src="./assets/Screenshot%202026-09-07%20at%2022.38.57.png" />
  <br/><br/>
  <img width="1440" height="900" alt="Caromoku Rules Modal" src="./assets/Screenshot%202026-09-07%20at%2022.39.04.png" />
</div>

---

## 🎮 Controls & Shortcuts

*   **Left Click:** Place Stone / Draw Mark
*   **[U] or [Ctrl+Z]:** Undo Move
*   **[R] or [Enter]:** New Game / Reset Board
*   **[M]:** Toggle Visual Mode (Gomoku Intersections ↔ Cờ Caro Cells)
*   **[T]:** Toggle Theme (Dark Theme ↔ Light Theme)
*   **[S]:** Toggle Audio Synthesis (Mute / Unmute)
*   **[?] or [H]:** Open / Close Rule Presets & Guide Modal
*   **[Esc]:** Dismiss Modal / Banner

---

<div align="center">
  <img width="1440" height="900" alt="Caromoku End Game State" src="./assets/Screenshot%202026-09-07%20at%2022.40.43.png" />
  <br/><br/>
  <img width="1440" height="900" alt="Caromoku Victory Highlight" src="./assets/Screenshot%202026-09-07%20at%2022.41.25.png" />
</div>

---

*Developed by zzerodesigns | Zero Assets, Pure Logic*
