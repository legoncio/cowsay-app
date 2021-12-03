COWSAY-APP

Este es el repositorio para la actividad de evaluación del curso nivelador del Master en Full Stack Web Development de la escuela Three Points

Para la correcta ejecución de la aplicación ejecutar desde la terminal, ubicándose en el directorio principal, el comando

npm init

Esto instalara los módulos necesarios. Luego, ejecutar el script de inicio

npm run start

Esto creara un servidor en el puerto 3000

Desde postman, hacer una petición tipo get a la url 'localhost:3000/cowsay', con el parámetro 'message' especificando el mensaje que se desee. Por ejemplo:

localhost:3000/cowsay?message=Hello Nodejs

La respuesta del servidor será la siguiente:

 ______________
< Hello Nodejs >
 --------------
        \   ^__^
         \  (O O)\_______
            (__)\       )\/\
             U ||----w |
                ||     ||