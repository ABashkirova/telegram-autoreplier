# Автоответчик telegram

Автоответчик на время отпуска :) [подробнее](https://medium.com/@jiayu./automatic-replies-for-telegram-85075f28321)

1. Зарегистрировать приложение в API telegram
2. Заполнить переменные в .env file:
```
API_ID=
API_HASH=
PHONE=
SESSION_FILE=
PASSWORD=
TPPROXY=
PPORT=
PKEY=
```
3. Стартануть докер-контейнер
`docker-compose -f "docker-compose.yml" up -d --build`