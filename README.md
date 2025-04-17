Appliance Repair Management System
📖 Overview
The Appliance Repair Management System is a full-stack web application designed to streamline the repair process for appliance repair businesses. This system allows companies to manage repair requests, assign technicians, track progress, and enhance customer satisfaction. It is built using PHP, MySQL, and Tailwind CSS, ensuring a responsive and user-friendly experience.

🛠️ Tech Stack
Frontend: Vite.js + JavaScript + HTML/CSS

Backend: Core PHP + REST APIs

Authentication: JWT (JSON Web Token)

Database: MySQL

Build Tools: Vite, ESLint

🔧 Features
Key Features of the System:
Role-Based Login System: Different user roles with distinct access levels (Admin, Technician, Customer).

JWT Authentication: Secure login with token-based authentication.

Technician Assignment: Admin can assign technicians to service requests based on availability.

Service Status Tracking: Monitor the progress of ongoing repairs (Pending, In-Progress, Completed).

Customer Management: Manage customer profiles, service history, and notifications.

Invoices & Payments: Generate and track invoices for completed repairs.

Admin Analytics Dashboard: View reports and analytics on repair activities, performance, and customer satisfaction.

🚀 Getting Started
Prerequisites:
PHP >= 7.x

MySQL

Composer (for managing PHP dependencies)

Vite.js (for frontend build)

Installation:
Clone the repository:

bash
Copy
Edit
git clone https://github.com/DEV-KUMAR51520/repair_services.git
cd repair_services
Install PHP dependencies (if not already installed):

bash
Copy
Edit
composer install
Set up the MySQL database:

Create a new MySQL database.

Import the database.sql file located in the project folder to set up tables and initial data.

Configure environment variables:

Create a .env file based on .env.example and set up your database credentials and JWT secret key.

Run the project:

Start the PHP built-in server:

bash
Copy
Edit
php -S localhost:8000
Open the project in your browser at http://localhost:8000.

🎨 Frontend Design
The frontend is designed using Vite.js for fast build times and a seamless user experience. Tailwind CSS is used to style the pages, ensuring a clean and responsive design.

🔐 Security Features
JWT Authentication: Secure login and authorization system to protect user data.

Role-Based Access Control: Different access levels for users to ensure data security.