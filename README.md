# Student Management CRUD Web Application

A beginner-friendly full-stack CRUD application using:
- Frontend: HTML, CSS, JavaScript
- Backend: Django
- Database: SQLite
- API: Django JSON REST-style endpoints

## Run
1. Open terminal in this folder.
2. Create a virtual environment: `python -m venv venv`
3. Activate it:
   - Windows: `venv\Scripts\activate`
4. Install Django: `pip install -r requirements.txt`
5. Create database: `python manage.py makemigrations` then `python manage.py migrate`
6. Start server: `python manage.py runserver`
7. Open: http://127.0.0.1:8000/

## API
- GET `/api/students/`
- POST `/api/students/`
- GET `/api/students/<id>/`
- PUT `/api/students/<id>/`
- DELETE `/api/students/<id>/`
