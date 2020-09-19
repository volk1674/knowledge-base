# Полезные команды

При создании нового пользователя на тестовой базе не забыть изменить профайл:
- `ALTER PROFILE DEFAULT LIMIT PASSWORD_LIFE_TIME UNLIMITED;`

Посмотреть пользователей и как настроены профайлы:
- `SELECT * FROM  DBA_USERS;`
- `SELECT * FROM  DBA_PROFILES ORDER BY profile;`


