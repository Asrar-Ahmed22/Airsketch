# ✦ AirSketch — Draw with the Air

> **Draw with your hands. No touch required.**

AirSketch is a browser-based hand-tracking drawing application that uses your webcam to detect hand gestures in real time. Powered by **MediaPipe Hands**, you can draw, erase, drag, and clear — all without touching your screen.

🔗 **[Live Demo](https://asrar-ahmed22.github.io/Airsketch/)**

---

## ✨ Features

- 🖐️ **Real-time Hand Tracking** — Detects 21 hand landmarks via webcam using MediaPipe
- 🖌️ **10 Brush Modes** — Normal, Neon Glow, Watercolor, Spray Paint, Starburst, Calligraphy, Dashed, Dots, Smoke, Electric
- 🌈 **Rainbow Mode** — Automatically cycles through colors as you draw
- ✨ **Glow Effects** — Neon and electric brushes with canvas glow rendering
- 🖱️ **Canvas Drag** — Pinch gesture to pan the drawing canvas
- 💾 **Export PNG** — Save your artwork with one click
- ↩️ **Undo Support** — Step back through your drawing history
- 🗑️ **Gesture Erase & Clear** — Fist to erase, open hand to clear all

---

## 🤚 Gesture Controls

| Gesture | Action |
|--------|--------|
| ☝️ Index finger up | Draw |
| 🤏 Pinch + move | Drag / pan canvas |
| ✌️ Two fingers up | Pause drawing |
| ✊ Closed fist | Erase |
| 🖐️ Open hand (hold) | Clear all |

---

## 🎨 Brush Modes

| Brush | Description |
|-------|-------------|
| Normal | Solid smooth line |
| Neon Glow | Glowing neon stroke |
| Watercolor | Soft translucent wash |
| Spray Paint | Scattered particle spray |
| Starburst | Radiating star patterns |
| Calligraphy | Variable-width ink stroke |
| Dashed | Segmented dashed line |
| Dots | Dotted point trail |
| Smoke | Blurry diffused cloud |
| Electric | Jittery lightning stroke |

---

## 🚀 Getting Started

### Prerequisites
- A modern browser (Chrome recommended)
- A working webcam

### Run Locally

```bash
git clone https://github.com/asrar-ahmed22/Airsketch.git
cd Airsketch
# Open index.html in your browser
# Or serve with a local server:
npx serve .
```

> ⚠️ Webcam access is required. Make sure to allow camera permissions when prompted.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| [MediaPipe Hands](https://developers.google.com/mediapipe/solutions/vision/hand_landmarker) | Real-time hand landmark detection |
| HTML5 Canvas | Drawing surface & brush rendering |
| Vanilla JavaScript | Gesture logic, brush effects, UI |
| CSS3 | Animations, glow effects, styling |

---

## 📁 Project Structure

```
Airsketch/
├── index.html        # Landing page & app shell
├── app.js            # Core logic: hand tracking, gestures, canvas
├── style.css         # Styling, glow effects, responsive layout
└── assets/           # Icons and fonts
```

---

## 🧠 How It Works

```
Webcam Input
    ↓
MediaPipe Hands (21 landmarks detected per frame)
    ↓
Gesture Classifier
(checks finger states: up/down, pinch distance, hand openness)
    ↓
Action Dispatcher
(draw / erase / drag / pause / clear)
    ↓
Canvas Renderer
(applies active brush effect to HTML5 Canvas)
```

---

## 📸 Screenshots

> Launch the [live demo](https://asrar-ahmed22.github.io/Airsketch/) to see it in action.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m 'Add my feature'`
4. Push to the branch: `git push origin feature/my-feature`
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Asrar Ahmed**
- GitHub: [@asrar-ahmed22](https://github.com/asrar-ahmed22)

---

<p align="center">Made with ❤️ and hand gestures ✋</p>
