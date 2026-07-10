# Mandelbrot Explorer v2026 - fractal explorer 2026

> **Browser-based Mandelbrot exploration with realtime deep zoom, WebGPU acceleration, and Rust/WASM rendering for version 2026.**

[![Platform](https://img.shields.io/badge/Platform-web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/millertom73/mandelbrot-explorer-v2026?style=flat-square)](https://github.com/millertom73/mandelbrot-explorer-v2026)

---

<p align="center">
  <a href="https://millertom73.github.io/mandelbrot-explorer-v2026/">
    <img src="https://img.shields.io/badge/Download-Mandelbrot%20Explorer%20Latest-brightgreen?style=for-the-badge" alt="Download Mandelbrot Explorer">
  </a>
</p>

> **[Direct Download - Mandelbrot Explorer v2026](https://millertom73.github.io/mandelbrot-explorer-v2026/)**

---

[Download Latest Build](https://millertom73.github.io/mandelbrot-explorer-v2026/)

---

## What is Mandelbrot Explorer?

Mandelbrot Explorer is a web-based fractal viewer built for interactive Mandelbrot rendering, fluid navigation, and extremely deep zoom exploration. It pairs WebGPU compute shaders with WebAssembly and Rust-driven computation so the experience stays responsive while fine detail is preserved as you move deeper into the set.

It is a solid fit for fractal study, color and orbit-visualization experiments, or inspecting highly intricate regions without leaving the browser. The rendering flow relies on progressive refinement and zoom reprojection, making it suitable for casual exploration as well as more technical analysis.

---

## Features

- Realtime Mandelbrot rendering in the browser
- Deep zoom support with perturbation theory
- Arbitrary-precision reference orbit computation
- WebGPU compute shader acceleration
- Progressive refinement for improving image detail over time
- Zoom reprojection to maintain visual continuity while navigating
- Advanced palette controls and orbit-based coloring
- 3D material rendering for alternate visual presentations

---

## Installation

1. Clone or download the repository:
   - `git clone https://github.com/millertom73/mandelbrot-explorer-v2026.git
2. Open the web build in a browser that supports the required graphics features.
3. If you are running a local server, launch it from the project folder and load the app in your browser.

Example:

`python -m http.server`

Then visit the local address shown by the server and open the application.

---

## Usage

Open the explorer in a supported browser, then pan around the fractal and zoom into any region you want to inspect. The renderer continues refining the image as more information becomes available, which is especially helpful when you are working near dense boundary areas.

Typical workflow:
- Open the app
- Navigate with zoom and pan controls
- Adjust palette or orbit coloring settings
- Move deeper into the fractal to inspect fine structure
- Use the 3D rendering mode when you want a different visual perspective

If you are measuring performance, compare shallow zooms with deep zoom behavior and watch how refinement and reprojection influence the image.

---

## Configuration

Settings are exposed through the web interface and may also be retained in browser state, depending on how the build is hosted. Common options include:

- Palette selection
- Orbit coloring controls
- Rendering quality or refinement behavior
- Deep zoom-related parameters
- 3D material rendering options

If your deployment adds a local configuration file or build-time setting, keep it with the browser build assets used by the app.

---

## Requirements

- A modern web browser
- WebGPU support for accelerated rendering
- WebAssembly support
- Sufficient GPU capability for deep zoom rendering
- Adequate system memory for high-detail exploration
- A local or hosted web environment to serve the app

---

## FAQ

**How do I update the project?**  
Pull the newest changes from the repository, or swap your deployed build for the latest release artifacts.

**Why does deep zoom take longer to refine?**  
Highly detailed areas need more computation, particularly when perturbation theory and high-precision orbit handling are involved.

**Where are the settings saved?**  
For most browser-based deployments, settings live in the app UI and may persist through browser storage.

**What should I do if the app does not render correctly?**  
Verify that your browser supports WebGPU and WebAssembly, then try a different compatible browser or update your graphics drivers.

**Can I tweak the visuals?**  
Yes. Palette controls, orbit coloring, and 3D material rendering offer multiple ways to change the look.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
