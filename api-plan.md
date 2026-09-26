# План API

Пользователи:
- POST /users - регистрация
- GET /users/{id} - получить пользователя

Привычки:
- GET /habits - список привычек
- POST /habits - создать привычку
- GET /habits/{id} - одна привычка
- PATCH /habits/{id} - изменить
- DELETE /habits/{id} - удалить

Отметки:
- POST /habits/{id}/checkins - отметить что сделал
- GET /habits/{id}/checkins - история
- DELETE /habits/{id}/checkins/{date} - убрать отметку
- GET /habits/{id}/stats - статистика (серия дней, процент)
