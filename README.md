# 🏥 Hospital Management System - MERN Stack

A full-stack **Hospital Management System** built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**. The application helps hospitals efficiently manage patients, doctors, appointments, and medical records through a secure, responsive, and user-friendly interface.

---

## 🚀 Features

- 🔐 **Secure Authentication** – JWT-based authentication with role-based access control (Admin, Doctor, Receptionist).
- 👨‍⚕️ **Doctor Management** – Add, update, view, and delete doctor profiles.
- 🧑‍🤝‍🧑 **Patient Management** – Register patients, maintain health records, and manage admissions.
- 📅 **Appointment Management** – Schedule, reschedule, and cancel appointments.
- 📁 **Medical Records** – Store and manage diagnosis, prescriptions, treatment history, and test reports.
- 📊 **Admin Dashboard** – Monitor patients, doctors, appointments, and overall hospital activities.
- 🔔 **Alerts & Notifications** – User-friendly alerts for successful actions and error handling.
- 🌐 **Responsive Design** – Optimized for desktop, tablet, and mobile devices.

---

## 🛠️ Tech Stack

### Frontend
- React.js
- React Router
- Axios
- Bootstrap / Tailwind CSS

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Bcrypt

---

## 📂 Project Structure

```
Hospital-Management-System/
│
├── client/          # React Frontend
├── server/          # Node.js & Express Backend
├── models/          # MongoDB Models
├── routes/          # API Routes
├── controllers/     # Business Logic
├── middleware/      # Authentication & Authorization
├── config/          # Database Configuration
└── README.md
```

---

## ⚙️ Installation & Setup

### Prerequisites

- Node.js (v16 or above)
- npm
- MongoDB (Local or MongoDB Atlas)

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/Hospital-Management-System.git
cd Hospital-Management-System
```

### 2️⃣ Install Dependencies

#### Backend

```bash
cd server
npm install
```

#### Frontend

```bash
cd ../client
npm install
```

### 3️⃣ Configure Environment Variables

Create a `.env` file inside the **server** folder.

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### 4️⃣ Start the Backend

```bash
cd server
npm start
```

### 5️⃣ Start the Frontend

```bash
cd client
npm start
```

The application will run at:

- Frontend: `http://localhost:3000`
- Backend: `http://localhost:5000`

---

## 📸 Screenshots

> Add screenshots of your application here.

- Login Page
- Admin Dashboard
- Doctor Dashboard
- Patient Management
- Appointment Management

---

## 📌 Future Enhancements

- 💳 Online Payment Integration
- 📧 Email Notifications
- 📱 SMS Appointment Reminders
- 📈 Analytics Dashboard
- 📄 PDF Report Generation
- 🩺 Telemedicine & Video Consultation

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Praveen Kumar Singh**

- LinkedIn: https://www.linkedin.com/in/praveen-singh-rajput-238b25241
- GitHub: https://github.com/yourusername
