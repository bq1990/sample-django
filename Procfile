release: python manage.py migrate
web: gunicorn config.wsgi:application
worker: celery worker --app=sample_django.taskapp --loglevel=info
