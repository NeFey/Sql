# Sql

SELECT ('столбцы или * для выбора всех столбцов; обязательно')

FROM ('таблица; обязательно')

WHERE ('условия/фильтрация, например, city='Moscow'; необязательно')

GROUP BY ('стобец, по которому хотим сгурпировать данные; необязательно')

HAWING ('условие/фильтрация на уровне сгурпированных данных; необязательно')

ORDER BY ('столбец, по которому хотим отсортировать вывод; необязательно')



НАХОЖДЕНИЕ КОЛЛИЧЕВСТВА ТАБЛИЦ - SELECT COUNT(*) AS TABLE_COUNT FROM INFORMATION_SCHEMA.TABLES WHERE TABLE_SCHEMA = 'YOUR_DATABASE_NAME'

НАХОЖДЕНИЕ НАЗВАНИЙ ТАБЛИЦ - select * from information_schema.tables

ВЫВЕСТИ ДАННЫЕ ИЗ ТАБЛИЦЫ - SELECT * FROM <table_name>
