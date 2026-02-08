# ACIM Controller

[![Release](https://img.shields.io/github/v/release/shellygov444-web/acim-controller-dev?include_prereleases&color=blue)](https://github.com/shellygov444-web/acim-controller-dev/releases)
[![License](https://img.shields.io/badge/License-Proprietary-red.svg )](EULA.txt)
[![Platform](https://img.shields.io/badge/Platform-Windows_10%2F11-0078D6.svg )](https://www.microsoft.com/windows/ )

> **Advanced Controller Input Mapper** - Professional-grade controller virtualization with intelligent touchpad modes and HID device management.

ACIM Controller is a Windows desktop application that transforms DualSense and other gamepads into versatile input devices. It features multi-mode touchpad support (tap click, click only, disable), controller hiding via HidHide integration, and real-time input profiling.

## ⚡ Performance

| Metric | Performance |
|--------|-------------|
| **Input Latency** | **0.02ms – 0.37ms** |
| **Memory Usage** | **15 – 25 MB RAM** |
| **Processing Core** | Rust (zero-overhead) |

**Verified by production logs:**

## ✨ Key Features

- **🎮 Multi-Mode Touchpad**: 3 distinct modes **Tap Click** (4-quadrant input), **Click Only** (legacy behavior), and **Disable** (touchpad off).
- **🥷 Controller Hiding**: Built-in HidHide integration to hide physical controllers from games while preserving virtual input.
- **⚡ Single Profile**: Save and load one configuration (multi-profile UI in development).
- **🔧 Deadzone Calibration**: Per-device calibration with functional backend (visual indicator alignment in progress).
- **🖥️ Windows Native**: Optimized for Windows 10/11 with Rust core for performance-critical input processing.

## 📦 What Gets Installed
The installer automatically handles:
* **HidHide Driver (v1.5.230.0)**: Required for controller hiding. Bundled offline, no download needed.
* **ACIM Core Service**: Rust-based input processing daemon.
* **ACIM UI**: Flutter frontend for configuration.

> **Note:** HidHide is mandatory for ACIM Controller to function. The installer includes it offline for reliability.

## 🚀 Quick Start
1.  **Download** the latest installer from [Releases](https://github.com/shellygov444-web/acim-controller-dev/releases ).
2.  **Install** using the setup wizard (requires Administrator for driver installation).
3.  **Connect** your DualSense controller via USB or Bluetooth.
4.  **Launch** ACIM Controller from the Start Menu.
5.  **Game!** Your physical controller is hidden; the virtual controller takes over.

## 🎮 DualSense Edge Support
ACIM Controller supports DualSense Edge paddle remapping with the following workflow:
* Assign face buttons (A/B/X/Y) to back paddles
* Remap freed face buttons to keyboard/mouse inputs
* **Note:** Paddle assignment removes that input from the original face button location
* **Requires:** USB connection for Edge detection

## 🎮 DualShock 4 Status
**Untested.** ACIM Controller uses standard HID protocols also found in DualShock 4, but we haven't validated compatibility. If you have a PS4 controller and want to test it, please report results in [Discord Server - Support](https://discord.gg/dnwYZhuk).

## 💬 Community & Support
Join our Discord community for support, feature requests, and bug reports: **[https://discord.gg/dnwYZhuk](https://discord.gg/dnwYZhuk)**

## ☕ Support the Project

If this application helps you achieve better performance, consider supporting the development! Tips help keep the lab running and allow for more frequent updates.

### 🏆 Supporter Perks
* **Tips of $5+** automatically grant you the **@Lab Supporter** role in our Discord!
* Exclusive access to development builds and beta features.

---

| Platform | Link/Address |
| :--- | :--- |
| **Main Support** | [**Support on Ko-fi**](https://ko-fi.com/controllerlab/tip) |
| **Discord Help** | [**Join the Server**](https://discord.gg/tXB8Dbbf) |

### ₿ Crypto Donations (Direct)
These are my official verified addresses from the **Controller Lab Portfolio**:

* **Bitcoin (BTC):** `bc1qwfxqvgfc0grdp9xmkuduqrx3qlg249569g8qf5`
* **Ethereum (ETH):** `0x13B4961Acc67Cf8eDc7Dc522daa33De8AFEbc2e1`
* **Solana (SOL):** `3E2j8w4rNndVMjdhcmJPh7AFc1yK5p7arH5Vjn8xTZwC`

---

## 📄 License
**ACIM Controller** is proprietary software. See `EULA.txt` for details.

**Third-Party Components:**
* HidHide by Nefarius - *BSD-3-Clause*
* Flutter - *BSD 3-Clause*
* Rust - *MIT/Apache 2.0*

## 🙏 Acknowledgments
* **Nefarius** for HidHide - making controller hiding possible on Windows.
* **DS4Windows community** for HID protocol documentation.
* **Flutter Desktop team** for the Windows embedder.

---
© 2026 ACIM Systems. All rights reserved.
