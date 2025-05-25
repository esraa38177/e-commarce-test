# e-commarce-test
Nile University E-Commerce website

Description

This e-commerce website, developed by a team of computer science students from Nile University, provides a platform for online shopping. Users can browse products, manage profiles, and handle orders. Built with Django and Python, the project emphasizes functionality and user experience, making it suitable for educational and practical applications.

Technologies Used

Python 3.7: Core programming language for backend development.
Django: Backend framework for building the web application.
HTML, CSS, JavaScript: Frontend technologies for user interface and interactivity.
Getting Started

Clone this repository and navigate to the project directory:

git clone [repository_url]
cd [repository_name]
Follow the installation instructions below to set up the project.

Installation Instructions

Prerequisites

Install Python 3.7 if not already installed:
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt update
sudo apt install python3.7
Set up Virtual Environment

cd /path/to/your/project
python3.7 -m venv venv
source venv/bin/activate
Install Dependencies

pip install -r requirements.txt
If requirements.txt does not exist, install Django manually:

pip install django
Set up Database

python manage.py migrate
Create Superuser

python manage.py createsuperuser
Run the Application

python manage.py runserver
Access the website at http://127.0.0.1:8000
Log in to the admin panel at http://127.0.0.1:8000/admin with the superuser credentials.
Usage

Frontend: Access the website to browse products, manage your profile, and place orders.
Admin Panel: Log in to manage users, products, orders, and other administrative tasks.
Additional Commands

Check Django version: django-admin --version
List installed packages: pip freeze
Generate migrations (if models change): python manage.py makemigrations
Contributors
