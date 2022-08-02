# Full Stack Book To Do FastAPI

https://www.fullstackbook.com/docs/projects/todo/backend/fastapi

## Setup

```
createdb fullstackbook-todo-fastapi
python3 -m venv venv
. venv/bin/activate
pip install -r requirements.txt
alembic upgrade head
uvicorn main:app --reload
```

## Configuration

Copy `.env.example` to `.env`.
