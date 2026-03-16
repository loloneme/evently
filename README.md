# Evently (MVP)

Frontend находится в [ветке](https://github.com/loloneme/evently/tree/frontend)

Backend находится в [ветке](https://github.com/loloneme/evently/tree/backend)

## Backend

* Реализована слоистая чистая архитектура - деление на repository (работа с БД), service (бизнес-логика), transport layer (хэндлеры)
* Реализован файл с миграцией БД
* Есть пагинация для крупных GET-запросов
* Хэширование пароля, аутентификация с использованием JWT-токенов
* Интерфейс сервиса описан в файле openapi.yaml с использованием  OpenAPI3.0 спецификации 

-------------------------------------

## Дизайн

Главный экран:

<img src='https://github.com/user-attachments/assets/fa288d1b-e865-4b3a-8b6c-ec3b7424f0ca' width=300 />

О мероприятии:

<img src='https://github.com/user-attachments/assets/26cf7dc9-e3ff-48ea-bcc0-483c22edff23' width=300 />

Карта с мероприятиями:

<img src='https://github.com/user-attachments/assets/4361fb7f-688a-4773-81d2-c3a6eb011315' width=300 />

Мероприятия, на которые зарегистрирован пользователь:

<img src='https://github.com/user-attachments/assets/3af21f98-73c3-4375-a967-215d162637cd' width=300 />

Мероприятия, созданные пользователями:

<img src='https://github.com/user-attachments/assets/1c0ea4a7-735b-41c6-8ac5-c6785f6c9e12' width=300 />
