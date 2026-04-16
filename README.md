# ✋ Hand Tracking Magic Effect (Browser-Based)

A real-time, browser-based hand tracking visual experience powered by **MediaPipe Hands**. This project renders glowing, fiber-optic style hand skeletons, fingertip particles, and dynamic cross-hand energy connections — all directly in the browser with **no installation required**.

---

## 🚀 Live Demo
https://devasena999.github.io/hand-magic/

---

## ✨ Features

* 📷 **Webcam-based hand tracking** (via MediaPipe Hands CDN)
* ✋ Detects **up to 2 hands**, each with **21 landmarks**
* 🌐 **Canvas overlay rendering** (no WebGL required)

### 🎨 Visual Effects

* **Fiber-optic threads** along hand skeleton

  * 5 parallel strands per connection
  * White hot core + colored glow
* **Fingertip sparkles**
* **Particle trails** following finger movement
* **Cross-hand energy field**

  * Connects all **441 landmark pairs (21×21)**
  * Distance-based glow intensity
  * Optimized with **batched canvas paths**

### 🌈 Color Themes (switchable)

* Purple (white → purple)
* Gold (white → orange/gold)
* Cyan (white → cyan)
* Rainbow (per-finger hue mapping)

### 🧠 Smart UI

* Loading splash screen during initialization
* Top status bar showing number of detected hands
* Hint message when no hands are visible

---

## 🛠️ How It Works

* Uses **MediaPipe Hands (CDN)** for real-time tracking
* Captures webcam feed and mirrors it as background
* Draws all effects using **HTML5 Canvas**
* Optimized rendering:

  * Cross-hand connections batched into **single path per glow layer**
  * Multi-layer glow system:

    * Outer bloom
    * Mid halo
    * Inner glow
    * White core

---

## 📦 Setup (No Installation Needed)

1. Download or copy the HTML file
2. Open it in **Chrome or Edge**
3. Allow camera access
4. Show your hands to the webcam

That’s it — no npm, no dependencies, no build step.

---

## 📁 Project Structure

```
hand-tracking-magic/
│
└── index.html   # Fully self-contained application
```

---

## ⚡ Performance Notes

* Cross-hand rendering uses **path batching** for efficiency
* Avoids per-line drawing for 441 connections
* Runs smoothly on modern browsers with hardware acceleration

---

## 🧩 Technologies Used

* MediaPipe Hands (via CDN)
* HTML5 Canvas
* JavaScript (Vanilla)

---

## 📌 Future Improvements

* Gesture-based interactions
* Adjustable particle density
* Mobile performance optimizations
* WebGL version for enhanced effects

---

## 🧾 License

MIT License — free to use and modify.

---

## 🙌 Acknowledgements

* Google MediaPipe team for real-time hand tracking

---

## 💡 Tip

For best results:

* Use good lighting
* Keep hands clearly visible
* Avoid cluttered backgrounds

---
