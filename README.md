# 🗂️ Task Manager – Full Stack Kanban Application

A modern **Task Management (Kanban) application** that helps users organize tasks efficiently. Features include secure authentication, drag-and-drop task movement, real-time activity tracking, and profile management.

This project demonstrates **full-stack development best practices** using **Node.js, Express, MongoDB, and React**.

---

## 🚀 Project Overview

The Task Manager app allows users to:

* Sign up and log in securely
* Create, edit, and delete tasks
* Organize tasks on a **Kanban board**
* Drag and drop tasks between different statuses
* Automatically track **recent activity**
* Update password or delete their profile
* Access a personalized dashboard

Each user has **isolated data**, ensuring full privacy and security.

---

## 🛠️ Tech Stack

### Frontend

* **React (Vite)** – Fast, modern React setup
* **React Router DOM** – Page navigation
* **Tailwind CSS** – Utility-first styling
* **@hello-pangea/dnd** – Drag-and-drop functionality
* **Axios** – API requests

### Backend

* **Node.js** – Server runtime
* **Express.js** – API framework
* **MongoDB & Mongoose** – Database and schema modeling
* **JWT** – Authentication
* **bcrypt** – Password hashing

---

## 📁 Project Structure

### Frontend Folder Structure

```text
frontend/
├── src/
│   ├── api/
│   │   ├── axios.js             # Axios configuration
│   │   └── tasks.js             # Task-related API calls
│   │
│   ├── auth/
│   │   └── AuthContext.jsx      # Authentication context
│   │
│   ├── components/
│   │   ├── KanbanBoard.jsx      # Kanban board layout
│   │   ├── TaskCard.jsx         # Task card component
│   │   ├── CreateTask.jsx       # Create task modal
│   │   └── RecentActivity.jsx   # Recent activity panel
│   │
│   ├── pages/
│   │   ├── Login.jsx            # Login page
│   │   ├── Signup.jsx           # Signup page
│   │   ├── Dashboard.jsx        # Main dashboard
│   │   └── Profile.jsx          # Profile management
│   │
│   ├── App.jsx                  # App routes
│   └── main.jsx                 # React entry point
│
├── index.html
└── package.json
```

### Backend Folder Structure

```text
backend/
├── src/
│   ├── config/
│   │   └── db.js                # MongoDB connection
│   │
│   ├── models/
│   │   ├── User.js              # User schema
│   │   └── Task.js              # Task schema
│   │
│   ├── middleware/
│   │   └── auth.middleware.js   # JWT authentication middleware
│   │
│   ├── controllers/
│   │   ├── auth.controller.js   # Signup, login, logout
│   │   ├── user.controller.js   # Profile update & delete
│   │   └── task.controller.js   # Task CRUD logic
│   │
│   ├── routes/
│   │   ├── auth.routes.js       # Auth routes
│   │   ├── user.routes.js       # User routes
│   │   └── task.routes.js       # Task routes
│   │
│   ├── app.js                   # Express app configuration
│   └── server.js                # Server entry point
│
├── .env                         # Environment variables
└── package.json                 # Dependencies & scripts
```

---

## ⚙️ Backend Setup Instructions

1. **Install dependencies:**

```bash
cd backend
npm install
```

2. **Configure environment variables:**

Create a `.env` file in the `backend/` folder with the following:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
FRONTEND_URL=http://localhost:5173
```

3. **Start the backend server:**

```bash
npm start
```

4. **Access the API:**

```
http://localhost:5000
```

---

## ⚙️ Frontend Setup Instructions

1. **Install dependencies:**

```bash
cd frontend
npm install
```

2. **Start the frontend development server:**

```bash
npm run dev
```

3. **Open in browser:**

```
http://localhost:5173
```

---

## 🖼️ Features

* **User Authentication:** Signup, login, and JWT-based secure sessions
* **Task Management:** Create, update, delete tasks
* **Kanban Board:** Drag-and-drop tasks between columns
* **Recent Activity:** Automatic activity log for every action
* **Profile Management:** Update password or delete profile
* **Personal Dashboard:** View your tasks and progress at a glance

---

## 💻 Future Enhancements

* Add **real-time collaboration** for multiple users using WebSockets
* Enable **notifications** for task deadlines
* Integrate **analytics** to track task completion trends
* Add **dark mode** for a better user experience

---

## 📂 Deployment

This project can be deployed on **Heroku, Vercel, or AWS**. Ensure that your frontend and backend URLs are properly configured in `.env` files for production.

---



