web: newrelic-admin run-program gunicorn ruqqus.__main__:app -k gevent -preload --max-requests 10000 --max-requests-jitter 500
worker: python3.7 scripts/recomputes.py
