Tango with Django Project
This project is a web application developed while following the "Tango with Django" book. It demonstrates the basics of building a Django web app, including template rendering, models, URL routing, and CRUD operations.

Table of Contents
Project Overview
Features
Installation
Usage
Project Structure
Technologies Used
License
Project Overview
The "Tango with Django" project is an educational exercise designed to teach the fundamentals of Django web development. Throughout the chapters, various features are added to the application to simulate real-world web development.

Features
User registration and authentication
Category and page management
Dynamic content with templates
Static files and media management
Admin interface for managing the website content
Installation
To run this project locally, follow these steps:

Clone the repository:


#Copy code
git clone https://github.com/ahmxd675/tango_with_django_project.git
cd tango_with_django_project
Create a virtual environment:


#Copy code
python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install dependencies:


#Copy code
pip install -r requirements.txt
Migrate the database:


#Copy code
python manage.py migrate
Run the development server:


#Copy code
python manage.py runserver
The application will be accessible at http://127.0.0.1:8000/.

Usage
After running the server, you can:

Register as a new user
Log in and create new categories and pages
Browse through the created pages and categories
Access the Django admin interface at /admin to manage the content
Project Structure
Here’s a brief overview of the main directories in the project:

media/ - Stores uploaded files
rango/ - The main Django app containing views, models, and URLs for the application
static/ - Static assets like CSS, JavaScript, and images
templates/ - HTML templates for rendering pages
tango_with_django_project/ - Contains the main settings and configurations for the Django project
Technologies Used
Django - A high-level Python web framework
SQLite - A lightweight, file-based database used for development
HTML/CSS - For front-end structure and styling
Python - The programming language used for server-side scripting
