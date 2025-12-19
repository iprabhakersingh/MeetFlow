🎥 MeetFlow — Real-Time Video Conferencing App

MeetFlow is a real-time video conferencing web application built using the MERN stack, WebRTC, and Socket.IO. It allows users to instantly join meetings via a shared link, communicate through live video/audio, chat in real time, and share screens — all directly in the browser.

🚀 Live Demo:
👉 https://meetflow-frontend.onrender.com/

✨ Features

🔴 Real-time Video & Audio Calling (WebRTC)

👥 Multi-user conferencing

💬 Live chat during meetings

🎥 Camera on/off control

🎙️ Microphone mute/unmute

🖥️ Screen sharing support

🔗 Join meeting via URL

⚡ Low-latency communication using Socket.IO

🌐 Fully deployed on Render

🛠️ Tech Stack
Frontend

React.js

Material UI (MUI)

WebRTC

Socket.IO Client

CSS Modules

Backend

Node.js

Express.js

Socket.IO

WebRTC Signaling Server

Database

MongoDB (for extensibility / future enhancements)

Deployment

Render (Frontend & Backend)

🔄 How It Works

User enters a username and joins the lobby

A unique meeting URL is used to connect participants

Socket.IO handles signaling between peers

WebRTC establishes peer-to-peer media connections

Users can:

Toggle video/audio

Share screen

Chat in real time

When a user leaves, streams are automatically updated

⚙️ Installation & Setup (Local)
1️⃣ Clone the repository
git clone https://github.com/your-username/meetflow.git
cd meetflow

2️⃣ Install dependencies

Frontend

cd frontend
npm install
npm start


Backend

cd backend
npm install
npm start

🔐 Environment Variables

Create a .env file in the backend directory:

PORT=8000


Frontend environment config example:

const server = process.env.NODE_ENV === "production"
  ? "https://your-backend-url.onrender.com"
  : "http://localhost:8000";

export default server;

🌍 Deployment

Frontend deployed on Render

Backend deployed on Render

WebRTC uses Google STUN servers for NAT traversal

🚀 Future Enhancements

🔒 Authentication & private rooms

📹 Meeting recording

👨‍💼 Host controls

📱 Mobile responsiveness improvements

📊 Meeting analytics

🗂️ MongoDB-based meeting history

👨‍💻 Developer

Prabhaker Singh
