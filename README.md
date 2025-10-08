HealEase - Doctor Booking Platform

HealEase is a full-stack web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It makes healthcare access easier by helping patients book doctor appointments and manage consultations seamlessly. The app provides dedicated dashboards for Patients, Doctors, and Admins.

🛠️ Tech Stack

Frontend: React.js

Backend: Node.js, Express.js

Database: MongoDB

Authentication: JSON Web Token (JWT)

🔑 Key Features
👩‍⚕️ Patient

Sign up, log in, and book doctor appointments.

View, cancel, or reschedule appointments.

Manage personal profile (name, email, address, gender, birthday, profile picture).

🩺 Doctor

Manage appointments and availability.

Dashboard with total patients, appointments, and earnings.

Update profile details (description, fees, address, and status).

👨‍💼 Admin

Add and manage doctor profiles.

View total doctors, patients, and appointments.

Cancel or mark appointments as completed.

🏠 Pages Overview
Home Page

Search doctors by specialty.

View top doctors and profiles.

Doctors Page

Browse and filter available doctors.

About Page

Learn about HealEase’s vision and goals.

Contact Page

Includes contact info and job opportunities.

Appointment Page

Shows doctor details and appointment form.

Requires login to book appointments.

Profile Page

View and edit profile details and appointments.

Admin & Doctor Dashboards

Manage doctors, patients, and appointments efficiently.

🌐 Project Setup
# Clone repository
git clone https://github.com/your-username/healease.git
cd healease

# Install dependencies
npm install
cd client
npm install


Create a .env file in the root directory:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret


Run the project:

npm run dev

📁 Folder Structure
healease/
├── client/          # Frontend (React)
├── server/          # Backend (Express)
├── models/          # Database Schemas
├── controllers/     # API Logic
├── routes/          # API Routes
├── middleware/      # Auth & Error Handling
├── config/          # Config Files
└── public/          # Static Assets
