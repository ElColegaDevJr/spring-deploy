## Despliegue de apps Spring Boot en Heroku

Crear archivo 'system.properties' en el proyecto con el contenido:

java.runtime.version=17

1. Crear cuenta en GitHub y Heroku
2. Tener configurado un git en el pc
    1. git config --global user.name "NOMBRE"
   2. git config --global user.email EMAIL
3. Subir el proyecto a GitHub desde IntelliJ IDEA desde la opción: VCS > Share project on GitHub
4.  Desde Heroku, crear app y elegir método GitHub y buscar el repositorio subido
5. Habilitar deploy automático,  ejecutar el Deploy

## Ejercicio 1

* Probar a empaquetar la aplicación con maven package desde IntelliJ IDEA

* Desde terminal en IntelliJ IDEA verificar que se ejecuta correctamente con el comando:

java -jar target/spring-deploy-1.0.jar

* Crear un perfil para dev y otro para test con una propiedad nueva que carguemos en el controlador

## Ejercicio 2

Desplegar el API REST de pc en Heroku y verificar funcionamiento desde POSTMAN

## Proveedores Cloud

* Heroku -- Java, Spring, PostgreSQL
* Netlify -- Frontend (React, Angular....)
* Vercel -- Frontend (React, angular....)