### REST API Yatube

API позволяет делать разные виды запросов к постам, комментариям, группам и подписчикам в проекте Yatube. Аутентификация по JWT-токену.

Стек технологий: Python 3.10, Django 2.2.16, Django REST Framework, Simple JWT

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/Chezhin/api_final_yatube
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
```

```
source venv/Scripts/activate
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

Запустить проект:

```
python3 manage.py runserver
```

### Документация

Чтобы открыть документацию и посмотреть примеры запросов, запустите сервер и перейдите по этой ссылке: http://127.0.0.1:8000/redoc/
