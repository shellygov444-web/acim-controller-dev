# ACIM Controller

[![Release](https://img.shields.io/github/v/release/shellygov444-web/acim-controller-dev?color=blue)](https://github.com/shellygov444-web/acim-controller-dev/releases)
[![License](https://img.shields.io/badge/License-Proprietary-red.svg)](EULA.txt)
[![Platform](https://img.shields.io/badge/Platform-Windows_10%2F11-0078D6.svg)](https://www.microsoft.com/windows/)

> **Advanced Controller Input Mapper** - Professional-grade controller virtualization with intelligent touchpad modes and HID device management.

ACIM Controller is a Windows desktop application that transforms DualSense and other gamepads into versatile input devices. It features multi-mode touchpad support (absolute, relative, gesture, mouse emulation), controller hiding via HidHide integration, and real-time input profiling.

## ✨ Key Features

- **🎮 Multi-Mode Touchpad**: 3 distinct modes including absolute positioning, relative mouse, gesture recognition, and hybrid input.
- **🥷 Controller Hiding**: Built-in HidHide integration to hide physical controllers from games while preserving virtual input.
- **⚡ Real-time Profiles**: Switch configurations instantly without restarting applications.
- **🔧 Professional Calibration**: Per-device touchpad calibration with deadzone and sensitivity tuning.
- **🖥️ Windows Native**: Optimized for Windows 10/11 with Rust core for performance-critical input processing.

## 📦 What Gets Installed
The installer automatically handles:
* **HidHide Driver (v1.5.230.0)**: Required for controller hiding. Bundled offline, no download needed.
* **ACIM Core Service**: Rust-based input processing daemon.
* **ACIM UI**: Flutter frontend for configuration.

> **Note:** HidHide is mandatory for ACIM Controller to function. The installer includes it offline for reliability.

## 🚀 Quick Start
1.  **Download** the latest installer from [Releases](https://github.com/shellygov444-web/acim-controller-dev/releases).
2.  **Install** using the setup wizard (requires Administrator for driver installation).
3.  **Connect** your DualSense controller via USB or Bluetooth.
4.  **Launch** ACIM Controller from the Start Menu.
5.  **Game!** Your physical controller is hidden; the virtual controller takes over.

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
