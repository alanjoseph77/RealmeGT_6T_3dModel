# 📱 Realme GT 6T — 3D Model (Three.js)

**Author:** [Alan Joseph](https://github.com/alanjoseph77)  
**Repository:** [RealmeGT_6T_3dModel](https://github.com/alanjoseph77/RealmeGT_6T_3dModel)  
**Version:** v3  
**Built With:** [Three.js r166](https://threejs.org/)

---

### 🧭 Overview
This project is a **real-time 3D model** of the **Realme GT 6T smartphone**, built entirely with **Three.js** — no external `.glb` or `.obj` models used.  
All textures, reflections, and materials are generated **procedurally** using the Canvas API and HDR environment lighting.

The model is designed to be:
- **Visually realistic**
- **Lightweight**
- **Fully interactive**
- **Optimized for mobile devices**

---

### ✨ Key Features
✅ **Procedural Textures**
- Dynamic “realme” branding
- Mirror + matte back finish
- Color variants with gradient shading

✅ **3D Geometry & Materials**
- RoundedBox geometry for frame & body
- Dual-lens camera system with flash and glass covers
- Metal frame, glass, and textured back panels

✅ **Lighting & Reflections**
- Multi-source lighting setup (key, fill, rim, hemisphere)
- HDR environment reflections using `RGBELoader`

✅ **Mobile Optimization**
- Responsive GUI layout
- Adaptive antialiasing and pixel ratio
- OrbitControls tuned for touch input

✅ **Interactive GUI (lil-gui)**
- Choose phone color: **Fluid Silver**, **Razor Green**, **Miracle Purple**
- Snap camera to preset views (Front, Rear 3/4, Side)

---

### 🚀 Live Demo
Once you enable **GitHub Pages**, your live version will appear here:  
👉 **[https://alanjoseph77.github.io/RealmeGT_6T_3dModel/realme.html](https://alanjoseph77.github.io/RealmeGT_6T_3dModel/realme.html)**

*(If the link doesn’t work yet, enable Pages under **Settings → Pages → Source: `main` branch (root)`**.)*

---

### 🛠️ How to Run Locally

#### Option 1 — Quick Open
Just open `realme.html` in your browser.

#### Option 2 — Run a Local Server
If some textures don’t load locally due to CORS restrictions, run a simple local server:

```bash
# Using Python 3
python -m http.server 8000
# Then open:
# http://localhost:8000/realme.html
