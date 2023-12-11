# Creación de una API con php para autenticar

Este es un proyecto para crear una api para autenticar      
Esta api retornará un jwt si las credenciales recibidas son correctas     
En sí mismo el proyecto utiliza diferentes tecnologías (docker, React en front, PHP en back con composer ).   

 
## Poner en marcha el proyecto  
1. Descargarlo (clonándolo o haciendo un fork)        

```git clone https://github.com/MAlejandroR/probando_jwt_api_auth.git ```

2. Copia el fichero __.env__
 Si no tienes un fichero __.env__, cópialo  del fichero __env__,  para que se usen las variables de entorno creadas

 Puedes modificar los valores según desees:      

```cp env .env```

En el terminal en la carpeta donde hayas descargado el proyecto, que estará el fichero ___docker-compose.yaml___ levanta los contenedores creados.    
``` docker compose up ```
Para acceder http://localhost8080 Si le pasas un usuario registrado debería de retornar un token    
http://localhost8081 Para acceder a phpmyadmin (ver credenciales en el ficher ___.env___)    



