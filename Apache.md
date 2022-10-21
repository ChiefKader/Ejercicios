# Apache

resumen  
resumen  
resumen  
resumen  
resumen

## Introducción
Este proyecto ha sido realizado en un centro docente para el aprendizaje de la instalación y uso de Apache.
Apache es un servidor web HTTP de código abierto, desarrollado y mantenido por una comunidad de usuarios en torno a la Apache Software Foundation. Su funcionalidad es servir a los usuarios todos los ficheros necesarios para visualizar la web en donde las solicitudes de los usuarios se realizan normalmente mediante un navegador. En cuanto a su historia, se comenzó a desarrollar en 1995 y se baso en el código de NCSA HTTPd 1.3, pero fue reescrito posteriormente; su nombre esta basado en la tribu Apache y también en la palabra patchy que significa parcheado.  
La motivación para la realización del proyecto es la de saber para que sirve Apache y de esta manera explicar lo que queremos conseguir.

## Configuración
### Crear tu propio sitio web
Abriremos la terminal de Linux(Ctrl+T) e introduciremos.
```
sudo mkdir /var/www/gci/
```
En nuestro caso lo hemos nombrado gci pero cualquier nombre valdria. A continuación crearemos un archivo html:
```
touch mohamed.html
```
```
sudo nano mohamed.html 
```
Una vez hecho lo anterios se nos abrira el archivo creado y procederemos a introducir lo siguiente:
```
<html>
<head>
  <title> Ubuntu rocks! </title>
</head>
<body>
  <p> I'm running this website on an Ubuntu Server server!
</body>
</html>
```
Finalmete crearemos un archivo de virtual host, para eso iremos a:
```
gci.example.com
```
### Configuracion del archivo de configuración de VirtualHost
Comenzaremos la configuración dirigiendonos a la carpeta de configuración de archivos.
```
cd /etc/apache2/sites-available/
```
Ahora consultaremos el nombre de nuestro subdominio, con el comando:
```
sudo cp 000-default.conf gci.conf
```


#### Webrafía
* [Digital Ocean](https://www.digitalocean.com/community/tutorials/how-to-install-the-apache-web-server-on-ubuntu-20-04-es)
* [LinuxConfig](https://linuxconfig.org/firewall-ufw-status-inactive-on-ubuntu-20-04-focal-fossa-linux)
* [DinaHosting](https://dinahosting.com/ayuda/que-es-apache-y-para-que-sirve/)
* [Wikipedia](https://es.wikipedia.org/wiki/Servidor_HTTP_Apache)
* [Ubuntu](https://ubuntu.com/tutorials/install-and-configure-apache#3-creating-your-own-website)
* []()
