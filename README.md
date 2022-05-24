# dj-social-book

A simple social media website

## Runing this Project

### Create venv

```bash
pip install -r requirements.txt --no-cache-dir --upgrade pip
```

### Upgrade Database

```bash
python manage.py makemigrations && python manage.py migrate 
```

### Create Superuser

```bash
python manage.py createsuperuser --email=admin@socialbook.com --username=admin
```

### Runserver

```bash
python manage.py runserver
```
