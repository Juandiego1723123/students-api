# students-api

API REST simple construida con FastAPI para gestionar un listado de estudiantes. Proyecto de practica para aprender Python, FastAPI y flujo de trabajo con Git (ramas, pull requests).

## Endpoints

- `GET /health` — chequeo de salud del servicio, responde `{"status": "ok"}`
- `GET /students` — devuelve la lista de estudiantes

## Stack

- Python
- FastAPI

## Como correrlo

```bash
pip install fastapi uvicorn
uvicorn main:app --reload
```

La API queda disponible en `http://127.0.0.1:8000`. Documentacion interactiva en `http://127.0.0.1:8000/docs`.
