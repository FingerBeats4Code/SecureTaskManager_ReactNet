# 🔐 Secure Task Manager

A full-stack application built with **.NET 8 Web API** and **React.js** to demonstrate secure user authentication, JWT handling, and role-based authorization.

---

## 🧩 Features

- User registration & login with JWT
- Role-based access control (Admin/User)
- Secure API communication
- React frontend with protected routes
- Basic task CRUD operations

---

## ⚙️ Tech Stack

- **Backend:** ASP.NET Core 8, Entity Framework Core
- **Frontend:** React.js, Axios, React Router
- **Auth:** JWT access/refresh tokens, role-based authorization

---

## 📁 Folder Structure

```
SecureTaskManager/
├── backend/
│   ├── Controllers/
│   ├── Services/
│   ├── Models/
│   └── Program.cs
└── frontend/
    └── src/
        ├── components/
        ├── pages/
        ├── context/
        └── utils/
```

---

## 🚀 Getting Started

### Backend (.NET)

```bash
cd backend
dotnet restore
dotnet run
```

### Frontend (React)

```bash
cd frontend
npm install
npm start
```

---

## 🔐 Authentication & Authorization

- **Login** issues with React & JWT tokens resolved using Axios interceptors.
- **Token refresh** logic implemented.
- **Role checks** done via middleware and `[Authorize(Roles = "...")]`.

---

## 🤝 Inspired By

Issues discussed on:
- StackOverflow on [CORS](https://stackoverflow.com/questions/45927761)
- JWT authentication [failures](https://stackoverflow.com/questions/41445717)
- Login persistence [with React](https://stackoverflow.com/questions/56261144)

---

Happy coding! 🎯
