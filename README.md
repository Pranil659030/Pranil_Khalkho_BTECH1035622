# 🗂️ Kanban Task Manager – Full Stack Application

A full-stack Kanban Task Management application that allows users to manage tasks efficiently with authentication, drag-and-drop task movement, and a responsive UI.

---

## 🚀 Features

### Authentication & User Management
- User Signup & Login (JWT Authentication)
- Logout
- Edit & Delete Profile
- User-specific tasks

### Kanban Task Board
- Three columns:
  - Pending
  - In Progress
  - Completed
- Drag & drop tasks between columns
- Task status updates persist in backend
- Mobile responsive layout

### Task Management
- Create, Read, Update, Delete tasks
- Filter tasks by status
- Each task contains:
  - Title
  - Description
  - Status
  - Due Date
  - Created At

---

## 🛠 Tech Stack

### Frontend
- React (Vite)
- Tailwind CSS
- Axios
- @hello-pangea/dnd
- React Icons

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcrypt
- CORS

---

## 📂 Project Structure

kanban-task-manager/
│── frontend/
│── backend/
│── README.md
│── .gitignore


---

## ⚙️ Setup Instructions

### Backend Setup

```bash
cd backend
npm install

Create a .env file inside backend folder:
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key


Start backend server:
npm run dev

Backend runs on:
http://localhost:5000

Frontend Setup
cd frontend
npm install
npm run dev

Frontend runs on:
http://localhost:5173

🔐 Environment Variables

Backend .env file:
MONGO_URI=
JWT_SECRET=
PORT=

🧪 API Endpoints
Auth Routes
POST   /api/auth/signup
POST   /api/auth/login
GET    /api/auth/profile
PUT    /api/auth/profile
DELETE /api/auth/profile


Task Routes
GET    /api/tasks
POST   /api/tasks
PUT    /api/tasks/:id
DELETE /api/tasks/:id


🌐 Deployment

Frontend: Vercel / Netlify

Backend: Render / Railway

Database: MongoDB Atlas


👨‍💻 Author

Pranil Khalkho

If you like this project, give it a star on GitHub!

---

✅ This README is:
- Professional  
- Interview-ready  
- GitHub-friendly  
- Beginner-friendly  

---

If you'd like, I can also generate:
- `.gitignore`
- `LICENSE`
- `CONTRIBUTING.md`
- Deployment guide (Vercel + Render)

Just tell me what you want next 🚀





