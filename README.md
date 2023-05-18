# API для Yatube
## Описание ✏️
Проект «API для Yatube» позволяет обращаться к социальной сети Yatube с помощью запросов.
### Технологии 🛠️
Python 3.9, Django 3.2, Django REST Framework 3.12.4

## Как запустить проект 🌐

Клонировать репозиторий и перейти в него в командной строке:

```
git@github.com:vovan46rus/api_final_yatube.git
```


Cоздать и активировать виртуальное окружение:
```
python -m venv venv
```
```
source venv/Scripts/activate
```

Установить зависимости:

```
pip install -r requirements.txt
```
Выполнить миграции:
```
python manage.py migrate
```
Запустить проект:
```
python manage.py runserver
```

### Документация ReDoc 📚
```
http://localhost:8000/redoc/
```
### Создание токена 🔑
```
/api/v1/jwt/create/
```

## Автор 👨‍💻
vovan46rus