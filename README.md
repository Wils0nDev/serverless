# SERVERLES
Las aplicaciones serverless se basan en funciones (también conocidas como "funciones sin servidor" o "funciones como servicio") que son pequeños bloques de código que se ejecutan en respuesta a eventos específicos.


# CONFIGURACION
 - Para este proyecto haremos uso de de los servicios https://www.netlify.com/, y poder desplegar nuestra aplicación.
 - Crear cuenta (con github) para agilizar el proceso

  - Instalar 

    ```
     npm install netlify-cli --save-dev
    ```
 - Login 
   ```
     netlify login
   ```
 -  Al hacer login te redireccionara a la cuenta con la que te registraste y deberas Autorizar el acceso. 

 - Para empezar a crear funciones con typescript ejecutar 
   -  Pudes verlo en : https://docs.netlify.com/functions/lambda-compatibility/?fn-language=ts
   ```
   npm install @netlify/functions
   ```



