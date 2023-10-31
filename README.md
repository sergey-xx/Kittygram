# infra_sprint1 

### Описание проекта:
Проект социальной сети для размещения домашних животных.

### Технологии
Frontend: React
Backand: Django REST API

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:sergey-xx/Kittygram.git
```

## Запуск Backend:
- Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

- Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

- Выполнить миграции:

```
python3 manage.py migrate
```
- Запуск сервера:

```
python3 manage.py migrate
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
