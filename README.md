# Проект API для Yatube
Проект "API для Yatube" добавляет функционал для работы с проектом социальной сети для публикации личных дневников по API. Реализованы возможность получения всех записей пользователей, создания/удаления/изменения записей, добавления/изменения/удаления комментариев к записям, авторизации и подписки.

## Стек технологий
* Django REST Framework
* Simple JWT - работа с JWT-токеном
* Git

## Установка проекта
Выполните команду:
```python
git clone https://github.com/ildarick93/API_for_Yatube
```
Перейдите в репозиторий:
```python
cd API_for_Yatube
```
В корневой папке проекта создайте виртуальную среду python:
```python
python -m venv venv
```
Активируйте виртуальную среду командой:
Windows:
```python
venv\Scripts\activate.bat
```
Linux или macOS:
```python
source venv/bin/activate
```
Установите необходимые зависимости с помощью pip:
```python
pip install -r requirements.txt
```
При необходимости обновления зависимостей используйте команду:
```python
python -m pip install —upgrade pip
```
Выполнить миграции:
```python
python manage.py migrate
```
Запустите проект:
```python
python manage.py runserver
```
