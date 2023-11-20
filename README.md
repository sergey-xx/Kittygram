# Kittigram 

### Описание проекта:
Проект социальной сети для размещения домашних животных.
### Возможности:
- Добавлять профиль любимого питомца
- Добавлять фотографию
- Выбирать цвет питомца из палитры
- Добавлять достижения

### Технологии
Frontend: React

Backand: Django REST API

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:sergey-xx/Kittygram.git
```

### Backend
**(Windows)**

В папке /backend создать виртуальное окружение:
```shell
> python -m venv venv
```
Активировать виртуальное окружение:
```shell
> source venv/Scripts/Activate
```

**(Linux)**

В папке /backend создать виртуальное окружение:
  
```bash
$ python3 -m venv venv
```
Активировать виртуальное окружение:
```bash
$ source venv/bin/activate
```

Далее

Установить зависимости:
```bash
$ pip install -r requirements.py
```
Выполнить миграции БД:
```bash
$ python manage.py migrate
```
Для доступа в админ-панель создайте супер-пользователя:
```bash
$ python manage.py createsuperuser
```

Запустить проект:
```bash
$ python manage.py runserver
```

## Frontend
- Установить Node.js® https://nodejs.org/en/download
- Находясь в директории проекта, установить зависимости:

```
npm i
```
- Запустить проект:
```
npm run start
```
  Фронт будет доступен по адресу: http://localhost:3000

### Для использования на сервере рекомендуется использовать:

- WSGI-сервер: Gunicorn 20.1.0 
- Веб-сервер: Nginx
