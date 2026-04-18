# 💬 Chat App

A full-stack **real-time chat application** built with **React, Node.js, Socket.IO, and MongoDB**, enabling instant messaging with authentication and media support.

---

## 📌 Overview

This Chat App allows users to communicate in real-time with a modern UI.
It includes **secure authentication, live messaging using WebSockets, and image upload support via Cloudinary**.

---

## ✨ Features

* 💬 Real-time messaging (Socket.IO)
* 🔐 User authentication (JWT + bcrypt)
* 🟢 Live online communication
* 🖼️ Image upload support (Cloudinary)
* 📜 Chat history stored in database
* ⚡ Fast and responsive UI (React + Vite)
* 🔔 Toast notifications

---

## 🛠️ Tech Stack

### 🎨 Frontend

* React 19 + Vite
* Tailwind CSS
* Axios
* React Router
* Socket.IO Client
* React Hot Toast

### ⚙️ Backend

* Node.js + Express
* MongoDB + Mongoose
* JWT Authentication
* bcryptjs
* Socket.IO (real-time communication)
* Cloudinary (image storage)

---

## 📂 Project Structure

```bash id="chatstr1"
chat-app/
│
├── client/                # Frontend
│   ├── src/
│   ├── context/
│   └── public/
│
├── server/                # Backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── lib/
│   └── server.js
│
└── README.md
```

---

## ⚙️ Setup

### 1️⃣ Clone

```bash id="chatclone1"
git clone https://github.com/Spicychickenlolipop/chat-app.git
cd chat-app
```

---

### 2️⃣ Backend Setup

```bash id="chatbackend1"
cd server
npm install
```

Create `.env`:

```env id="chatenv1"
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret
CLOUDINARY_CLOUD_NAME=your_name
CLOUDINARY_API_KEY=your_key
CLOUDINARY_API_SECRET=your_secret
```

Run:

```bash id="chatrun1"
npm run server
```

---

### 3️⃣ Frontend Setup

```bash id="chatfrontend1"
cd client
npm install
npm run dev
```

---

## 🚀 Usage

1. Open `http://localhost:5173`
2. Register / Login
3. Select user
4. Send messages in real-time
5. Upload images in chat

---

## 🖼️ Screenshots

<img width="1599" height="820" alt="Screenshot 2026-04-19 001522" src="https://github.com/user-attachments/assets/d240128a-c97b-48ec-be08-5bc6a1a02b01" />
<img width="1192" height="821" alt="Screenshot 2026-03-30 044908" src="https://github.com/user-attachments/assets/f48d1168-19f4-48e8-8772-4ad355822565" />

---

## 🌐 Deployment

* Frontend → Vercel
* Backend → Render
* Database → MongoDB Atlas
* Media → Cloudinary

---

## ⭐ Support

If you like this project, give it a ⭐
