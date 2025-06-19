# Ionity-AEDi-Initiation-Bash
Linux/Rpi Setup after OS with some needed software
# Project Alpha Installer Suite (Antwerp Designs Ionity)

![Formal Meta-Data Spec Poster](./image1) <!-- Image 1: Formal Meta-Data Spec Poster -->
![van Antwerp Design Logo](./image2)     <!-- Image 2: van Antwerp Design Logo -->

---

## Overview

**Project Alpha Installer Suite** is a universal, cross-platform system repair, AI/Dev/Design studio, and advanced installer toolkit. Designed and authored by **Johan Wilhelm van Antwerp** under **Antwerp Designs Ionity**, this suite embodies Policy 986 AED and is Creative Commons 4.0 licensed for non-commercial, internal, or educational use.  
It empowers users to repair, configure, deploy, and maintain advanced environments on Raspberry Pi, ARM, x86, and cloud/VM platforms—offline or online.

**Author:** Johan Wilhelm van Antwerp  
**Contact:** [johan@antwerpdesigns.com](mailto:johan@antwerpdesigns.com)  
**Policy:** AED Policy 986 applies (see `/docs/policy986.md`)

---

## Features

- 🚀 **Universal Installer:** Gnome, Microsoft, Pi, and ARM/AMD64 repair and full-stack install automation
- 🔧 **System Repair:** DPKG, APT, broken package, and kernel auto-detect/fix with logging and restore-points
- 🛡 **Security:** AI-assisted defense (Fail2Ban, Nmap, AIDE, Cockpit, Netdata, Wazuh, Thunderwall)
- 🤖 **AI/LLM Tools:** Offline LLMs (Gemini, DeepSeek, Ollama), Copilot CLI, backend debugging, code execution
- 📐 **Design Suite:** FreeCAD, GIMP, Krita, Inkscape, Blender, OpenSCAD, Kdenlive, and more
- 💻 **Dev Stack:** VSCode, Python, .NET 7/9, Node-RED, Docker, Azure CLI, VirtualBox
- 🌐 **Networking:** WireGuard, RaspAP, Pi-hole, SSH/SFTP/FTP, hostapd, dnsmasq, Netdata
- 📊 **Monitoring:** System health, battery, logs, ports, AI watchdog, restore points
- 📂 **Drive/Cloud:** Google Drive, OneDrive, Snap, cloud storage mounting
- 🏗 **Custom Launchers:** Integrated desktop launchers for all tools (see `/scripts/gnome-studio-setup`)
- 🎨 **Retro/Modern UI:** 8-bit neon theme, logo cursor, and tabbed GUI (HTML/JS/Py/Tkinter/Qt)
- 📝 **Comprehensive Docs:** Manuals, troubleshooting, logs, screenshots, policy/metadata embedded

---

## Getting Started

> **Recommended:** Use on Debian/Ubuntu, Raspberry Pi OS, or compatible ARM/x86 systems.

### 1. Clone the Installer Suite

```bash
git clone https://github.com/AntwerpDesignsIonity/instastall.git
cd instastall
```

### 2. Run the Main Installer (for bash)

```bash
chmod +x install.sh
./install.sh
```

### 3. Use the GUI (Python3/Tkinter)

```bash
python3 gui_main.py
```

### 4. (Advanced) Use the WebApp (offline/online HTML5/JS)

Open `index.html` in your browser or deploy as a PWA/Electron app.

---

## Core Pillars (Tabbed Layout)

- **Hardware:** GPIO, sensors, device info, drives, partitions, overlays, bootloader tools
- **Software:** All editors, IDEs, design and AI SDKs, APT/SNAP/Flatpak, update/upgrade
- **Monitor:** Live graphs, logs, system/battery stats, process/task manager, AI watchdog
- **Boot/Install:** Raspi-config, OS settings, pixel/underscan, camera, SSH, audio/HDMI, overlays, boot order
- **Update/Upkeep:** Update scripts, repair tools, cleanup, dependency managers, auto-debug
- **Recovery:** Restore points, backup, full DPKG/APT/Kernel repair, emergency scripts
- **Security:** Firewall, port scanner, SSL kill, Thunderwall, anti-overlay, clipboard lockdown
- **Network:** WiFi AP, RaspAP, Pi-hole, WireGuard, VPN, DNS, Netdata, Cockpit
- **Cloud/Drives:** Google Drive, OneDrive, Snap, local/cloud backup, SFTP/FTP
- **Dev/AI:** VSCode, .NET, Python, Node, Copilot CLI, LLM chatbots (Chatzy, AIDE, Owl AIEDi)
- **Help/Docs:** Manuals, screenshots, troubleshooting, guides, meta/policy/legal

---

## Sample Programs & Utilities

- `install.sh` — Full repair, update, and install script (bash)
- `whaledebug.sh` — System monitor, auto-restore, fault-finder with logging
- `gnome-studio-setup` — Automated CAD/Dev/AI/design desktop setup script
- `gui_main.py` — Tkinter/Qt GUI system monitor and repair launcher
- `policy986.md` — Full version of Antwerp Designs Policy 986 (embedded meta)
- `index.html` — Full offline webapp with retro/modern UI, tabbed tools, and code runner
- `raspi-config-helper.sh` — Raspi-config automation, overlays, pixel doubling, advanced boot

---

## Adding Programs & Contributions

> **Want to add more utilities?**  
Open an issue or PR with the utility, script, or package list.  
We welcome contributions that fit the mission of rapid system repair, dev toolkit, design, AI, security, or monitoring.

---

## Licensing & Policy

- **Author:** Johan Wilhelm van Antwerp (Antwerp Designs Ionity, Policy 986 AED)
- **License:** Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)
- **Trademark:** Tm², CC², All Rights Reserved as per Policy 986

> **Contact for commercial licensing, partnerships, or legal:**
> johanvanantwerp007@gmail.com | johan@antwerpdesigns.com | [ionity.world](https://ionity.world/)

---

## Logo & Branding

All logos and art © 2025 Johan Wilhelm van Antwerp / Antwerp Designs.  
See `image1` (Meta-Data Poster) and `image2` (van Antwerp Design Logo) above.

---

## Meta Data

- **Project:** AED-986.IO Universal Dev Installer
- **Date:** 2025-06-19
- **Owner:** Johan Wilhelm van Antwerp (ID: 9003135105083, Rustenburg, ZA)
- **Status:** Active, Policy 986, Master Policy enforced
- **Location:** Pretoria, Gauteng, South Africa
- **Means of Creation:** Digital, RPI, ARM, Linux, AI, cloud
- **Purpose:** System repair, dev/design/AI toolkit, secure installer, monitoring

---

## Credits

Johan Wilhelm van Antwerp — Author, Founder, Chief Engineer  
Gem (AI Assistant) — Co-Designer, Documentation  
Antwerp Designs Ionity — Platform & Ecosystem

---

## Inspirational Statement

> "Anything is possible with God."  
> — Antwerp Designs, Policy 986, 2018–2025

---

## Notices

- All scripts and tools are for internal, non-commercial, and educational use unless explicit written consent is provided.
- Policy 986 AED applies universally. See `/docs/policy986.md` for full legal and operational terms.

---

**For more info, see [ionity.world](https://ionity.world/) or contact the author.**
