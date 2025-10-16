# 📸 Instagram Clone

> A next-generation **Instagram-like social media application** featuring **Real-time interactions** — built using **React**, **Nest.js** and **WebSocket**.  
> Designed to blend the creativity of visual sharing

---

## 🚀 Features
🗣️ **Real-Time Messaging** – Live chat with WebSocket  
🖼️ **Photo Uploads & Feeds** – Post, like, and comment instantly
📱 **Fully Responsive UI** – Optimized for mobile and desktop  
🔐 **Authentication System** – Secure login & registration flow  

---

## 🧠 Tech Stack

| Category | Technologies |
|-----------|--------------|
| **Frontend** | React.js, TailwindCSS, ShadCN UI |
| **Backend** | Nest.js, REST API ||
| **Database** | MongoDB |
| **Realtime** | WebSocket (Socket.io) |
| **Deployment** | Vercel (Frontend), Render / Railway (Backend) |

---

## 🧩 Architecture Overview

```mermaid
graph TD;
  D --> E[React Frontend 🎨];
  E --> F[WebSocket 💬];
  F --> G[Nest.js Backend 🌍];
  G --> H[MongoDB 💾];
