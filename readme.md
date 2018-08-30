# readme
## setup
```
pip install django
pip install --upgrade pip
django-admin startproject example
pip install gunicorn
```

## run
### runserver
```
cd example
python manage.py runserver
```

### gunicorn
```
cd example
gunicorn example.wsgi:application
```
