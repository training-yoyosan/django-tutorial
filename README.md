This is a tutorial for Django 2.2, from https://docs.djangoproject.com/en/2.2/intro.

# Setup

```bash
python -m venv env
source env/bin/activate
python -m pip install Django==2.2 autopep8
python manage.py migrate
```

# Run

```bash
source env/bin/activate
python manage.py runserver
```

Open http://localhost:8000.