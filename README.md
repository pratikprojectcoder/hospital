Hospital Management System

A full-stack Hospital Management System built using Django that helps manage patients, doctors, appointments, departments, and medical records through a centralized web application. The project is designed to simplify hospital operations by digitizing healthcare workflows and providing organized data management.

Features
Patient Management
Add, update, delete, and view patient records
Store personal details, medical history, and contact information
Maintain centralized patient database
Doctor Management
Manage doctor profiles and specializations
Assign doctors to departments
Track doctor-related appointments and records
Appointment Scheduling
Book appointments between patients and doctors
View scheduled appointments
Manage appointment status and timings
Department Management
Create and manage hospital departments
Associate doctors with departments
Organize healthcare services efficiently
Medical Records
Store patient diagnoses and treatment details
Maintain digital health records
Easy access to patient history
Admin Dashboard
Centralized dashboard for managing hospital operations
Overview of patients, doctors, and appointments
Data visualization and analytics
Seed Data Generation
Custom Django management commands for generating realistic test data
Simplifies development and testing
Tech Stack
Technology	Purpose
Python	Backend Programming
Django	Web Framework
SQLite	Database
HTML	Structure
CSS	Styling
Bootstrap	Responsive UI
Django ORM	Database Operations
Project Structure
Hospital/
│
├── hospital/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── app/
│   ├── migrations/
│   ├── templates/
│   ├── static/
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   ├── admin.py
│   └── urls.py
│
├── manage.py
├── requirements.txt
└── README.md
Installation
1. Clone the Repository
git clone https://github.com/your-username/Hospital.git
2. Navigate to Project Directory
cd Hospital
3. Create Virtual Environment
Windows
python -m venv venv
venv\Scripts\activate
Mac/Linux
python3 -m venv venv
source venv/bin/activate
4. Install Dependencies
pip install -r requirements.txt
5. Apply Migrations
python manage.py makemigrations
python manage.py migrate
6. Create Superuser
python manage.py createsuperuser
7. Run Development Server
python manage.py runserver

Open browser:

http://127.0.0.1:8000/
Database

The project uses SQLite as the default database.

Database file:

db.sqlite3

Django ORM is used for:

CRUD operations
Model relationships
Query optimization
Data handling
Main Functionalities
CRUD Operations
Create
Read
Update
Delete

Implemented for:

Patients
Doctors
Appointments
Departments
Medical Records
Dashboard Analytics

The system provides:

Total patient count
Doctor statistics
Department overview
Appointment tracking
Healthcare data summaries
Admin Panel

Django Admin Panel is used for:

Managing records
Monitoring database entries
Updating hospital data
Administrative control

Access Admin Panel:

http://127.0.0.1:8000/admin
Seed Data

Custom management commands are included for generating sample hospital data.

Run:

python manage.py seed_data

This helps in:

Testing
Demonstrations
Development
Future Improvements
Authentication and role-based access
Email notifications
Prescription management
Billing and payment integration
REST API integration
AI-based patient analytics
Cloud deployment
Docker support
Learning Outcomes

Through this project:

Learned Django MVC architecture
Worked with relational databases
Implemented full-stack web development
Managed CRUD operations using Django ORM
Built responsive UI components
Developed scalable backend logic
Author

Pratik Mudras

GitHub:
https://github.com/pratikprojectcoder
