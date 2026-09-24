# Orion Fitness

A gym management website built with Django as a learning project to practice Django's MVC architecture, ORM, and built-in authentication system.

## Tech Stack
- **Backend:** Python, Django
- **Database:** SQLite
- **Frontend:** Django templates, HTML/CSS

## Features
- User registration and login (via a dedicated `authapp` module using Django's authentication system)
- Gym-themed front-end pages built with Django templates

## About This Project
This was built as a practice project to get hands-on with Django's structure — models, views, templates, and the ORM — following along with an online tutorial and adapting it. It helped build a working understanding of Django's authentication flow and app structure, which carries over well to building things like Django REST APIs.

## Local Setup
1. Clone the repository
```bash
   git clone https://github.com/meshmell100/gymorionfitness.git
   cd gymorionfitness/orionfitness
```
2. Install Django
```bash
   pip install django
```
3. Run migrations
```bash
   python manage.py migrate
```
4. Start the server
```bash
   python manage.py runserver
```
