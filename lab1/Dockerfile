# FROM python:latest
# WORKDIR /app
# COPY . .

# CMD [ "python", "app.py" ]

FROM python:3.12-slim
WORKDIR /app
COPY app.py .


RUN useradd -m appuser
USER appuser

CMD [ "python", "app.py" ]
