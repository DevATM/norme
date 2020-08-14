# Django norme

> First respect the python norme !

- You have to respect the tree structure like this :  
> https://github.com/tclaudel/django_script could help you to create projects and apps  
- You must have subdirectories : forms, models, static, templates, views with a subdirectory named like the app This will contains everything, 
the basics files like forms.py must contain nothing excpet the import of the files contained in the subdir
- You have to name the files inside subdirectories as name(singular)_type.py ex : member_model.py
```
.
├── DATM
│   ├── asgi.py
│   ├── __init__.py
│   ├── __pycache__
│   │   ├── __init__.cpython-37.pyc
│   │   └── settings.cpython-37.pyc
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── intranet
│   ├── admin.py
│   ├── apps.py
│   ├── forms
│   │   └── intranet
│   │       └── tmp
│   ├── __init__.py
│   ├── migrations
│   │   └── __init__.py
│   ├── models
│   │   └── intranet
│   │       └── member_model.py
│   ├── models.py
│   ├── static
│   │   └── intranet
│   │       ├── css
│   │       │   └── tmp
│   │       ├── img
│   │       │   └── tmp
│   │       └── js
│   │           └── tmp
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