# cinema-service-API

API of Cinema Service for ordering tickets written on Django REST Framework

## Installing

Python3 must be already installed

```shell
git https://github.com/katevasilenko/cinema-service-API.git
cd cinema-service-API
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
set DB_HOST=<your db hostname>
set DB_NAME=<your db name>
set DB_USER=<your db username>
set DB_PASSWORD=<your db user password>
set SECRET_KEY=<your secret key>
python manage.py runserver
```

## Also, you can run with Docker

Docker should be already installed

```shell
docker-compose up
```

## Getting access

- create user on /api/user/register/
- get access token on /api/user/token/

## Features

* Authentication with JWT Token
* Managing tickets and orders, creating actors, genres, movies, halls and session
* API documentation implemented: http://127.0.0.1:8000/api/doc/swagger/
* Powerful admin panel for advanced managing
