# Examen de la asignatura Despliegue de Aplicaciones Web
## Despliegue de aplicación Angular con CI/CD

Este proyecto consiste en el despliegue automático de una aplicación frontend desarrollada con Angular en un servidor VPS mediante Apache.

## Tecnologías utilizadas

- Angular
- Git y GitHub
- GitHub Actions
- Apache2 (VPS Ubuntu)

## Funcionamiento

Cada vez que se realiza un push a la rama `main`, se ejecuta automáticamente un workflow de GitHub Actions que:

1. Instala las dependencias del proyecto.
2. Compila la aplicación en modo producción.
3. Copia los archivos generados al servidor VPS mediante SSH y rsync.

La aplicación se puede observar en la siguiente dirección:

http://examen.apm-code.com
