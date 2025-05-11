Homework 2 — FastAPI та Docker та PostgreSQL

FastAPI-застосунок із базою даних PostgreSQL
Встановлено "Dockerfile" для Python 3.10
Налаштовано "docker-compose.yaml" з двома сервісами: "web" при використанні FastAPI та "db" за допомоги PostgreSQL
Оновлено рядок підключення до бази данних  у `conf/db.py`
Запуск застосунку через команду: docker-compose up --build


Після запуску:

FastAPI: http://localhost:8000

Swagger-документація: http://localhost:8000/docs

ReDoc: http://localhost:8000/redoc