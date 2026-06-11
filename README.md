<div align="center">

<img src="https://nativecode.jakubhecht.sk/assets/icon.png" width="120" alt="NativeCode logo">

# NativeCode

### The first truly native AI coding IDE for Mac & Windows

**SwiftUI. MLX. 100% local. Built for Apple Silicon and Windows.**

[![macOS](https://img.shields.io/badge/macOS-14.0+-000000?style=flat&logo=apple&logoColor=white)](https://nativecode.jakubhecht.sk)
[![Apple Silicon](https://img.shields.io/badge/Apple%20Silicon-recommended-blue?style=flat&logo=apple&logoColor=white)](https://nativecode.jakubhecht.sk)
[![Version](https://img.shields.io/badge/version-1.3.5-success?style=flat)](https://nativecode.jakubhecht.sk)
[![Price](https://img.shields.io/badge/price-free-brightgreen?style=flat)](https://nativecode.jakubhecht.sk)
[![Windows](https://img.shields.io/badge/Windows-10%2F11-0078D4?style=flat&logo=windows&logoColor=white)](#-nativecode-for-windows--new-beta)
[![Windows beta](https://img.shields.io/badge/Windows%20beta-NEW-orange?style=flat)](#-nativecode-for-windows--new-beta)

[**Website**](https://nativecode.jakubhecht.sk) · [**Download**](https://nativecode.jakubhecht.sk) · [**Report a bug**](https://github.com/heyitsjakub/NativeCode/issues/new/choose) · [**Request a feature**](https://github.com/heyitsjakub/NativeCode/issues/new/choose)

<img src="https://nativecode.jakubhecht.sk/assets/screenshot.png?v=1.3.5" alt="NativeCode screenshot" width="800">

</div>

---

## 🪟 NativeCode for Windows — NEW (Beta)

**NativeCode now runs on Windows too.** A ground-up native port built with **WinUI 3** (Windows App SDK) — not Electron, not a web wrapper — bringing the same agentic coding experience to Windows 10 and 11.

<div align="center">
<img src="https://nativecode.jakubhecht.sk/assets/screenshot-windows.png?v=1.0.1" alt="NativeCode for Windows screenshot" width="800">
</div>


- 🪟 **Native WinUI 3 app** — fluent, dark-themed, self-contained (no .NET install required)
- 🧠 **Local and remote models** — runs local models via **Ollama**, or any OpenAI-compatible server (LM Studio, remote Ollama)
- 🔒 **Private by default** — your project stays on your PC when using local models
- 📝 **Monaco editor** — same VS Code-style editing, in a WebView2 host
- 🛠️ **Agentic tools** — file read/edit/search, shell commands, visible task lists, plan mode
- 💻 **Integrated terminal** — bottom terminal panel (`Ctrl-J`) backed by a real ConPTY session
- 🖼️ **Vision support** — paste images into chat when the model supports it
- 🎛️ **GPU offload control, network model discovery, one-click Ollama install**
- 🌍 **English & Slovak** UI

### Quick start (Windows)

1. Download `NativeCode-1.0.1-beta-setup.exe` from the [releases](https://github.com/heyitsjakub/NativeCode/releases)
2. Run it — it's a **per-user install**, no admin rights needed. (The beta isn't code-signed yet, so Windows SmartScreen may warn — click **More info → Run anyway**.)
3. Install **Ollama** when prompted (one click) to run models locally, or point the app at a remote OpenAI-compatible server
4. Open a project folder and start coding with your AI agent

### System requirements (Windows)

- Windows 10 (1809+) or Windows 11, 64-bit (x64)
- 16 GB RAM minimum, 32 GB recommended for larger models
- [Ollama](https://ollama.com) for local models (installable from inside the app)
- Around 5–15 GB free disk space, depending on the selected model

> The Windows build is in **beta** — feedback and bug reports are very welcome via the [issue tracker](https://github.com/heyitsjakub/NativeCode/issues/new/choose).

---

## What is NativeCode?

NativeCode is a native coding IDE with a built-in AI agent that can read, edit, search, and run approved commands across your project. It's built for local-first coding — natively on **macOS** (SwiftUI + MLX on Apple Silicon) and now on **Windows** (WinUI 3 + Ollama). The points below describe the macOS app; see [NativeCode for Windows](#-nativecode-for-windows--new-beta) for the Windows port.

- 🍎 **Native SwiftUI app** — not Electron, not a web wrapper
- ⚡ **Powered by MLX** — Apple Silicon optimized local inference
- 🧠 **Local and remote models** — works with local Rapid-MLX models and OpenAI-compatible servers
- 🔒 **Private by default** — your project stays on your machine when using local models
- 📝 **Monaco editor** — familiar VS Code-style editing
- 🛠️ **Agentic tools** — file reading, editing, search, shell commands, and visible task lists
- 💻 **Integrated terminal** — bottom terminal panel with `Command-J`
- 🖼️ **Vision support** — paste images into chat when the selected model supports vision

## Why NativeCode?

|                          | NativeCode    | Cursor         | Bodega One     | Continue.dev    |
| ------------------------ | ------------- | -------------- | -------------- | --------------- |
| Native SwiftUI (macOS)   | ✅            | ❌ Electron    | ❌ Electron    | ❌ VS Code ext  |
| Native WinUI 3 (Windows) | ✅            | ❌ Electron    | ❌ Electron    | ❌ VS Code ext  |
| Apple Silicon optimized  | ✅ MLX        | ❌             | ⚠️ via Ollama   | ⚠️ via Ollama    |
| Windows GPU acceleration | ✅ + offload control | ❌      | ⚠️ via Ollama   | ⚠️ via Ollama    |
| 100% local option        | ✅            | ❌             | ✅             | ✅              |
| Price                    | **Free**      | $20/mo         | $79+           | Free            |

NativeCode is the only IDE that combines a **native SwiftUI interface** with **MLX-powered local inference** — no Electron, no telemetry, no subscriptions.

## Supported models

### macOS — local (via Rapid-MLX, Apple Silicon)

Curated MLX catalog, downloaded from `mlx-community`:

- **Qwen3** — 8B (4/6/8-bit), 14B (4/6-bit), 32B (4-bit) — thinking-capable, strong at code
- **Qwen3-Coder-30B-A3B** — 4/6/8-bit (MoE) — dedicated coding model
- **Qwen3-VL** — 4B (4/8-bit), 8B (4/6/8-bit), 30B-A3B (4-bit) — vision + code
- **Gemma 3** — 12B (4-bit QAT), 27B (4-bit) — Google multimodal

### Windows — local (via Ollama)

Pulled on demand through the built-in Ollama integration:

- **Qwen3** — 1.7B, 4B, 8B, 14B, 32B — thinking-capable, strong at code
- **Qwen3-Coder-30B** — coding MoE
- **Qwen3-VL** — 8B, 30B — vision + code
- **Gemma 3** — 4B, 12B, 27B — Google multimodal
- Any other Ollama tag you pull

### Remote — both platforms (OpenAI-compatible APIs)

- LM Studio
- Ollama running on another machine
- Any server exposing an OpenAI-compatible `/v1` endpoint

## Quick start (macOS)

1. Download `NativeCode.dmg` from [nativecode.jakubhecht.sk](https://nativecode.jakubhecht.sk)
2. Drag NativeCode to your Applications folder
3. Open the app and follow the in-app setup
4. Open a project folder and start coding with your AI agent

Full installation guide: [nativecode.jakubhecht.sk/#install](https://nativecode.jakubhecht.sk/#install)

## System requirements (macOS)

- macOS 14.0 or later
- Apple Silicon Mac recommended
- 16 GB RAM minimum
- 32 GB RAM recommended for larger models
- Around 5-15 GB free disk space, depending on selected model

## What's new on Windows (1.0.1 beta)

- **Bug fixes** — this release fixes bugs and improves stability. The Windows build remains in **beta**.

## What's new in 1.3.5 (macOS)

- **Added chat history** — your conversations are now saved automatically. A new **History** button sits right next to **New chat**, so you can browse and reopen any of your past chats.

## FAQ

**How is this different from Cursor?**
NativeCode is a true native app — SwiftUI on macOS, WinUI 3 on Windows — not an Electron wrapper. It uses significantly less memory; on macOS it integrates directly with Apple Silicon via MLX, and on Windows it runs models locally through Ollama.

**Why MLX and not llama.cpp or Ollama?**
MLX is Apple's native ML framework, optimized for Apple Silicon. It provides better performance and lower memory usage than cross-platform alternatives on Mac.

**What about Windows or Linux?**
A native **Windows** version is now available in beta — a ground-up WinUI 3 port that runs local models via Ollama. See [NativeCode for Windows](#-nativecode-for-windows--new-beta) above. Linux is not planned. On macOS the app stays native SwiftUI + MLX; the Windows build is its own native port (WinUI 3 + Ollama), not a cross-platform wrapper.

**Is my code sent anywhere?**
Not when using local models. NativeCode has zero telemetry by default. You can verify this with a firewall — Little Snitch or Lulu on macOS, or Windows Defender Firewall / GlassWire on Windows.

**Will the source code be open-sourced?**
Not currently planned. NativeCode is a single-developer commercial product.

**Is it really free?**
Yes — the current version is free for personal and commercial use. A Pro version with advanced features is planned for the future, but the core experience will remain free.

## Reporting a bug

Found a bug? Please open an issue using the bug report template:

👉 [**Report a bug**](https://github.com/heyitsjakub/NativeCode/issues/new/choose)

Before opening a new issue, please include:

- NativeCode version and platform (macOS or Windows)
- OS version (macOS or Windows build)
- Machine specs — Mac model, or CPU/GPU/RAM on Windows
- Selected AI model
- Backend — local Rapid-MLX (macOS), local Ollama (Windows), or a remote OpenAI-compatible server
- Steps to reproduce the issue

## Requesting a feature

Have an idea for NativeCode? Open a [**Feature Request**](https://github.com/heyitsjakub/NativeCode/issues/new/choose) issue.

## Source code

NativeCode is a closed-source product. This GitHub repository exists for bug reports, feature requests, release notes, and community feedback. A Pro version with advanced features is planned for the future — the core experience will remain free.

## About the developer

NativeCode is built by **Jakub Hecht** ([Jakub Studio](https://jakubhecht.sk)), a self-taught iOS/macOS developer from Slovakia.

- 🌐 Website: [jakubhecht.sk](https://jakubhecht.sk)
- 📧 Email: [info@jakubhecht.sk](mailto:info@jakubhecht.sk)
- 🐦 GitHub: [@heyitsjakub](https://github.com/heyitsjakub)

## License

NativeCode is free to use for personal and commercial work. The source code is currently not publicly available.

---

<div align="center">

**Built in Slovakia · Made for Mac & Windows**

⭐ If you like NativeCode, please star this repo to support development.

</div>
