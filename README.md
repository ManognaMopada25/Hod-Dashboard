#  AI-Based Task Management System

An AI-powered task management web application developed as an academic group project. The system enables users to create, manage, and track tasks while providing AI-powered assistance through an integrated chatbot. The application uses Next.js for the frontend, Node.js for the backend, and MongoDB for data storage.



##  Features

- 🔐 User Authentication (Login)
- 👤 User Profile Management
- 📋 Create, Update and Delete Tasks
- 📊 Task Dashboard
- 🤖 AI Chatbot Integration using RapidAPI
- 📝 Task Tracking
- 🔒 Protected Routes using Authentication Middleware
- 💾 MongoDB Database Integration



##  Tech Stack

### Frontend
- Next.js
- React.js
- HTML
- CSS

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### AI Integration
- RapidAPI Chatbot API

### Tools
- VS Code
- Git
- GitHub



##  Project Structure

```
AI-Task-Management-System
│
├── src
│   ├── app
│   │   ├── dashboard
│   │   ├── login
│   │   ├── profile
│   │   ├── layout.js
│   │   └── page.js
│   │
│   └── components
│       ├── LoginForm.js
│       ├── StudentDashboard.js
│       ├── TaskDashboard.js
│       └── EditProfile.js
│
├── server
│   ├── middleware
│   │   ├── auth.js
│   │   └── authMiddleware.js
│   │
│   ├── models
│   │   ├── User.js
│   │   └── Task.js
│   │
│   ├── routes
│   │   ├── auth.js
│   │   ├── tasks.js
│   │   └── users.js
│   │
│   ├── scripts
│   ├── db.js
│   └── server.js
│
└── README.md
```



##  How to Run

### Clone Repository

```bash
git clone https://github.com/Chandini1214/AI-Task-Management-System.git
```

### Install Dependencies

Frontend

```bash
npm install
```

Backend

```bash
cd server
npm install
```

### Configure Environment Variables

Create a `.env` file and add:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
RAPID_API_KEY=your_api_key
```

### Start Backend

```bash
npm start
```

### Start Frontend

```bash
npm run dev
```

Open:

```
http://localhost:3000
```



##  Future Enhancements

-  Mobile Application
-  AI-based Productivity Analytics
-  Google Calendar Integration
-  Cloud Deployment (AWS/Vercel)
-  Team Performance Reports
-  Voice-based Task Creation
-  Multi-language Support


## 👩‍💻 Developed By
```
**Mopada Manogna**
**Chandini Daneti**
**Peketi Krishna Priya**
**Dunna Manisha**
```
B.Tech - Information Technology (2026)



## 📜 License

This project is developed for educational purposes.
