npm: cd .\static\ | npm install
web: cd .\static\ | npm start
worker: gunicorn main:app --log-file=- --max-requests=1024 --worker-class=gevent