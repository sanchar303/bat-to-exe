<div align="center">

<img src="./banner.svg" alt="BAT to EXE Converter" width="100%" />

<br />

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-0f172a?style=for-the-badge&logo=windows&logoColor=38bdf8)](https://github.com/sanchar303/bat-to-exe)
[![Dependencies](https://img.shields.io/badge/Dependencies-Zero%20External%20Tools-0f172a?style=for-the-badge&logo=powershell&logoColor=a78bfa)](https://github.com/sanchar303/bat-to-exe)
[![Workflow](https://img.shields.io/badge/Mode-Drag%20%26%20Drop-0f172a?style=for-the-badge&logo=gnubash&logoColor=34d399)](https://github.com/sanchar303/bat-to-exe)

<p>
  <strong>Compile Windows <code>.bat</code> scripts into standalone <code>.exe</code> executables natively—no third-party compilers, SDKs, or installations required.</strong>
</p>

[Explore More Projects](https://tr.ee/sanchar) • [YouTube](https://www.youtube.com/@sanchar888) • [Instagram](https://www.instagram.com/sanchar888) • [TikTok](https://www.tiktok.com/@s.koirala888) • [Snapchat](https://www.snapchat.com/add/s.koirala888) • [LinkedIn](https://lnkd.in/p/gYCmjJau)

</div>

---

### Core Capabilities

* **Instant Drag-and-Drop Compilation:** Drag any `.bat` file (such as `matrix.bat`) directly onto `build_exe.bat` to generate a matching `matrix.exe` in the same folder.
* **Automatic `favicon.png` Icon Embedding:** Detects `favicon.png` in the working directory and embeds it as the executable icon—cleanly omitting icon injection when absent.
* **Zero External Dependencies:** Uses built-in Windows `.NET` and PowerShell engines to assemble native executables out of the box.
* **Silent & Standalone Output:** Produces portable `.exe` binaries ready to share or run across Windows 10 and Windows 11 systems.

---

### Quick Start

1. Place **`build_exe.bat`** (and an optional **`favicon.png`**) in your project directory.
2. **Drag and drop** your target `.bat` script directly onto `build_exe.bat`, or run it from Command Prompt:
   ```bat
   build_exe.bat your_script.bat
