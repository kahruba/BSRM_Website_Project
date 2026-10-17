# 🏭 BSRM Employee Management Portal

A complete employee management and job application workflow system inspired by real-world HR operations.

Built with **HTML, CSS, and JavaScript** for the frontend and **Django and Python** for the backend, this portal allows employees to register, apply for jobs, track application statuses, and update their profiles. Administrators can manage employee applications, approve or reject requests, and maintain employee information through a centralized dashboard.

## 🌐 Project Links

- **🚀 Live Website:** [Visit BSRM Employee Management Portal](https://kahruba.github.io/BSRM_Website_Project/)
- **💻 GitHub Repository:** [View Source Code on GitHub](https://github.com/kahruba/BSRM_Website_Project)

---

## 🧩 Key Features

### 👨‍💼 Employee Management System

- Employee registration and login.
- Personalized employee dashboard.
- Guided job application form.
- Application status tracking.
- Profile management for confirmed employees.
- Access to company policies and guidelines.

### 📋 Application Status Management

Applications can have the following statuses:

- **Pending** — The application is waiting for administrator review.
- **Confirmed** — The application has been approved.
- **Re-Apply** — The employee can apply again after rejection or removal.

### 🛠️ Admin Control Panel

- Admin login and authentication.
- Centralized dashboard for employee applications.
- Review, approve, or reject job applications.
- Automatic application status updates following admin decisions.
- View employee details and edit profile information.
- Manage employee records through an organized interface.

---

## 🧠 System Highlights

- Realistic HR workflow simulation.
- Responsive and user-friendly interface.
- Clean UI inspired by BSRM's brand style.
- Frontend and backend implementation.
- Smooth navigation and structured dashboards.
- Local storage support in the frontend demo version.
- Django database integration in the backend version.

---

## 🛠️ Technology Stack

### Frontend

- HTML5
- CSS3
- JavaScript
- Responsive layouts and dashboard UI
- Browser Local Storage for the frontend demo

### Backend

- Python
- Django
- Django Authentication
- Django Models, Views, and Templates
- Database integration

### Development Tools

- Visual Studio Code
- Git and GitHub
- Browser Developer Tools

---

## ⚡ Features in Action

- Employee registration and login.
- Job application submission.
- Dynamic application status display.
- Admin review and approval workflow.
- Employee profile viewing and editing.
- Structured dashboards for employees and administrators.
- Responsive design and user-friendly navigation.

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.10 or later
- Django
- Git (recommended)

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/kahruba/BSRM_Website_Project.git
cd BSRM_Website_Project
```

**2. Install the dependencies**

If the repository contains a `requirements.txt` file, run:

```bash
pip install -r requirements.txt
```

**3. Apply database migrations**

For the Django backend version:

```bash
python manage.py migrate
```

**4. Start the development server**

```bash
python manage.py runserver
```

**5. Open the application**

Visit the following URL in your browser:

```text
http://127.0.0.1:8000/
```

> **Note:** The published GitHub Pages version is a static frontend demo. Django features require a separately configured backend server. The commands above apply only if the cloned repository contains the Django project files, including `manage.py`.

---

## 🧑‍💻 Usage Guide

### Employee Workflow

1. Register an employee account.
2. Log in to the portal.
3. Access the employee dashboard.
4. Submit a job application.
5. Track the application status.
6. Update the profile after confirmation, where supported.
7. Review company policies and guidelines.

### Administrator Workflow

1. Log in to the admin panel.
2. Review submitted applications.
3. Approve or reject applications.
4. Update employee information.
5. Manage employee records through the dashboard.

---

## 📚 Learning and Development Highlights

This project provides practical experience with:

- Building a complete employee management workflow.
- Developing frontend interfaces and backend functionality.
- Understanding Django's request-response lifecycle.
- Handling forms and validating user input.
- Implementing status-based UI updates.
- Structuring employee and administrator dashboards.
- Working with authentication and database operations.
- Using Git and GitHub for version control and project hosting.

---

## 📂 Project Structure

The exact structure depends on the version of the project.

### Frontend Version

```text
BSRM_Website_Project/
├── index.html
├── about.html
├── styles.css
├── employee_login.html
├── employee_register.html
├── employee_dashboard.html
├── employee_profile.html
├── admin_login.html
├── dashboard_admin.html
└── images/
```

### Django Backend Version

A Django implementation may use a structure similar to:

```text
project/
├── manage.py
├── requirements.txt
├── templates/
├── static/
├── employee/
└── admin_panel/
```

---

## 🔒 Security Considerations

The Django backend can provide security features such as:

- Django authentication.
- CSRF protection.
- Server-side form validation.
- Access controls for administrative actions.

**Important:** These protections depend on the actual backend implementation and configuration. A static frontend demo alone does not provide Django authentication or server-side security.

---

## 🤝 Contributing

Contributions and suggestions are welcome!

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Commit and push your changes.
5. Open a pull request.

---

## 💡 Future Improvements

Potential enhancements include:

- Salary slips and payroll management.
- Employee attendance tracking.
- Email notifications for application decisions.
- More granular role-based access control.
- Improved database integration.
- Automated employee reporting.
- Enhanced validation and security features.

---

## 📄 License

This project is intended to be distributed under the MIT License. Add an actual `LICENSE` file to the repository if you want to formally publish it under that license.

---

**Developed as a practical employee management system project.**

🔗 [Live Demo](https://kahruba.github.io/BSRM_Website_Project/) | [GitHub Repository](https://github.com/kahruba/BSRM_Website_Project)
