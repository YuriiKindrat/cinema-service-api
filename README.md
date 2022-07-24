# Cinema service api

Django REST framework project that demonstrate the work of cinema service


## Instalation

### Python and PostgreSQL must be already installed !

```shell
git clone https://github.com/YuriiKindrat/cinema_serivice_api
cd taxi_service
python3 -m venv venv
venv/Scripts/activate
pip install -r requirments.txt
export/set DEBUG=True
export/set DB_HOST=<host name>
export/set DB_NAME=<db name>
export/set DB_USER=<user name>
export/set DB_PASSWORD=<db password>
python manage.py migrate
python manage.py runserver
```
### To use Debugger:
```shell
export/set DEBUG=True
```
### To use Docker:
```shell
docker-compose build
docker-compose up
```

## Features

* JWT authentication for users
* Swagger documentation for api
* Possibility to use docker