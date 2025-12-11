FROM python:3.10-slim

WORKDIR /app

RUN pip install pygame
RUN pip install websockets

COPY client/main.py /app/main.py

CMD ["python", "main.py"]
