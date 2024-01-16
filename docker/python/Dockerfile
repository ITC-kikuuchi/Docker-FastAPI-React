FROM tiangolo/uvicorn-gunicorn-fastapi:python3.10

COPY ./python/app /app
COPY ./python/requirements.txt .

RUN pip install --trusted-host pypi.python.org -r requirements.txt

CMD ["uvicorn", "main:app", "--reload", "--host", "0.0.0.0", "--port", "3001"]