# TaskFlow API 🚀

A RESTful backend API built using Node.js, Express, and MongoDB to manage users and tasks.

---

## 📌 Features
- User Registration
- Create Tasks
- Get Tasks by User
- MongoDB Database Integration
- RESTful API structure

---

## 🛠 Tech Stack
- Node.js
- Express.js
- MongoDB (Mongoose)

---

## ⚙️ Setup Instructions

1. Clone the repository:
   git clone https://github.com/abdullahdevi/taskflow-api.git

2. Navigate to the project:
   cd taskflow-api

3. Install dependencies:
   npm install

4. Create a `.env` file in the root directory:
   MONGO_URI=your_mongodb_connection_string
   PORT=5000

5. Start the server:
   npm run dev

---

## 📡 API Endpoints

### 👤 User
- POST `/api/users/register`
  - Register a new user

### 📋 Tasks
- POST `/api/tasks`
  - Create a new task

- GET `/api/tasks/:userId`
  - Get all tasks for a specific user

---

## 🧪 Example Request

### Create Task

POST `/api/tasks`

```json
{
  "userId": "your_user_id_here",
  "title": "Learn Node.js"
}
