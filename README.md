<div align="center">

<a href="https://github.com/sanchar303/bat-to-exe" title="BAT to EXE Converter — Native Windows .bat to .exe Compiler">
  <img src="./banner.svg" alt="BAT to EXE Converter" width="100%" />
</a>

<br />

<a href="https://github.com/sanchar303/bat-to-exe" title="Native Windows Compilation Pipeline">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=15&duration=2600&pause=850&color=38BDF8&center=true&vCenter=true&width=720&lines=Drag+%26+Drop+.bat+to+.exe+Compiler+for+Windows+10+%26+11;Zero+Third-Party+SDKs+%E2%80%A2+Pure+Windows+.NET+%26+PowerShell+Engine;Auto-Detects+favicon.png+for+Custom+Executable+Icons;Standalone+Portable+Binaries+in+One+Click" alt="Terminal Telemetry" />
</a>

<br />

<a href="https://github.com/sanchar303/bat-to-exe" title="Supported Operating Systems: Windows 10 & Windows 11">
  <img src="https://img.shields.io/badge/PLATFORM-WINDOWS%2010%20%7C%2011-0B1120?style=for-the-badge&logo=windows&logoColor=38BDF8" alt="Windows 10/11" />
</a>
<a href="https://github.com/sanchar303/bat-to-exe" title="Compiles using stock Windows .NET & PowerShell">
  <img src="https://img.shields.io/badge/RUNTIME-ZERO%20DEPENDENCIES-0B1120?style=for-the-badge&logo=powershell&logoColor=A78BFA" alt="Zero Dependencies" />
</a>
<a href="https://github.com/sanchar303/bat-to-exe" title="Supports drag-and-drop and CLI arguments">
  <img src="https://img.shields.io/badge/WORKFLOW-DRAG%20%26%20DROP-0B1120?style=for-the-badge&logo=gnubash&logoColor=34D399" alt="Drag and Drop" />
</a>
<a href="https://tr.ee/sanchar" title="Explore all web apps & builds on Linktree">
  <img src="https://img.shields.io/badge/HUB-TR.EE%2FSANCHAR-0B1120?style=for-the-badge&logo=linktree&logoColor=43E660" alt="Linktree Hub" />
</a>

<br /><br />

<a href="https://tr.ee/sanchar" title="Linktree — All Projects & Links">
  <img src="https://img.shields.io/badge/Linktree-0F172A?style=flat-square&logo=linktree&logoColor=43E660" alt="Linktree" />
</a>
<a href="https://lnkd.in/p/gYCmjJau" title="Connect on LinkedIn">
  <img src="https://img.shields.io/badge/LinkedIn-0F172A?style=flat-square&logo=linkedin&logoColor=0A66C2" alt="LinkedIn" />
</a>
<a href="https://www.youtube.com/@sanchar888" title="YouTube — @sanchar888">
  <img src="https://img.shields.io/badge/YouTube-0F172A?style=flat-square&logo=youtube&logoColor=FF0000" alt="YouTube" />
</a>
<a href="https://www.instagram.com/sanchar888" title="Instagram — @sanchar888">
  <img src="https://img.shields.io/badge/Instagram-0F172A?style=flat-square&logo=instagram&logoColor=E4405F" alt="Instagram" />
</a>
<a href="https://www.tiktok.com/@s.koirala888" title="TikTok — @s.koirala888">
  <img src="https://img.shields.io/badge/TikTok-0F172A?style=flat-square&logo=tiktok&logoColor=00F2FE" alt="TikTok" />
</a>
<a href="https://www.snapchat.com/add/s.koirala888" title="Snapchat — s.koirala888">
  <img src="https://img.shields.io/badge/Snapchat-0F172A?style=flat-square&logo=snapchat&logoColor=FFFC00" alt="Snapchat" />
</a>
<a href="https://github.com/sanchar303" title="GitHub — @sanchar303">
  <img src="https://img.shields.io/badge/GitHub-0F172A?style=flat-square&logo=github&logoColor=F8FAFC" alt="GitHub" />
</a>

</div>

---

### Core Architecture

**`build_exe.bat`** turns standard Windows batch scripts into standalone **`.exe`** executables using Windows' built-in `.NET` and PowerShell compilation stack—no external compilers, no IExpress popups, and no third-party runtimes.

<table>
  <tr>
    <td width="50%" valign="top">
      <strong>Drag-and-Drop Compilation</strong><br /><br />
      Drop any script (e.g., <code>matrix.bat</code>) directly onto <code>build_exe.bat</code> in File Explorer. It packages the payload and writes <code>matrix.exe</code> straight into the same directory.
    </td>
    <td width="50%" valign="top">
      <strong>Automatic <code>favicon.png</code> Embedding</strong><br /><br />
      Place a <code>favicon.png</code> file beside <code>build_exe.bat</code> and it automatically converts and injects it as the <code>.exe</code> icon. If no icon file is present, compilation proceeds cleanly without icon injection.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong>Stock Windows Execution</strong><br /><br />
      Relies strictly on native Windows components present on Windows 10 and Windows 11. Output executables run standalone on target machines with zero setup.
    </td>
    <td width="50%" valign="top">
      <strong>Direct CLI Invocation</strong><br /><br />
      Trigger builds directly from Command Prompt, PowerShell, or automated scripts:<br />
      <code>build_exe.bat your_script.bat</code>
    </td>
  </tr>
</table>

<details>
  <summary><strong>Quick Start &amp; Terminal Usage</strong></summary>
  <br />

  1. Place **`build_exe.bat`** (and an optional **`favicon.png`**) in your working directory.
  2. **Drag and drop** your `.bat` file onto `build_exe.bat`, or press <kbd>Win</kbd> + <kbd>R</kbd>, open `cmd`, and run:
     ```bat
     build_exe.bat matrix.bat
     ```
  3. Launch the resulting **`matrix.exe`** directly from File Explorer or terminal.

</details>

---

### Windows Native Utility Suite

Standalone Windows tools built with the same zero-dependency philosophy:

| Utility | File | Capability | Build |
| :--- | :--- | :--- | :---: |
| **BAT to EXE Converter** | `build_exe.bat` | Drag-and-drop `.bat` to `.exe` compiler with automatic `favicon.png` icon embedding | ![Active](https://img.shields.io/badge/LIVE-0F172A?style=flat-square&color=10B981) |
| **Live Size Monitor** | `live_size.bat` | Real-time file and directory size telemetry readout on drag-and-drop | ![Active](https://img.shields.io/badge/LIVE-0F172A?style=flat-square&color=10B981) |
| **Hyper-Extract Studio** | `archive.bat` | Fast Windows archive extraction and compression utility | ![Active](https://img.shields.io/badge/LIVE-0F172A?style=flat-square&color=10B981) |
| **NetPulse Command** | `msfconsole.bat` | Upgraded Windows CLI console with `enc`/`dec` file encryption, `hash`, `watch`, and persistent macros | ![Active](https://img.shields.io/badge/LIVE-0F172A?style=flat-square&color=10B981) |
| **Desktop Piano** | `piano.exe` | Zero-latency standalone Windows GUI keyboard compiled from Batch | ![Active](https://img.shields.io/badge/LIVE-0F172A?style=flat-square&color=10B981) |

---

### Web Ecosystem & Linktree Directory

<table>
  <tr>
    <td width="40%" align="center" valign="middle">
      <a href="https://tr.ee/sanchar" title="Open Sanchar Koirala Linktree Directory">
        <img src="./preview.png" alt="Sanchar Koirala Linktree Preview" width="100%" />
      </a>
      <br /><br />
      <a href="https://tr.ee/sanchar" title="Visit tr.ee/sanchar">
        <img src="https://img.shields.io/badge/OPEN%20DIRECTORY-TR.EE%2FSANCHAR-38BDF8?style=for-the-badge&logo=linktree&logoColor=0B1120" alt="Open Linktree" />
      </a>
    </td>
    <td width="60%" valign="top">
      <strong>Featured Deployments</strong><br />
      <sub>Hover any badge for host details or click to launch:</sub>
      <br /><br />
      <table>
        <thead>
          <tr>
            <th align="left">Project</th>
            <th align="center">Host</th>
            <th align="center">Action</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td><strong>Play Mine</strong></td>
            <td align="center">Cloudflare Pages</td>
            <td align="center"><a href="https://play-mine.pages.dev" title="Open Play Mine on Cloudflare Pages"><img src="https://img.shields.io/badge/Launch-0F172A?style=flat-square&logo=cloudflare&logoColor=F38020" alt="Play Mine" /></a></td>
          </tr>
          <tr>
            <td><strong>Falas (फलास)</strong></td>
            <td align="center">Cloudflare Pages</td>
            <td align="center"><a href="https://falash.pages.dev" title="Open Falas on Cloudflare Pages"><img src="https://img.shields.io/badge/Launch-0F172A?style=flat-square&logo=cloudflare&logoColor=F38020" alt="Falas" /></a></td>
          </tr>
          <tr>
            <td><strong>Only Me Ted</strong></td>
            <td align="center">Cloudflare Pages</td>
            <td align="center"><a href="https://only-me-ted.pages.dev" title="Open Only Me Ted on Cloudflare Pages"><img src="https://img.shields.io/badge/Launch-0F172A?style=flat-square&logo=cloudflare&logoColor=F38020" alt="Only Me Ted" /></a></td>
          </tr>
          <tr>
            <td><strong>Aetheria</strong></td>
            <td align="center">Google Share</td>
            <td align="center"><a href="https://share.google/EAjJCYtv9BU0PWZma" title="Open Aetheria"><img src="https://img.shields.io/badge/Launch-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="Aetheria" /></a></td>
          </tr>
          <tr>
            <td><strong>UNC AI</strong></td>
            <td align="center">Netlify</td>
            <td align="center"><a href="https://unc-ai.netlify.app" title="Open UNC AI on Netlify"><img src="https://img.shields.io/badge/Launch-0F172A?style=flat-square&logo=netlify&logoColor=00C7B7" alt="UNC AI" /></a></td>
          </tr>
          <tr>
            <td><strong>The Citadel Node</strong></td>
            <td align="center">Netlify</td>
            <td align="center"><a href="https://the-citadel-node.netlify.app" title="Open The Citadel Node on Netlify"><img src="https://img.shields.io/badge/Launch-0F172A?style=flat-square&logo=netlify&logoColor=00C7B7" alt="The Citadel Node" /></a></td>
          </tr>
          <tr>
            <td><strong>Dell G15 Movies</strong></td>
            <td align="center">Web / APK / EXE</td>
            <td align="center"><a href="https://share.google/7hzZvSfqNjw9m8Dem" title="Open Dell G15 Movies"><img src="https://img.shields.io/badge/Launch-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="Dell G15 Movies" /></a></td>
          </tr>
        </tbody>
      </table>
    </td>
  </tr>
</table>

<br />

<details open>
  <summary><strong>Multiplayer, P2P &amp; Interactive Games</strong></summary>
  <br />

  | App | Platform | Direct Link |
  | :--- | :--- | :---: |
  | **Play Mine** | Cloudflare Pages | <a href="https://play-mine.pages.dev" title="play-mine.pages.dev"><img src="https://img.shields.io/badge/play--mine.pages.dev-0F172A?style=flat-square&logo=cloudflare&logoColor=F38020" alt="Play Mine" /></a> |
  | **Falas (फलास)** | Cloudflare Pages | <a href="https://falash.pages.dev" title="falash.pages.dev"><img src="https://img.shields.io/badge/falash.pages.dev-0F172A?style=flat-square&logo=cloudflare&logoColor=F38020" alt="Falas" /></a> |
  | **Only Me Ted** | Cloudflare Pages | <a href="https://only-me-ted.pages.dev" title="only-me-ted.pages.dev"><img src="https://img.shields.io/badge/only--me--ted.pages.dev-0F172A?style=flat-square&logo=cloudflare&logoColor=F38020" alt="Only Me Ted" /></a> |
  | **Cosmic Void** | Google Share | <a href="https://share.google/it8q8tYvuyck9krjQ" title="Open Cosmic Void"><img src="https://img.shields.io/badge/Open%20App-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="Cosmic Void" /></a> |
  | **P2P Games** | Cloudflare Pages / Share | <a href="https://p2p-ttt.pages.dev" title="p2p-ttt.pages.dev"><img src="https://img.shields.io/badge/p2p--ttt.pages.dev-0F172A?style=flat-square&logo=cloudflare&logoColor=F38020" alt="P2P Games" /></a> <a href="https://share.google/rBfcygjrgFAc0Lrt0" title="Mirror Link"><img src="https://img.shields.io/badge/Mirror-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="Mirror" /></a> |
  | **SK57 P2P** | Netlify | <a href="https://sk57-p2p.netlify.app" title="sk57-p2p.netlify.app"><img src="https://img.shields.io/badge/sk57--p2p.netlify.app-0F172A?style=flat-square&logo=netlify&logoColor=00C7B7" alt="SK57 P2P" /></a> |

</details>

<details>
  <summary><strong>AI, Cloud &amp; Developer Infrastructure</strong></summary>
  <br />

  | App | Platform | Direct Link |
  | :--- | :--- | :---: |
  | **Aetheria** | Google Share | <a href="https://share.google/EAjJCYtv9BU0PWZma" title="Open Aetheria"><img src="https://img.shields.io/badge/Open%20App-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="Aetheria" /></a> |
  | **UNC AI** | Netlify | <a href="https://unc-ai.netlify.app" title="unc-ai.netlify.app"><img src="https://img.shields.io/badge/unc--ai.netlify.app-0F172A?style=flat-square&logo=netlify&logoColor=00C7B7" alt="UNC AI" /></a> |
  | **NVIDIA AI** | Google Share | <a href="https://share.google/JLBJGCMYR8MaL2m1F" title="Open NVIDIA AI"><img src="https://img.shields.io/badge/Open%20App-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="NVIDIA AI" /></a> |
  | **UNC API** | Google Share | <a href="https://share.google/2orpDgwhPEC47e0Yj" title="Open UNC API"><img src="https://img.shields.io/badge/Open%20App-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="UNC API" /></a> |
  | **The Citadel Node** | Netlify / Share | <a href="https://the-citadel-node.netlify.app" title="the-citadel-node.netlify.app"><img src="https://img.shields.io/badge/the--citadel--node.netlify.app-0F172A?style=flat-square&logo=netlify&logoColor=00C7B7" alt="The Citadel Node" /></a> <a href="https://share.google/D06rD7kBRYKtDGZKz" title="Mirror Link"><img src="https://img.shields.io/badge/Mirror-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="Mirror" /></a> |
  | **Flash Server Deploy** | Google Share | <a href="https://share.google/NYTlgTzotC4HLoWvb" title="Open Flash Server Deploy"><img src="https://img.shields.io/badge/Open%20App-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="Flash Server Deploy" /></a> |
  | **Sanchar DB** | Google Share | <a href="https://share.google/91XLsxqgC3b4eavsU" title="Open Sanchar DB"><img src="https://img.shields.io/badge/Open%20App-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="Sanchar DB" /></a> |
  | **SK Authenticator** | Cloudflare Pages | <a href="https://sk-auth.pages.dev" title="sk-auth.pages.dev"><img src="https://img.shields.io/badge/sk--auth.pages.dev-0F172A?style=flat-square&logo=cloudflare&logoColor=F38020" alt="SK Authenticator" /></a> |
  | **SK FTP** | Cloudflare Pages | <a href="https://skftp.pages.dev" title="skftp.pages.dev"><img src="https://img.shields.io/badge/skftp.pages.dev-0F172A?style=flat-square&logo=cloudflare&logoColor=F38020" alt="SK FTP" /></a> |
  | **SK Control** | Google Share | <a href="https://share.google/3nkYhJf5SqS2th3Mt" title="Open SK Control"><img src="https://img.shields.io/badge/Open%20App-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="SK Control" /></a> |
  | **CloudM Nexus** | Cloudflare Pages | <a href="http://cloudm.pages.dev" title="cloudm.pages.dev"><img src="https://img.shields.io/badge/cloudm.pages.dev-0F172A?style=flat-square&logo=cloudflare&logoColor=F38020" alt="CloudM Nexus" /></a> |
  | **SK Embed** | Cloudflare Pages | <a href="https://sk-embed.pages.dev" title="sk-embed.pages.dev"><img src="https://img.shields.io/badge/sk--embed.pages.dev-0F172A?style=flat-square&logo=cloudflare&logoColor=F38020" alt="SK Embed" /></a> |
  | **PeerSync** | Google Share | <a href="https://share.google/uT3nd2ol5XBlPrTPT" title="Open PeerSync"><img src="https://img.shields.io/badge/Open%20App-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="PeerSync" /></a> |

</details>

<details>
  <summary><strong>Finance, POS &amp; Blockchain Systems</strong></summary>
  <br />

  | App | Platform | Direct Link |
  | :--- | :--- | :---: |
  | **SK Bank** | Android APK | <a href="https://github.com/sanchar303/data/raw/refs/heads/master/SK%20Bank_v1.0.0_20261109.apk" title="Download SK Bank v1.0.0 APK"><img src="https://img.shields.io/badge/Download%20APK-0F172A?style=flat-square&logo=android&logoColor=3DDC84" alt="SK Bank APK" /></a> |
  | **Project Economy** | Google Share | <a href="https://share.google/KaQCIS8F8IP6XgZoC" title="Open Project Economy"><img src="https://img.shields.io/badge/Open%20App-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="Project Economy" /></a> |
  | **8848 POS** | Google Share | <a href="https://share.google/D06rD7kBRYKtDGZKz" title="Open 8848 POS"><img src="https://img.shields.io/badge/Open%20App-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="8848 POS" /></a> |
  | **Chrono Wealth Vault** | Google Share | <a href="https://share.google/LtVTUu84eP6q6KsmN" title="Open Chrono Wealth Vault"><img src="https://img.shields.io/badge/Open%20App-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="Chrono Wealth Vault" /></a> |
  | **My BlockChain** | Netlify / Cloudflare | <a href="https://b-chain.netlify.app" title="b-chain.netlify.app"><img src="https://img.shields.io/badge/b--chain.netlify.app-0F172A?style=flat-square&logo=netlify&logoColor=00C7B7" alt="My BlockChain Netlify" /></a> <a href="https://b-chain.pages.dev" title="b-chain.pages.dev"><img src="https://img.shields.io/badge/b--chain.pages.dev-0F172A?style=flat-square&logo=cloudflare&logoColor=F38020" alt="My BlockChain Cloudflare" /></a> |

</details>

<details>
  <summary><strong>Media, Streaming &amp; Social Platforms</strong></summary>
  <br />

  | App | Platform | Direct Link |
  | :--- | :--- | :---: |
  | **Dell G15 Movies (Web)** | Google Share | <a href="https://share.google/7hzZvSfqNjw9m8Dem" title="Open Dell G15 Movies"><img src="https://img.shields.io/badge/Open%20Web-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="Dell G15 Movies Web" /></a> |
  | **Dell G15 Movies (Builds)** | Android APK / Win EXE | <a href="https://github.com/sanchar303/data/raw/refs/heads/master/Dell%20G15%20Movies_v1.0.0_20261113.apk" title="Download Android APK"><img src="https://img.shields.io/badge/Android%20APK-0F172A?style=flat-square&logo=android&logoColor=3DDC84" alt="Dell G15 Movies APK" /></a> <a href="https://github.com/sanchar303/data/raw/refs/heads/master/dell-g15-movies.pages.dev.exe" title="Download Windows EXE"><img src="https://img.shields.io/badge/Windows%20EXE-0F172A?style=flat-square&logo=windows&logoColor=38BDF8" alt="Dell G15 Movies EXE" /></a> |
  | **Romisha** | Cloudflare Pages | <a href="https://romisha-mp4.pages.dev" title="romisha-mp4.pages.dev"><img src="https://img.shields.io/badge/romisha--mp4.pages.dev-0F172A?style=flat-square&logo=cloudflare&logoColor=F38020" alt="Romisha" /></a> |
  | **SK IMDB** | Google Share | <a href="https://share.google/k67MUdCETyYA7nnhV" title="Open SK IMDB"><img src="https://img.shields.io/badge/Open%20App-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="SK IMDB" /></a> |
  | **Nexus Social Hub** | Netlify | <a href="https://nexus-social-hub.netlify.app" title="nexus-social-hub.netlify.app"><img src="https://img.shields.io/badge/nexus--social--hub.netlify.app-0F172A?style=flat-square&logo=netlify&logoColor=00C7B7" alt="Nexus Social Hub" /></a> |
  | **Public Chat** | Google Share | <a href="https://share.google/wBzsOLhRs3t7CRuGg" title="Open Public Chat"><img src="https://img.shields.io/badge/Open%20App-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="Public Chat" /></a> |
  | **Decentralized Chat** | Google Share | <a href="https://share.google/W1iUFMr2xmJnEmRIF" title="Open Decentralized Chat"><img src="https://img.shields.io/badge/Open%20App-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="Decentralized Chat" /></a> |
  | **NexChat** | Google Share | <a href="https://share.google/PbyGS49lPlW8gJjRI" title="Open NexChat"><img src="https://img.shields.io/badge/Open%20App-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="NexChat" /></a> |
  | **Clubhouse SK** | Google Share | <a href="https://share.google/2cATBrYK1ShpkhxCN" title="Open Clubhouse SK"><img src="https://img.shields.io/badge/Open%20App-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="Clubhouse SK" /></a> |
  | **UNC BOARD** | Google Share | <a href="https://share.google/H0PtmXEGnb1nQr9bL" title="Open UNC BOARD"><img src="https://img.shields.io/badge/Open%20App-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="UNC BOARD" /></a> |

</details>

<details>
  <summary><strong>Utilities, Academic &amp; Portfolio</strong></summary>
  <br />

  | App | Platform | Direct Link |
  | :--- | :--- | :---: |
  | **DupliApp** | Cloudflare Pages / Share | <a href="https://dupliapp.pages.dev" title="dupliapp.pages.dev"><img src="https://img.shields.io/badge/dupliapp.pages.dev-0F172A?style=flat-square&logo=cloudflare&logoColor=F38020" alt="DupliApp" /></a> <a href="https://share.google/XNlE42IKn9axOPEg6" title="Mirror Link"><img src="https://img.shields.io/badge/Mirror-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="Mirror" /></a> |
  | **Eh-Pic Fair** | Google Share | <a href="https://share.google/c4m5cYEkUL2GegRq7" title="Open Eh-Pic Fair"><img src="https://img.shields.io/badge/Open%20App-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="Eh-Pic Fair" /></a> |
  | **P1 Calculator** | Google Share | <a href="https://share.google/7ZylnFJygPEbZUA90" title="Open P1 Calculator"><img src="https://img.shields.io/badge/Open%20App-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="P1 Calculator" /></a> |
  | **MAT Questions** | Cloudflare Pages / Share | <a href="https://mat-questions.pages.dev" title="mat-questions.pages.dev"><img src="https://img.shields.io/badge/mat--questions.pages.dev-0F172A?style=flat-square&logo=cloudflare&logoColor=F38020" alt="MAT Questions" /></a> <a href="https://share.google/cPIR9i2XVG8UT6xUf" title="Mirror Link"><img src="https://img.shields.io/badge/Mirror-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="Mirror" /></a> |
  | **Shopping List** | Cloudflare Pages | <a href="https://sk-list.pages.dev" title="sk-list.pages.dev"><img src="https://img.shields.io/badge/sk--list.pages.dev-0F172A?style=flat-square&logo=cloudflare&logoColor=F38020" alt="Shopping List" /></a> |
  | **Sanchar Koirala CV** | Google Share | <a href="https://share.google/l8BoEKpKGNkhnSmcp" title="View Sanchar Koirala CV"><img src="https://img.shields.io/badge/View%20CV-0F172A?style=flat-square&logo=google&logoColor=38BDF8" alt="Sanchar Koirala CV" /></a> |

</details>

---

<div align="center">

### Connect

<a href="https://tr.ee/sanchar" title="Linktree — tr.ee/sanchar">
  <img src="https://img.shields.io/badge/LINKTREE-TR.EE%2FSANCHAR-0F172A?style=for-the-badge&logo=linktree&logoColor=43E660" alt="Linktree" />
</a>
<a href="https://lnkd.in/p/gYCmjJau" title="LinkedIn — Sanchar Koirala">
  <img src="https://img.shields.io/badge/LINKEDIN-SANCHAR%20KOIRALA-0F172A?style=for-the-badge&logo=linkedin&logoColor=0A66C2" alt="LinkedIn" />
</a>
<a href="https://www.youtube.com/@sanchar888" title="YouTube — @sanchar888">
  <img src="https://img.shields.io/badge/YOUTUBE-%40SANCHAR888-0F172A?style=for-the-badge&logo=youtube&logoColor=FF0000" alt="YouTube" />
</a>
<a href="https://www.instagram.com/sanchar888" title="Instagram — @sanchar888">
  <img src="https://img.shields.io/badge/INSTAGRAM-%40SANCHAR888-0F172A?style=for-the-badge&logo=instagram&logoColor=E4405F" alt="Instagram" />
</a>
<a href="https://www.tiktok.com/@s.koirala888" title="TikTok — @s.koirala888">
  <img src="https://img.shields.io/badge/TIKTOK-%40S.KOIRALA888-0F172A?style=for-the-badge&logo=tiktok&logoColor=00F2FE" alt="TikTok" />
</a>
<a href="https://www.snapchat.com/add/s.koirala888" title="Snapchat — s.koirala888">
  <img src="https://img.shields.io/badge/SNAPCHAT-S.KOIRALA888-0F172A?style=for-the-badge&logo=snapchat&logoColor=FFFC00" alt="Snapchat" />
</a>

<br /><br />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1120,50:1E293B,100:0F172A&height=90&section=footer" width="100%" alt="Footer Wave" />

<sub>© 2026 Sanchar Koirala | All rights reserved</sub>

</div>
