# Resumen
Gestor de bases de datos potente y seguro.

## Entrar a usuario postgres
`sudo -u postgres pqsl`

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
