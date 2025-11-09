# 🎓 College LMS Portal

> **A full-stack Learning Management System (LMS)** built to streamline college administration and academic workflows — featuring dashboards for students, faculty, and administrators with secure authentication and modern UI.

---

## 🚀 Overview

The **College LMS Portal** is a complete academic management system built using the **MERN stack (MongoDB, Express.js, React.js, Node.js)**.  
It enables digital transformation of a college ecosystem by connecting students, teachers, and admins through an intuitive and secure web platform.  

The system allows:
- Students to register, enroll in courses, view materials, and submit assignments.
- Faculty to manage classes, assignments, and grades.
- Admins to oversee courses, users, and reports.

---

## ✨ Core Features

### 👩‍🎓 Student Module
- Register and log in securely.
- Enroll in available courses.
- Upload and download assignments.
- View grades, attendance, and notices.

### 👨‍🏫 Faculty Module
- Manage courses and upload study materials.
- Post assignments and evaluate student submissions.
- Communicate with students via announcements.

### 🏛️ Admin Module
- Manage all users (students, faculty, admins).
- Create and update course data.
- Monitor activity analytics and system logs.

### 🔐 Security & System Features
- JSON Web Token (JWT) authentication.
- Role-based access control.
- Input validation and data encryption.
- Centralized error handling for clean backend operations.

### 💻 Interface & Design
- Built with **ReactJS + TailwindCSS** for a fast and elegant UI.
- Fully **responsive layout** supporting mobile and desktop.
- Dynamic routing using React Router DOM.
- Dark/Light mode support (optional).

---

## 🧠 Architecture


> The backend follows **MVC architecture** ensuring scalability and clean code separation between routes, controllers, and models.

---

## 🛠️ Tech Stack

| Category | Technologies Used |
|-----------|------------------|
| **Frontend** | React.js, TailwindCSS, Axios, React Router DOM |
| **Backend** | Node.js, Express.js, RESTful APIs |
| **Database** | MongoDB, Mongoose |
| **Authentication** | JWT, Bcrypt |
| **Version Control** | Git & GitHub |
| **Deployment** | Vercel (Frontend), Render/Railway (Backend) |

---

## ⚙️ Installation & Setup Guide

Follow these steps to run the project locally 👇

### 1️⃣ Clone the repository
```bash
git clone https://github.com/adityasingh-codes/college-lms-portal.git
cd college-lms-portal
# Install backend dependencies
npm install

# Move to client folder and install frontend dependencies
cd client
npm install
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
NODE_ENV=development

college-lms-portal/
│
├── client/                     # React Frontend
│   ├── src/
│   │   ├── components/         # Reusable UI components
│   │   ├── pages/              # Screens (Home, Login, Dashboard, etc.)
│   │   ├── context/            # State management
│   │   ├── assets/             # Images & icons
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
│
├── server/                     # Backend (Express)
│   ├── routes/                 # All API endpoints
│   ├── controllers/            # Business logic
│   ├── models/                 # MongoDB Schemas
│   ├── middleware/             # JWT Auth, Validation
│   ├── config/                 # DB Connection setup
│   ├── utils/                  # Helper functions
│   └── server.js               # Entry point
│
├── .env.example
├── package.json
└── README.md

🧩 Key Highlights

🚀 End-to-end integration of frontend & backend.

📦 Reusable component architecture in React.

🔐 Full JWT-based authentication with user roles.

⚡ Optimized MongoDB queries for large data.

🎨 Clean, professional UI with Tailwind components.


🌐 Deployment

You can deploy this LMS easily:

Frontend:

Vercel or Netlify → Connect your GitHub repo and deploy directly.

Backend:

Render or Railway → Deploy the Node/Express API with MongoDB Atlas URI.

👨‍💻 Developer Information

👋 Aditya Singh
B.Tech (CSE - AI & ML) | UPES Dehradun
📧 Email: adityasingh.ai@gmail.com

🌐 Portfolio: https://adityasingh-portfolio.vercel.app

💼 LinkedIn: https://linkedin.com/in/adityasingh-ai

🐙 GitHub: https://github.com/adityasingh-codes
