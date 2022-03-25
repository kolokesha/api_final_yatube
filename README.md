Проект «API для Yatube»
### api_final_project
Данный проект представляет из себя API, построенное на основе Django REST Framework. 
Это API для блог-платформы Yatube.
Тут можно писать посты, объединять их в группы, комментировать их и подписываться на авторов.
### Технологии
Python 3.7
Django 2.2.19
### Запуск проекта в dev-режиме
- клонируйте репозиторий и перейдите в него в командной строке
```
git clone ссылка
cd api_final_yatube
```
- Разверните виртуальное окружение
```
python -m venv venv
```
- Активируйте виртуальное окружение
- Установите зависимости из файла requirements.txt
```
pip install -r requirements.txt
``` 
- В папке с файлом manage.py выполните команду запуска dev-сервера:
```
python3 manage.py runserver

