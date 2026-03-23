# 🎓 MERN LMS (Learning Management System)

A full-stack Learning Management System (LMS) built using the MERN stack (MongoDB, Express, React, Node.js). This platform allows students to explore courses, purchase them, and track progress, while instructors can create and manage courses.

---

## 🚀 Features

### 👨‍🎓 Student Features

* Browse and filter courses
* View course details and curriculum
* Purchase courses (PayPal integration)
* Track learning progress
* Watch course videos

### 👨‍🏫 Instructor Features

* Create and manage courses
* Upload course content
* Edit existing courses

### 🔐 Authentication

* User registration & login
* Protected routes
* Role-based access (Student / Instructor)

---

## 🛠️ Tech Stack

**Frontend:**

* React.js (Vite)
* Tailwind CSS
* shadcn/ui
* React Router

**Backend:**

* Node.js
* Express.js

**Database:**

* MongoDB

**Other Tools:**

* PayPal API (Payment Integration)
* Axios
* Context API (State Management)

---

## 📁 Project Structure

```
MERN-LMS/
│
├── client/   # React Frontend
└── server/   # Node.js Backend
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/mern-lms.git
cd mern-lms
```

### 2. Install dependencies

```bash
cd client
npm install

cd ../server
npm install
```

---

### 3. Run the project

```bash
# Run backend
cd server
npm run dev

# Run frontend
cd client
npm run dev
```

---

## 🔐 Environment Variables

Create a `.env` file in the server folder and add:

```env
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
CLIENT_URL=http://localhost:5173
```

---
Sameer Chaudhary
