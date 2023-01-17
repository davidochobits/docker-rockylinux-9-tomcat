# Dockerfile / Tomcat 10 en RockyLinux  9

Dockerfile pensado para poner en servicio un Tomcat 10 sobre un servidor con RockyLinux 9. Le acompañan los ficheros de configuración necesarios para su administración. Además de los ficheros que acompañan al Dockerfile, también está disponible la versión de Apache Tomcat 10.1.5

Para realizar la construcción de la imagen:

<code>docker build -t davidochobits/tomcat10:latest .</code>

Una vez generada la imagen, utilizamos el siguiente comando:

<code>docker run -dti --name "Nombre Contenedor" -p 8080:8080 -imagen- </code>

El usuario administrador por defecto es *admin* y su contraseña es *admin*

Se agradecen comentarios al respecto. 
