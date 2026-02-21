# magic-particles-3d
Control 10,000 interactive 3D particles in your browser using hand gestures and AI computer vision
# ✋ Interactive 3D Hand-Tracked Particle System



A real-time, browser-based 3D particle system that uses your webcam and hand gestures to control 10,000 particles. Built purely with **Three.js** and Google's **MediaPipe**, this project requires no backend and runs entirely on the client side.

**[Try the Live Demo Here!](https://Aakash0678.github.io/particle-system/)** *(Requires webcam access)*

## ✨ Features
* **Real-time Hand Tracking:** Uses MediaPipe's AI vision models to detect hand landmarks at 60fps.
* **Dynamic 3D Rendering:** Renders and animates 10,000 individual particles using Three.js WebGL.
* **Gesture Controls:**
  * **Move Hand:** Rotates the entire 3D particle system on the X and Y axes.
  * **Open/Close Fingers:** Scales the particle system up and down based on the distance between your thumb and index finger.
  * **Pinch:** Triggers a smooth mathematical morph between 5 different geometric templates (Sphere, Heart, Saturn, Flower, Firework) and color palettes.
* **Smooth Interpolation:** Utilizes linear interpolation (`lerp`) for buttery-smooth transitions between shapes, colors, and transformations.

## 🛠️ Tech Stack
* **HTML5 / CSS3 / JavaScript (Vanilla)**
* **Three.js** (WebGL 3D Rendering)
* **MediaPipe Hands** (Computer Vision / Machine Learning)

## 🚀 How to Run Locally

Because web browsers have strict security policies regarding webcam access (CORS and media device rules), you cannot simply double-click the `index.html` file. You must run it through a local web server.

