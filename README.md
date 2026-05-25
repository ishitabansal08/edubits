# 📘 Edubits

**Edubits** is a full-stack student productivity and learning platform designed to help students **manage academics, practice concepts, and track progress** in one place.
It integrates a powerful **Quiz Engine** with smart algorithms alongside productivity tools like GPA calculators and task management.

---

## 🚀 Live Demo

* **Frontend:** [https://quizengine-sepia.vercel.app](https://quizengine-sepia.vercel.app)
* **Backend API:** [https://quizengine-makv.onrender.com](https://quizengine-makv.onrender.com)

---

## 🧠 Core Modules

### 1️⃣ QuizEngine (Smart Learning System)

An algorithm-driven quiz platform that adapts to user performance.

**Features**

* JWT-based authentication
* Topic-wise quizzes
* Dependency-based topic unlocking (prerequisite graph)
* Adaptive scoring algorithm
* Difficulty-aware question sorting
* Real-time leaderboard
* Progress tracking per topic

---

### 2️⃣ Edubits Productivity Tools

**Features**

* 📝 Task Tracker (Kanban-style)
* 🔍 Search, filters, priority & deadlines
* 📊 SGPA & CGPA calculator
* 📄 GPA export (PDF ready)
* Unified user account across all tools

---

## 🏗️ Tech Stack

### Frontend

* React (Vite)
* JavaScript (ES6+)
* CSS / Tailwind (if applicable)
* Axios

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication

### Algorithms Used

* Graphs (topic prerequisites)
* Sorting (leaderboards, difficulty levels)
* Scoring algorithms
* Unlocking logic based on dependencies

---

## 📁 Project Structure

```bash
edubits/
│
├── backend/
│   ├── controllers/
│   ├── algorithms/
│   │   ├── scoring.js
│   │   ├── graph.js
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   └── server.js
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   ├── services/
│   └── main.jsx
│
├── .gitignore
├── package.json
└── README.md
```

---

## 🔐 Authentication Flow

1. User registers / logs in
2. JWT token is generated
3. Token is stored on client
4. Protected routes verify token
5. Same auth works across **Edubits + QuizEngine**

---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository

```bash
git clone https://github.com/ishitabansal08/edubits.git
cd edubits
```

### 2️⃣ Backend Setup

```bash
cd backend
npm install
npm run dev
```

Create a `.env` file:

```env
MONGO_URI=your_mongodb_url
JWT_SECRET=your_secret_key
PORT=5000
```

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

## 📌 Why Edubits?

* Combines **productivity + learning**
* Real algorithm usage (graphs, scoring, sorting)
* Clean backend architecture
* Resume-worthy full-stack project
* Designed with scalability in mind

---

## 🚧 Future Enhancements

* Admin dashboard for quiz creation
* Analytics dashboard
* AI-based question recommendations
* Mobile-first UI
* Collaborative study groups

---

## 👩‍💻 Author

**Ishita Bansal**
Student | Full-Stack Developer
GitHub: [https://github.com/ishitabansal08](https://github.com/ishitabansal08)

---

