# User Management System

User management system designed to facilitate secure identity and access management for web applications. It features a set of functionalities including user registration, login, account recovery, and password management, ensuring a seamless and secure user experience.

1. Django Installation

```python
pip install Django
```

2. Django Rest Framework Installation

```python
pip install djangorestframework
```

3. Start Django Project

```python
django-admin startproject loginRegisterAPI
```

```python
cd loginRegisterAPI
```

```python
python manage.py startapp userApi
```

4. Register userApi app

```python
INSTALLED_APPS = [
    'userApi.apps.UserApiConfig',
]
```

5. Register Django Rest Framework

```python
INSTALLED_APPS = [
    'rest_framework',
]
```

6. Models

```python
python manage.py migrate
```

7. Start out application

```python
python manage.py runserver
```

8. Create superuser

```python
python manage.py createsuperuser
```

9. Run application again

```python
python manage.py runserver
```

10. Include URL for our app

```python
urlpatterns = [
    path('admin/', admin.site.urls),
    path("", include("todoList.urls"))
]
```

11. Update the url file

```python
from django.urls import path
from .views import index

urlpatterns = [
    path("", index, name = "index")
]
```
