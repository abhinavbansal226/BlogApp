# 💬 Real-Time Chat Application (MERN + Socket.IO)

A full-stack real-time chat application built using the **MERN stack** (MongoDB, Express, React, Node.js) and **Socket.IO** for instant messaging and user presence. This project includes modern features like user authentication, image uploads, profile management, and online/offline indicators—all styled with Tailwind CSS and deployed on Vercel.

---

## 🚀 Features

- 🗃️ **MERN Stack:** MongoDB, Express.js, React.js, Node.js
- ⚡ **Real-Time Messaging:** Instant chat updates and user status via Socket.IO
- 🔐 **Authentication:** Secure login/signup using JWT and bcrypt
- 📸 **Image Uploads:** Cloudinary integration for chat and profile images
- 🔍 **User Search:** Search bar for finding users in real-time
- 🎨 **Responsive UI:** Tailwind CSS with React Router for smooth navigation
- 🌐 **Deployed on Vercel:** Frontend & backend deployed with environment configurations

---

## 🛠️ Tech Stack

| Frontend            | Backend             | Real-Time | Styling        | Storage        | Deployment |
|---------------------|---------------------|-----------|----------------|----------------|------------|
| React + Vite        | Node.js + Express   | Socket.IO | Tailwind CSS   | MongoDB + Cloudinary | Vercel     |

---

## 📦 Project Structure

### Frontend
- **React** app bootstrapped with **Vite**
- **React Router DOM** for routing
- **Tailwind CSS** for styling
- **Context API** for Auth and Chat state
- **Image Uploads** to Cloudinary (base64 encoding)
- Routes: Login, Homepage, Profile

### Backend
- **Express Server**
- **Mongoose** for MongoDB models
- **JWT** for authentication
- **Socket.IO** for real-time events
- **Cloudinary** for image storage
- **CORS**, **dotenv**, and more for environment config and cross-origin support

