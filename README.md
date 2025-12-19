🎥 MeetFlow — Real-Time Video Conferencing App

MeetFlow is a real-time video conferencing web application built using the MERN stack, WebRTC, and Socket.IO. It allows users to instantly join meetings via a shared link and communicate through live video/audio, in-meeting chat, and screen sharing — all directly in the browser.

🚀 Live Demo  
https://meetflow-frontend.onrender.com/


✨ Features

🔴 Real-time video & audio communication  
👥 Multi-user video conferencing  
💬 Live chat during meetings  
🎥 Camera on/off toggle  
🎙️ Microphone mute/unmute  
🖥️ Screen sharing support  
🔗 Join meeting via URL  
⚡ Low-latency real-time communication  
🌐 Cloud deployed application  


🛠️ Tech Stack

- ⚛️ React.js
- 🟢 Node.js
- 🚂 Express.js
- 🍃 MongoDB
- 📡 WebRTC
- 🔌 Socket.IO
- 🎨 Material UI
- ☁️ Render


🔄 How It Works

1. User enters a username and joins the lobby  
2. A meeting URL connects all participants  
3. Socket.IO handles real-time signaling  
4. WebRTC establishes peer-to-peer media streams  
5. Users can control camera, microphone, screen sharing, and chat  
6. Streams update automatically when users join or leave  


⚙️ Installation & Setup

Clone the repository  
git clone https://github.com/your-username/meetflow.git  
cd meetflow  

Install dependencies and start the application  
npm install  
npm start  


🔐 Environment Configuration

PORT=8000  

Server configuration logic  

const server =
  process.env.NODE_ENV === "production"
    ? "https://your-backend-url.onrender.com"
    : "http://localhost:8000";

export default server;


🌍 Deployment

Deployed on Render  
Real-time communication using Socket.IO  
Peer-to-peer media streaming with WebRTC  
Google STUN servers used for NAT traversal  

🚀 Future Enhancements

🔒 User authentication & private rooms  
📹 Meeting recording  
👨‍💼 Host controls  
📱 Improved mobile responsiveness  
📊 Meeting analytics  
🗂️ Persistent meeting storage  

👨‍💻 Developer

Prabhaker Singh  
