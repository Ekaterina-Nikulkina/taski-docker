# Проект Taski

**Taski** *— удобное приложение для планирования своих задач.*

## Технологии

Python 3.11.1, Django 4.1, Django REST framework, React

## Как запустить проект:

- Клонируйте репозиторий.

- Запустите проект с помощью команды:
```docker compose up```

- Соберите статику Django с помощью команды:
```docker compose exec backend python manage.py collectstatic```
- Скопируйте статику:
```docker compose exec backend cp -r /app/collected_static/. /static/static/```

По адресу http://127.0.0.1:8000/ сайт будет доступен.

## Автор

Екатерина