# Git
### Resumen
Sistema de control de versiones enfocado en el trabajo comunitario de software
### Eliminar directorios y archivos innecesarios
Para borrar un archivo o directorio se debe ejecutar el siguiente comando en la ubicación correspondiente:

`git rm -r directorio`

`git prune`

Luego se debe hacer commit y push.

### Refrescar .gitignore para borrar archivos que fueron agregados erroneamente

Actualizar el gitignore y hacer commit de todos los últimos cambios.

`git rm -r --cached .`

`git add .`

`git commit -m "gitignore refresh"`

`git push origin master`

### Guardar cambios locales y volver al último pull hecho

`git stash`

### (Re)aplicar los cambios guardados

`git stash apply`

### Descartar los cambios hechos

`git stash clear`
