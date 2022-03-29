# Учебный проект
### Описание
```
Проект собирает отзывы пользователей на произведения.
```
Произведения делятся на категории.
```
Регистрация с отправляет письмо с кодом подтверждения на указанный email.
```
### Технологии
Python 3.7
Django 2.2.19
### Запуск локального проекта
```
- В папке infra выполните команду:
```
docker-compose up -d --build 
```
docker-compose exec web python manage.py migrate
```
docker-compose exec web python manage.py collectstatic --no-input
```
### Авторы
Александр, Валентин, Игорь
