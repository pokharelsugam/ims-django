# Django Inventory Management System

Inventory Management System built with Django Rest Framework

## Features

- User, group, product, product category, department, suplier and purchase management

## Project Structure


<pre><code>
.
└── ims-django
    ├── env
    ├── base 
    │   ├── __pycache__
    │   ├── migrations
    │   ├── __init__.py
    │   ├── views.py
    │   ├── models.py
    │   ├── admin.py
    │   ├── urls.py
    │   ├── tests.py
    │   ├── apps.py
    │   └── serializers.py
    ├── IMS
    │   ├── __pycache__
    │   ├── __init__.py
    │   ├── asgi.py
    │   ├── settings.py
    │   ├── urls.py
    │   └── wsgi.py
    ├── manage.py
    └── db.sqlite3
      
</code></pre>
## Getting Started

### Prerequisites

- Python 3.6+
- Django 3.2+
- Django Rest Framework
- Git

### Installation

1. Install Python
2. Install Django
   <pre><code>
   pip install django
   </code></pre>
4. Install Virtual Environment
   <pre><code>
   pip install virtualenv
   </code></pre>
6. Clone the repository
   <pre><code>
   git clone https://github.com/pokharelsugam/ims-django.git
   cd elibrary-django
   </code></pre>
8. Create a virtual environment and activate it.
   <pre><code>
   virtualenv env
   env\scripts\activate
   pip install django
   pip install djangorestframework
   </code></pre>
10. Run the migrations
    <pre><code>
    python manage.py makemigrations #may or may not be required
    python manage.py migrate	#must be required
    </code></pre>
12. Create a superuser
    <pre><code>
    python manage.py createsuperuser
    </code></pre>
14. Start the development server
    <pre><code>
    python manage.py runserver
    </code></pre>

## Usage
<ul>
<li>Navigate to http://127.0.0.1:8000/admin to access the admin interface and manage your ims data.</li>
<li>Test api by using Postman</li>
</ul>
