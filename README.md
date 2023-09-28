# infra_sprint1 

### Описание проекта:
Проект социальной сети для размещения домашних животных.

### Технологии
Frontend: React
Backand: Django REST API

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:sergey-xx/infra_sprint1.git
```

Cоздать и активировать виртуальное окружение:

Запуск Backend:
```
python3 -m venv env
```

```
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```


### Для использования на сервере рекомендуется использовать:

WSGI-сервер: Gunicorn 20.1.0 
Веб-сервер: Nginx
