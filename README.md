# README.md

# Zonic — WebVPlayer
**Codename:** WebVPlayer  
**Tagline:** _No libraries. No clutter. Just music._

Zonic is a lightweight, streaming-first music player for Android — fast, focused, and designed to get you from URL → vibe with zero fuss. Built with Jetpack Compose and Media3 (ExoPlayer), Zonic prioritizes reliable playback, a smooth UI, and developer-friendly diagnostics — without the bloat of full catalog apps.

---

## 🚀 Why Zonic?
- Streaming-first: open the app the Auto-play does its work
- Minimal & modern: Jetpack Compose UI that feels native and fluid.  
- Rock-solid playback: Media3 (ExoPlayer) + OkHttp for reliable streaming (including authenticated sources).  
- Lightweight: core features that matter — nothing extraneous.

---

## ✨ Key Features
- ⚡ **Auto-play on launch** — open the app and the first track starts playing automatically.  
- 📁 **Folder browsing & switching** — open any folder and switch tracks manually; selecting a track plays it immediately.  
- 🔁 **Loop modes** — Loop One and Loop All.  
- 🔀 **Shuffle** — functional and snappy.  
- 📱 **Background playback** — lock-screen and notification controls supported.  
- 💾 **Optional cache** — reduce rebuffering for frequently-played streams; cache clear in Settings.  
- 🪄 **Filename prettifier** — converts `track_name_v1.mp3` into human-friendly titles.

---

## ⚠️ Known Issue
- **Playlist functionality and UI:** The playlist functionality and ui remains minimal because of its complexity It will be better in future
---

## 🛠 Roadmap ( to be done by varun-legend in future)
- Improve fetch logic for large remote folders.  
- Queue / playlist functionality.  
- UI resilience & notification-state consistency improvements.  

---

## 🎵 Supported Formats
Thanks to ExoPlayer and device codecs: **MP3, AAC, M4A, WAV, FLAC, OPUS, WEBM, MKV, VORBIS, MP4**, and more.

---

## 🔐 Privacy Promise
- **No analytics. No telemetry.**  
- Cache stays local and is controlled by the user.

---

## 🧾 Tech Stack
- **Language:** Kotlin  
- **UI:** Jetpack Compose  
- **Playback:** Media3 (ExoPlayer) + `media3-datasource-okhttp`  
- **Networking:** OkHttp (Retrofit)  
- **Concurrency:** Kotlin Coroutines

---

## 📦 Distribution & Source
This repository provides **release binaries only**. The full source code is **not** distributed here. Zonic is provided under a proprietary license — **modification, redistribution, or reverse-engineering are strictly prohibited**. See `LICENSE.txt` in this repository for full legal details.

---

## 🐛 Report issues / Contact
- Report bugs via the Releases page or open an issue on the project’s public issue tracker (if available).  
- Built by **Varun Prasath (varun-legend)** — reach out on GitHub: `varun-legend`.

---

## ⚖️ License
Zonic is distributed under a proprietary license. By downloading or installing the app, you accept the terms in `LICENSE.txt`. If you require redistribution rights or source access (for partnership, auditing or licensing), contact the author.

---