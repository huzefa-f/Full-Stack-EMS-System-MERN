# Employee Management System (EMS)

A full-stack **Employee Management System (EMS)** built using the **MERN Stack**. This application streamlines employee management by providing secure authentication, attendance tracking, leave management, payroll management, and role-based dashboards for both administrators and employees.

---

## 🚀 Live Demo

**Frontend (Vercel):**  
👉 https://full-stack-ems-system-mern-psi.vercel.app

> **Note:** If the application takes a few seconds to load on the first visit, the backend server may be waking up from an idle state.
> Admin Login Email: huzefafakharems@gnail.com, Password: admin123

---

## ✨ Features

### 🔐 Authentication
- Secure JWT-based authentication
- Role-based access control (Admin & Employee)
- Protected routes
- Change password functionality

### 👨‍💼 Employee Management
- Add new employees
- Update employee details
- Delete employee records
- View employee profiles

### 🕒 Attendance Management
- Employee check-in
- Attendance history
- Daily attendance tracking
- Attendance statistics

### 📝 Leave Management
- Apply for leave
- View leave history
- Admin approval/rejection of leave requests

### 💰 Payroll Management
- Generate payslips
- View payroll history
- Salary management

### 📊 Dashboard
#### Admin Dashboard
- Employee statistics
- Attendance overview
- Leave requests
- Payroll summary

#### Employee Dashboard
- Personal profile
- Attendance records
- Leave status
- Payslips

---

# 🛠️ Tech Stack

## Frontend

- React 19
- Vite
- Tailwind CSS
- React Router DOM
- Axios
- React Hot Toast
- Lucide React

## Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Bcrypt
- Multer
- Nodemailer
- Inngest

---

# 📁 Project Structure

```
FullStack-EMS
│
├── client
│   ├── src
│   │   ├── api
│   │   ├── assets
│   │   ├── components
│   │   ├── context
│   │   ├── pages
│   │   └── App.jsx
│   └── package.json
│
├── server
│   ├── config
│   ├── constants
│   ├── controllers
│   ├── inngest
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── seed.js
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

# ⚙️ Installation

## 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repository.git

cd FullStack-EMS
```

---

## 2. Backend Setup

Navigate to the server directory.

```bash
cd server
```

Install dependencies.

```bash
npm install
```

Create a `.env` file.

```env
PORT=4000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

SMTP_HOST=your_smtp_host
SMTP_PORT=587
SMTP_USER=your_email
SMTP_PASS=your_password
```

Start the backend server.

```bash
npm run server
```

---

## 3. Frontend Setup

Navigate to the client directory.

```bash
cd client
```

Install dependencies.

```bash
npm install
```

Create a `.env` file.

```env
VITE_BACKEND_URL=http://localhost:4000
```

Run the development server.

```bash
npm run dev
```

---

# 📡 API Modules

- Authentication
- Employee Management
- Attendance Management
- Leave Management
- Payroll Management
- Profile Management
- Dashboard

---

# 🗄️ Database Collections

- Users
- Employees
- Attendance
- Leave Applications
- Payslips

---

# 🔒 Security

- JWT Authentication
- Password Hashing using Bcrypt
- Protected API Routes
- Role-Based Authorization
- Secure Environment Variables

---

# 🚀 Future Enhancements

- Email notifications
- Employee document management
- Attendance reports
- Payroll analytics
- Calendar integration
- Export reports as PDF/Excel
- Dark mode
- Multi-company support

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

Developed as a Full Stack MERN project for learning, portfolio, and demonstration purposes.

If you found this project helpful, consider giving it a ⭐ on GitHub.
