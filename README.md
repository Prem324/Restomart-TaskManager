# 📝 Task Manager

A full-stack Task Manager application that allows users to create, edit, delete, and manage tasks. Built using **Next.js (App Router)** for the frontend and **Node.js + Express + TypeORM + SQLite** for the backend.

---

## 📁 Repository Structure

```
Restomart-TaskManager/
├── backend/        # Node.js, Express, SQLite, TypeORM
└── frontend/       # Next.js App Router, TypeScript, Tailwind CSS
```

---

## 🚀 Tech Stack

### ✅ Frontend

- **Next.js (App Router)**
- **TypeScript**
- **Tailwind CSS**
- **Client-side routing**
- **Form validation**
- **Toast notifications**
- **Dark mode**

### ✅ Backend

- **Node.js**
- **Express**
- **TypeORM**
- **SQLite**

---

## ⚙️ Backend Setup Instructions

### 📌 Prerequisites

- Node.js >= 18
- npm or yarn

### 📦 Installation

```bash
cd backend
npm install
# or
yarn install
```

### ▶️ Start Server

```bash
npm start
# or
yarn start
```

### 📂 Notes

- The `database.sqlite` file will be automatically created by TypeORM on first run.
- API will be accessible at: [http://localhost:3001](http://localhost:3001)

### 🌱 Backend Environment Variables

Create a `.env` file in the `backend/` directory with the following content:

```
PORT=3001
```

You can also use the provided `.env.example`.

---

## 🧪 API Endpoints

| Method | Endpoint     | Description             |
| ------ | ------------ | ----------------------- |
| GET    | `/tasks`     | Get all tasks           |
| GET    | `/tasks/:id` | Get a single task       |
| POST   | `/tasks`     | Create a new task       |
| PUT    | `/tasks/:id` | Update an existing task |
| DELETE | `/tasks/:id` | Delete a task           |

---

## 💻 Frontend Setup Instructions

### 📌 Prerequisites

- Node.js >= 18
- npm or yarn

### 📦 Installation

```bash
cd frontend
npm install
# or
yarn install
```

### 🌱 Frontend Environment Variables

Create a `.env.local` file in the `frontend/` directory with the following content:

```
NEXT_PUBLIC_API_URL=http://localhost:3001
```

You can also use the provided `.env.local.example`.

### ▶️ Start Development Server

```bash
npm run dev
# or
yarn dev
```

Frontend will be available at: [http://localhost:3000](http://localhost:3000)

---

## 🧭 Frontend Pages

| Route       | Description              |
| ----------- | ------------------------ |
| `/home`     | Home page with task list |
| `/add`      | Add new task             |
| `/edit/:id` | Edit existing task       |

---

## ✨ Features Implemented

- ✅ Create, update, delete tasks
- ✅ Filter tasks by status
- ✅ Display `createdAt` and `updatedAt` timestamps
- ✅ Responsive design (Tailwind CSS)
- ✅ Dark mode
- ✅ Form validation for required fields
- ✅ Toast notifications
- ✅ Reusable components for TaskForm, TaskCard, TaskList
- ✅ Confirmation dialog before deletion

---

## 📸 Screenshots / Demo

### Home Page

![Home Screenshot](https://res.cloudinary.com/dlakv8a0n/image/upload/v1750316254/home-page.png)

### Add Task

![Add Task Screenshot](https://res.cloudinary.com/dlakv8a0n/image/upload/v1750316254/add-page.png)

### Edit Task

![Edit Task Screenshot](https://res.cloudinary.com/dlakv8a0n/image/upload/v1750316254/edit-page.png)

---

## ⚠️ Known Issues / Limitations

- No authentication or user roles
- SQLite is best for development or light usage
- Search/filter functionality can be improved

---

## 📂 Example `.env` Files

### `backend/.env.example`

```env
PORT=3001
```

### `frontend/.env.local.example`

```env
NEXT_PUBLIC_API_URL=http://localhost:3001
```

---

## 👨‍💻 Author

Made with ❤️ using modern web technologies. Open to improvements and contributions!
