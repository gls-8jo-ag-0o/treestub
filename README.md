# treestub
Takes an AI generated project tree structure and stubs it out


Example Stub:
```
myproject/
│── docker-compose.yml
│── Dockerfile
│── requirements.txt
│── .env
│── README.md
│── config/
│   ├── settings_local.py
│   ├── settings_production.py
│── scripts/
│   ├── start.sh
│   ├── migrate.sh
│── logs/
│   ├── error.log
│   ├── access.log
│── static/
│   ├── css/
│   │   ├── style.css
│   ├── js/
│   │   ├── main.js
│── media/
│── myapp/
│   ├── manage.py
│   ├── myproject/
│   │   ├── __init__.py
│   │   ├── settings.py
│   │   ├── urls.py
│   │   ├── wsgi.py
│   │   ├── asgi.py
│   ├── myapp/
│   │   ├── __init__.py
│   │   ├── views.py
│   │   ├── urls.py
│   │   ├── models.py
│   │   ├── forms.py
│   │   ├── serializers.py
│   │   ├── admin.py
│   │   ├── tests.py
│   │   ├── middleware.py
│   │   ├── api/
│   │   │   ├── __init__.py
│   │   │   ├── views.py
│   │   │   ├── urls.py
│   │   │   ├── serializers.py
│   │   ├── migrations/
│   │   │   ├── __init__.py
│   │   ├── templates/
│   │   │   ├── base.html
│   │   │   ├── index.html
│   │   │   ├── dashboard.html
│   │   │   ├── partials/
│   │   │   │   ├── header.html
│   │   │   │   ├── footer.html
│   │   ├── static/
│   │   │   ├── css/
│   │   │   │   ├── app.css
│   │   │   ├── js/
│   │   │   │   ├── app.js
│   │   │   ├── images/
│   │   │   │   ├── logo.png
│   ├── users/
│   │   ├── __init__.py
│   │   ├── models.py
│   │   ├── views.py
│   │   ├── serializers.py
│   │   ├── urls.py
│   │   ├── forms.py
│   │   ├── templates/
│   │   │   ├── login.html
│   │   │   ├── register.html
│   │   │   ├── profile.html
│── tests/
│   ├── __init__.py
│   ├── test_views.py
│   ├── test_models.py
│   ├── test_forms.py
│── .gitignore
```
