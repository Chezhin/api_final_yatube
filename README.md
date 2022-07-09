### REST API Yatube

API позволяет делать разные виды запросов к постам, комментариям, группам и подписчикам в проекте Yatube. Аутентификация по JWT-токену.

Стек технологий: Python 3.10, Django 2.2.16, Django REST Framework, Simple JWT

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/yandex-praktikum/kittygram.git
```

```
cd kittygram
```

Cоздать и активировать виртуальное окружение:

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

Запустить проект:

```
python3 manage.py runserver
```

### Вход

Для входа создайте суперпользователя:

```
python3 manage.py createsuperuser
```

Отправьте POST-запрос, с именем пользователя и паролем на http://127.0.0.1:8000/api/v1/token/, чтобы получить токен.

### Документация

Чтобы открыть документацию и посмотреть примеры запросов, запустите сервер и перейдите по этой ссылке: http://127.0.0.1:8000/redoc/
