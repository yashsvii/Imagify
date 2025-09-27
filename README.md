# React + Vite

# Imagify 🎨

**Imagify** is a full-stack AI image generation web app built using the **MERN stack**. Users can input a text prompt to generate stunning images using the **ClipDrop API (Stable Diffusion)**. The app includes authentication, image saving, sharing, and downloading features — all wrapped in a sleek Tailwind-powered UI.

---

## ✨ Features

- 🧠 **AI-Powered Generation** — Generate images from text using ClipDrop (Stable Diffusion)
- 👤 **User Authentication** — Signup / Login system with JWT
- 💾 **Save Images** — Users can save generated images to their profile
- 📤 **Share & Download** — Instantly share or download your creations
- 🖥️ **Responsive UI** — Built with Tailwind CSS for a clean, mobile-friendly design

---

## 🛠 Tech Stack

### 🔹 Frontend

- React.js
- Tailwind CSS

### 🔹 Backend

- Node.js
- Express.js

### 🔹 Database

- MongoDB (with Mongoose)

### 🔹 External API

- [ClipDrop API](https://clipdrop.co/apis) — for AI image generation

### 🔹 Hosting

- 🔗 [Imagify is Live](https://imagify-pzo3.onrender.com)

---

## ⚙️ Environment Variables

Create a `.env` file in your **backend** directory with the following variables:

```env
CLIPDROP_API_KEY=your_clipdrop_api_key
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret_key
PORT=5000
```
