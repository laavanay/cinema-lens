web: gunicorn cinema_lens.wsgi:application --log-file - --log-level info
release: python manage.py migrate --noinput
