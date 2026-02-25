# job_portal
https://ajittorane6568.pythonanywhere.com/login


🧑‍💼 Job Portal – Flask Web Application

A full-stack Job Portal Web Application built using Python (Flask), SQLite, HTML, CSS, Bootstrap, and Jinja2.
This platform allows users to register, apply for jobs, upload resumes, and track application status, while admins can manage job posts and applications.

🚀 Features
👤 User

Register & Login
View available jobs
Apply for jobs
Upload resume (PDF/DOC)
Track application status (Pending / Shortlisted / Rejected)
View all applied jobs

👨‍💼 Admin

Secure Admin Login
Post new jobs
Edit job details
Delete jobs (auto removes related applications)
View all received applications
Download candidate resumes
Update application status
Delete applications

🔐 Authentication

Separate login for Admin and Users
Secure session-based authentication

🛠️ Tech Stack
Layer	Technology
Frontend	HTML, CSS, Bootstrap 5
Backend	Python (Flask)
Database	SQLite
Templating	Jinja2
File Uploads	Flask Static Folder
Hosting	PythonAnywhere / Render
📂 Project Structure
job_portal/
│
├── app.py
├── job_portal.db
├── requirements.txt
├── static/
│   └── uploads/
└── templates/
    ├── login.html
    ├── register.html
    ├── dashboard.html
    ├── admin.html
    ├── jobs.html
    ├── post_job.html
    ├── base.html

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/yourusername/job-portal-flask.git
cd job-portal-flask

2️⃣ Install Dependencies
pip install flask


or

pip install -r requirements.txt

3️⃣ Run the Application
python app.py


Open browser:

http://127.0.0.1:5000

🔐 Admin Login

You can create an admin directly in the database or by modifying the register logic.

Admin privileges allow:

Posting jobs
Managing applicants
Changing job statuses
Deleting jobs


📌 Use Case

This project is ideal for:

Final year students
Freshers
Internship / Placement portals

HR management mini systems

🎯 Resume Value

This project demonstrates:
Full-stack development
Authentication & role-based access
File handling
Database integration
Real-world CRUD operations
Admin & user dashboards

📜 License

This project is open-source and free to use for learning and educational purposes.
