<div align="center">
  <a href="https://zzerodesigns.github.io/caromoku/">
    <img width="1440" height="900" alt="Caromoku Hero" src="https://github-production-user-asset-6210df.s3.amazonaws.com/141258233/647400220-b6ba5699-7659-4d0d-8520-55ebb136b474.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20260907%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20260907T164800Z&X-Amz-Expires=300&X-Amz-Signature=886d555bf764c5ab733a59afe1c43775537d5cdb9e5e8ff8cde36488aca30568&X-Amz-SignedHeaders=host&response-content-type=image%2Fpng" />
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
  <img width="1440" height="900" alt="Caromoku Gameplay Overview" src="https://github-production-user-asset-6210df.s3.amazonaws.com/141258233/647400216-e406c04b-6fde-4006-82fa-36fc471ea315.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20260907%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20260907T165144Z&X-Amz-Expires=300&X-Amz-Signature=c74ad656bcdf1fd6145c7cef53b853a334cdcc8912be22e0675e421b8d6fd764&X-Amz-SignedHeaders=host&response-content-type=image%2Fpng" />
  <br/><br/>
  <img width="1440" height="900" alt="Caromoku Dark Board" src="https://github-production-user-asset-6210df.s3.amazonaws.com/141258233/647400217-c3d647d9-e7b9-480c-89c3-94ea222ffedf.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20260907%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20260907T165159Z&X-Amz-Expires=300&X-Amz-Signature=2916c2d1b1648620826933648b743b5f0ecda6b77d64ef5d202933906e96dad8&X-Amz-SignedHeaders=host&response-content-type=image%2Fpng" />
  <br/><br/>
  <img width="1440" height="900" alt="Caromoku Board Style" src="https://github-production-user-asset-6210df.s3.amazonaws.com/141258233/647400219-78ac74a9-547f-4102-ba66-aba1f2a03463.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20260907%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20260907T165221Z&X-Amz-Expires=300&X-Amz-Signature=0c625d42429114c452242ce4089dee1a9349cfaba136bd109531f230a0871226&X-Amz-SignedHeaders=host&response-content-type=image%2Fpng" />
  <br/><br/>
  <img width="1440" height="900" alt="Caromoku Grid Presentation" src="https://github-production-user-asset-6210df.s3.amazonaws.com/141258233/647400221-9e7835d7-5ade-4f21-bcef-2237b811444d.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20260907%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20260907T165235Z&X-Amz-Expires=300&X-Amz-Signature=772912656d7a0e01812d1d5554ace430cb30877626338c8b135e99f10e201bc9&X-Amz-SignedHeaders=host&response-content-type=image%2Fpng" />
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
  <img width="1440" height="900" alt="Caromoku Theme Contrast" src="https://github-production-user-asset-6210df.s3.amazonaws.com/141258233/647400225-7964cabe-b392-4641-8439-3a6865b6a83d.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20260907%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20260907T165250Z&X-Amz-Expires=300&X-Amz-Signature=176fe1610a311121e2cd8ed17d88a2c99eead022e33dfbfc6893a258ea7498af&X-Amz-SignedHeaders=host&response-content-type=image%2Fpng" />
  <br/><br/>
  <img width="1440" height="900" alt="Caromoku Options & Settings" src="https://github-production-user-asset-6210df.s3.amazonaws.com/141258233/647400215-7a088642-d977-4b3b-881a-db5604326dd2.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20260907%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20260907T165301Z&X-Amz-Expires=300&X-Amz-Signature=e9bdaf94c8b24d22e0850207df4caf26720668ca07ebcb721eac22eb48dcf8a7&X-Amz-SignedHeaders=host&response-content-type=image%2Fpng" />
  <br/><br/>
  <img width="1440" height="900" alt="Caromoku Rules Modal" src="https://github-production-user-asset-6210df.s3.amazonaws.com/141258233/647400214-773e830e-abad-4c57-a6f2-2e631b49fa95.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20260907%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20260907T165316Z&X-Amz-Expires=300&X-Amz-Signature=5bb3f8268d4d9ef8744ba1099a8c6587d358c3645f997c26432df23600c4d63d&X-Amz-SignedHeaders=host&response-content-type=image%2Fpng" />
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
  <img width="1440" height="900" alt="Caromoku End Game State" src="https://github-production-user-asset-6210df.s3.amazonaws.com/141258233/647400218-de7cde2f-1ed4-4ecc-b352-bb8b97e56888.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20260907%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20260907T165349Z&X-Amz-Expires=300&X-Amz-Signature=212a3341ec8970f90d8802603dab008cf4aa5ca5900d4f7aae71664144268ec9&X-Amz-SignedHeaders=host&response-content-type=image%2Fpng" />
  <br/><br/>
  <img width="1440" height="900" alt="Caromoku Victory Highlight" src="https://github-production-user-asset-6210df.s3.amazonaws.com/141258233/647400223-50bfe397-f700-4d91-86c3-8596d116c4b4.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20260907%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20260907T165404Z&X-Amz-Expires=300&X-Amz-Signature=f97c77b0ae810cd00a1ae987e43afefd7a6f33efc107987709a21fc763a1bc7c&X-Amz-SignedHeaders=host&response-content-type=image%2Fpng" />
</div>

---

*Developed by zzerodesigns | Zero Assets, Pure Logic*
