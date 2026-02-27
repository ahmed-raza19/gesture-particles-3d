# Gesture Particles 3D

> Turn your hand into a particle brush.  
> One‑finger gun, two‑finger heart, three‑finger flower, four‑finger Saturn,  
> fist fireworks and open‑palm galaxy – all driven by MediaPipe & Three.js.

![demo gif](assets/demo.gif)

---

## 🚀 Live demo

Open `code.html` in any modern browser (camera access required).  
No build step, no dependencies – just clone and double‑click.

---

## ✨ Features

- Real‑time hand tracking via [MediaPipe Hands](https://mediapipe.readthedocs.io/en/latest/solutions/hands.html)
- 4 000 glowing 3‑D particles rendered with [Three.js](https://threejs.org)
- Gesture modes:
  - ☝️ **1 finger** → particle gun  
  - ✌️ **2 fingers** → heart shape  
  - 👌 **3 fingers** → flower  
  - 🖖 **4 fingers** → Saturn  
  - ✊ **fist** → fireworks  
  - 🖐 **palm** → floating galaxy  
- Pinch thumb + index to shift the colour palette  
- Smooth morphing & physics for dynamic visuals
- Works offline once assets are cached – ideal for GitHub Pages

---

## 🛠 Setup & use

```bash
git clone https://github.com/<your‑user>/gesture-particles-3d.git
cd gesture-particles-3d
# open the file or serve it with a static server:
# python -m http.server 8000
# visit http://localhost:8000/code.html
