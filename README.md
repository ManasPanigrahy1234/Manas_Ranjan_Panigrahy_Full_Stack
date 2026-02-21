
Full-stack Store Rating Web Application built with React.js, Express.js, and MySQL using Sequelize ORM. It allows users to register, log in, view stores, and submit ratings (1–5). Implements secure JWT authentication and role-based access for Admin, Users, and Store Owners, ensuring efficient store and rating management.
**Tech Stack**
Frontend
•	React.js
•	Vite
•	Axios
•	Bootstrap
Backend
•	Node.js
•	Express.js
•	Sequelize ORM
•	JWT Authentication
•	bcryptjs
Database
•	MySQL
**Features**
•	User registration and login
•	JWT-based authentication
•	Role-based access control
•	View all stores
•	Submit and update ratings
•	Admin dashboard for managing users and stores
•	Store owner dashboard to view ratings
•	Secure password encryption
<img width="290" height="357" alt="image" src="https://github.com/user-attachments/assets/c1f3a429-1dd3-4a54-ab50-b26cbc9ebe29" /># Manas_Ranjan_Panigrahy_Full_Stack
**Prerequisites**
Install the following:
•	Node.js
•	MySQL
•	Git
**Database Setup**
1.Open MySQL
2.Create database:
SQL
CREATE DATABASE store_rating;

3.Update database credentials in:
backend/config/database.js
Example
database: 'store_rating',
username: 'root',
password: 'your_password',
host: 'localhost'
**How to Run Backend**
Open Command Prompt:
cd backend
npm install
npm start
Backend Run On
http://localhost:5000
**How to Run Frontend**
Open new Command Prompt:
cd frontend
npm install
npm run dev
**code**
cd frontend
npm install
npm run dev
**Frontend runs on:**
http://localhost:5173
**API Base URL**
http://localhost:5000/api
**Authentication**
Uses JWT for secure authentication.
Roles:
System Administrator
Normal User
Store Owner
**Author**
Manas Ranjan Panigrahy
Final Year Computer Science Engineering Student
Full Stack Developer








