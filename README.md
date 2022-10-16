# php base repository

Este repositorio contiene una configuración básica para ejecutar aplicaciones php con base de datos MYSQL

## Contenedores

- contenedor con la versión de PHP 8.1.1
- contenedor con la versión MySQL 8.0.26
- contenedor con la versión NGINX 1.19

## Instrucciones

- `make build` para construir los contenedores
- `make start` para iniciar los contenedores
- `make stop` para detener los contenedores
- `make restart` para reiniciar los contenedores
- `make prepare` para instalar dependencias con composer (una vez creado el proyecto)
- `make ssh-be` para ingresar al contenedor backend por SSH
