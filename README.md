# Student Management System

A full-stack **Student Management System** built using the **MERN stack**. The application provides a modern dashboard for managing student records with CRUD operations, search, filtering, validation, and MongoDB database persistence.

---

## 📌 Project Overview

The Student Management System is a web-based application designed to simplify the management of student information.

It allows users to:

- Add new student records
- View existing student records
- Edit student information
- Delete student records
- Search students
- Filter students by course and year
- Validate student information
- Store student data securely in MongoDB

The project follows a full-stack architecture where the React frontend communicates with the Node.js and Express.js backend through REST APIs using Axios.

---

## ✨ Features

### 👤 Student Management

- Add a new student
- View all students
- Edit existing student details
- Delete student records
- Persistent data storage using MongoDB

### 🔎 Search

Students can be searched using:

- Student ID
- Student Name
- Email
- Course

### 🎯 Filters

Students can be filtered by:

- Course
- Academic Year
- Course + Academic Year combination

### ✅ Validation

The application includes:

- Required-field validation
- Unique Student ID validation
- Course validation
- Year validation
- Backend Mongoose validation

### 📊 Dashboard

The dashboard provides:

- Total Students
- Active Students
- Number of Courses
- Recently added student records
- Student Directory

### 🎨 User Interface

The application includes a modern **Burgundy Luxe** dashboard design with:

- Responsive layout
- Sidebar navigation
- Dashboard statistics
- Search interface
- Student directory table
- Add/Edit student modal
- Interactive action buttons
- Course badges
- Pagination

---

## 🛠️ Technology Stack

### Frontend

- React.js
- Vite
- Axios
- Lucide React
- CSS

### Backend

- Node.js
- Express.js
- Mongoose
- CORS
- dotenv

### Database

- MongoDB Atlas

### Development Tools

- Visual Studio Code
- Git
- GitHub
- npm

---

## 🏗️ Project Architecture

```text
React Frontend
      │
      │ Axios / REST API
      ▼
Node.js + Express.js
      │
      │ Mongoose
      ▼
MongoDB Atlas



### Project Structure
student-management-system/
│
├── client/
│   ├── public/
│   │
│   ├── src/
│   │   ├── components/
│   │   │   ├── Sidebar.jsx
│   │   │   ├── StatCard.jsx
│   │   │   ├── StudentDirectory.jsx
│   │   │   └── StudentForm.jsx
│   │   │
│   │   ├── App.jsx
│   │   ├── index.css
│   │   └── main.jsx
│   │
│   ├── package.json
│   └── vite.config.js
│
├── server/
│   ├── models/
│   │   └── Student.js
│   │
│   ├── routes/
│   │   └── studentRoutes.js
│   │
│   ├── .env
│   ├── server.js
│   └── package.json
│
├── .gitignore
├── package.json
├── package-lock.json
└── README.md

