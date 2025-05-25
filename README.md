# Nile University E-Commerce Project

## Description

This e-commerce website, developed by a team of computer science students from Nile University, provides a platform for online shopping. Users can browse products, manage profiles, and handle orders. Built with Django and Python, the project emphasizes functionality and user experience, making it suitable for educational and practical applications.

## Technologies Used

- **Python 3.7**: Core programming language for backend development.
- **Django**: Backend framework for building the web application.
- **HTML, CSS, JavaScript**: Frontend technologies for user interface and interactivity.
- *(Add other technologies, such as Bootstrap or jQuery, if used in your project.)*

## Getting Started

Clone this repository and navigate to the project directory:

```bash
git clone [repository_url]
cd [repository_name]
```

Follow the installation instructions below to set up the project.

## Installation Instructions

### Prerequisites

- Ensure you have WSL installed with a Linux distribution, such as Ubuntu.
- Install Python 3.7 if not already installed:

```bash
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt update
sudo apt install python3.7
```

### Set up Virtual Environment

```bash
cd /path/to/your/project
python3.7 -m venv venv
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```
*If `requirements.txt` does not exist, install Django manually:*

```bash
pip install django
```

### Set up Database

```bash
python manage.py migrate
```

### Create Superuser

```bash
python manage.py createsuperuser
```

### Run the Application

```bash
python manage.py runserver
```

- Access the website at [http://127.0.0.1:8000](http://127.0.0.1:8000)
- Log in to the admin panel at [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin) with the superuser credentials.

## Usage

- **Frontend**: Access the website to browse products, manage your profile, and place orders.
- **Admin Panel**: Log in to manage users, products, orders, and other administrative tasks.

### Additional Commands

- Check Django version: `django-admin --version`
- List installed packages: `pip freeze`
- Generate migrations (if models change): `python manage.py makemigrations`

## Contributors

| Name         | Student ID  |
|--------------|-------------|
| Esraa Ahmed  | 221000462   |
| Ganna Saad   | 221001828   |
| Radwa Emad   | 222000092   |
| Hamsa Elfaky | 221001806   |

## License

*(If applicable, specify the license here, e.g., MIT or GPL. Consult with your team to determine the appropriate license for your project.)*