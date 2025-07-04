# Mesh Propagation System for Unity

A **GPU-driven**, high-performance propagation tool that lets you scatter and stream millions of meshes in real time—optimized for mobile and desktop platforms, and fully open-source.

## 📹 Tutorial Series

Explore the complete workflow through step-by-step video tutorials:

- [Setup and Core Architecture](https://www.youtube.com/playlist?list=YOUR_PLAYLIST_ID_1)
- [GPU-Driven Scatter & Compute Shaders](https://www.youtube.com/playlist?list=YOUR_PLAYLIST_ID_2)
- [Frustum Culling & Performance Optimization](https://www.youtube.com/playlist?list=YOUR_PLAYLIST_ID_3)
- [Mobile Platform Fine-Tuning](https://www.youtube.com/playlist?list=YOUR_PLAYLIST_ID_4)

---

## 🚀 Core Highlights

- **GPU-Driven Scattering**: Compute shader propagation for millions of instances without frame drops.
- **Instant Frustum Culling**: Visibility culling via compute buffers, per camera.
- **Customizable Brushes**: Create brush shapes, density curves, and randomization channels.
- **URP Support Only**: Built exclusively for the Universal Render Pipeline.
- **Cross-Platform**: Mobile and desktop optimizations, with LOD integration.
- **Artist-Centric**: User-friendly editor UI—no scripting required.

---

## 🔧 Prerequisites

- Unity 2021.3 LTS or newer
- Universal Render Pipeline (URP)
- GPU with compute shader support

---

## 📦 Installation

1. Clone the repository:
   - git clone https://github.com/YourNameHere/MeshPropagation.git
2. Import into your Unity project:
   - Drag and drop the **MeshPropagation** folder into your **Assets** directory

---

## ⚙️ Quick Start

1. **Create Propagation Data**: Right-click in **Project** → Create > Propagation > New Scene Propagation Data.
2. **Configure**: Open **Window > Propagation System**, assign your data asset and **Main Camera**.
3. **Paint Meshes**: Select a surface (e.g., a Plane), adjust brush **Radius**, **Density**, and **Randomness**.
4. **Assign Assets**: In the Propagate panel, add meshes and select a material (default: mPropagationDefault).
5. **Play**: Enter Play Mode; meshes will stream and cull dynamically.

---

## 📈 Performance Tips

- Use density falloff curves to reduce overdraw at distance.
- Pair with Unity LOD Groups for hierarchical detail.
- Leverage GPU instancing by grouping similar meshes/materials.

---

## 🛠️ Contributing & Feedback

> This tool is in alpha. For bug reports or feature requests, please open an issue on GitHub.

1. Fork and branch: feature/YourFeature
2. Commit with descriptive messages
3. Submit a Pull Request to main

---

## 📄 License

MIT License

---

## 🙋‍♂️ Author & Contact

Developed with ❤️ by **Batuhan Malkoç** ([GitHub](https://github.com/YourNameHere))

> _"Rendering the future—one mesh at a time._"