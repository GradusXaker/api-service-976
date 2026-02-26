# REST API Service

REST API на FastAPI с CRUD операциями.

## Запуск
```
pip install -r requirements.txt
uvicorn main:app --reload
```

## Endpoints
- GET /items - Список всех элементов
- POST /items - Создать элемент
- GET /items/{id} - Получить элемент
- PUT /items/{id} - Обновить элемент
- DELETE /items/{id} - Удалить элемент
