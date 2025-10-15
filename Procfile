release: flask db upgrade && flask translate compile
web: gunicorn run:app --bind 0.0.0.0:$PORT
