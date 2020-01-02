# User Login/Logout Page

## Tech-Stack

- Django version 2.2.6
- Sqlite Database


## Initial Setup
- Setup virtual environment in your PC ([setup details](https://docs.djangoproject.com/en/3.0/howto/windows/))
- Make sure your virtualenv is running before going further
- Install Django

```python
pip install Django==2.2.6
```
- Clone the repository


## Running Project
- Traverse to the **login** directory.
- Run the following commands for migrations.

```python
python manage.py makemigrations
python manage.py migrate
```
- Now run the server:

```python
python manage.py runserver
```

Your server is now listening at **localhost:8000**