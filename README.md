# Full Stack Task Manager App

## Features

- User Authentication (Register/Login)
- JWT-based Authorization
- Role-based access (User/Admin)
- Task CRUD (Create, Read, Update, Delete)
- Protected routes
- Toast notifications

---

## Tech Stack

- Backend: Node.js, Express.js
- Database: MongoDB (Mongoose)
- Frontend: React (Vite)
- Auth: JWT, bcrypt

---

## Setup Instructions

### Backend

```bash
cd backend
npm install
npm run dev
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## API Endpoints

### Auth

- POST /api/v1/auth/register
- POST /api/v1/auth/login

### Tasks

- GET /api/v1/tasks
- POST /api/v1/tasks
- PUT /api/v1/tasks/:id
- DELETE /api/v1/tasks/:id

---

## Security

- Password hashing using bcrypt
- JWT authentication
- Protected API routes

---

## Future Improvements

- Redis caching
- Docker deployment
- Role-based UI

---

## Author

Nandni Dixit

## Scalability

This system can be scaled using microservices architecture, Redis caching for faster data access, and load balancing to handle high traffic efficiently.
