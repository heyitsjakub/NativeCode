<div align="center">

<img src="https://nativecode.jakubhecht.sk/assets/icon.png" width="120" alt="NativeCode logo">

# NativeCode

### A truly native AI coding IDE for Mac & Windows

**SwiftUI. WinUI 3. Local AI. Built for Apple Silicon and Windows.**

[![macOS](https://img.shields.io/badge/macOS-14.0+-000000?style=flat&logo=apple&logoColor=white)](https://nativecode.jakubhecht.sk)
[![Apple Silicon](https://img.shields.io/badge/Apple%20Silicon-recommended-blue?style=flat&logo=apple&logoColor=white)](https://nativecode.jakubhecht.sk)
[![macOS version](https://img.shields.io/badge/macOS-1.3.6-success?style=flat)](https://nativecode.jakubhecht.sk)
[![Windows](https://img.shields.io/badge/Windows-10%2F11-0078D4?style=flat&logo=windows&logoColor=white)](#-nativecode-for-windows)
[![Windows version](https://img.shields.io/badge/Windows-1.0.4-success?style=flat)](#-nativecode-for-windows)
[![Price](https://img.shields.io/badge/price-free-brightgreen?style=flat)](https://nativecode.jakubhecht.sk)

[**Website**](https://nativecode.jakubhecht.sk) · [**Download**](https://nativecode.jakubhecht.sk) · [**Report a bug**](https://github.com/heyitsjakub/NativeCode/issues/new/choose) · [**Request a feature**](https://github.com/heyitsjakub/NativeCode/issues/new/choose)

<img src="https://nativecode.jakubhecht.sk/assets/screenshot.png?v=1.3.6" alt="NativeCode screenshot" width="800">

</div>

---

## 🪟 NativeCode for Windows

**NativeCode runs natively on Windows.** It is a ground-up **WinUI 3** app built with the Windows App SDK — not Electron and not a web wrapper — bringing the same agentic coding experience to Windows 10 and 11.

<div align="center">
<img src="https://nativecode.jakubhecht.sk/assets/screenshot-windows.png?v=1.0.4" alt="NativeCode for Windows screenshot" width="800">
</div>

- 🪟 **Native WinUI 3 app** — Fluent, dark-themed, and self-contained; no separate .NET runtime installation required
- 🧠 **Local and remote models** — run local models via **Ollama**, or connect to any OpenAI-compatible server such as LM Studio or a remote Ollama instance
- 🔒 **Private by default** — your project stays on your PC when using local models
- 📝 **Monaco editor** — familiar VS Code-style editing hosted in WebView2
- 🛠️ **Agentic tools** — file read, edit, search, shell commands, visible task lists, and plan mode with approval
- 💻 **Integrated terminal** — bottom terminal panel (`Ctrl-J`) backed by a real ConPTY session
- 🖼️ **Vision support** — paste images into chat when the selected model supports vision
- 🎛️ **Built-in model management** — GPU offload control, network model discovery, and one-click Ollama installation
- 🌍 **English and Slovak UI**

### Quick start (Windows)

1. Download `NativeCode-1.0.4-setup.exe` from the [releases](https://github.com/heyitsjakub/NativeCode/releases) or the [NativeCode website](https://nativecode.jakubhecht.sk)
2. Run it — it is a **per-user install**, so administrator rights are not required
3. If Windows SmartScreen warns you, click **More info → Run anyway**. The app is not code-signed yet, so this warning is expected for the current release
4. Install **Ollama** when prompted to run models locally, or connect the app to a remote OpenAI-compatible server
5. Open a project folder and start coding with your AI agent

### System requirements (Windows)

- Windows 10 (1809+) or Windows 11, 64-bit (x64)
- 16 GB RAM minimum; 32 GB recommended for larger models
- [Ollama](https://ollama.com) for local models, installable from inside the app
- Around 5–15 GB of free disk space, depending on the selected model

Feedback and bug reports are welcome via the [issue tracker](https://github.com/heyitsjakub/NativeCode/issues/new/choose).

---

## What is NativeCode?

NativeCode is a native coding IDE with a built-in AI agent that can read, edit, search, and run approved commands across your project. It is built for local-first coding on **macOS** with SwiftUI and MLX, and on **Windows** with WinUI 3 and Ollama.

- 🍎 **Native SwiftUI app on macOS** — not Electron and not a web wrapper
- 🪟 **Native WinUI 3 app on Windows** — built specifically for Windows 10 and 11
- ⚡ **Powered by MLX on Mac** — optimized local inference on Apple Silicon
- 🧠 **Local and remote models** — use Rapid-MLX or Ollama locally, or connect to an OpenAI-compatible server
- 🔒 **Private by default** — your project stays on your machine when using local models
- 📝 **Monaco editor** — familiar VS Code-style editing
- 🛠️ **Agentic tools** — file reading, editing, search, shell commands, approvals, and visible task lists
- 💻 **Integrated terminal** — `Command-J` on macOS and `Ctrl-J` on Windows
- 🖼️ **Vision support** — paste images into chat when the selected model supports vision

## Why NativeCode?

|                          | NativeCode             | Cursor      | Bodega One     | Continue.dev   |
| ------------------------ | ---------------------- | ----------- | -------------- | -------------- |
| Native SwiftUI (macOS)   | ✅                     | ❌ Electron | ❌ Electron    | ❌ VS Code ext |
| Native WinUI 3 (Windows) | ✅                     | ❌ Electron | ❌ Electron    | ❌ VS Code ext |
| Apple Silicon optimized  | ✅ MLX                 | ❌          | ⚠️ via Ollama | ⚠️ via Ollama |
| Windows GPU acceleration | ✅ with offload control | ❌          | ⚠️ via Ollama | ⚠️ via Ollama |
| 100% local option        | ✅                     | ❌          | ✅             | ✅             |
| Price                    | **Free**               | $20/month   | $79+           | Free           |

NativeCode combines platform-native interfaces with local AI inference — without Electron, telemetry, or a subscription.

## Supported models

### macOS — local via Rapid-MLX

Curated MLX catalog downloaded from `mlx-community`:

- **Qwen3** — 8B (4/6/8-bit), 14B (4/6-bit), and 32B (4-bit)
- **Qwen3-Coder-30B-A3B** — 4/6/8-bit MoE coding model
- **Qwen3-VL** — 4B (4/8-bit), 8B (4/6/8-bit), and 30B-A3B (4-bit)
- **Gemma 3** — 12B (4-bit QAT) and 27B (4-bit)

### Windows — local via Ollama

Pulled on demand through the built-in Ollama integration:

- **Qwen3** — 1.7B, 4B, 8B, 14B, and 32B
- **Qwen3-Coder-30B** — coding MoE
- **Qwen3-VL** — 8B and 30B
- **Gemma 3** — 4B, 12B, and 27B
- Any other Ollama tag you pull

### Remote — both platforms

NativeCode can connect to OpenAI-compatible APIs, including:

- LM Studio
- Ollama running on another machine
- Any server exposing an OpenAI-compatible `/v1` endpoint

## Quick start (macOS)

1. Download `NativeCode.dmg` from [nativecode.jakubhecht.sk](https://nativecode.jakubhecht.sk)
2. Drag NativeCode into your Applications folder
3. Open the app and follow the in-app setup
4. Open a project folder and start coding with your AI agent

Full installation guide: [nativecode.jakubhecht.sk/#install](https://nativecode.jakubhecht.sk/#install)

## System requirements (macOS)

- macOS 14.0 or later
- Apple Silicon Mac recommended
- 16 GB RAM minimum
- 32 GB RAM recommended for larger models
- Around 5–15 GB of free disk space, depending on the selected model

## What's new on Windows (1.0.4)

Version 1.0.4 is the first full Windows release and brings the latest AI workspace improvements from the Mac app:

- **Full-window AI mode** — expand the assistant across the whole window and hide the file tree and editor to focus on the conversation
- **NativeCode AI icon** — the assistant now uses the NativeCode AI identity throughout the app
- **Livelier suggestion buttons** — starter prompts now scale and glow with a smooth hover animation
- **Chat history** — conversations are saved automatically and can be reopened from the History view

## What's new on macOS (1.3.6)

- **Full-window AI mode** — focus entirely on the AI conversation and return to the editor layout with the same control
- **Fresh NativeCode AI icon** — used across chat, settings, onboarding, and model recommendations
- **Livelier suggestion buttons** — starter prompts now respond with a smooth scale and glow animation
- **Liquid Glass touches** — small visual refinements give the app a more polished native feel

## FAQ

**How is this different from Cursor?**  
NativeCode is a platform-native app — SwiftUI on macOS and WinUI 3 on Windows — not an Electron wrapper. On macOS it integrates directly with Apple Silicon through MLX, while on Windows it runs models locally through Ollama.

**Why MLX and not llama.cpp or Ollama on macOS?**  
MLX is Apple's native machine-learning framework, optimized for Apple Silicon. It offers efficient local inference and unified memory support on Mac.

**What about Windows or Linux?**  
A native **Windows** version is available as a ground-up WinUI 3 app that runs local models through Ollama. Linux is not currently planned. The macOS and Windows apps are separate native implementations rather than a cross-platform wrapper.

**Is my code sent anywhere?**  
Not when using local models. NativeCode has zero telemetry by default. You can verify this with Little Snitch or LuLu on macOS, or Windows Defender Firewall or GlassWire on Windows.

**Will the source code be open-sourced?**  
Not currently planned. NativeCode is a closed-source product.

**Is it really free?**  
Yes. The current version is free for personal and commercial use. A Pro version with advanced features is planned for the future, but the core experience will remain free.

## Reporting a bug

Found a bug? Open an issue using the bug report template:

👉 [**Report a bug**](https://github.com/heyitsjakub/NativeCode/issues/new/choose)

Please include:

- NativeCode version and platform
- Operating-system version
- Machine specifications — Mac model, or CPU, GPU, and RAM on Windows
- Selected AI model
- Backend — local Rapid-MLX, local Ollama, or a remote OpenAI-compatible server
- Steps to reproduce the issue

## Requesting a feature

Have an idea for NativeCode? Open a [**Feature Request**](https://github.com/heyitsjakub/NativeCode/issues/new/choose).

## Source code

NativeCode is a closed-source product. This GitHub repository exists for bug reports, feature requests, release notes, and community feedback. A Pro version with advanced features is planned for the future, while the core experience will remain free.

## About the developer

NativeCode is built by **Jakub Hecht** from [Jakub Studio](https://jakubhecht.sk), a self-taught iOS and macOS developer from Slovakia.

- 🌐 Website: [jakubhecht.sk](https://jakubhecht.sk)
- 📧 Email: [info@jakubhecht.sk](mailto:info@jakubhecht.sk)
- 🐦 GitHub: [@heyitsjakub](https://github.com/heyitsjakub)

## License

NativeCode is free to use for personal and commercial work. The source code is currently not publicly available.

---

<div align="center">

**Built in Slovakia · Made for Mac & Windows**

⭐ If you like NativeCode, please star this repository to support development.

</div>
