# 🧠 AI-Powered Blog Application (MST Stack + Google Gemini)

This full-stack AI-enabled blog application is built using the **MST stack** — MongoDB, Express, React, and Node.js — with **Google Gemini AI** integration for auto-generating blog content. The project includes media optimization using **ImageKit**, a secure admin dashboard, and real-time blog/comment management. The entire app is deployed on **Vercel** with proper environment configuration for a production-ready experience.

---

## 🚀 Features

- 🤖 AI-generated blog content using Google Gemini
- 🗃️ Full CRUD blog & comment management with secure admin login
- 🖼️ Real-time media upload and optimization with ImageKit
- 🔐 JWT-based authentication and protected routes
- ✍️ Rich text editor (React-Quill) with Markdown parsing
- 🌐 Frontend and backend deployed on Vercel
- 📊 Dynamic dashboard with blog & comment analytics

---

## 🛠️ Tech Stack

| Frontend        | Backend           | AI Integration  | Media Handling  | Deployment |
|----------------|-------------------|-----------------|------------------|------------|
| React + Vite   | Node.js + Express | Google Gemini API | ImageKit + Multer | Vercel     |

---

## 📦 Project Structure

### 🖥️ Frontend
- Built with **Vite + React**
- **React Router** for page routing
- **React-Quill** for blog editing
- **Tailwind CSS** for responsive styling
- **Context API** for auth & global state

### 🌐 Backend
- **Node.js + Express** with modular routes/controllers
- **Mongoose** for MongoDB integration
- **JWT** for admin authentication
- **Multer** for image uploads
- **Google Gemini API** for AI-based content generation

---

## 🧠 AI-Powered Content Creation

- Uses **Google Gemini API** to automatically generate full blog descriptions from titles.
- AI generation is triggered during blog creation in the admin dashboard.
- Loading state and toast notifications handle asynchronous API feedback.

---

## 📂 Image Upload & Optimization

- **Multer** handles file parsing on backend.
- Images are uploaded to **ImageKit**, where they are compressed, resized, and served in optimized formats (e.g., WebP).
- URLs are saved in MongoDB for retrieval.

---

## 🛡️ Authentication & Authorization

- JWT tokens issued on admin login
- Protected routes for blog/comment CRUD operations
- Tokens stored and managed via localStorage and React Context

---

## 📑 Admin Dashboard

- View, publish/unpublish, delete blogs
- Approve/delete user comments
- Add blogs with AI-powered content generation
- Dashboard metrics: total blogs, drafts, comments, etc.


