# 📹 Video Calling App.

> A real-time peer-to-peer video calling application built with **WebRTC**, **Node.js**, and **React.js** — empowering seamless communication through the browser.

---

## ✨ Features

- 🔗 **Peer-to-Peer WebRTC Connection**
- 💬 **Real-Time Video & Audio Calling**
- 🔒 **End-to-End Encryption**
- ⚡ **Low Latency & High Performance**
- 🌐 **Works in All Modern Browsers**
- 🎯 **No Installation Required**

---

## 🛠️ Tech Stack

| Layer       | Technologies Used                      |
|-------------|----------------------------------------|
| Frontend    | React.js, HTML5, CSS3                  |
| Backend     | Node.js, Express.js                    |
| Real-Time   | WebRTC (RTCPeerConnection, DataChannel)|
| Signaling   | WebSockets / Socket.IO                 |
| STUN/TURN   | Google STUN Server / Coturn (optional) |

---

## 📁 Project Structure

videoCalling/
├── backend/ # Node.js signaling server
│ └── app.js # Entry point for server
├── frontend/ # React client
│ └── src/ # App components & logic
└── README.md # Project documentation

yaml
Copy
Edit

---

## 🚀 Getting Started

### ✅ Prerequisites

- Node.js (v14+)
- npm or yarn
- Modern browser (Chrome, Firefox, etc.)

### 📦 Installation

```bash
# Clone the repository
git clone https://github.com/Khushikumari2/videoCalling.git
cd videoCalling

# Backend setup
cd backend
npm install

# Frontend setup
cd ../frontend
npm install
▶️ Run the Application
bash
Copy
Edit
# Start backend
cd backend
npm start

# Start frontend
cd ../frontend
npm start
Open your browser and go to: http://localhost:3000

Share your ID with a friend and start video calling! 🎥👯‍♀️

