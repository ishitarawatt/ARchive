<div align="center">

# 🧩 ARchive

### Cross-Platform Augmented Reality System

**Scan an image. See it come alive, on the web or on your phone.**

![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white)
![WebXR](https://img.shields.io/badge/WebXR-Web%20AR-FF6B35?style=for-the-badge)
![Unity](https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

[**▶ Watch the demo**](DEMO_LINK)

</div>

---

## 📖 Overview

ARchive is a hybrid augmented reality system that delivers the **same marker-based AR experience on both the web and mobile**. Point a camera at an image marker and ARchive recognises it, then overlays a **3D model or video** on top of the real world in real time.

## 🎯 The problem

| Challenge with today's AR | Impact |
|---|---|
| **Limited cross-platform access** | Experiences are locked to a single app or device |
| **High technical complexity** | Creating AR content requires specialist skills |
| **Static, rigid content** | Overlays are hard-wired and difficult to update |

## 💡 The solution

ARchive pairs a **browser-based AR experience** (no install needed) with a **native mobile AR app**, both driven by a **shared backend** that maps each image marker to its content. Updating what a marker shows means changing the mapping, not rebuilding the app.

---

## ⚙️ How it works

```
 ┌────────────┐     ┌────────────────┐     ┌──────────────────┐     ┌──────────────┐
 │  Camera    │ ──▶ │ Image marker   │ ──▶ │ Shared backend:  │ ──▶ │ 3D model /   │
 │  (web or   │     │ recognition    │     │ marker → content │     │ video overlay│
 │  mobile)   │     │                │     │ mapping          │     │ in real time │
 └────────────┘     └────────────────┘     └──────────────────┘     └──────────────┘
```

1. The user opens the web AR page or the mobile app and grants camera access.
2. The camera feed is scanned for a known **image marker**.
3. On a match, the system looks up the content linked to that marker.
4. The matching **3D model or video** is anchored over the marker.

---

## ✨ Features

- 🌐 **Web AR** built with Three.js and WebXR
- 📱 **Mobile AR** built with Unity and AR Foundation
- 🔍 **Image-based recognition** for marker detection
- 🎬 **3D model and video overlays**
- 🗂️ **Shared backend** for content-to-marker mapping
- 🎨 **Responsive, user-friendly interface**

## 🛠️ Tech stack

| Layer | Technologies |
|---|---|
| **Web AR** | Three.js, WebXR, JavaScript, HTML, CSS |
| **Mobile AR** | Unity, AR Foundation, C# |
| **Design & assets** | Figma, Cinema 4D |

---

## 🖼️ Screenshots

<div align="center">

| | | |
|:---:|:---:|:---:|
| <img src="1.jpeg" width="220"> | <img src="2.jpeg" width="220"> | <img src="3.jpeg" width="220"> |
| <img src="4.jpeg" width="220"> | <img src="5.jpeg" width="220"> | <img src="9.jpeg" width="220"> |

</div>

---

## 🗺️ Roadmap

- [ ] Publish the web and mobile source in this repo
- [ ] Add setup and run instructions
- [ ] Admin interface to manage marker-to-content mappings
- [ ] Support for more content types beyond models and video

## 📄 License

Released under the [MIT License](LICENSE).

<div align="center">

*Built by [Ishita Rawat](https://github.com/ishitarawatt)*

</div>
