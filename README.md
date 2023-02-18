# Learning Log
___
![pyhon_version](https://img.shields.io/badge/python-3.8-orange)
![django_version](https://img.shields.io/badge/django-3.2-orange)
![bootstrap_version](https://img.shields.io/badge/bootstrap-4-orange)

Веб-приложение при помощи которого 
пользователь сможет вести журнал интересующих его тем и создавать записи 
в журнале во время изучения каждой темы. Домашняя страница Learning Log 
содержит описание сайта и приглашает пользователя зарегистрироваться 
либо ввести свои учетные данные. После успешного входа пользователь
получает возможность создавать новые темы, добавлять новые записи
и редактировать существующие записи.
![demo1](demo1.jpg)
![demo2](demo2.jpg)
![demo3](demo3.jpg)

## Настройка перед запуском

Первое, что нужно сделать, это cклонировать репозиторий:

```sh
$ git clone https://github.com/Andrei2020-web/Learning_log.git
$ cd learning_log
```

Создайте виртуальную среду для установки зависимостей и активируйте ее:

```sh
$ virtualenv venv
$ source venv/bin/activate
```

Затем установите зависимости:

```sh
(venv)$ pip install -r requirements.txt
```

Запускаем сервер:

```sh
(venv)$ python manage.py runserver
```
