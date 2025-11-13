# 📌 AI Resume Builder — Full-Stack SaaS App (React, Node.js, Gemini AI, ImageKit)

Create, enhance, and download professional resumes using an AI-powered full-stack application.  
Built with **React + Vite**, **Node.js**, **Express**, **MongoDB**, **Google Gemini AI**, and **ImageKit**.

---

## 🚀 Live Demo

### 🌐 Frontend  
🔗 https://ai-resume-builder-rho-snowy.vercel.app/

### 🟩 Backend API  
🔗 https://ai-resume-builder-backend-ielq.onrender.com/

---

## 📖 About the Project

The **AI Resume Builder** is a modern SaaS-style resume creation tool powered by AI. It enables users to:

- ✔ Create and manage multiple resumes  
- ✔ Auto‑fill sections with smart suggestions  
- ✔ Enhance content using **Google Gemini AI**  
- ✔ Clean profile images (background removal + face-centering)  
- ✔ Preview resumes in real-time  
- ✔ Use multiple modern templates  
- ✔ Download resumes as PDF  
- ✔ Securely store data in MongoDB  
- ✔ Login/Register to access saved resumes  
- ✔ Share resume publicly via link  

This project uses **separate frontend and backend deployments (Vercel + Render)** and follows real‑world production architecture.

---

## ✨ Features

### 🔥 AI‑Powered Enhancements
- Auto-generate resume summary (Gemini AI)  
- Improve job descriptions  
- Rewrite experience in professional tone  
- Generate bullet points  
- “One‑click Enhance” for all sections  

---

### 🎨 Resume Builder
- Real-time WYSIWYG preview  
- Modern templates  
- Customizable fonts and layout  
- Add/remove dynamic sections  
- Auto-save to database  
- Public shareable resume link  

---

### 🖼 Image Processing (ImageKit)
- Remove background  
- Auto crop + face-center  
- Optimize for resume layouts  

---

### 🔐 Authentication & Dashboard
- Register / Login  
- JWT-based authentication  
- Manage multiple resumes  
- Edit / delete  
- MongoDB cloud storage  

---

## 🧰 Tech Stack

### Frontend  
- React.js (Vite)  
- Tailwind CSS  
- React Router  
- Zustand / Context API  
- PDF Export tools  

### Backend  
- Node.js  
- Express.js  
- MongoDB (Atlas)  
- Mongoose  
- CORS  
- ImageKit SDK  

### AI  
- Google Gemini API  
- OpenAI-compatible REST endpoint  

### Deployment  
- **Frontend:** Vercel  
- **Backend:** Render  
- **Database:** MongoDB Atlas  

---

## 🛠 Installation & Setup

### 1️⃣ Clone Repo
```bash
git clone https://github.com/sanjayrawatt/AI-Resume-Builder.git
cd AI-Resume-Builder
```

---

### 2️⃣ Backend Setup
```bash
cd server
npm install
```

Create `.env`:

```
MONGODB_URI=your_mongo_uri
JWT_SECRET=your_secret
OPENAI_API_KEY=your_gemini_key
OPENAI_BASE_URL=https://generativelanguage.googleapis.com/v1beta/openai/
OPENAI_MODEL=gemini-2.5-flash
IMAGEKIT_PRIVATE_KEY=your_key
IMAGEKIT_PUBLIC_KEY=your_key
IMAGEKIT_URL_ENDPOINT=your_url
```

Run:
```bash
npm start
```

---

### 3️⃣ Frontend Setup
```bash
cd client
npm install
```

Create `.env`:
```
VITE_API_URL=http://localhost:3000
```

Run:
```bash
npm run dev
```

---

## 🌐 Deployment Guide

### **Backend on Render**
- Root Directory → `server`
- Build Command → `npm install`
- Start Command → `npm start`
- Add environment variables  
- Deploy  

### **Frontend on Vercel**
- Root Directory → `client`
- Framework → Vite  
- Add env:  
```
VITE_API_URL=https://your-backend.onrender.com
```
- Deploy  

---

## 📁 Folder Structure
```
AI-Resume-Builder/
│
├── client/          # React Frontend
│   ├── src/
│   ├── components/
│   ├── templates/
│   └── ...
│
├── server/          # Node Backend
│   ├── configs/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   └── server.js
│
└── README.md
```

---

## 🤝 Contributing
Pull requests are welcome. For major changes, open an issue first.

---

## 📜 License
MIT License

---

## 💬 Contact  
**Sanjay Singh Rawat**  
GitHub: https://github.com/sanjayrawatt  
Portfolio: https://sanjay-singh-rawat-portfolio.netlify.app/
