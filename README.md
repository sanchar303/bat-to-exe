<div align="center">

<img src="favicon.png" width="76" height="76" alt="BAT to EXE Converter" />

# BAT to EXE Converter

**Zero-dependency Windows `.bat` to `.exe` compiler + standalone desktop utilities.**

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-0ea5e9?style=flat-square&logo=windows&logoColor=white)](https://github.com/sanchar303/bat-to-exe)
[![Dependencies](https://img.shields.io/badge/Dependencies-None%20(Native%20.NET)-22c55e?style=flat-square)](https://github.com/sanchar303/bat-to-exe)
[![GitHub Pages](https://img.shields.io/badge/Web%20Portal-Live-38bdf8?style=flat-square&logo=githubpages&logoColor=white)](https://github.com/sanchar303/bat-to-exe/deployments)
[![Author](https://img.shields.io/badge/By-Sanchar%20Koirala-1e293b?style=flat-square)](https://github.com/sanchar303)

[Download Converter](./bat_to_exe_converter.exe) · [How It Works](#how-it-works) · [Companion Tools](#more-standalone-tools) · [Repository Layout](#repository-structure)

</div>

---

## Overview

`bat_to_exe_converter.exe` turns any Windows batch script (`.bat`) into a portable, standalone executable (`.exe`) without installing third-party compilers, SDKs, or runtimes. It compiles directly using the `.NET` C# compiler and imaging libraries already built into Windows 10 and Windows 11.

This repository also hosts the live **GitHub Pages** download portal (`index.html`) alongside four standalone, single-binary Windows utilities you can grab and run immediately.

---

## Quick Start

1. **Download** [`bat_to_exe_converter.exe`](./bat_to_exe_converter.exe) and place it in any folder on your Windows PC.
2. **Add an icon (optional):** Drop a PNG named `favicon.png` into the same folder as your `.bat` file or `bat_to_exe_converter.exe`. If no `favicon.png` is present, it compiles cleanly with the default Windows executable icon.
3. **Drag and drop:** Drag any `.bat` file directly onto `bat_to_exe_converter.exe`.

A matching `.exe` (for example, `script.bat` → `script.exe`) is generated immediately in the same directory.

---

## How It Works

| Capability | Behavior |
| :--- | :--- |
| **Native Compilation** | Invokes the built-in Windows `.NET` C# toolchain (`csc.exe`)—no Python, Node.js, or external wrappers required. |
| **Auto-Matched Output** | Preserves your source filename and outputs the compiled `.exe` right next to the original `.bat`. |
| **Multi-Size Icon Embedding** | Automatically converts `favicon.png` into a crisp multi-resolution Windows `.ico` resource when present. |
| **Argument Forwarding** | Dragging files or folders onto your newly compiled `.exe` forwards all `%*` command-line arguments to your batch script intact. |

---

## More Standalone Tools

Every utility below is pre-compiled, portable, and ready to run on Windows 10 / 11 with zero setup:

| Tool | Binary | What It Does |
| :--- | :--- | :--- |
| **Live Size Monitor** | [`live_size.exe`](./live_size.exe) | Drag any file or folder onto it to monitor real-time size, write speed, net delta, and disk I/O activity inside a live console HUD. |
| **Hyper-Extract Studio** | [`archive.exe`](./archive.exe) | Multi-threaded archiving and extraction engine built for packing large directories and extracting heavy archives fast. |
| **NetPulse Command** | [`network.exe`](./network.exe) | Real-time network command center to track live throughput, reveal saved Wi-Fi passwords, export PNG Wi-Fi QR codes, host custom hotspots, and scan LAN devices. |
| **Piano** | [`piano.exe`](./piano.exe) | Zero-latency 88-key polyphonic studio piano with 6 built-in instrument presets, live chord detection, sustain pedal, and auto-shifting keyboard shortcuts across every octave. |

---

## Repository Structure

```text
bat-to-exe/
├── bat_to_exe_converter.exe   # Primary drag-and-drop BAT to EXE compiler
├── live_size.exe              # Real-time file/folder size & I/O HUD monitor
├── archive.exe                # Hyper-Extract Studio multi-threaded archiver
├── network.exe                # NetPulse Command network & Wi-Fi utility
├── piano.exe                  # 88-key low-latency polyphonic studio piano
├── index.html                 # Single-file web download portal (GitHub Pages)
├── favicon.png                # Site icon & default .exe icon asset
├── CNAME                      # Custom domain configuration for GitHub Pages
└── google450a35d41fc058df.html # Google Search Console site verification
```

---

## Running Unsigned Executables on Windows

Because these binaries are lightweight, self-compiled standalone `.exe` tools without a paid commercial EV certificate, **Windows Defender SmartScreen** may show a *"Windows protected your PC"* prompt on first run.

To launch:
1. Click **More info**.
2. Click **Run anyway**.

---

<div align="center">

Built by **[Sanchar Koirala](https://github.com/sanchar303)**

</div>
