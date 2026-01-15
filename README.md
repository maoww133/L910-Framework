L910-Framework
Лабораторная по Node.js фреймворку
Сущности данных:
1. Пьесы (plays.json): id (string), title (string), duration (number), isClassic (boolean), premiereDate (string как Date), genres (array).
2. Представления (performances.json): id (string), playId (string), date (string как Date), seatsAvailable (number), isSoldOut (boolean), actors (array).
Роутинг:
- GET /plays (все пьесы)
- GET /plays/:id (пьеса по id)
- POST /plays (создать)
- PUT /plays/:id (обновить полностью)
- PATCH /plays/:id — (обновить частично)
- Аналогично для /performances
