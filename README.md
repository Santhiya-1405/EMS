# Employee Management System

A full-stack **Employee Management System** built using the **MERN Stack** (MongoDB, Express.js, React.js, Node.js). The application enables administrators to efficiently manage employees, departments, salaries, and leave requests, while providing employees with a dedicated dashboard to manage their profile, salary, and leave information.

---

## 📌 Features

### 🔐 Authentication
- Secure JWT Authentication
- Role-Based Access Control (Admin & Employee)
- Login & Logout
- Change Password

### 👨‍💼 Admin Module
- Dashboard with live statistics
- Employee Management (Add, Edit, View, Delete)
- Department Management (CRUD)
- Salary Management
- Leave Management (Approve/Reject)
- Search Employees & Departments
- Upload Employee Profile Photo

### 👨‍💻 Employee Module
- Employee Dashboard
- View Personal Profile
- Apply for Leave
- View Leave Status
- View Salary History
- Change Password

---

# 🛠️ Tech Stack

### Frontend
- React.js
- Vite
- Tailwind CSS
- React Router DOM
- Axios

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Multer (File Upload)

---

# 📂 Project Structure

```
EmployeeMS
│
├── frontend
│   ├── src
│   ├── public
│   ├── package.json
│   └── vite.config.js
│
├── server
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── public
│   │    └── uploads
│   ├── userSeed.js
│   ├── package.json
│   └── .env
│
└── README.md
```

---

# ⚙️ Installation

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/EmployeeMS.git

cd EmployeeMS
```

---

## 2️⃣ Backend Setup

Navigate to the server folder.

```bash
cd server

npm install
```

Create a **.env** file.

```env
PORT=2806

MONGODB_URL=your_mongodb_connection_string

JWT_KEY=your_secret_key
```

Run the admin seed file.

```bash
node userSeed.js
```

Default Admin Credentials

```
Email : admin@gmail.com

Password : admin
```

Start Backend

```bash
npm start
```

---

## 3️⃣ Frontend Setup

Navigate to frontend folder.

```bash
cd frontend

npm install

npm run dev
```

Application will run at

```
http://localhost:5173
```

---

# 📋 Modules

## Authentication
- Login
- JWT Authentication
- Role-Based Authorization

## Dashboard
- Live Statistics
- Employee Count
- Department Count
- Salary Count
- Leave Count

## Employee
- Add Employee
- Edit Employee
- Delete Employee
- View Employee Details
- Upload Profile Picture

## Department
- Add Department
- Update Department
- Delete Department
- Search Department

## Salary
- Add Salary
- View Salary History

## Leave
- Apply Leave
- Leave Approval
- Leave History

## Settings
- Change Password

---

# 📸 Employee Image Upload

Employee profile images are uploaded using **Multer**.

Images are stored inside

```
server/public/uploads/
```

Access uploaded images

```
http://localhost:2806/uploads/<filename>
```

---

# 🐞 Bug Fixes

- Fixed duplicate response issue in Authentication Controller.
- Fixed routing errors in App.jsx.
- Corrected Sidebar Navigation.
- Fixed unauthorized redirection.
- Added missing Axios imports.
- Implemented complete Department CRUD.
- Added Employee CRUD operations.
- Added Salary Management.
- Added Leave Management.
- Added Employee Dashboard.
- Added live Dashboard Summary.
- Fixed role-based routing.

---

# 📦 Dependencies

### Backend
- Express.js
- MongoDB
- Mongoose
- JWT
- bcryptjs
- Multer
- dotenv
- cors

### Frontend
- React
- React Router DOM
- Axios
- Tailwind CSS
- Vite

---

# 🚀 Future Enhancements

- Attendance Management
- Payroll Generation
- Email Notifications
- Report Generation (PDF & Excel)
- Role Permission Management
- Dark Mode
- Dashboard Charts & Analytics

---


