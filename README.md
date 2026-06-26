# Hospital Management System using MERN Stack, Redux, TailwindCSS and Framer Motion

## Overview

A full-stack Hospital Management System built with the MERN stack (MongoDB, Express.js, React, Node.js), Redux for state management, TailwindCSS for responsive UI, and Framer Motion for smooth animations. The system aims to streamline hospital operations, improve patient care, and enhance overall efficiency.

## Features

### Dashboard Features:
- Dashboard Overview
- Add Admin
- Add Doctor
- Add Receptionists
- See all Doctors
- See all Appointments
- Manage Appointments

### Backend Features:
- Secure REST API
- JWT Authentication
- MongoDB Integration
- Role-based Access Control

### Frontend Features:
- Book Appointment
- Send Message to Admin
- Login / Register
- Responsive Design

## Technologies Used

- **Frontend:** React, Redux, TailwindCSS, Framer Motion
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT

## Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/try/download/community)

## Setup Instructions

1. **Clone the repository:**

```bash
git clone https://github.com/iamrealkkd/hospital-management-system.git
```

2. **Install backend dependencies:**

```bash
cd hospital-management-system/backend
npm install
```

3. **Set up environment variables:**

Create a `.env` file in the `backend` directory:

```
PORT=5000
DB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

4. **Install frontend dependencies:**

```bash
cd ../frontend
npm install
```

5. **Run the development servers:**

Start the backend server:

```bash
cd backend
node server.js
```

Start the frontend server:

```bash
cd frontend
npm run dev
```

6. **Access the application:**

Open your browser and navigate to `http://localhost:5173`.

## Contributing

Contributions are welcome! Feel free to submit pull requests, bug reports, or feature requests.

## License

This project is licensed under the [MIT License](LICENSE).