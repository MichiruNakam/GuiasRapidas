# SCREEN
### Resumen
Programa de linea de comandos para crear múltiples hilos de la terminal, que se pueden desacoplar para funcionar aún después de cortar una conexión.
### Crear una nueva screen
`screen`  ctr+A+C

*Inmediatamente después puedes ejecutar la tarea que desees*
### Desacoplar la screen actual
ctr+A+D
### Listar screens
`screen -ls`
### Reacoplar screens
`screen -r` si hay solo una

`screen -r <id-screen>` si hay más de una

### Eliminar screens
`killall screen` para eliminarlas todas

`screen -S <id-screen> -X quit` para eliminar una
