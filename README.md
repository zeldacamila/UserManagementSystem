# User Management System

User management system designed to facilitate secure identity and access management for web applications. It features a set of functionalities including user registration, login, account recovery, and password management, ensuring a seamless and secure user experience.

## Requirements

- Python 3.10 or higher
- virtualvenv
- Django 5.0.3
- djangorestframework 3.15.1

## Environment Setup

1. Clone the repository:

```bash
git clone https://github.com/zeldacamila/UserManagementSystem.git
cd UserManagementSystem/loginRegisterAPI
```

2. Create virtual environment

```bash
python -m venv venv
```

3. Activate virtual env

```bash
source venv/bin/activate
```

On Windows:

```bash
venv\Scripts\activate
```

4. Install libraries

```bash
pip install -r requirements.txt
```

5. Start out application

```bash
python manage.py migrate
python manage.py runserver
```
