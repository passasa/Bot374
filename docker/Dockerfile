FROM python:3.11-slim

WORKDIR /app

COPY bot/ /app/
COPY bot/requirements.txt /app/requirements.txt

RUN pip install --no-cache-dir -r requirements.txt

CMD ["python", "main.py"]
