# equipo6
# Moodle con Docker Compose

Este repositorio contiene la configuración para desplegar **Moodle** utilizando **Docker Compose**. Moodle es una plataforma de aprendizaje de código abierto utilizada para crear cursos en línea.

## Requisitos Previos

Asegúrate de tener instalados los siguientes programas en tu sistema:

- [Git](https://git-scm.com/downloads)
- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Instrucciones para Clonar el Repositorio

Primero, clona este repositorio en tu máquina local ejecutando:

```bash
git clone https://github.com/FelixJr1426/equipo6.git
cd moodle-docker
```

## Instrucciones para Desplegar Moodle con Docker Compose

Para iniciar el entorno de Moodle, simplemente ejecuta:

``` bash
docker-compose up -d
```
Esto descargará las imágenes necesarias, construirá los contenedores y ejecutará el entorno de Moodle en segundo plano.

## Acceder a Moodle
Una vez que el entorno esté en ejecución, abre tu navegador y accede a:
```bash
http://localhost:8080
```


### Notas Importantes:
1. **Personaliza** la URL del repositorio en `git clone` y otros detalles si cambian en tu entorno.
2. Asegúrate de que tu archivo **`docker-compose.yml`** esté correctamente configurado para que estas instrucciones funcionen sin problemas.

Este `README.md` proporcionará a tus usuarios toda la información necesaria para ejecutar tu entorno de Moodle con Docker Compose. 🚀


