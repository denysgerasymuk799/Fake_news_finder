worker: python worker.py
web: cd flask_app && python -m textblob.download_corpora && gunicorn app:app --timeout 660
