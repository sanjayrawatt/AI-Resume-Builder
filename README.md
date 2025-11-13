📌 AI Resume Builder — Full-Stack SaaS App (React, Node.js, Gemini AI, ImageKit)

Create, edit, enhance, and download professional resumes using an AI-powered full-stack application.
Built with React + Vite, Node.js + Express, MongoDB, Google Gemini AI, and ImageKit for smart image processing.

🚀 Live Demo
🌐 Frontend:

https://ai-resume-builder-rho-snowy.vercel.app/

🟩 Backend API:

https://ai-resume-builder-backend-ielq.onrender.com/

📖 About the Project

The AI Resume Builder is a modern SaaS-style resume creation tool powered by AI.
It enables users to:

✔ Create and manage multiple resumes
✔ Auto-fill sections with smart suggestions
✔ Enhance content using Google Gemini AI
✔ Clean profile images using background removal & face-center cropping
✔ Preview resumes in real-time
✔ Use multiple modern resume templates
✔ Download resumes as PDF
✔ Securely store data in MongoDB
✔ Login/Register to access saved resumes
✔ Share resume publicly via link

This project uses separate frontend and backend deployments (Vercel + Render) and follows real-world architecture.

✨ Features
🔥 AI-Powered Enhancements

Auto-generate resume summary (Gemini AI)

Improve job descriptions

Generate professional bullet points

Rewrite experience in a polished tone

“One-click Enhance” button for every section

🎨 Resume Builder Tools

Real-time WYSIWYG preview

Multiple modern templates

Customizable fonts & styling

Add/remove sections dynamically

Auto-save to database

Public resume share link

🖼 Image Processing

Powered by ImageKit:

Remove image background

Auto crop & face-center

Optimize for resume layouts

🔐 Authentication & Dashboard

Register / Login

JWT-based authentication

Manage multiple resumes

Edit / delete resumes

Cloud-based storage in MongoDB

📦 Tech Stack
Frontend

React.js (Vite)

Tailwind CSS

React Router

Zustand / Context API (optional)

PDF Export

Backend

Node.js

Express.js

MongoDB + Mongoose

CORS

ImageKit SDK

AI

Google Gemini API (OpenAI-compatible endpoints)

Deployment

Backend: Render

Frontend: Vercel

Database: MongoDB Atlas

🛠️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/sanjayrawatt/AI-Resume-Builder.git
cd AI-Resume-Builder

2️⃣ Backend Setup
cd server
npm install


Create .env in /server:

MONGODB_URI=your_mongo_uri
JWT_SECRET=your_secret
OPENAI_API_KEY=your_gemini_key
OPENAI_BASE_URL=https://generativelanguage.googleapis.com/v1beta/openai/
OPENAI_MODEL=gemini-2.5-flash
IMAGEKIT_PRIVATE_KEY=your_key
IMAGEKIT_PUBLIC_KEY=your_key
IMAGEKIT_URL_ENDPOINT=your_url


Run server:

npm start

3️⃣ Frontend Setup
cd client
npm install


Create .env in /client:

VITE_API_URL=http://localhost:3000


Run frontend:

npm run dev

🌐 Deployment
Backend (Render)

Set root directory: server

Build command: npm install

Start command: npm start

Add all environment variables

Deploy ✨

Frontend (Vercel)

Root directory: client

Framework: Vite

Environment variable:

VITE_API_URL=https://your-backend.onrender.com


Deploy ⚡

📸 Screenshots

(Add your screenshots here)

🧩 Folder Structure
AI-Resume-Builder/
│
├── client/                # React frontend
│   ├── src/
│   ├── components/
│   ├── templates/
│   └── ...
│
├── server/                # Node backend
│   ├── configs/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   └── server.js
│
└── README.md

🤝 Contributing

Pull requests are welcome!
For major changes, open an issue first.

📜 License

This project is licensed under the MIT License.

💬 Contact

Made by Sanjay Singh Rawat
🔗 GitHub: https://github.com/sanjayrawatt

🔗 Portfolio: https://sanjay-singh-rawat-portfolio.netlify.app/
