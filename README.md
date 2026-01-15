# PAPI.IO - Undetectable Hardware Mouse Jiggler & Anti-AFK Solution

![PAPI.IO Device](https://papiio.com/img/tespit-edilemez-mouse-jiggler-donanim-papiio.jpg)

[![Firmware](https://img.shields.io/badge/Firmware-V8.0-success)](https://papiio.com)
[![Status](https://img.shields.io/badge/Status-Undetectable-brightgreen)](https://papiio.com)
[![Hardware](https://img.shields.io/badge/Hardware-HID%20Compliant-blue)](https://papiio.com)
[![License](https://img.shields.io/badge/License-Proprietary-red)](https://papiio.com)

## 🏗️ Project Overview

**PAPI.IO** is a sophisticated hardware-based solution designed to prevent computer sleep, maintain "Active" status on communication platforms (Teams, Slack, Discord), and bypass intrusive employee monitoring software (Berqun, Hubstaff, Teramind).

Unlike software-based mouse jigglers (`.exe` scripts) that are easily detected by IT departments and EDR systems, PAPI.IO operates entirely at the **Physical Layer (Layer 1)**. It emulates a standard USB Human Interface Device (HID), making it indistinguishable from a physical keyboard or mouse.

👉 **Official Website:** [papiio.com](https://papiio.com)

---

## ⚙️ Technical Architecture

PAPI.IO is engineered with a **"Security First"** approach. It does not require drivers, software installation, or administrative privileges.

### 1. HID Emulation Protocol
The device utilizes a microcontroller unit (MCU) programmed to mimic the VID/PID (Vendor ID / Product ID) of standard peripherals (e.g., Logitech, Microsoft). 
- **System Recognition:** Detected as `HID-compliant mouse` or `USB Input Device`.
- **Driver Requirement:** None (Uses generic OS drivers).

### 2. Stochastic Movement Algorithm (Chaos Theory)
To defeat AI-based behavioral analysis used by monitoring tools, PAPI.IO avoids repetitive patterns.
- **Bezier Curves:** Mouse movements follow natural, curved paths rather than robotic straight lines.
- **RNG Timing:** Click intervals and movement durations are randomized using stochastic algorithms.
- **Bio-Rhythm Engine:** The firmware includes a "Human Mode" that simulates micro-pauses and random "coffee breaks" to mimic natural human behavior.

### 3. One-Way Data Flow (Air-Gap)
Security is guaranteed by hardware design limitations.
- **Write-Only:** The device can only send keystrokes/mouse inputs to the host PC.
- **No Read Capability:** It cannot read data, files, or screen content from the computer.
- **Virus Proof:** Since it lacks storage mounting capabilities, it cannot transmit malware or exfiltrate data.

---

## 🛡️ Detection Analysis

| Detection Method | Software Jigglers (.exe) | Mechanical Jigglers | **PAPI.IO Hardware** |
| :--- | :---: | :---: | :---: |
| **Process List Scan** | ❌ DETECTED | ✅ SAFE | **✅ SAFE** |
| **IT Logs / Registry** | ❌ DETECTED | ✅ SAFE | **✅ SAFE** |
| **Heuristic / AI Analysis** | ❌ DETECTED | ⚠️ SUSPICIOUS | **✅ UNDETECTED** |
| **Device Manager** | N/A | N/A | **✅ "HID Keyboard"** |

---

## 🚀 Operating Modes

The V8.0 Firmware supports multiple operation modes manageable via a local Wi-Fi interface (Offline Network).

### 🏢 Office Mode (Ghost)
Designed for corporate environments.
- Keeps Teams/Slack status green.
- Uses micro-movements (1px jitter) or wide-range activity.
- **Feature:** `Smart Zeroing` (Returns cursor to original position).

### 🎮 Gamer Mode
Designed to bypass Anti-Cheat systems (Vanguard, EAC, BattlEye).
- **HWID Spoofing:** Masquerades as a gaming keyboard.
- **Anti-AFK:** Prevents being kicked from lobbies.
- **No Injection:** Since it does not inject code into the game memory, it is safe from memory scanners.

### 📱 Remote Control Mode
Turns your smartphone into a physical peripheral controller.
- Virtual Trackpad & Keyboard.
- Media Controls (Netflix/Spotify).

---

## 🔌 Setup & Usage

PAPI.IO operates on a "Plug & Forget" basis.

1.  **Connect:** Plug the device into any USB port (or wall charger).
2.  **Access:** Connect to the `PAPI_SECURE` Wi-Fi network using your phone.
3.  **Control:** Navigate to `192.168.4.1` in your browser.
4.  **Disconnect:** Once the mode is set, you can disconnect your phone. The device runs autonomously on its own processor.

---

## ⚠️ Disclaimer

This project is developed as a tool for **Digital Sovereignty** and **Privacy**. It is intended to protect users from invasive surveillance practices and "Bossware" that violate personal privacy rights.

The developer advocates for result-oriented work cultures rather than surveillance-based micromanagement.

---

## 📞 Contact & Support

This is a proprietary hardware project. Source code is closed to prevent patching by monitoring companies.

- **Developer:** Yücelerden (Mechatronics Engineer)
- **Purchase:** [papiio.com](https://papiio.com)
- **Support:** [WhatsApp Direct Line](https://wa.me/905374309260)

© 2024 PROGISY TECHNOLOGY INC. All rights reserved.
