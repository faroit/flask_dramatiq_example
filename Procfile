web: bin/start-pgbouncer-stunnel pipenv run gunicorn app:app --workers 16 --threads 8 --log-file -
worker: bin/start-pgbouncer-stunnel pipenv run dramatiq app -p4