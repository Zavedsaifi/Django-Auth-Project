# Django-Auth-Project
A Django-based project with a robust authentication system, including user registration, login, logout, password reset, and permissions management.

# Features
User registration with Username and Password.
Login/logout functionality.
Password reset with Phone Number.
Role-based access and permissions management.
User profile page with editable details.
Responsive UI using HTML, CSS, and Bootstrap.

# Getting Started
Prerequisites
  Python 3.8 or higher
  Django 4.x
  A database (SQLite is the default)

# Project Structure
django-auth-project/
├── auth_app/            # Core authentication app
│   ├── models.py        # Custom user model (if implemented)
│   ├── views.py         # Login, logout, and registration views
│   ├── forms.py         # Forms for user authentication and profile updates
│   ├── templates/       # HTML templates for authentication pages
│   ├── urls.py          # URL routes for the auth_app
├── django_auth_project/ # Main project directory
│   ├── settings.py      # Django project settings
│   ├── urls.py          # Project-level URL configurations
├── static/              # Static files (CSS, JS, images)
├── templates/           # Shared templates
├── manage.py            # Django command-line utility
└── requirements.txt     # Python dependencies

# Core Functionalities
1. User Registration
  Users can sign up using an Username and password1, Re-Type Password.
2. Login/Logout
  Users can log in using their Username and password.
  Secure session handling for authentication.
3. Password Reset
  Users can reset their password via a secure Phone Number.
4. Profile Management
Users can view and update their profiles.
5. Role-Based Access
Define roles like admin, editor, and viewer with permissions using Django's built-in User and Group models.




