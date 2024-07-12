# Student Management System (Django)

## Overview
This project implements a Student Management System using Django, a high-level Python web framework. The system allows users to manage student records, including basic information and uploaded documents, utilizing Django's media handling capabilities.

## Features
- **Student CRUD Operations**: Create, Read, Update, and Delete student records.
- **File Uploads**: Allow users to upload and manage documents (e.g., student photos, certificates).
- **Admin Interface**: Utilize Django Admin for easy management of student data and uploaded files.

## Installation
1. Clone the repository:
git clone <repository_url>
cd <project_directory>


2. Install dependencies:
pip install -r requirements.txt

3. Configure Django settings:
- Set up database settings in `settings.py`.
- Configure `MEDIA_ROOT` and `MEDIA_URL` for handling uploaded files.

4. Apply database migrations:

python manage.py migrate

5.runserver
