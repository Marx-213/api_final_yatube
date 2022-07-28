# Как запустить проект:
### Описание
Благодаря этому проекту можно будет угощать мороженым друзей из разных городов.
### Технологии
Python 3.7
Django 2.2.19
### Запуск проекта в dev-режиме
Клонировать репозиторий и перейти в него в командной строке:
```
git clone https://github.com/yandex-praktikum/kittygram.git
``` 
Установить и активировать виртуальное окружение:
``` 
python3 -m venv env
source env/bin/activate
```
Установить зависимости из файла requirements.txt:
```
python3 -m pip install --upgrade pip
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
### Авторы
Андрей, Стёпа, Лера и Максим 

