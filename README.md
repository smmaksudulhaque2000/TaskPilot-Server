# TaskPilot

TaskPilot is a modern and user-friendly **Task Management Application** that allows users to **add, edit, delete, reorder, and drag & drop tasks** between categories: **To-Do, In Progress, and Done**. It ensures **real-time synchronization** and **responsive UI** for both desktop and mobile users.

## 🚀 Live Demo
[TaskPilot Live](https://taskpilot-e895c.web.app/)

---

## 📌 Features
- 🔐 **Authentication:** Google Sign-In (Firebase)
- 📋 **Task Management:** Add, edit, delete, reorder, and drag & drop tasks
- 📂 **Database & Persistence:** MongoDB + Express.js backend
- ⚡ **Real-time updates:** MongoDB Change Streams/WebSockets
- 🎨 **UI & UX:** Modern, clean, and responsive design (Vite.js + React)
- 🌑 **Dark mode (Optional) & Deadline indicators** 

---

## 🏗️ Tech Stack

### 🖥️ **Frontend**
- React.js (Vite.js)
- Firebase Authentication
- React Beautiful DnD (Drag-and-Drop Library)
- Tailwind CSS (UI Styling)

### 🖥️ **Backend**
- Node.js + Express.js (REST API)
- MongoDB (Database)
- WebSockets / MongoDB Change Streams (Real-time updates)

---

## 📦 **Installation & Setup**

### 1️⃣ **Clone the Project**
```bash
git clone https://github.com/smmaksudulhaque2000/TaskPilot-Client
cd TaskPilot
```

### 2️⃣ **Setup Frontend**
```bash
cd frontend
npm install
npm run dev
```

### 3️⃣ **Setup Backend**
```bash
cd backend
npm install
npm start
```

### 4️⃣ **Configure .env File**
Create a `.env` file in the backend directory and add:
```
MONGO_URI=your_mongodb_connection_string
FIREBASE_API_KEY=your_firebase_api_key
```

---

## 🔌 **API Endpoints**
| Method | Endpoint        | Description |
|--------|----------------|-------------|
| POST   | `/tasks`       | Add a new task |
| GET    | `/tasks`       | Retrieve all tasks for the logged-in user |
| PUT    | `/tasks/:id`   | Update a task (title, description, category) |
| DELETE | `/tasks/:id`   | Delete a task |

---

## 🛠 **Dependencies**
Frontend:
- `react`
- `vite`
- `firebase`
- `react-beautiful-dnd`
- `tailwindcss`

Backend:
- `express`
- `mongoose`
- `cors`
- `dotenv`
- `socket.io`

---

## ⚠️ **Troubleshooting**
#### 🔹 **Issue:** Server not running?
✅ **Solution:** Check `.env` file configuration and MongoDB connection.

#### 🔹 **Issue:** Authentication not working?
✅ **Solution:** Verify Firebase credentials.

---

## ✨ **Contributors**
- **Your Name** - [GitHub Profile](https://github.com/smmaksudulhaque2000)

---

## 📜 **License**
This project is licensed under the **MIT License**.

---

🎯 **TaskPilot** makes task management more efficient and seamless!
