<p align="center">
  <img src="https://avatars.githubusercontent.com/u/149110357?v=4" width="112" alt="Hitomatito avatar">
</p>

<h1 align="center">Hitomatito</h1>

<p align="center">
  <strong>Android &amp; Linux developer building tools for hardware that ships without them.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white">
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white">
  <img src="https://img.shields.io/badge/Bluetooth_LE-0082FC?style=flat-square&logo=bluetooth&logoColor=white">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black">
</p>

---

## About

I work at the intersection of software and hardware: Bluetooth LE reverse engineering, WiFi internals, ADB, HID, Linux kernel configuration, and device-specific quirks. I like turning *"there is no app for this"* into something people can install and use.

Most of my work is open source, local-first, and built around giving you full control over hardware you already own — no cloud, no accounts.

---

## 🔥 Main Projects

### [AmWF](https://github.com/Hitomatito/AmWF) &nbsp;·&nbsp; ⭐ 16 &nbsp;·&nbsp; 🍴 1

> **Monitor mode and packet injection on Snapdragon Android phones — no laptop, no terminal, no firmware rebuild.**

AmWF turns a rooted Qualcomm Snapdragon phone into a portable WiFi analysis tool. Enable monitor mode, verify hardware capabilities, and audit WPS security of your own routers — all from a clean, one-handed interface. No scripts, no leftover state, no internet permission.

<p align="center">
  <img src="https://img.shields.io/github/v/release/Hitomatito/AmWF?style=flat-square&label=release&color=0891b2">
  <img src="https://img.shields.io/badge/Android-7.0%2B-3DDC84?style=flat-square&logo=android&logoColor=white">
  <img src="https://img.shields.io/badge/Root-required-orange?style=flat-square">
  <img src="https://img.shields.io/badge/License-GPL--3.0-blue?style=flat-square">
</p>

**What it does:**
- 📡 Enables monitor mode on Qualcomm `con_mode` interface with one tap
- 🔍 Runs WPS Pixie Dust audits locally — no server, no account
- ✅ Hardware compatibility check before changing anything (chipset, driver, root, injection)
- 🔄 Restores WiFi automatically when done — no leftover state

`Kotlin` · `Android` · `Qualcomm` · `NDK` · `WiFi` · `Root` · `GPL-3.0`

---

### [RedmagicCooler](https://github.com/Hitomatito/RedmagicCooler)

> **Full BLE control for RedMagic magnetic coolers — fan, thermal automation, RGB, profiles — without the official app.**

RedmagicCooler reverse-engineers the Bluetooth LE protocol of RedMagic / Nubia magnetic coolers and exposes every feature from a native Material You Android app. Covers 8 cooler models across 6 generations, runs entirely on-device, and ships with a CI-tested release pipeline.

<p align="center">
  <img src="https://github.com/Hitomatito/RedmagicCooler/actions/workflows/ci.yml/badge.svg" alt="CI">
  <img src="https://img.shields.io/github/v/release/Hitomatito/RedmagicCooler?style=flat-square" alt="Latest release">
  <img src="https://img.shields.io/badge/Android-7.0%2B-3DDC84?style=flat-square&logo=android&logoColor=white">
  <img src="https://img.shields.io/badge/Kotlin-2.3-7F52FF?style=flat-square&logo=kotlin&logoColor=white">
  <img src="https://img.shields.io/badge/license-MIT-blue?style=flat-square">
</p>

**What it does:**
- 🌀 Manual fan control (0–100%) and automatic thermal mode with sensor-driven regulation
- 🌈 Full RGB control — rainbow, breathing, solid color, off
- 💾 Multiple saved cooler profiles — switch between devices instantly
- 🔗 Auto-reconnect with backoff after dropped BLE connections
- 📵 No internet permission, no telemetry, no accounts — fully local

| Generation | Model | Status |
| :---: | --- | --- |
| 1–4 | Dual-Core · Turbo · Magcooler · Heat Sink 4 Pro | Supported by UUID |
| 5 | Heat Sink 5 Pro | ✅ Hardware-tested |
| 5–6 | Heat Sink 5 · Heat Sink 6 · Heat Sink 6 Pro | Supported by UUID |

`Kotlin` · `Jetpack Compose` · `BLE` · `Material You` · `CI` · `MIT`

---

## More Projects

| Project | What it does | Stack |
| --- | --- | --- |
| [HardWire](https://github.com/Hitomatito/HardWire) | Hardware inspector for Android over local or USB/Wi-Fi ADB — 10 categories, SoC lookup, snapshots | `Kotlin` `Compose` `ADB` |
| [DualSense UI](https://github.com/Hitomatito/dualsenseUI) | GTK4 control center for DualSense & DualSense Edge on Linux — lightbar, triggers, audio, firmware | `Python` `GTK4` `Linux` |
| [Orbit](https://github.com/Hitomatito/Orbit) | Shows every file, service, and config an app leaves on Linux, then uninstalls it cleanly | `Rust` `CLI` |
| [tap-ducky](https://github.com/Hitomatito/tap-ducky) | Turns any rooted Android phone into a USB Rubber Ducky HID keystroke injector | `Dart` `Flutter` |
| [BitChord](https://github.com/Hitomatito/BitChord) | YouTube Music client with clean aesthetics inspired by Apple Music | `Kotlin` `Android` |
| [GamePulse HUD](https://github.com/Hitomatito/gamepulse_hud) | Real-time FPS, CPU/GPU temp, and memory overlay for Android games | `Kotlin` `Android` |
| [vili-hitcore](https://github.com/Hitomatito/vili-hitcore) | Custom QGKI kernel for the Xiaomi 11T Pro (vili / SM8350) | `C` `Linux` |

## Toolbox

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![GTK4](https://img.shields.io/badge/GTK4-4A86CF?style=flat-square)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Bluetooth LE](https://img.shields.io/badge/Bluetooth_LE-0082FC?style=flat-square&logo=bluetooth&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)

## Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Hitomatito&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub Stats" height="165">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Hitomatito&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" height="165">
</p>

## Working style

Active: **AmWF** and **RedmagicCooler** are my primary focus right now. **HardWire**, **DualSense UI**, and **vili-hitcore** are ongoing. The rest is best-effort — issues and pull requests are welcome, but I cannot promise a timeline.

Everything listed here is public and buildable. Some work stays private.

## Contact

Open an issue in the relevant repository. That is the fastest route and keeps the answer public for the next person.

---

<sub>Last reviewed: November 2026 · Built in public, one hardware quirk at a time.</sub>
