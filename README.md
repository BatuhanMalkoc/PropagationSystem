# Mesh Propagation System for Unity

A **GPU-driven**, high-performance propagation tool that lets you scatter and stream millions of meshes in real time—optimized for mobile and desktop platforms, and fully open-source.

## 📹 Tutorial Series

Step-by-step video tutorials covering all core workflows:

- [Tutorial 1: How To Install Propagation System For The First Time](https://youtu.be/9PUoShCcgsU)
- [Tutorial 2: How To Propagate Your First Mesh](https://youtu.be/Bav2IcHjNL0ve)
- [Tutorial 3: How To Make Your Propagation Meshes Visible In Play Mode](https://youtu.be/YrH5NkR8akY)

---

## 🚀 Core Highlights

- **GPU-Driven Scattering**: Built entirely on Unity’s latest Indirect Rendering system—enabling millions of mesh instances without traditional instancing bottlenecks.
- **Instant Frustum Culling**: High-performance visibility culling executed with compute shaders
- **Customizable Brushes**: Create brush shapes and randomization channels.
- **Modular MVP Architecture**: Fully modular structure following the MVP (Model-View-Presenter) pattern—clean, scalable, and easy to extend.
- **Cross-Platform**: Mobile and desktop optimizations
- **Artist-Centric**: User-friendly editor UI—no scripting required.

---

## 🔧 Prerequisites

- Unity 2021.3 LTS or newer
- Universal Render Pipeline (URP)
- GPU with compute shader support

---

## 📦 Installation

1. Download the latest release from the [Releases Page](https://github.com/BatuhanMalkoc/PropagationSystem/releases/tag/Alpha).
   - File: `PropagationSystemv0.1.0-alpha.unitypackage`
2. Open your Unity project.
3. Drag and drop the `.unitypackage` file into the **Assets/** folder or import via **Assets > Import Package > Custom Package**.

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