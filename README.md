Kittygram

Kittygram — веб-приложение для публикации информации о котиках.

Проект состоит из backend-части на Django REST Framework и frontend-части на React. Пользователи могут регистрироваться, авторизоваться, добавлять котиков, загружать изображения и указывать достижения питомцев.

Возможности

регистрация и авторизация пользователей;
token-аутентификация;
создание, просмотр, редактирование и удаление записей о котиках;
загрузка изображений;
добавление достижений;
связь записи с владельцем;
пагинация;
взаимодействие frontend и backend через API.
Стек технологий Backend: Python Django Django REST Framework Djoser SQLite Pillow django-cors-headers

Frontend: React React Router JavaScript CSS API

Основные эндпоинты:

/api/cats/
/api/achievements/
/api/users/
/api/token/login/
/api/token/logout/
Запуск backend Перейти в директорию backend: cd backend

Создать и активировать виртуальное окружение: python -m venv venv, source venv/bin/activate

Для Windows: venv\Scripts\activate

Установить зависимости: pip install -r requirements.txt

Применить миграции: python manage.py migrate

Запустить backend: python manage.py runserver

Backend будет доступен по адресу: http://127.0.0.1:8000/

Запуск frontend В отдельном терминале перейти в директорию frontend: cd frontend

Установить зависимости: npm install

Запустить frontend: npm start

Frontend будет доступен по адресу: http://localhost:3000/
