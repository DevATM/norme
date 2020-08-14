# Django norme

> First respect the python norme !

- You have to respect the tree structure like this :  
> https://github.com/tclaudel/django_script could help you to create projects and apps  
- You must have subdirectories : forms, models, static, templates, views This will contains everything, 
the basics files like forms.py must contain nothing excpet the import of the files contained in the subdir
- You have to name the files inside subdirectories as name(singular)_type.py ex : member_model.py
```
.
├── DATM
│   ├── asgi.py
│   ├── __init__.py
│   ├── __pycache__
│   │   ├── __init__.cpython-37.pyc
│   │   ├── settings.cpython-37.pyc
│   │   ├── urls.cpython-37.pyc
│   │   └── wsgi.cpython-37.pyc
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── db.sqlite3
├── intranet
│   ├── admin.py
│   ├── apps.py
│   ├── forms
│   │   └── intranet
│   │       └── tmp
│   ├── __init__.py
│   ├── migrations
│   │   ├── 0001_initial.py
│   │   ├── 0002_auto_20200814_0955.py
│   │   ├── 0003_auto_20200814_1035.py
│   │   ├── 0004_auto_20200814_1041.py
│   │   ├── __init__.py
│   │   └── __pycache__
│   │       ├── 0001_initial.cpython-37.pyc
│   │       ├── 0002_auto_20200814_0955.cpython-37.pyc
│   │       ├── 0003_auto_20200814_1035.cpython-37.pyc
│   │       ├── 0004_auto_20200814_1041.cpython-37.pyc
│   │       └── __init__.cpython-37.pyc
│   ├── models
│   │   ├── __init__.py
│   │   ├── member_model.py
│   │   └── __pycache__
│   │       ├── __init__.cpython-37.pyc
│   │       └── member_model.cpython-37.pyc
│   ├── models.py
│   ├── __pycache__
│   │   ├── admin.cpython-37.pyc
│   │   ├── __init__.cpython-37.pyc
│   │   └── models.cpython-37.pyc
│   ├── static
│   │   ├── css
│   │   │   └── tmp
│   │   ├── img
│   │   │   └── profile_pictures
│   │   └── js
│   │       └── tmp
│   ├── templates
│   │   └── intranet
│   │       └── tmp
│   ├── tests.py
│   ├── views
│   │   └── intranet
│   │       └── tmp
│   └── views.py
├── manage.py
├── static
│   ├── css
│   ├── img
│   └── js
└── templates

```
