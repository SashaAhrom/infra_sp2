# infra_sp2(educational project)
## Description
```
api_yamdb project deployed to docker
```
## Running a project in dev mode
```
In the infra folder, run the commands:
- docker-compose up -d --build 
- docker-compose exec web python manage.py migrate
- docker-compose exec web python manage.py collectstatic --no-input
```
## System requirements
```
Python 3.7
Django 2.2.19
Djangorestframework 3.12.4
Docker 20.10.12
```
