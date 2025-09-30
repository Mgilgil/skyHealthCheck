# skyHealthCheck
This project was created as part of my university coursework. It is a Django web application for Sky employees to complete wellbeing health checks, submit votes, and view summaries based on their role. The repository includes the full code, test plan, an individual report, and a group report covering design, security, and ethical considerations.

The repository contains:  
- The complete **Django project** with all source code.  
- An **individual report** describing my contributions, implementation details, and test plan.  
- A **group report** covering database design, front-end, security, and professional conduct (legal and ethical issues).

Demo video:
https://youtu.be/T2LEyhbNTFU 

---

## Features  

- **User Authentication**  
  - Secure signup, login, logout, and password reset using Django’s built-in authentication system.  
  - Roles include Engineer, Team Leader, Department Leader, and Senior Manager.  

- **Role-Based Access**  
  - Engineers can complete health checks.  
  - Team Leaders, Department Leaders, and Senior Managers can view summaries and feedback.  

- **Health Check & Voting**  
  - Employees submit votes and feedback linked to sessions and cards.  
  - Votes include comments and trend states, supporting analysis of workplace wellbeing.  

- **Summary Pages**  
  - Role-based summaries showing results and comments.  
  - Clear, concise presentation of workplace wellbeing data.  

- **User Profile Management**  
  - Users can update their name, email, or password.  
  - Changes reflected immediately in the database.  

- **Security Features**  
  - Password hashing with modern algorithms.  
  - CSRF protection on all forms.  
  - Input validation to prevent invalid submissions.  

- **UI/UX Design**  
  - Consistent Sky branding across all pages.  
  - Responsive design using Bootstrap for desktop and mobile.  
  - Accessible colour contrasts and clean navigation.  

---

## Testing  

A detailed **test plan** was implemented to validate all features, including:  
- **Signup & Login** – Valid and invalid cases, error handling, and redirects.  
- **Password Reset** – Email validation, reset links, and password strength enforcement.  
- **Voting & Health Check** – Ensures votes cannot be submitted with missing fields.  
- **Summaries** – Display role-specific results and handle missing data gracefully.  
- **Profile Updates** – Valid/invalid input handling for name, email, and password changes.  

All positive and negative cases were documented, with results included in the **individual report**.  

---

## Technologies Used  

- **Python (Django Framework)**  
- **SQLite** – database backend  
- **Bootstrap** – responsive front-end  
- **HTML, CSS, JavaScript** – for templates and UI  
- **Git & GitHub** – version control and group collaboration  

---

## How to Run  

1. Clone this repository:  
   ```bash
   git clone https://github.com/Mgilgil/SkyHealthCheck.git
2. Unzip and extract the file
3. Open terminal and enter cd django db
4. python manage.py runserver
5. Access the application locally at http://127.0.0.1:8000/
6. Dummy login credentials provided in report.
