# 3D Solar System Simulation

A fully interactive, mobile-friendly 3D Solar System simulation built with [Three.js](https://threejs.org/) and [GSAP](https://greensock.com/gsap/). This simulation includes animated planets, orbit controls, a dynamic starfield, pause/resume functionality, tooltips, pinch-to-zoom (touch support), and zoom-on-double-click for planet focus.

##  Features

- Realistic orbital motion for all 8 planets
- Saturn's iconic rings and Earth's Moon
- Interactive UI for adjusting planet speeds
- Double-click to zoom in/out on planets
- Mouse hover tooltips with planet names
- Pinch-to-zoom support on mobile devices
- Dynamic star background with twinkling effect
- Touch and mouse input supported
- Responsive layout for all screen sizes

---

##  File Structure

```
Vaibhav Pandey.html       # Main HTML file (contains all logic and rendering)
README.md        # You're reading it
```

---

##  Technologies Used

- [Three.js](https://threejs.org/) — 3D engine for rendering and scene creation
- [GSAP](https://greensock.com/gsap/) — Smooth animations
- Vanilla JavaScript — App logic
- HTML5 — Single-page application structure

---

##  Mobile Controls

- **Pinch to Zoom**: Zooms camera in/out using two-finger gesture
- **Touch & Drag**: Not implemented (you can add OrbitControls or custom gestures)

---

##  Desktop Controls

- **Double-click on planet**: Zoom in or out
- **Mouse hover**: Show planet name tooltip
- **Use panel sliders**: Change planet orbit speeds
- **Pause/Resume**: Toggle planetary motion

---

##  How to Run

1. **Clone or Download Repository**
2. Open `Vaibhav Pandey.html` in any modern web browser (Chrome, Firefox, Edge, Safari)
3. No build tools or servers needed (static file)

---

##  Planets Included

| Planet   | Texture Source | Orbit Radius | Size | Initial Speed  |
|----------|----------------|--------------|------|----------------|
| Mercury  | NASA/Wikipedia | 4            | 0.3  | 0.04           |
| Venus    | NASA/Wikipedia | 6            | 0.5  | 0.015          |
| Earth    | NASA/Apollo 17 | 8            | 0.6  | 0.01           |
| Mars     | ESA/OSIRIS     | 10           | 0.4  | 0.008          |
| Jupiter  | NASA           | 13           | 1.2  | 0.005          |
| Saturn   | NASA/Cassini   | 16           | 1.0  | 0.003          |
| Uranus   | Hubble         | 19           | 0.9  | 0.002          |
| Neptune  | Hubble         | 22           | 0.8  | 0.001          |

---

## Credits

- Planet Textures: NASA, Wikimedia Commons, Three.js examples
- Saturn's Rings: [Three.js Fundamentals](https://threejsfundamentals.org/)
- Lens flare: Three.js built-in texture

---

##  Author

Created by Vaibhav Pandey 
