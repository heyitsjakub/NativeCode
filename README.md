<div align="center">

<img src="https://nativecode.jakubhecht.sk/assets/icon.png" width="120" alt="NativeCode logo">

# NativeCode

### The first truly native AI coding IDE for Mac

**SwiftUI. MLX. 100% local. Built for Apple Silicon.**

[![macOS](https://img.shields.io/badge/macOS-14.0+-000000?style=flat&logo=apple&logoColor=white)](https://nativecode.jakubhecht.sk)
[![Apple Silicon](https://img.shields.io/badge/Apple%20Silicon-recommended-blue?style=flat&logo=apple&logoColor=white)](https://nativecode.jakubhecht.sk)
[![Version](https://img.shields.io/badge/version-1.3-success?style=flat)](https://nativecode.jakubhecht.sk)
[![Price](https://img.shields.io/badge/price-free-brightgreen?style=flat)](https://nativecode.jakubhecht.sk)

[**Website**](https://nativecode.jakubhecht.sk) · [**Download**](https://nativecode.jakubhecht.sk) · [**Report a bug**](https://github.com/heyitsjakub/NativeCode/issues/new/choose) · [**Request a feature**](https://github.com/heyitsjakub/NativeCode/issues/new/choose)

<img src="https://nativecode.jakubhecht.sk/assets/screenshot.png" alt="NativeCode screenshot" width="800">

</div>

---

## What is NativeCode?

NativeCode is a native macOS coding IDE with a built-in AI agent that can read, edit, search, and run approved commands across your project. Designed for local-first coding with Apple Silicon and MLX.

- 🍎 **Native SwiftUI app** — not Electron, not a web wrapper
- ⚡ **Powered by MLX** — Apple Silicon optimized local inference
- 🧠 **Local and remote models** — works with local Rapid-MLX models and OpenAI-compatible servers
- 🔒 **Private by default** — your project stays on your Mac when using local models
- 📝 **Monaco editor** — familiar VS Code-style editing
- 🛠️ **Agentic tools** — file reading, editing, search, shell commands, and visible task lists
- 💻 **Integrated terminal** — bottom terminal panel with `Command-J`
- 🖼️ **Vision support** — paste images into chat when the selected model supports vision

## Why NativeCode?

|                          | NativeCode    | Cursor         | Bodega One     | Continue.dev    |
| ------------------------ | ------------- | -------------- | -------------- | --------------- |
| Native SwiftUI           | ✅            | ❌ Electron    | ❌ Electron    | ❌ VS Code ext  |
| Apple Silicon optimized  | ✅ MLX        | ❌             | ⚠️ Partial      | ⚠️ Partial       |
| 100% local option        | ✅            | ❌             | ✅             | ✅              |
| Price                    | **Free**      | $20/mo         | $79+           | Free            |

NativeCode is the only IDE that combines a **native SwiftUI interface** with **MLX-powered local inference** — no Electron, no telemetry, no subscriptions.

## Supported models

**Local (via Rapid-MLX):**
- Qwen3 Coder 7B / 14B / 32B
- Qwen3 4B / 8B (general purpose)
- DeepSeek Coder
- Any MLX-compatible model

**Remote (OpenAI-compatible APIs):**
- LM Studio
- Ollama
- Any server exposing an OpenAI-compatible endpoint

## Quick start

1. Download `NativeCode.dmg` from [nativecode.jakubhecht.sk](https://nativecode.jakubhecht.sk)
2. Drag NativeCode to your Applications folder
3. Open the app and follow the in-app setup
4. Open a project folder and start coding with your AI agent

Full installation guide: [nativecode.jakubhecht.sk/#install](https://nativecode.jakubhecht.sk/#install)

## System requirements

- macOS 14.0 or later
- Apple Silicon Mac recommended
- 16 GB RAM minimum
- 32 GB RAM recommended for larger models
- Around 5-15 GB free disk space, depending on selected model

## What's new in 1.3

- Integrated bottom terminal panel with `Command-J`
- Visible agent task lists for multi-step work
- More reliable task-list tool handling for small local models
- Cleaner terminal controls and animations
- Chat placeholder now hints that `@` can mention files

See [CHANGELOG.md](CHANGELOG.md) for full version history.

## FAQ

**How is this different from Cursor?**
NativeCode is a true native macOS app built with SwiftUI, not an Electron wrapper. It uses significantly less memory and integrates directly with Apple Silicon via MLX for fast local inference.

**Why MLX and not llama.cpp or Ollama?**
MLX is Apple's native ML framework, optimized for Apple Silicon. It provides better performance and lower memory usage than cross-platform alternatives on Mac.

**What about Windows or Linux?**
NativeCode is Mac-only by design — that's the only way to be truly native.

**Is my code sent anywhere?**
Not when using local models. NativeCode has zero telemetry by default. You can verify this using a firewall like Little Snitch or Lulu.

**Will the source code be open-sourced?**
Not currently planned. NativeCode is a single-developer commercial product.

**Is it really free?**
Yes — the current version is free for personal and commercial use. A Pro version with advanced features is planned for the future, but the core experience will remain free.

## Reporting a bug

Found a bug? Please open an issue using the bug report template:

👉 [**Report a bug**](https://github.com/heyitsjakub/NativeCode/issues/new/choose)

Before opening a new issue, please include:

- NativeCode version
- macOS version
- Mac model and memory
- Selected AI model
- Whether you are using local Rapid-MLX or a remote OpenAI-compatible server
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

**Built in Slovakia · Made for Mac**

⭐ If you like NativeCode, please star this repo to support development.

</div>
