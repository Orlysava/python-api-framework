# Python API Framework

FastAPI-based REST framework with batteries included.

## Features
- JWT auth with refresh tokens
- SQLAlchemy async (asyncpg)
- Cursor-based pagination
- Request validation (Pydantic v2)
- Auto-generated OpenAPI docs

## Run
```bash
pip install -r requirements.txt
uvicorn app.main:app --reload
# Docs at http://localhost:8000/docs
```
