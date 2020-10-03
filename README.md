# ECOMMERCE-SPORT-PROYECTO
ECOMMERCE SPORT PROYECTO realizado para el curso de Henry Full Stack , etapa demo 1.

Mi linkedin: www.linkedin.com/in/matias-ruiz-mdz/
Equipo de trabajo: Gustavo  - Cecilia - Ignacio - Agustina

![alt text](IMAGEN PROYECTO APRETAR AQUI 1.jpg "IMAGEN PROYECTO APRETAR AQUI 1")

## COMENZANDO

cuenta con dos carpetas: `api` y `client`. En estas carpetas estará el código del back-end y el front-end respectivamente. (En ambos instaralar NPM INSTALL)

Para cargar en tu base de datos En `api` vas a tener que crear un archivo llamado: `.env` que tenga la siguiente forma:

```
DB_USER=usuariodepostgres
DB_PASSWORD=passwordDePostgres
DB_HOST=localhost
EMAIL= emailtienda 
PASSWORD= passwordemail
```
Utilizando PGAdmin vas a crear tu nueva database "development".
Tenés que reemplazar `usuariodepostgres` y `passwordDePostgres` con tus propias credenciales para conectarte a postgres. Este archivo va ser ignorado por github, ya que contiene información sensible (las credenciales).

El contenido de `client` fue creado usando: Create React App.

## EJECUTAR
 
 Para ejecutar el proyecto una vez hecho los pasos anteriores vamos a correr NPM START en Api y luego en Client.
