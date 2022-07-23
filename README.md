# Cinema service api

Django REST framework project that demonstrate the work of cinema service


## Instalation

### Python must be already installed !

```shell
git clone https://github.com/YuriiKindrat/cinema_serivice_api
cd taxi_service
python3 -m venv venv
venv/Scripts/activate
pip install -r requirments.txt
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