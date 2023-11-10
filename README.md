#Databases HW_12-02
## VADIM TSVETKOV

«Работа с данными (DDL/DML)»

**Задание 1.**

1.1. Поднимите чистый инстанс MySQL версии 8.0+. Можно использовать локальный сервер или контейнер Docker.

![img](https://github.com/vadimtsvetkov/Databases-HW_12-02/blob/main/1.1_mysql.jpg)

1.2. Создайте учётную запись sys_temp.

![img](https://github.com/vadimtsvetkov/Databases-HW_12-02/blob/main/1.2_create_user.jpg)

1.3. Выполните запрос на получение списка пользователей в базе данных. (скриншот)

![img](https://github.com/vadimtsvetkov/Databases-HW_12-02/blob/main/1.3_select_user.jpg)

1.4. Дайте все права для пользователя sys_temp.

![img](https://github.com/vadimtsvetkov/Databases-HW_12-02/blob/main/1.4_privileges.jpg)

1.5. Выполните запрос на получение списка прав для пользователя sys_temp. (скриншот)

![img](https://github.com/vadimtsvetkov/Databases-HW_12-02/blob/main/1.5_show_grants.jpg)

1.6. Переподключитесь к базе данных от имени sys_temp.

![img](https://github.com/vadimtsvetkov/Databases-HW_12-02/blob/main/1.6_user.jpg)

1.6.1. По ссылке https://downloads.mysql.com/docs/sakila-db.zip скачайте дамп базы данных

![img](https://github.com/vadimtsvetkov/Databases-HW_12-02/blob/main/1.6_download_damp.jpg)

1.7. Восстановите дамп в базу данных.

![img](https://github.com/vadimtsvetkov/Databases-HW_12-02/blob/main/1.7_create_database.jpg)
![img](https://github.com/vadimtsvetkov/Databases-HW_12-02/blob/main/1.7_damp_to_base.jpg)

1.8. При работе в IDE сформируйте ER-диаграмму получившейся базы данных. При работе в командной строке используйте команду для получения всех таблиц базы данных. (скриншот)

![img](https://github.com/vadimtsvetkov/Databases-HW_12-02/blob/main/1.8_dbeaver.jpg)
![img](https://github.com/vadimtsvetkov/Databases-HW_12-02/blob/main/1.8_%D1%81hart.jpg)

**Задание 2.**

Составьте таблицу, используя любой текстовый редактор или Excel, в которой должно быть два столбца: в первом должны быть названия таблиц восстановленной базы, во втором названия первичных ключей этих таблиц. Пример: (скриншот/текст)

![img](https://github.com/vadimtsvetkov/Databases-HW_12-02/blob/main/2_table.jpg)
