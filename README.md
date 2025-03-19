Disaster Response Coordination App
A comprehensive platform designed to coordinate disaster response efforts, connecting affected communities with resources, volunteers, and emergency services.

Overview
The Disaster Response Coordination App provides a centralized system for managing disaster response activities, including:

Incident reporting and tracking
Resource allocation and donation management
Volunteer coordination
Emergency alerts and notifications
User authentication and account management
Technology Stack
Frontend: React.js, React Router, React-Toastify
Backend: Express.js, Node.js
Database: MongoDB 

Getting Started
Prerequisites
Node.js (v14 or higher recommended)
npm (v6 or higher)

Installation
1. Clone the repository:

git clone https://github.com/your-username/APP4080-Disaster-Response-Coordination.git
cd APP4080-Disaster-Response-Coordination


2. Install backend dependencies:

cd backend
npm install

3. Install frontend dependencies:

cd ../frontend
npm install


Running the Application
Backend Server
cd backend
npm start


The server will run on http://localhost:5000 

Frontend Application
cd frontend
npm start


The application will open in your browser at http://localhost:3000

Features
Home Dashboard
Central hub displaying critical information and navigation to all app features.

Incident Reporting
Submit and track disaster incidents with location data, severity, and resource needs.

User Authentication
Secure login and signup functionality for users and organizations.

Donations Management
Platform for coordinating monetary and material donations to affected areas.

Volunteer Coordination
System for registering, scheduling, and deploying volunteers to disaster sites.

Alerts System
Real-time notifications for emergency updates and critical information.

Testing
Run the test suite with:

cd frontend
npm test


Deployment
Build the frontend for production:

cd frontend
npm run build
