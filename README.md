This project implements a secure authentication system using JSON Web Tokens (JWT) with Django. JSON Web Tokens are a compact, URL-safe means of representing claims to be transferred between two parties. This system allows users to authenticate and access protected resources by generating and validating JWT tokens.

Features
-Token-Based Authentication: Utilizes JWT for secure user authentication.
-Django Integration: Built on top of Django, a high-level Python web framework.
-User Management: Easily manage user authentication and authorization.
-Secure: Implements best practices for secure token handling and validation.

pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
