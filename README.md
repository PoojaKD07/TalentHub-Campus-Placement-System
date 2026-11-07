# TalentHub – Campus Placement Management System

A web-based Campus Placement Management System developed using **Python Flask, SQLite, HTML, CSS, and MySQL**. TalentHub simplifies and manages campus recruitment activities by connecting students, companies, and placement coordinators through a centralized platform.

## 📌 Project Overview

TalentHub is designed to digitize the campus placement process. It provides separate functionalities for students, companies, and placement coordinators, making recruitment activities easier to manage, track, and monitor.

The system helps students explore job opportunities and apply for eligible positions, enables companies to post job openings and manage applications, and allows coordinators to supervise the overall placement process.

## 🎯 Objectives

- Develop a centralized platform for campus placement activities.
- Provide separate access for students, companies, and coordinators.
- Automate job eligibility checking based on CGPA, department, and backlogs.
- Simplify job applications and application tracking.
- Support interview scheduling and offer management.
- Maintain structured placement-related information in a database.

## 🚀 Key Features

### 1. Student Module
- Student registration and login.
- View available job opportunities.
- Check job eligibility.
- Apply for eligible jobs.
- Track application status.
- View interview schedules and placement offers.

### 2. Company Module
- Company registration and login.
- Create and manage job postings.
- Specify job eligibility requirements.
- View student applications.
- Manage recruitment and interview information.
- Update application and selection statuses.

### 3. Placement Coordinator Module
- Manage student and company information.
- Monitor job postings and applications.
- Supervise placement activities.
- Track interview and offer details.
- Manage the overall placement process.

### 4. Additional Features
- Role-based access.
- Database integration.
- Job eligibility verification.
- Application management.
- Interview scheduling.
- Offer management.
- CSRF protection and input validation.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| Flask | Web application framework |
| SQLite | Application database |
| MySQL | Alternative database schema |
| HTML | Web page structure |
| CSS | User interface styling |
| Jinja2 | Dynamic HTML templates |
| GitHub | Version control and project hosting |

## 📂 Project Structure

```text
TalentHub-Campus-Placement-System/
│
├── app/
│   ├── __init__.py
│   ├── db.py
│   ├── repositories.py
│   ├── services.py
│   │
│   ├── routes/
│   │   ├── __init__.py
│   │   ├── main.py
│   │   ├── student.py
│   │   ├── company.py
│   │   └── coordinator.py
│   │
│   ├── templates/
│   │   └── HTML templates
│   │
│   ├── static/
│   │   └── style.css
│   │
│   └── schema.sql
│
├── tests/
│   └── test_talenthub.py
│
├── instance/
│   └── .gitkeep
│
├── run.py
├── seed.py
├── requirements.txt
├── schema_mysql.sql
├── .gitignore
└── README.md
```

## ⚙️ Installation and Setup

### Prerequisites

Make sure the following are installed:

- Python 3.10 or later
- pip (Python package manager)
- Git (optional, for cloning the repository)

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/TalentHub-Campus-Placement-System.git
cd TalentHub-Campus-Placement-System
```

Replace `YOUR-USERNAME` with your GitHub username.

### Step 2: Create a Virtual Environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

Activate it on Linux/macOS:

```bash
source venv/bin/activate
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Initialize the Database

The application uses SQLite for its default database configuration. Follow the database initialization process defined in the application.

If the project requires sample data, run:

```bash
python seed.py
```

### Step 5: Run the Application

```bash
python run.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

## 🗄️ Database Information

The project includes database schemas for:

- **SQLite:** `app/schema.sql`
- **MySQL:** `schema_mysql.sql`

The SQLite database is used by the application's default configuration. The MySQL schema is provided as an alternative database definition.

## 🧪 Testing

The project includes automated tests in the `tests/` directory.

To run the tests:

```bash
pytest
```

Make sure the required dependencies are installed before executing the tests.

## 🔐 Security Features

- Role-based access control.
- Password handling through the application's authentication implementation.
- CSRF protection.
- Input validation.
- Controlled access to role-specific functionality.

## 📸 Application Screenshots

Screenshots of the application can be added here to demonstrate the user interface and major functionalities.

### Homepage

<!-- Add your homepage screenshot here -->
<!-- Example: ![Homepage](evidence/01_homepage.png) -->

### Student Dashboard

<!-- Add your student dashboard screenshot here -->

### Company Dashboard

<!-- Add your company dashboard screenshot here -->

### Coordinator Dashboard

<!-- Add your coordinator dashboard screenshot here -->

### Job Application and Management

<!-- Add your job application screenshot here -->

## 🔮 Future Enhancements

- Email notifications for application updates.
- Resume upload and management.
- Advanced placement analytics and reports.
- Improved dashboard visualizations.
- Automated interview notifications.
- Integration with external recruitment platforms.

## 👩‍💻 Contributors

Developed as an academic project to demonstrate web application development, database management, backend programming, and software engineering concepts.

## 📄 License

This project is intended for academic and educational purposes.

---

**TalentHub – Connecting Students, Companies, and Opportunities.**
