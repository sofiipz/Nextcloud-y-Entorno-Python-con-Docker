# Nextcloud-y-Entorno-Python-con-Docker
Práctica de la asignatura de Computación en la Nube de 1º de DAM. En esta práctica se ha desplegado un servidor Nextcloud y un entorno de desarrollo en Python utilizando Docker.

## Parte 1 - Nextcloud
Se ha descargado la imagen oficial de Nextcloud (versión 30.0.8 con Apache) y se ha creado un contenedor con persistencia de datos mediante volúmenes. Se ha accedido a la aplicación desde el navegador, configurado con SQLite y subido un archivo. Luego, se ha eliminado y recreado el contenedor para verificar la persistencia de los datos.

## Parte 2 - Entorno de desarrollo en Python
Se ha creado un contenedor basado en `python:3.11-slim` con un bind mount para sincronizar archivos con el host. Se ha instalado la librería NumPy y ejecutado un script en Python dentro del contenedor para realizar operaciones matemáticas básicas con arrays y matrices.

## Requisitos
- Docker instalado
- Conexión a internet para descargar las imágenes

Este proyecto demuestra el uso de Docker para gestionar servicios en la nube y entornos de desarrollo.

**Fecha:** Abril 2025
