# 📸 Instagram Clone (AI + 3D Camera Effects)

> A next-generation **Instagram-like social media application** featuring **AI-powered filters**, **3D camera effects**, and **real-time interactions** — built using **React**, **Node.js**, **TensorFlow.js**, and **WebSocket**.  
> Designed to blend the creativity of visual sharing with the intelligence of artificial vision.

---

## 🚀 Features

💡 **AI-Powered Filters** – Apply real-time smart filters using TensorFlow.js  
🌐 **3D Camera Effects** – Dynamic depth and lighting effects with Three.js  
🗣️ **Real-Time Messaging** – Live chat with WebSocket  
🖼️ **Photo Uploads & Feeds** – Post, like, and comment instantly  
🤳 **Smart Camera Mode** – Face recognition and beauty filter in live preview  
🧠 **AI Landmark Detection** – Detect facial points for effects and animations  
📱 **Fully Responsive UI** – Optimized for mobile and desktop  
🔐 **Authentication System** – Secure login & registration flow  

---

## 🧠 Tech Stack

| Category | Technologies |
|-----------|--------------|
| **Frontend** | React.js, TailwindCSS, ShadCN UI |
| **Backend** | Node.js, Express.js, REST API |
| **AI / ML** | TensorFlow.js, MediaPipe FaceMesh |
| **3D Graphics** | Three.js, GSAP |
| **Database** | MongoDB |
| **Realtime** | WebSocket (Socket.io) |
| **Deployment** | Vercel (Frontend), Render / Railway (Backend) |

---

## 🧩 Architecture Overview

```mermaid
graph TD;
  A[Camera Stream 📸] --> B[TensorFlow.js 🤖];
  B --> C[Facial Landmark Detection 🧠];
  C --> D[3D Effects Renderer 🌈];
  D --> E[React Frontend 🎨];
  E --> F[WebSocket 💬];
  F --> G[Node.js Backend 🌍];
  G --> H[MongoDB 💾];
