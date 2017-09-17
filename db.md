## Postgres and MySql 

|Description|Postgres|MySql|ANSI|
|---|---|---|---|
|Simply start using shell in Docker|psql -U postgres|mysql --password|--|
|Quit from shell||\q + Enter|--|
|Show list of existing databases|\l, \list |SHOW DATABASES| ?|
|Use certain db|\c db_name|USE db_name| ?|
|Show chosen database|SELECT current_database()|SELECT database()|?|
|Show all schemas in current db|select nspname from pg_catalog.pg_namespace ||select nspname from pg_catalog.pg_namespace|
