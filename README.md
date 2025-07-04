````markdown
# Mesh Propagation System for Unity

A **GPU-driven**, high-performance propagation tool that lets you scatter and stream millions of meshes in real time—now optimized for both mobile and desktop platforms, and fully open-source.

## 📹 Tutorial Series

Explore the complete workflow through step-by-step video tutorials:

- [Setup and Core Architecture](https://www.youtube.com/playlist?list=YOUR_PLAYLIST_ID_1)
- [GPU-Driven Scatter & Compute Shaders](https://www.youtube.com/playlist?list=YOUR_PLAYLIST_ID_2)
- [Frustum Culling & Performance Optimization](https://www.youtube.com/playlist?list=YOUR_PLAYLIST_ID_3)
- [Mobile Platform Fine-Tuning](https://www.youtube.com/playlist?list=YOUR_PLAYLIST_ID_4)

---

## 🚀 Core Highlights

- **GPU-Driven Scattering**: Compute-shader based propagation for up to **millions of instances** without frame drops.
- **Instant Frustum Culling**: Camera-based visibility culling via compute buffers.
- **Customizable Brushes**: Define brush shapes, density curves, and randomization channels.
- **Render Pipeline Support**: Dedicated support for **Universal Render Pipeline (URP)**.
- **Cross-Platform**: Optimized for mobile devices and high-end PCs with LOD integration.
- **Artist-Centric**: Intuitive editor UI—no coding required to start painting meshes.

---

## 🔧 Prerequisites

- **Unity** 2021.3 LTS or newer
- **Universal Render Pipeline (URP)**
- GPU capable of **Compute Shaders**

---

## 📦 Installation

1. Clone or download the repository:
   ```bash
   git clone https://github.com/YourNameHere/MeshPropagation.git
````

2. In your Unity project, import the package:

   * Drag the entire `MeshPropagation/` folder into your project's `Assets/` directory.

---

## ⚙️ Quick Start

1. **Create Propagation Data**

   * Right-click in the **Project** window → `Create > Propagation > New Scene Propagation Data`.
2. **Configure the System**

   * Open **Window > Propagation System**.
   * Assign your newly created **Scene Propagation Data** asset and your **Main Camera**.
3. **Paint Meshes**

   * Select a surface object (e.g., a `Plane`) in the **Scene**.
   * Adjust brush parameters: **Radius**, **Density**, **Randomness**.
4. **Assign Mesh & Material**

   * In the **Propagate** panel, add your chosen mesh(es) and select a material (default: `mPropagationDefault`).
5. **Play Mode**

   * Enter **Play Mode** to see the propagation in action, complete with streaming and culling.

---

## 📈 Performance Tips

* **Density Falloff**: Use density curves to lessen overdraw at greater distances.
* **LOD Integration**: Pair with Unity LOD Groups for hierarchical detail management.
* **GPU Instancing**: Use similar meshes and materials to leverage instancing benefits.

---

## 🛠️ Contributing & Feedback

> ⚠️ **Alpha Release**
>
> This tool is in *alpha*. For bug reports or feature requests, please open an issue on GitHub.

1. Fork the repository and create a feature branch: `feature/YourFeature`
2. Commit changes with descriptive messages
3. Open a **Pull Request** against the `main` branch

---

## 📄 License

Released under the **MIT License** — see [LICENSE](LICENSE) for full details.

---

## 🙋‍♂️ Author & Contact

Developed with ❤️ by **Batuhan Malkoç** ([GitHub](https://github.com/YourNameHere))

> *"Rendering the future—one mesh at a time.*"

```
```
