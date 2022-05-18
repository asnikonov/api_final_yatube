# api_yatube
Api для социальной сети yatube https://github.com/asnikonov/hw05_final.
#### Технологии
- Python 3.7.8
- Django 2.2.16
- Django REST framework 3.12.4


### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/asnikonov/api_final_yatube
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
```

```
source venv/bin/activate
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
python3 manage.py makemigrations
```

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```

Ссылки:
#### Проект:
http://127.0.0.1:8000
#### Документация:
http://127.0.0.1:8000/redoc