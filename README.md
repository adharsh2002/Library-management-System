# Library Management System

This Django-based web application is a Library Management System, allowing users to manage students, books, and book transactions.

## Features
- Two Forms: Students and Books
- One Form to issue a book to a particular student (supporting multiple transactions for one student).

## Getting Started

### Clone the Repository

bash
git clone https://github.com/adharsh2002/Library-management-System.git
cd Library-Management-System

### Create and Activate Virtual Environment
virtualenv -p python3 venv
cd venv
source bin/activate

### Run Steps
cd ..
<br>
cd LMS
<br>
python manage.py makemigrations
<br>
python manage.py migrate
<br>
python manage.py runserver


