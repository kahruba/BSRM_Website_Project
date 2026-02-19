BSRM Employee Management Portal 🏭

A complete employee handling and job-application workflow system inspired by real industry-level HR operations.
Built with HTML, CSS, JavaScript (Frontend) and Django (Backend), this portal allows employees to register, apply for jobs, track application status, and update profiles — while admins manage all employee approvals and data in a centralized dashboard.
________________________________________________________________

🧩 Key Features

👨‍💼 Employee System
	
  •	Employee registration & secure login
  •	Personalized employee dashboard
  •	Apply for job through a guided form	
  •	Check job application status in real-time:	
  •	Pending — waiting for admin approval	
  •	Confirmed — employee is accepted	
  •	Re-Apply — admin rejected or removed	
  •	Employees can update their profile after confirmation	
  •	View company policies and follow guidelines
  _______________________________________________________________
🛠 Admin Control Panel

  •	Admin login with authentication	
  •	View all employee applications in a structured dashboard	
  •	Approve or reject job requests
  •	When approved → employee automatically moves to Confirmed status
  •	When rejected → employee gets Re-Apply option	
  •	View employee details and edit profile information	
  •	Manage employee data in a clean, organized UI
  _______________________________________________________________
  🧠 System Highlights

  •	Realistic HR workflow simulation	
  •	Fully responsive UI	
  •	Clean design inspired by BSRM brand style	
  •	Frontend and backend both implemented by me	
  •	Smooth navigation and clean structure	
  •	Local storage (frontend version) + Django database (backend version)
  ___________________________________________________________________
🛠️ Tech Stack

Frontend
	•	HTML5
	•	CSS3
	•	JavaScript
	•	Responsive layout & dashboard UI
	•	Local storage (frontend demo version)
Backend
	•	Django
	•	Python
	•	Django Authentication
	•	Django Models, Views, Templates
Tools
	•	VS Code
	•	Git & GitHub
	•	Browser DevToolS
____________________________________________________________________
⚡ Features in Action
	•	Employee registration & session handling
	•	Job application submission
	•	Dynamic status display (Pending / Confirmed / Re-Apply)
	•	Admin review system
	•	Editable employee profiles
	•	Fully styled dashboards with smooth workflow
___________________________________________________________________
🚀 Getting Started

Prerequisites
	•	Python 3.10+
	•	Django installed
	•	Git installed (optional but recommended)
___________________________________________________________________
Installation
# Clone the repository
git clone https://github.com/you cd office_emp_proj

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Run server
python manage.py runserver
_________________________________________________________________
🧑‍💻 Usage Guide

Employee
	1.	Register an account
	2.	Log in
	3.	Go to dashboard
	4.	Apply for job
	5.	Track application progress
	6.	After confirmation → update profile
	7.	Follow company rules

Admin
	1.	Log in to admin panel
	2.	View all applications
	3.	Approve or reject
	4.	Manage employee info
___________________________________________________________________
📚 Learning & Development Highlights
	•	Implemented full workflow automation
	•	Built both frontend + backend
	•	Django view lifecycle & template rendering
	•	Form handling & data validation
	•	Status-based UI changes
	•	Clean dashboard structuring
	•	Practical project to understand HR management systems
___________________________________________________________________
📂 Project Structure
/static              - CSS, JS, images
/templates           - HTML templates
/employee            - Employee app (views, models, URLs)
/admin_panel         - Admin features
manage.py            - Django project root
____________________________________________________________________
🔒 Security
	•	CSRF protection enabled
	•	Django authentication system
	•	Error-handled forms
	•	Secure admin actions
____________________________________________________________________
🤝 Contributing

PRs are welcome!
	1.	Fork repository
	2.	Create a new branch
	3.	Commit changes
	4.	Push
	5.	Create PR
_________________________________________________________________
📄 License

This project is licensed under the MIT License.
_______________________________________________________________
💡 Future Improvements
	•	Add salary slips / payroll
	•	Add employee attendance system
	•	Email notifications for approval
	•	Role-based access controls
	•	Full database integration for frontend version
