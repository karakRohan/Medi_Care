Medical Appointment Booking System

A full-stack Medical Appointment Booking Web Application where patients can book appointments with doctors, manage schedules, and communicate through a modern and responsive interface.

🚀 Features
👨‍⚕️ Patient Features
User Registration & Login
Book Doctor Appointments
View Appointment History
Cancel Appointments
Search Doctors by Specialization
Responsive Dashboard
🩺 Doctor Features
Doctor Login Panel
Manage Appointment Requests
Update Availability
View Patient Details
🛠️ Admin Features
Manage Doctors & Patients
Monitor All Appointments
Dashboard Analytics
Secure Authentication System
🧰 Tech Stack
Frontend
React.js
Tailwind CSS
Axios
React Router DOM
Backend
Node.js
Express.js
Database
MongoDB
Authentication
JWT Authentication
bcrypt.js
📂 Project Structure
medical-appointment-app/
│
├── frontend/
│   ├── src/
│   ├── public/
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   └── server.js
│
├── package.json
└── README.md
⚙️ Installation
1️⃣ Clone the Repository
git clone https://github.com/your-username/medical-appointment-app.git
2️⃣ Go to Project Directory
cd medical-appointment-app
3️⃣ Install Dependencies
Frontend
cd frontend
npm install
Backend
cd backend
npm install
🔑 Environment Variables

Create a .env file inside the backend folder and add:

PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
▶️ Run the Project
Start Backend
cd backend
npm run server
Start Frontend
cd frontend
npm start
🌐 API Endpoints
Method	Endpoint	Description
POST	/api/auth/register	Register User
POST	/api/auth/login	Login User
GET	/api/doctors	Get All Doctors
POST	/api/appointments	Book Appointment
DELETE	/api/appointments/:id	Cancel Appointment
📸 Screenshots
Home Page
Doctor Listing Page
Appointment Booking Page
Admin Dashboard
🔒 Security Features
Password Hashing using bcrypt
JWT Token Authentication
Protected Routes
Input Validation
📈 Future Improvements
Video Consultation
Online Payments
Email Notifications
Prescription Upload
Chat System
👨‍💻 Author

Rohan Karak
Full Stack Developer

📄 License

This project is licensed under the MIT License.
