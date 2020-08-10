# Docker

## Crear imagen a partir de un Dockerfile
navegar al directorio

`docker build . -t <nombre_image:version>`

## Eliminar imágenes, containers, volumes y networks basura
`docker system prune`

## Eliminar imágenes, containers, volumes y networks no usados
`docker system prune -a`

## Listar imágenes
`docker image ls`

## Listar containers
`docker container ls`

## Entrar al bash de un container activo
`docker exec -it <container_id> /bin/bash`

## Matar un container
`docker kill <container_id>`

## Detener todos los containers
`docker stop $(docker ps -aq)`

## Eliminar todos los containers*
`docker rm $(docker ps -aq)`
*Solo funciona cuando los containers están detenidos
