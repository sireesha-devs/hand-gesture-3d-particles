# Hand Gesture Controlled 3D Particle System ✋✨

An interactive **real-time 3D particle visualization** controlled using **hand gestures** detected via your webcam.  
Built with **Three.js** for rendering and **MediaPipe Hands** for AI-based hand tracking.

Particles dynamically morph into different shapes based on the number of fingers shown and react to gestures like pinching and hand movement.

---

## 🚀 Live Demo
👉 Enable webcam access and show your hand to interact with the particles.

(Deploy easily using **GitHub Pages** — see instructions below)

---

## 🎯 Features

- 🖐️ **Real-time hand tracking** using MediaPipe
- 🎇 **6000+ animated particles** rendered with Three.js
- 🔄 **Smooth morphing shapes** based on finger count
- 🎨 **Dynamic color changes** based on hand position
- 👌 **Pinch gesture** to expand/explode particles
- 🪐 Multiple particle formations:
  - Sphere
  - Heart ❤️
  - Flower 🌸
  - Sun / Star ☀️
  - Saturn 🪐
  - Firework 💥

---

## 🖐️ Gesture Controls

| Gesture | Effect |
|------|------|
| Fist (0 fingers) | Sphere |
| 1 Finger | Heart |
| 2 Fingers | Flower |
| 3 Fingers | Sun / Star |
| 4 Fingers | Saturn |
| 5 Fingers | Fireworks |
| Pinch (Index + Thumb) | Expand / Explode |
| Move Hand | Rotate particles & change color |

---

## 🛠️ Tech Stack

- **JavaScript**
- **Three.js** – 3D rendering
- **MediaPipe Hands** – AI hand tracking
- **WebGL**
- **HTML5 / CSS3**

All libraries are loaded via CDN — no build tools required.

---

## 📂 Project Structure

hand-gesture-3d-particles/
│
├── index.html # Main application file
├── README.md # Project documentation


---

## ▶️ How to Run Locally

> ⚠️ Webcam access requires running via a local server (not `file://`).

### Option 1: Using VS Code (Recommended)
1. Install **Live Server** extension
2. Right-click `index.html`
3. Click **"Open with Live Server"**

### Option 2: Using Python
```bash
python -m http.server
```
Then open :
   http://localhost:8000



