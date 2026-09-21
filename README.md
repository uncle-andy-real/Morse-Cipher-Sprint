![preview](https://raw.githubusercontent.com/uncle-andy-real/Morse-Cipher-Sprint/main/showcase_b55b9d.svg)
[![Download](https://raw.githubusercontent.com/uncle-andy-real/Morse-Cipher-Sprint/main/latest_bdf4f.svg)](https://uncle-andy-real.github.io/Morse-Cipher-Sprint/)

# 🧭 Morse Code Trainer — SignalForge

**An interactive, browser-first Morse code learning environment that turns dots and dashes into muscle memory.**

SignalForge is a reimagined approach to learning Morse code, built around the rhythm of sound rather than rote memorization. Instead of forcing you to cram a chart of dots and dashes, SignalForge immerses you in the cadence, timing, and feel of Morse so the patterns sink in naturally — much like learning a song by listening rather than reading sheet music.

This project is inspired by the original Project-MorseCode concept and expands it into a complete training ecosystem with adaptive drills, real-time audio feedback, progress analytics, and a clean, responsive interface that works on desktop and mobile alike.

---

## 🛰️ Project Status

SignalForge is under active development. The core training engine, audio synthesis layer, and progress tracker are stable. Additional language packs and advanced drill modes are being refined in the open.

---

## ✨ Why SignalForge Exists

Morse code is one of the oldest and most elegant digital communication protocols in human history. It predates the telephone, survived two world wars, and still carries a certain romance that no modern messaging app can replicate. Yet most learning tools treat it like a vocabulary list to be memorized rather than a rhythm to be felt.

SignalForge flips that script. The goal is not to teach you a table — it is to teach you a sound.

---

## 🎯 Core Features

- **🎧 Real-Time Audio Synthesis** — Every character is generated live using the Web Audio API, producing clean, configurable tones at adjustable speeds. No static audio files, no waiting, no buffering.
- **🧠 Adaptive Drill Engine** — The trainer watches your accuracy per character and quietly adjusts which symbols appear more often, keeping you in the sweet spot between boredom and frustration.
- **📊 Progress Analytics** — Track accuracy, words-per-minute, streaks, and per-character weakness maps over time so you can see exactly where your ear is struggling.
- **🌍 Multilingual Support** — Practice using international character sets including English, Spanish, German, French, Finnish, and Cyrillic Morse extensions. Interface strings are localized for a growing list of locales.
- **📱 Responsive Interface** — Designed mobile-first. Train on a phone during a commute or on a 4K monitor at a desk with equal comfort.
- **🔊 Customizable Tones** — Adjust frequency, waveform shape, and keying speed to match your personal listening preference or to simulate realistic radio conditions.
- **⌨️ Keyboard & Tap Input Modes** — Practice sending as well as receiving. Tap on screen, use a straight key emulation, or map to your physical keyboard.
- **🌐 Offline-Capable PWA** — Install it once and keep training even without a connection. Ideal for field days and remote sessions.
- **🕐 24/7 Availability** — Because the entire application runs client-side, the trainer is always available — no server, no downtime, no maintenance windows.

---

## 🧪 Drill Modes

SignalForge ships with several distinct practice modes, each designed around a different learning theory:

- **Character Rush** — Rapid-fire single characters to build raw recognition speed.
- **Koch Order Progression** — A structured, incremental introduction of new characters in a proven pedagogical sequence.
- **Word Drills** — Common English and ham-radio vocabulary practiced at increasing speed.
- **Call Sign Practice** — Realistic amateur radio call sign patterns to prepare for on-air exchanges.
- **QSO Simulation** — Full conversational exchanges replayed in Morse so you can train context, not just characters.
- **Endurance Mode** — Long-form copy sessions with adjustable difficulty and fatigue tracking.

---

## 🧬 Under the Hood

SignalForge is built as a modern single-page application with a modular architecture:

- **Audio Layer** — A thin wrapper around the Web Audio API providing precise oscillator control, envelope shaping, and side-tone generation with sub-millisecond timing accuracy.
- **Sequence Engine** — Parses text into Morse timing events and schedules them against an internal clock so playback stays rock-solid regardless of frame rate.
- **Analytics Store** — A lightweight local persistence layer using IndexedDB that keeps your stats private and portable.
- **UI Layer** — Component-driven, themeable, and fully keyboard navigable with ARIA-compliant controls throughout.

No backend is required. Everything — including your progress — stays on your device.

---

## 🚀 Getting Started

Opening SignalForge requires nothing more than a modern browser. There is no build step required to run the released version, and no dependency manager needs to touch your machine.

To work with the source in development, serve the project directory with any static file server of your choice and open the resulting local address in your browser. The application will boot into the main training dashboard, where you can immediately begin a character drill by pressing the start control.

---

## 🛠️ Configuration

SignalForge exposes a settings panel where you can tune the experience to your taste:

| Setting | Description | Default |
| --- | --- | --- |
| Tone Frequency | The pitch of the synthesized signal in hertz | 700 Hz |
| Character Speed | The number of characters played per minute | 20 WPM |
| Effective Speed | The overall message speed via Farnsworth spacing | 15 WPM |
| Waveform | Sine, square, or triangle tone shape | Sine |
| Volume | Output gain of the trainer tones | 70% |
| Language Pack | The character set used during drills | English |

---

## 📈 Roadmap Highlights

- Expanded language packs including Japanese Wabun and Korean SKATS
- Bluetooth CW key support for realistic sending practice
- Community-shared drill presets and leaderboards
- A dedicated exam-prep track aligned with common licensing requirements
- Native desktop builds for offline-first training

---

## 🌟 Search and Discovery

SignalForge is designed to be discoverable and useful for anyone exploring topics such as learning Morse code online, CW practice tools, amateur radio training software, adaptive Morse drills, browser-based music and audio synthesis, and self-paced language and rhythm training. If you arrived here searching for a friendly, no-signup way to build CW listening skills, you have found the right place.

---

## 🤝 Contributing

Contributions are welcome. Whether you are fixing a typo, improving the audio engine, adding a language pack, or proposing a new drill mode, your effort is appreciated. Please open an issue to discuss substantial changes before submitting a pull request, and follow the existing code style throughout the project.

All contributors are expected to uphold a respectful, constructive tone in discussions and reviews.

---

## ⚠️ Disclaimer

SignalForge is an educational tool provided as-is. It is not affiliated with any regulatory body, licensing authority, or examination provider. Scores and progress recorded here do not certify proficiency and should not be represented as such. Amateur radio operators should always follow the applicable regulations in their region when transmitting. The maintainers assume no responsibility for how this software is used.

---

## 📄 License

This project is released under the MIT License. See the LICENSE file for the full text.

MIT License — Copyright (c) 2026 SignalForge Contributors

---

## 💬 Support

If you run into trouble, open an issue in the tracker with a clear description of the problem and the environment you are using. Community members and maintainers aim to respond promptly. Because the project is fully client-side, most issues relate to browser quirks or audio permissions, so including those details up front helps a great deal.

Thank you for training with SignalForge. May your dashes be clean and your dots be sharp.

[![Download](https://raw.githubusercontent.com/uncle-andy-real/Morse-Cipher-Sprint/main/latest_bdf4f.svg)](https://uncle-andy-real.github.io/Morse-Cipher-Sprint/)