# StaffSync – Human Resource Management System

A modern, full-stack Human Resource Management System built using the MERN Stack (MongoDB, Express.js, React.js, and Node.js).

StaffSync simplifies HR operations through dedicated dashboards for HR personnel, Managers, and Employees.

## Demo Accounts

Use the following accounts for testing the application (if initialized by the demo seed):

| Role | Email | Password |
|------|-------|----------|
| HR | hr@staffsync.demo | StaffSync@2026 |
| Manager | manager@staffsync.demo | StaffSync@2026 |
| Employee | employee@staffsync.demo | StaffSync@2026 |

Demo accounts use fictional employee data. Do not use real employee or payroll information.

## Features

### HR Dashboard
- Add, edit, delete, and view employees.
- Manage employee records.
- Approve or reject leave requests.
- Monitor employee attendance.
- Publish company announcements.
- View reports and analytics.

### Employee Dashboard
- View and update personal profiles.
- Mark daily attendance.
- Apply for leave.
- Track leave request status.
- View company announcements.
- Access training programs.

### Manager Dashboard
- Manage team members.
- Review and approve leave requests.
- Monitor team attendance.
- Manage training programs.
- Track employee development.

## Technology Stack

**Frontend**
- React.js
- Material UI
- Redux Toolkit
- React Router
- Axios
- Recharts

**Backend**
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcrypt

**Tools**
- Visual Studio Code
- Git & GitHub
- Postman
- MongoDB Atlas

## Project Structure

```text
StaffSync/
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── routes/
│   │   ├── App.jsx
│   │   └── App.css
│   └── index.html
├── server/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── app.js
│   └── server.js
├── .env.example
├── package.json
└── README.md
```

## Installation and Setup

### Prerequisites
- Node.js 22.12 or above
- npm
- MongoDB Atlas account
- Git

### 1. Clone Repository

```bash
git clone https://github.com/sarva1210/staff-sync.git
cd staff-sync
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the root directory.

```env
PORT=4000
NODE_ENV=development
MONGODB_URI=YOUR_MONGODB_CONNECTION_STRING
JWT_SECRET=YOUR_SECRET_KEY
CLIENT_ORIGIN=http://127.0.0.1:5173
SEED_DEMO=true
```

Keep your `.env` file private. Never upload database credentials or secrets to GitHub.

### 4. Start Application

```bash
npm run dev
```

Frontend: `http://127.0.0.1:5173`

Backend: `http://127.0.0.1:4000`

## Security

- JWT-based authentication.
- Password hashing using bcrypt.
- Role-Based Access Control.
- Protected frontend routes.
- Backend authorization middleware.
- Input validation.
- Secure database operations.

## Database Collections

- Users
- Employees
- Attendance
- Leaves
- Announcements
- Training
- Notifications
- Audits

## Project Objective
The main objective of StaffSync is to digitize and simplify organizational HR operations through a centralized platform.
The application aims to improve employee management, attendance tracking, leave processing, internal communication, and team development..
