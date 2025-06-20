# AWS CodePipeline Assignment

## Resumen

Este proyecto configura un pipeline CI/CD en AWS CodePipeline para desplegar un sitio web estático alojado en un bucket S3.

## Pasos realizados

- Creación de repositorio GitHub con código estático (index.html).
- Configuración de pipeline en AWS CodePipeline:
  - Fuente: GitHub (rama main).
  - Build: omitido (sitio estático).
  - Deploy: Bucket S3 configurado para hosting estático.
- Automatización del despliegue al hacer push a GitHub.
- Verificación del sitio desplegado vía URL pública de S3.

## Configuraciones Importantes

- El bucket S3 está configurado para hosting estático y permisos de lectura pública.
- El rol IAM de CodePipeline tiene permisos para acceder al repositorio y al bucket S3.
- El pipeline está configurado para dispararse automáticamente con cambios en la rama main de GitHub.

## Capturas de pantalla

- (Aquí insertar las imágenes de la configuración del pipeline y despliegue)

