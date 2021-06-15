1. Install the necessary requirements
```bash
$ python3 -m venv .venv
$ pip install -r requirements.txt
```

2. Create database

```bash
$ python
>>> from api import db
>>> db.create_all()
```

## Run the app
```bash
$ python api.py
```