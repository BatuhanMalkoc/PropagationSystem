````markdown
# Mesh Propagation System for Unity

A **GPU-driven**, high-performance propagation tool that lets you paint and stream millions of meshes in real time—now mobile-friendly and fully open-source.

![Propagation Preview](https://your-image-url.com/preview.gif)

---

## 🚀 Core Highlights

- **GPU-Driven Scatter**: Compute-shader based propagation for up to **millions of instances** with zero Hiccup.
- **Frustum Culling**: Instant camera-based visibility culling using compute buffers.
- **Brush Customization**: Define your own brush shapes, density curves, and randomization channels.
- **Material Agnostic**: Paint with **any mesh** and **any URP/Built-in** material.
- **Mobile & Desktop**: Optimized code paths and LOD support for both high-end PCs and mobile platforms.
- **Artist-Friendly**: Intuitive editor interface—no code required to get started.

---

## 🔧 Prerequisites

- **Unity** 2021.3 LTS or higher
- **Universal Render Pipeline (URP)** or **Built-in RP**
- **Compute Shader** support on target platform

---

## 📦 Installation

1. Clone or download this repository:
   ```bash
   git clone https://github.com/YourNameHere/MeshPropagation.git
````

2. Open your Unity project and import:

   * In the **Project** window, drag the entire `MeshPropagation/` folder into `Assets/`.

---

## ⚙️ Quick Start

1. **Create Propagation Data**

   * Right-click in **Project** → `Create > Propagation > New Scene Propagation Data`.
2. **Assign Data & Camera**

   * Open **Window > Propagation System**. Drag your asset into **Scene Data** and assign **Main Camera**.
3. **Paint Your Surface**

   * Select a surface (e.g., a `Plane`) in the **Scene**. Adjust brush settings (radius, density, randomness).
4. **Assign Mesh & Material**

   * In the **Propagate** panel, add your desired mesh(s) and select a material (default: `mPropagationDefault`).
5. **Run & Enjoy**

   * Enter **Play Mode**. Watch as your meshes stream in and out based on camera view and performance settings.

---

## 📈 Performance Tips

* **Density Curves**: Use fall-off curves to reduce overdraw at distance.
* **LOD & Culling**: Combine with Unity LOD Groups for further optimization.
* **Batching**: Group similar meshes under the same material to benefit from GPU instancing.

---

## 🛠️ Contributing & Feedback

> ⚠️ **Alpha Release**
>
> This tool is in *alpha*. If you encounter issues or have feature requests, please open an issue on GitHub.

1. Fork the repo and create a branch: `feature/YourFeature`
2. Commit your changes with clear messages
3. Submit a **Pull Request** to the `main` branch

---

## 📄 License

This project is released under the **MIT License** — see [LICENSE](LICENSE) for details.

---

## 🙋‍♂️ Author & Contact

Built with ❤️ by **Batuhan Malkoç** ([GitHub](https://github.com/YourNameHere))

> *"Render the future—one mesh at a time.*"

```
```
