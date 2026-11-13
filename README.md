<div align="center">

```
  ██╗  ██╗██╗████████╗ ██████╗ ███╗   ███╗ █████╗ ████████╗██╗████████╗ ██████╗
  ██║  ██║██║╚══██╔══╝██╔═══██╗████╗ ████║██╔══██╗╚══██╔══╝██║╚══██╔══╝██╔═══██╗
  ███████║██║   ██║   ██║   ██║██╔████╔██║███████║   ██║   ██║   ██║   ██║   ██║
  ██╔══██║██║   ██║   ██║   ██║██║╚██╔╝██║██╔══██║   ██║   ██║   ██║   ██║   ██║
  ██║  ██║██║   ██║   ╚██████╔╝██║ ╚═╝ ██║██║  ██║   ██║   ██║   ██║   ╚██████╔╝
  ╚═╝  ╚═╝╚═╝   ╚═╝    ╚═════╝ ╚═╝     ╚═╝╚═╝  ╚═╝   ╚═╝   ╚═╝   ╚═╝    ╚═════╝
```

**Android · Linux · Hardware**

*Building software for the hardware gap —*  
*the space between what your device can do and what any app lets you do.*

</div>

---

## About

I work where software meets hardware: Bluetooth LE protocol reverse engineering, WiFi internals, kernel configuration, ADB, and HID. The common thread is control — giving users access to capabilities their devices have but manufacturers don't expose.

Everything I ship is open source, local-first, and runs without accounts or internet permissions.

---

## Primary Work

Two projects in active development. Both are rooted in the same idea: your hardware is capable of more than its official software allows.

<br>

**[AmWF](https://github.com/Hitomatito/AmWF)**
&nbsp;&nbsp;
[![release](https://img.shields.io/github/v/release/Hitomatito/AmWF?style=flat-square&label=release&color=0891b2)](https://github.com/Hitomatito/AmWF/releases)
[![stars](https://img.shields.io/github/stars/Hitomatito/AmWF?style=flat-square&color=f4a261)](https://github.com/Hitomatito/AmWF/stargazers)
[![license](https://img.shields.io/badge/GPL--3.0-blue?style=flat-square)](https://github.com/Hitomatito/AmWF/blob/main/LICENSE)

Monitor mode and WPS Pixie Dust auditing on rooted Qualcomm Snapdragon phones — from a clean Android UI, without a terminal or laptop. AmWF uses the Qualcomm `con_mode` interface and a patched `wpa_supplicant` to enable monitor mode and packet injection without touching firmware. Hardware is verified before anything changes; WiFi is restored automatically when done.

```
Android 7.0+   ·   Kotlin / NDK   ·   Qualcomm Snapdragon   ·   Root required
```

<br>

**[RedmagicCooler](https://github.com/Hitomatito/RedmagicCooler)**
&nbsp;&nbsp;
[![CI](https://github.com/Hitomatito/RedmagicCooler/actions/workflows/ci.yml/badge.svg)](https://github.com/Hitomatito/RedmagicCooler/actions/workflows/ci.yml)
[![release](https://img.shields.io/github/v/release/Hitomatito/RedmagicCooler?style=flat-square)](https://github.com/Hitomatito/RedmagicCooler/releases/latest)
[![license](https://img.shields.io/badge/MIT-blue?style=flat-square)](https://github.com/Hitomatito/RedmagicCooler/blob/main/LICENSE)

Full BLE control for RedMagic / Nubia magnetic coolers — fan speed, automatic thermal regulation, RGB lighting, and saved profiles — without the official app. The BLE protocol was reverse-engineered from scratch. Supports 8 cooler models across 6 generations, identified by manufacturer data in the scan record. Runs entirely on-device: no internet permission, no telemetry.

```
Android 7.0+   ·   Kotlin 2.3   ·   Jetpack Compose   ·   BLE   ·   Material You
```

---

## Other Projects

| | |
|---|---|
| [HardWire](https://github.com/Hitomatito/HardWire) | Hardware inspector for Android over local or USB/Wi-Fi ADB. Ten hardware categories, SoC lookup, device comparison, and history snapshots. |
| [DualSense UI](https://github.com/Hitomatito/dualsenseUI) | GTK4 control center for DualSense and DualSense Edge on Linux. Lightbar, adaptive triggers, audio, battery, and firmware. Ships as `.deb`, `.rpm`, and Flatpak. |
| [Orbit](https://github.com/Hitomatito/Orbit) | Tracks every file, service, and config an app registers on Linux, then removes all of it cleanly. |
| [tap-ducky](https://github.com/Hitomatito/tap-ducky) | Turns any rooted Android phone into a USB HID keystroke injector — the Rubber Ducky, in your pocket. |
| [vili-hitcore](https://github.com/Hitomatito/vili-hitcore) | Custom QGKI kernel for the Xiaomi 11T Pro (vili / SM8350). |
| [GamePulse HUD](https://github.com/Hitomatito/gamepulse_hud) | Real-time FPS, CPU/GPU temperature, and memory overlay for Android games. |
| [BitChord](https://github.com/Hitomatito/BitChord) | YouTube Music client with clean aesthetics inspired by Apple Music. |

---

## Stack

<div align="center">

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)
![Bluetooth LE](https://img.shields.io/badge/Bluetooth_LE-0082FC?style=flat-square&logo=bluetooth&logoColor=white)
![GTK4](https://img.shields.io/badge/GTK4-4A86CF?style=flat-square)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

</div>

---

## Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Hitomatito&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" height="160">
&nbsp;&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Hitomatito&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" height="160">

</div>

---

**AmWF** and **RedmagicCooler** are my primary focus. Everything else is best-effort — issues and pull requests are welcome.

Open an issue in the relevant repository to get in touch. That is the fastest path, and it keeps the answer public for whoever comes next.

---

<div align="right">
<sub>Last updated November 2026</sub>
</div>
