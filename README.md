# Проектная работа 12 
## v0.0.4
Данная проектная работа предназначена для оттачивания навыков с работой фреймворка Express.js.
Для установки проекта требуется:
1. Клонировать репозиторий командой *git clone*;
2. Установить все npm зависимости с помощью команды *npm i*;
3. Запустить сборку проекта командой *npm run start* (или *npm run dev*).

После запуска загружается адрес localhost:3000 который загружает фронтенд проекта Mesto.

В ответ на запрос *GET localhost:3000/users* сервер вернёт JSON-объект из файла users.json.

В ответ на запрос *GET localhost:3000/cards* сервер вернёт JSON-объект из файла cards.json.

В ответ на запрос *GET localhost:3000/users/8340d0ec33270a25f2413b69*, сервер вернёт JSON-объект пользователя с переданным после /users идентификатором.

Если пользователя с запрошенным идентификатором нет, API вернет 404 статус ответа и JSON: *{ "message": "Нет пользователя с таким id" }*.

При запросе на несуществующий адрес, API вернет 404 статус ответа и JSON: *{ "message": "Запрашиваемый ресурс не найден" }*.
