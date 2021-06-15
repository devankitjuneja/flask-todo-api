## Follow the steps to install the pre-requisites

1. Setup a python virtual environment and install dependencies.
```bash
$ python3 -m venv .venv
$ source .venv/bin/activate
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