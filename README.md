Flask REST Api Boilerplate
=============

This repository contains boilerplate code for a RESTful API based on Flask and Flask-RESTPlus.

### Directory structure:

    .
    ├── server_name
    │   ├── api
    │   │   ├── blog
    │   │   │   ├── business.py
    │   │   │   ├── endpoints
    │   │   │   │   ├── categories.py
    │   │   │   │   ├── __init__.py
    │   │   │   │   ├── posts.py
    │   │   │   ├── __init__.py
    │   │   │   ├── parsers.py
    │   │   │   └── serializers.py
    │   │   ├── __init__.py
    │   │   └── restplus.py
    │   ├── app.py
    │   ├── database
    │   │   ├── __init__.py
    │   │   ├── models.py
    │   ├── db.sqlite
    │   ├── __init__.py
    │   └── settings.py
    ├── LICENSE.txt
    ├── logging.conf
    ├── README.md
    ├── requirements.txt
    ├── setup.cfg
    ├── setup.py

### Python 3.6 Virtual environment:

    python3 -m venv venv  # if not created already
    source venv/bin/activate
    pip install --upgrade pip

### Install requirements:

    pip install -r requirements.txt

### Export environment variables:

    Not required

### Start server:

    (venv) $ python3 setup.py develop
    (venv) $ python3 server_name/app.py

### Swagger url:

Visit [http://localhost:8888/api/](http://localhost:8888/api/) For swagger UI.

### Start celery:

    Not added yet

