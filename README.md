# 🏨 Hotel Management System

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Django](https://img.shields.io/badge/Django-Web%20Framework-092E20)
![SQLite](https://img.shields.io/badge/Database-SQLite-003B57)
![HTML](https://img.shields.io/badge/Frontend-HTML%20%7C%20CSS%20%7C%20JS-E34F26)

A web-based hotel management system built with **Python, Django and SQLite**. It helps manage hotels, rooms and user accounts through a simple browser interface and the Django admin panel.


## ✨ Features
- 🔐 User accounts: registration, login and logout
- 🏢 Hotel management: add and manage hotel details
- 🛏️ Room management: add, edit and list rooms with details
- 🧑‍💼 Django admin panel for administrators
- 📱 Responsive HTML, CSS and JavaScript front end

<!-- Add or remove items, for example: room booking, payments, search and filters, booking history -->

## 🛠️ Tech Stack
| Area | Tools |
|---|---|
| Language | Python |
| Framework | Django |
| Database | SQLite |
| Frontend | HTML, CSS, JavaScript |

## 📁 Project Structure
```
hotel-management-system-django/
├── HMS/             # Project settings and URL configuration
├── accounts/        # User authentication app
├── hotel/           # Hotel app
├── room/            # Room app
├── Templates/       # HTML templates
├── static/          # CSS, fonts, images, JavaScript
├── manage.py
└── requirements.txt
```

## 🚀 Getting Started

```bash
# 1. Clone the repository
git clone https://github.com/ashiqmuneeb/hotel-management-system-django.git
cd hotel-management-system-django

# 2. Create and activate a virtual environment
python -m venv venv
venv\Scripts\activate          # Windows
# source venv/bin/activate     # Linux / macOS

# 3. Install dependencies
pip install -r requirements.txt

# 4. Create the database tables
python manage.py migrate

# 5. Create an admin user
python manage.py createsuperuser

# 6. Run the development server
python manage.py runserver
```

Open **http://127.0.0.1:8000/** in your browser. The admin panel is at **http://127.0.0.1:8000/admin/**.

## 🔐 Configuration
Do not commit secrets. Set your own `SECRET_KEY` and keep `DEBUG = False` in production.

## 🔮 Future Improvements
- Online room booking and availability calendar
- Payment integration
- REST API with Django REST Framework
- Deployment with Docker or Render

## 🙏 Credits
Front-end template credit: (add author and link if you used a template)

## 📄 License
Add a `LICENSE` file (MIT recommended) and link it here.
