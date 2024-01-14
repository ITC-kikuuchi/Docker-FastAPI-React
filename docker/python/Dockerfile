FROM tiangolo/uvicorn-gunicorn-fastapi:python3.7

COPY ./python/app /app
COPY ./python/requirements.txt .

CMD ["uvicorn", "main:app", "--reload", "--host", "0.0.0.0", "--port", "3001"]