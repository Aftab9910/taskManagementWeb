# Task Management MERN Application

A full-stack **Task Management Web Application** built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js).  
This project allows users to manage tasks efficiently by creating, updating, deleting, and tracking their status.

---

## 🚀 Features

- Create, Update, Delete Tasks
- Mark tasks as Completed / Pending
- Task List View
- RESTful API integration
- Responsive UI

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Axios
- HTML5
- CSS3
- JavaScript

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose

---

## 📁 Project Structure


Backend Setup

cd backend
npm install
npm start

Create a .env file inside backend folder:

PORT=5000
MONGO_URI=your_mongodb_connection_string


| Method | Endpoint           | Description   |
| ------ | ------------------ | ------------- |
| POST   | /api/auth/register | Register user |
| POST   | /api/auth/login    | Login user    |
| GET    | /api/tasks         | Get all tasks |
| POST   | /api/tasks         | Create task   |
| PUT    | /api/tasks/:id     | Update task   |
| DELETE | /api/tasks/:id     | Delete task   |




