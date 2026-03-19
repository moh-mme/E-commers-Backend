# E-commers-Backend
A robust and scalable backend API for an e-commerce application built with Node.js, Express, and Sequelize. This project provides secure authentication, role-based access control, and full CRUD operations for managing users, products, and orders.

🚀 Features

🔐 JWT Authentication & Authorization

👥 Role-Based Access Control (Admin / Manager / User)

📦 Product Management (CRUD)

🛒 Order Handling System

👤 User Management System

🗄️ Database integration using Sequelize ORM

⚡ RESTful API architecture

🛡️ Secure password handling


Tech Stack

Node.js

Express.js

Sequelize ORM

PostgreSQL (or any SQL DB)

JSON Web Token (JWT)

📁 Project Structure
├── controllers/
├── models/
├── routes/
├── middleware/
├── config/
└── app.js
🔑 Authentication

This API uses JWT-based authentication.
Include your token in headers:

Authorization: Bearer <your_token>
⚙️ Getting Started
npm install
npm run dev
📌 Notes

Only authorized users can access protected routes

Managers/Admins have elevated permissions

Environment variables are required (.env)

👨‍💻 Author

Backend developed for learning and building scalable API systems.
