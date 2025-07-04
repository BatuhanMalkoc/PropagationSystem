# Mesh Propagation Tool for Unity

A simple and efficient tool for scattering meshes across your Unity scenes using a custom brush system.

![Preview](https://your-image-url.com/preview.gif)

---

## 🚀 Features

- Paint meshes directly into the scene
- Supports custom brushes and mesh densities
- Runtime visibility with propagation system
- Camera-based mesh culling system

---

## 🔧 Requirements

- Unity 2021.3 LTS or higher
- URP or Built-in Render Pipeline
- No external dependencies

---

## 📦 Installation

1. Clone or download this repository
2. Open your Unity project
3. Drag and drop the `MeshPropagation` folder into your `Assets/` directory

---

## 🧠 How To Use

1. Right-click in the Project window → `Create > Propagation > New Scene Propagation Data`
2. Drag the created asset into the Scene Data field in the Propagation window
3. Add a mesh (e.g. Capsule) and assign `mPropagationDefault` as material
4. Place a `Plane` under the scene as a surface
5. Use brush settings to paint meshes in the scene
6. To make meshes appear in play mode:
    - Right-click in Hierarchy → `Propagation System > Create Propagation System`
    - Assign your `Scene Propagation Data` and `Main Camera`
    - Add the `OnCameraUpdate` component to the camera

---

## 📄 License

MIT License

---

## 🙋‍♂️ Author

Made with ❤️ by [YourNameHere](https://your-website-or-github.com)