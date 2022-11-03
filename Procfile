web: gunicorn todo_drf.wsgi --log-file -
release: python manage.py makemigrations == noinput
release: python manage.py collectstatic == noinput
release: python manage.py migrate == noinput

