# Lab 29 - Class 401d24

## Project
Django Custom User

## Author

Kaitlin Davis | February 2024

## About
This Django project is an implementation of a custom user model, allowing the use of the default User model provided by Django. It is created to demonstrate the creation and use of a custom user within the Django admin interface as well as handling user authentication and permissions. This project is configured for Django 5 and follows the latest practices for creating secure and efficient user models.

## Features
- Custom user model named `CustomUser` which replaces the default User model.
- Full integration with Django Admin for managing custom users.
- Secure authentication system, ensuring that user login and logout are handled via `POST` requests, complying with Django 5 requirements.

## Installation
Follow these steps to set up and run the project:

1. **Clone the repository**

    ```sh
    git clone https://github.com/KaitlinDa/snacks-crud.git
    cd snacks-crud
    ```

2. **Set up the Python virtual environment**

    ```sh
    python -m venv venv
    source venv/bin/activate
    ```

3. **Install the requirements**

    ```sh
    pip install -r requirements.txt
    ```

4. **Run database migrations**

    ```sh
    python manage.py makemigrations
    python manage.py migrate
    ```

5. **Create a superuser account in Django**

    ```sh
    python manage.py createsuperuser
    ```

6. **Start the development server**

    ```sh
    python manage.py runserver
    ```

7. **Open your web browser and navigate to** `http://127.0.0.1:8000/` to explore the application.

## User Acceptance Tests
There are no User Acceptance Tests required for this lab. 

## Resources
I used the help of the class demo, LearnDjango, and ChatGPT for this assignment. 