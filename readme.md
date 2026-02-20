# 🌍 Real-Time Location Tracker

A real-time location tracking web application built using **Node.js**, **Express**, and **Socket.io**.

Users can share their live location and see other connected users moving in real time.

---

## 🚀 Live Demo

🔗 https://location-tracker-unhg.onrender.com/

---
IMPORTANT!
Allow the website to access location or it will show blue ocean if you dont want to allow then zoom out your screen

## 📸 Features

- 📡 Real-time location updates
- 👥 Multiple users support
- 🔄 Auto updates when users connect/disconnect
- 🌐 Works on local network and public deployment
- ⚡ Fast WebSocket-based communication

---

## 🛠 Tech Stack

- Node.js
- Express.js
- Socket.io
- EJS
- HTML, CSS, JavaScript

---

## 📂 Project Structure

project-root/
│
├── public/ # Static files (CSS, JS)
├── views/ # EJS templates
├── server.js # Main server file
├── package.json
└── README.md


---

## 🧠 How It Works

1. Client sends location using Geolocation API.
2. Server receives it via Socket.io.
3. Server broadcasts location to all connected clients.
4. When a user disconnects, their marker is removed.

---

## 🖥 Run Locally

```bash
git clone https://github.com/Bhavy-Kakaniya/location-tracker.git
cd location-tracker
npm install
npm start
http://localhost:3000

🎯 Future Improvements

🔐 User authentication

📌 Custom usernames

🗺 Map UI improvements

🗄 Store location history

📱 Mobile UI optimization
