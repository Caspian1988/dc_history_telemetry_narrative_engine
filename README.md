# 🏛️ DC CONDUCTOR // Narrative Engine

An interactive, web-based telemetry and tour narrative interface for Washington, D.C. historical waypoints. Built with lightweight vanilla JS and Leaflet.js, **DC Conductor** provides real-time route visualization, location telemetry, and hybrid dynamic voice narration for custom sightseeing circuits.

![DC Conductor Interface](https://raw.githubusercontent.com/caspian1988/dc-history-app/main/preview.png) *(Replace with your screenshot link)*

[![DEMO LIVE TRACKER](https://img.shields.io/badge/DEMO-LIVE_TRACKER-brightgreen?style=for-the-badge&logo=github)](https://caspian1988.github.io/dc_history_telemetry_narrative_engine/)

Check out the interactive live demo:  
👉 **[DC Conductor Live App](https://caspian1988.github.io/dc-history-app/)** *(Replace with your actual GitHub Pages URL)*

---

## ⚡ Key Features

* **🛰️ Tactical Dark-Mode Map Display**: Integrated high-contrast map telemetry using Esri satellite tiles and CSS dark-mode filtering, optimized for low-light operator environments.
* **🎙️ Hybrid Audio Narration System**: Automatically prioritizes authentic human voice narration files (`.mp3`). If an audio clip is not yet recorded for a specific waypoint, the engine seamlessly falls back to browser SpeechSynthesis TTS.
* **📍 Interactive Waypoint Telemetry**: Instant route jumping across 30+ curated D.C. historical markers, featuring dynamic map centering and visual focus indicators.
* **⚡ Zero Third-Party API Dependencies**: Runs completely client-side without external map API keys or rate-limit blocks, ensuring 100% uptime and local file compatibility.

---

## 🛠️ Tech Stack

* **Frontend Framework**: HTML5 / CSS3 (CSS Grid & Flexbox)
* **Typography**: Orbitron & JetBrains Mono (Google Fonts)
* **Mapping Library**: Leaflet.js v1.9.4
* **Map Tile Provider**: Esri World Topo Map / World Imagery
* **Audio Engine**: Web Audio API & Web Speech API (`SpeechSynthesis`)

---

## 📂 Project Structure

```text
├── index.html          # Main application UI and narrative logic
├── audio/              # Voice narration repository
│   ├── stop_3.mp3      # Recorded narration for Waypoint 3
│   ├── stop_4.mp3      # Recorded narration for Waypoint 4
│   └── ...
└── README.md           # Project documentation
