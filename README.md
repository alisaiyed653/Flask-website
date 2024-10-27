# Flask Web Application Project

This repository showcases my skills in developing a Flask-based web application. It features a contact form that collects user information and sends it securely via email. This project demonstrates proficiency in Python web development, email server integration, secure handling of environment variables, and Git version control.

## Skills and Technologies Demonstrated

### 1. **Flask Web Framework**
   - Developed a scalable, maintainable backend using Flask, a lightweight and efficient Python web framework.
   - Implemented routes and views to handle different parts of the web application, including Home, About, and Contact pages.
   - Utilized Flask’s templating capabilities for rendering dynamic HTML content with Jinja2.

### 2. **HTML/CSS for Frontend Design**
   - Created responsive and professional-looking web pages (`home.html`, `about.html`, `contact.html`) using HTML and CSS.
   - Applied custom styles to enhance user experience, ensuring consistency in design across all pages.
   - Integrated a contact form for collecting and sending user information, utilizing input fields, form validation, and submission handling.

### 3. **SMTP Email Integration**
   - Configured the application to send contact form submissions via email using the SMTP protocol.
   - Integrated with Microsoft Outlook's SMTP server (`smtp.office365.com`) for secure email transmission.
   - Demonstrated proficiency in handling multipart email formats using Python’s `smtplib`, `MIMEText`, and `MIMEMultipart`.

### 4. **Environment Variable Management**
   - Implemented secure handling of sensitive information (e.g., email credentials) using environment variables stored in a `.env` file.
   - Utilized the `python-dotenv` library to load these variables, demonstrating knowledge of secure coding practices.
   - Configured `.gitignore` to prevent sensitive files, like `.env`, from being tracked or pushed to GitHub.

### 5. **Version Control and Git Workflow**
   - Demonstrated competency in using Git for version control, with careful commit practices to track development stages.
   - Managed repository history effectively, staged and committed changes systematically, and documented project details in GitHub.
   - Created a `.gitignore` file to manage project artifacts and sensitive files, ensuring clean and secure code.

---

## Project Structure

This structure is organized for scalability, with clear separation of concerns for easy maintenance:

Flask-Website/ ├── server.py # Main Flask application file, contains routes and email handling logic ├── templates/ # HTML templates folder for rendering pages │ ├── home.html # Home page template │ ├── about.html # About page template │ └── contact.html # Contact page template ├── static/│ └── scp.png # Logo or additional images ├── .env # Environment variables (excluded from Git for security) ├── .gitignore # Specifies files and directories to ignore in Git └── README.md # Project documentation


---

## Setup and Installation

### Step 1: Clone the Repository
```
git clone <repository_url>
cd Flask-Website
```
### Step 2: Set Up a Virtual Environment
```
python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```
### Step 4: Configure Environment Variables
Add the following environment variables to a .env file:
```
OUTLOOK_EMAIL=your_email@example.com
OUTLOOK_APP_PASSWORD=your_app_password
```
### Step 5: Run the Application
```
python server.py
```
Access the application at http://127.0.0.1:5000.

## Key Learning and Demonstration Points

### Web Application Development:
Built a fully functional Flask application, handling routes, templates, and static assets.
### Security Best Practices: 
Leveraged environment variables for secure storage of sensitive information, avoiding hard-coded credentials.
### Version Control with Git: 
Applied Git for version management, maintaining a clear history of changes and ensuring secure, structured commits.
### Email Integration: 
Configured SMTP for automated email notifications, demonstrating skills in Python email libraries and third-party API configuration.
