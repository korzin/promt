## Postgres and MySql 

|Description|Postgres|MySql|ANSI|
|---|---|---|---|
|Simply start using shell(Docker)|psql -U postgres|mysql --password|--|
|Quit from shell(Docker)|\q + Enter|\q + Enter|--|
|Show list of existing databases|\l, \list |SHOW DATABASES| ?|
|Use certain db|\c db_name|USE db_name| ?|
|Show chosen database|SELECT current_database()|SELECT database()|?|
|Show all schemas in current db|select nspname from pg_catalog.pg_namespace |*The schema is the database*| select schema_name from information_schema.schemata|
|Show all tables in certain schema| \dt *schema_name*.\*|*The schema is the database BUT ? do some research*|?| 



