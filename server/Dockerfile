FROM python:3.10-slim

WORKDIR /app

RUN pip install websockets

COPY server/main.py /app/main.py
COPY maps /app/maps

CMD ["python", "main.py"]
