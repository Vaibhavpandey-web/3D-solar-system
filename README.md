<div align="center">

# 3D Solar System

A browser-based experiment in planetary motion, WebGL rendering and interactive controls.

![JavaScript](https://img.shields.io/badge/JavaScript-111827?style=flat-square) ![Three.js](https://img.shields.io/badge/Three.js-111827?style=flat-square) ![GSAP](https://img.shields.io/badge/GSAP-111827?style=flat-square)

</div>

---

[Get started](#run-locally) · [Controls](#controls) · [Source](index.html)

## Highlights

- Sun and eight planets with animated orbital movement.
- Per-planet speed sliders and pause/resume controls.
- Hover labels, double-click camera transitions and touch pinch zoom.
- Starfield, lighting, orbit paths, Moon and Saturn ring geometry.

## Controls

| Action | Interaction |
| --- | --- |
| Change orbital speed | Adjust a planet slider |
| Pause planetary motion | Select Pause / Resume |
| Identify a planet | Hover over it |
| Move camera toward a planet | Double-click it |
| Adjust zoom on touch devices | Pinch with two fingers |

## Run locally

```bash
git clone https://github.com/Vaibhavpandey-web/3D-solar-system.git
cd 3D-solar-system
python -m http.server 8080
```

Open [localhost:8080](http://localhost:8080). External libraries and assets require an internet connection.

<details>
<summary><strong>Implementation and limitations</strong></summary>

The scene and controls are contained in `index.html`. Libraries and most textures are loaded from external URLs. The Saturn ring texture still uses a placeholder URL and needs a real asset. Camera transitions currently continue to look at the scene origin.

Planet sizes, distances and speeds are illustrative rather than scientifically to scale. This is an interactive graphics project, not an astronomical prediction tool.

</details>

## Credits

Planet imagery is referenced from Wikimedia Commons; the scene also references Three.js example assets. Consult the original asset sources for their individual attribution and reuse terms.

---

Built by [Vaibhav Pandey](https://github.com/Vaibhavpandey-web) · [Portfolio](https://vaibhav-pandey-portfolio-henna.vercel.app/)
