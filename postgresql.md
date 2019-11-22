# Resumen
Gestor de bases de datos potente y seguro.

## Entrar a usuario
`psql -U <user> <database>`

## Entrar a usuario postgres (administrador)
`sudo -u postgres pqsl`

## Crear usuario (desde administrador)
`create user <user>`

## Cambiar a modo trust
El modo por defecto de autenticación de usuarios es peer. Esto significa que los usuarios de postgres deben existir en postgres y en el sistema operativo. En modo trust, solo necesitan existir en postgres, y en modo md5 solo deben existir en postgres pero con contraseña.
`sudo nano /etc/postgresql/10/main/pg_hba.conf`

Editar `local all all peer` a `local all all trust` y luego reiniciar el equipo para actualizar la configuración.

## Crear base de datos
`create database <nombrebd>;`

## Listar bases de datos
`\l` o `\list`

## Salirse de un comando
Tecla Q

## Conectarse a una base de datos
`\c <nombrebd>`

## Listar tablas
`\dt`

## Eliminar tabla
`drop table <nombretabla>;`

## Limpiar tabla
`delete from <nombretabla>;`

## Indexar tabla
`CREATE INDEX index_name ON table_name(column_name);` de una sola columna
