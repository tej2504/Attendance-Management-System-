Name : R Tejashree 
                                              College Name : Vel Tech Rnagarajan Dr.Sagunthala R&D Institute of Science and Technology 
Roll No : VTU21891 
Contact : vtu21891@veltech.edu.in 
          7010213425
# Employee Attendance Management System
A full-stack Employee Attendance Management System designed to track daily attendance, monitor team performance, and generate analytical reports.
The system supports role-based authentication for Employees and Managers with a clean corporate UI and real-time dashboard insights.

Above i have included a complete documentation of the Screenshots and details of the required deliverables. (Attendance Management system Documentation)

Features

Employee Features

Secure Login & Registration
Daily Check-in / Check-out
View Attendance History (Calendar & Table)
Monthly Summary (Present / Absent / Late / Half-Day)
Dashboard with attendance statistics
Profile Management

Manager Features

Secure Login
View All Employees Attendance
Filter by Employee, Date, Status, Department
Team Summary Dashboard
Bar Chart 
Department-wise Analytics
Export Attendance Reports (CSV)
Team Calendar View

Tech Stack

Frontend

React.js
Redux Toolkit
React Router
Recharts (for charts)
Axios

Backend

Node.js
Express.js
JWT Authentication
Role-Based Authorization

Database

MongoDB (Mongoose ODM)

Authentication & Authorization

JWT-based authentication
Role-based access control
Protected routes
Secure password hashing

📊 Dashboard Highlights

Employee Monthly Stats
Manager Team Overview
Department-wise Attendance
Attendance Trend Visualization
Late Entry Tracking

📁 Project Structure
attendance-system/
 ├── backend/
 │    ├── controllers/
 │    ├── routes/
 │    ├── models/
 │    └── middleware/
 └── frontend/
      ├── components/
      ├── pages/
      ├── redux/
      ├── services/
      └── assets/

⚙️ Setup Instructions
Clone the Repository
git clone <your-repo-link>
cd attendance-system

Backend Setup
cd backend
npm install


Create a .env file:

PORT=5000
MONGO_URI= refer .env file in backend 
JWT_SECRET= refer .env file in backend


Run backend:

npm start

Frontend Setup
cd frontend
npm install
npm start


App runs at:

http://localhost:3000

Sample Credentials

Manager:

manager@company.com
manager123


Employee:

alice@company.com
password123

Instructions for viewing Video Demonstration Link : 

1. Click the Loom link below 
2. To view the Demo link , do not Sign-in to google when prompted by google. Continue viewing the Demo video without Sign-in. (or)
3. Sign-in to loom completely , Log-in and then view this video for better experience. 

Vedio Demonstration Link (Loom Link ): https://www.loom.com/share/e7f4fcd2b2964178be76b4219a61ab59



