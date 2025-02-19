# Используем официальный образ Python
FROM python:3.9-slim

# Устанавливаем рабочую директорию
WORKDIR /app

# Копируем скрипт в контейнер
COPY square.py .

# Запускаем скрипт при старте контейнера
CMD ["python", "square.py"]