# API Yatube

## Описание проекта:

Данный проект представляет API проекта Yatube

## Стек:

Python, Django Rest Framework, SQLite, Redoc

## Как запустить проект (Windows):

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/pavel-kiselev-practicum/api_final_yatube
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
```

```
source venv/scripts/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Создать миграции:

```
python3 manage.py makemigrations
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```
## Примеры запросов:

Примеры запросов можно получить, установив проект и перейдя по ссылке

http://127.0.0.1:8000/redoc/
