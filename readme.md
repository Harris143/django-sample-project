
# Django Sample Project

This is a simple blog-style Django application that demonstrates:

- Django project structure
- Model-View-Template (MVT) pattern
- ORM-based CRUD functionality
- Bootstrap-integrated UI
- Admin panel management

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Harris143/django-sample-project.git
cd django-sample-project
```

### 2. Set Up the Virtual Environment

```bash
# Create virtual environment
python -m venv .venv

# Activate it
# For Windows:
.\.venv\Scripts\activate

# For macOS/Linux:
source .venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install django
```

### 4. Apply Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Create Superuser (Optional for Admin Panel)

```bash
python manage.py createsuperuser
```

### 6. Run the Development Server

```bash
python manage.py runserver
```

Visit the app: [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 🛠 Features

- Create posts using a form
- View post list on homepage
- Admin dashboard for model management
- Bootstrap layout with reusable base template

---

## 🗂 Folder Structure

```
mysite/
├── blog/
│   ├── migrations/
│   ├── templates/
│   │   └── blog/
│   │       ├── base.html
│   │       ├── home.html
│   │       └── create_post.html
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── mysite/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── db.sqlite3
└── manage.py
```

---

## 📜 License

MIT License

---
