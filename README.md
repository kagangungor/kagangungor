# Hi there, I'm Kağan Güngör 👋

**Systems & Desktop Engineer | Local AI & High-Performance Architecture**

I build high-performance, zero-telemetry native desktop applications, low-latency audio/speech pipelines, and offline-first AI integrations. Focused on system-level .NET/C#, Win32 interop, and on-device GPU acceleration.

---

### 🎙️ Featured Open Source Project: [TRWhisper](https://github.com/kagangungor/TRWhisper)

[![GitHub Release](https://img.shields.io/github/v/release/kagangungor/TRWhisper?color=0078D6&logo=github&style=flat-square)](https://github.com/kagangungor/TRWhisper/releases/latest)
[![GitHub Stars](https://img.shields.io/github/stars/kagangungor/TRWhisper?color=yellow&logo=github&style=flat-square)](https://github.com/kagangungor/TRWhisper/stargazers)
[![Downloads](https://img.shields.io/github/downloads/kagangungor/TRWhisper/total?color=2ea44f&logo=github&style=flat-square)](https://github.com/kagangungor/TRWhisper/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Windows_11_x64-0078D6?logo=windows11&logoColor=white&style=flat-square)](https://github.com/kagangungor/TRWhisper)
[![.NET](https://img.shields.io/badge/.NET-9.0-512BD4?logo=dotnet&logoColor=white&style=flat-square)](https://dotnet.microsoft.com/)
[![License](https://img.shields.io/github/license/kagangungor/TRWhisper?color=orange&style=flat-square)](https://github.com/kagangungor/TRWhisper/blob/main/LICENSE)

A completely local, privacy-first **push-to-talk voice dictation application** built for Windows 11 and tuned for Turkish dictation — an offline, zero-telemetry alternative to cloud dictation tools.

> 🆕 **Latest: [v2.1.0](https://github.com/kagangungor/TRWhisper/releases/tag/v2.1.0)** — one-click & automatic backups, a daily API call cap for cloud LLM cost control, and API key rotation reminders.

- ⚡ **In-Process Whisper.net & CUDA 13 Acceleration:** Near-instant local transcription (~2–3s on GPU) with in-process Whisper.net engine and automatic idle VRAM cleanup.
- 🌊 **Real-Time Live Streaming Preview:** Words stream dynamically into a floating overlay pill with real-time waveform visualization before final transcription.
- 🤖 **Context-Aware Personas & Foreground App Detection:** Detects active windows (VS Code, Visual Studio, Outlook, Windows Terminal, etc.) and auto-switches LLM post-processing personas (Clean, Code, Email, Bulleted Summary, Translation).
- 📖 **Turkish Normalization & Phonetic Jargon Engine:** Rule-based normalization for spoken Turkish numbers, dates, currency, percentages, and suffix vowel harmony, paired with user-defined phonetic dictionaries.
- 🔒 **Offline-First & DPAPI Security:** Audio never leaves the machine and there is zero telemetry; optional cloud LLM API keys are encrypted with Windows DPAPI (bound to your Windows account, custom entropy) and are never sent over plain HTTP.
- ⌨️ **DirectType & Smart Clipboard Engine:** Seamless text insertion via Win32 `SendInput` / Unicode keystrokes or clipboard paste with automatic clipboard restoration.
- 🎯 **Silero VAD & Hallucination Suppression:** Precision voice activity detection and custom heuristic filters for phantom subtitle suppression.
- 💾 **Backup, Cost Control & Key Lifecycle:** ZIP backups of settings, dictionary and dictation history (API key never included), a daily cloud API call cap with block/warn modes, and API key age tracking with rotation reminders.
- 🛡️ **Supply-Chain Integrity:** Every downloaded binary and model is verified against a pinned SHA-256 digest (fail-closed), with 152 automated unit tests guarding the codebase.

👉 **[Explore the Repository & Download Releases](https://github.com/kagangungor/TRWhisper)**

---

### 🛠️ Tech Stack & Technical Expertise

| Domain | Technologies & Frameworks |
|---|---|
| **Core & Systems** | C#, .NET 9, C++, Win32 API (`WH_KEYBOARD_LL`, `SendInput`), Multi-threading & Async, Memory Optimization |
| **Desktop UI / UX** | WPF (Windows Presentation Foundation), Modern XAML, Custom Floating Overlays, Windows Tray Integration |
| **AI, Audio & ML** | Whisper.net, whisper.cpp, NVIDIA CUDA 13, Silero VAD, Local LLM Inference (Ollama), Gemini / OpenAI APIs, DPAPI Encryption |
| **Testing & Quality** | xUnit, Automated UI Smoke Testing, RegEx Processing Engines, Zero-Leak Memory Auditing |
| **DevOps & Tooling** | Git, GitHub Releases, Inno Setup (Custom Pascal Scripting), PowerShell, Visual Studio |

---

### 🔭 Current Focus & Highlights

- 🚀 Architecting high-performance native desktop tools that prioritize user privacy and zero data leakage.
- ⚡ Exploring low-latency on-device AI inference pipelines (voice-to-text, embedding models, local SLMs).
- 🧩 Engineering deep Win32 integrations with modern .NET 9 runtimes.

---

### 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=kagangungor&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Kağan Güngör GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kagangungor&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</p>

---

### 📬 Connect with Me

<p align="left">
  <a href="https://kagangungor.com">
    <img src="https://img.shields.io/badge/Website-kagangungor.com-181717?style=flat-square&logo=googlechrome&logoColor=white" alt="Website" />
  </a>
  <a href="https://linkedin.com/in/kagangungor208">
    <img src="https://img.shields.io/badge/LinkedIn-Kağan_Güngör-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://x.com/kaganismy">
    <img src="https://img.shields.io/badge/X-@kaganismy-000000?style=flat-square&logo=x&logoColor=white" alt="X (Twitter)" />
  </a>
  <a href="mailto:kagangungor@dlinemedia.com">
    <img src="https://img.shields.io/badge/Email-kagangungor@dlinemedia.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

⭐️ *If you find my open-source projects useful, feel free to drop a star on the repositories!*
