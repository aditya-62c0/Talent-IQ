# 🧠 Talent IQ – Real-Time Collaborative Coding Platform

## 📋 Overview
**Talent IQ** is a real-time collaborative coding platform built using the **MERN stack**. It enables users to sign in, join coding sessions, and collaborate live with others to solve problems and discuss solutions. The platform integrates **Clerk** for authentication and **Stream API** for real-time communication.

---

## 🚀 Features
- 🔐 Secure user authentication using **Clerk**
- 💬 Real-time collaboration via **Stream API**
- 🧑‍💻 Live coding sessions with multiple participants
- 📊 User and session management using **MongoDB**
- 🎨 Responsive and modern UI using **React, Tailwind CSS, and DaisyUI**
- ⚡ Built with **Vite** for lightning-fast frontend development

---

## 🧩 Tech Stack
**Frontend:** React.js, Vite, Tailwind CSS, DaisyUI  
**Backend:** Node.js, Express.js  
**Database:** MongoDB Atlas  
**Authentication:** Clerk  
**Real-Time Communication:** Stream API  

---

## ⚙️ Local Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/talent-iq.git
cd talent-iq
```

### 2️⃣ Setup Backend
```bash
cd backend
npm install
cp .env.example .env
# Fill in your credentials in the .env file
npm run dev
```

### 3️⃣ Setup Frontend
```bash
cd ../frontend
npm install
cp .env.example .env
# Add your frontend keys and backend URL
npm run dev
```

**Now open:** http://localhost:5173

---

## 🌐 Environment Variables

### Backend (.env)
```
PORT=3000
NODE_ENV=development
DB_URL=your_mongodb_connection_url
INNGEST_EVENT_KEY=your_inngest_event_key
INNGEST_SIGNING_KEY=your_inngest_signing_key
STREAM_API_KEY=your_stream_api_key
STREAM_API_SECRET=your_stream_api_secret
CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
CLIENT_URL=http://localhost:5173
```

### Frontend (.env)
```
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
VITE_API_URL=https://your-backend-url/api
VITE_STREAM_API_KEY=your_stream_api_key
```

---

## ☁️ Deployment

### 🔸 Deploy Backend (Render or Railway)
1. Push your backend folder to a **separate GitHub repo** (or subfolder).
2. Go to [Render](https://render.com) → **New Web Service** → Connect your GitHub repo.
3. Add all backend environment variables.
4. Build Command: `npm install`
5. Start Command: `npm start`
6. After deployment, note your backend URL (e.g. `https://talent-iq-backend.onrender.com`).

---

### 🔸 Deploy Frontend (Vercel or Netlify)
1. Push the frontend folder to GitHub.
2. Go to [Vercel](https://vercel.com) → **New Project** → Import your repo.
3. Add frontend environment variables (`VITE_CLERK_PUBLISHABLE_KEY`, `VITE_API_URL`, `VITE_STREAM_API_KEY`).
4. Deploy the site.

✅ **Tip:** Update the `CLIENT_URL` in your backend `.env` to your deployed frontend URL.

---

## 👨‍💻 Developer
**Jagannadh Aditya Seepana**  
Full Stack Developer | MERN Stack | Real-Time Web Apps

---

## 📚 Learning Outcomes
- Learned to integrate **Clerk** for secure authentication
- Worked with **Stream API** for real-time collaboration
- Understood **full-stack architecture and API integration**
- Deployed and managed environment configurations on **Vercel/Render**

---

## 🏁 License
This project is open source and available under the **MIT License**.
