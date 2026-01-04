# Описание

Минимальный тестовый проект :
Схема работы:

Browser / curl → Nginx → Python backend


Python backend: простой HTTP-сервер, отвечает на / текстом Hello from Effective Mobile!

Nginx: реверс-прокси, проксирует все запросы на Python сервер


# Как запустить проект:

Через Docker-Compose

 Запустить docker-compose файл :
    sudo docker compose up -d

# Как проверить результат:

В браузере:

    http://localhost:8080/

Через curl:

    curl http://localhost:8080/ 

# Ожидаемый ответ:

Hello from Effective Mobile!