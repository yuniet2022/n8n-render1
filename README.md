# n8n en Render

Este repositorio contiene la configuración mínima para desplegar **n8n** en [Render](https://render.com).

## Archivos
- **Dockerfile** → indica a Render usar la imagen oficial de n8n.
- **.env.example** → variables de entorno necesarias.
- **.gitignore** → excluye archivos locales innecesarios.

## Deploy
1. Conecta este repositorio a Render.
2. Crea un **Web Service** nuevo → selecciona este repo → ambiente Docker.
3. Agrega las variables de entorno (usa .env.example como guía).
4. Render construirá e iniciará el servicio.
