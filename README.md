# Aprendiendo PostgreSQL

## Interactuar con el entorno

1. Ingresar al contenedor en ejecución que contiene PostgreSQL
2. Empezar a usar un usuario sin privilegios, en este caso el usuario `postgres` usando el comando `su - postgres`
3. Exportar la variable de entorno PGDATA con el comando `export PGDATA=~/data`
4. Para validar que funciona ejecute el comando `pg_ctl status`4
