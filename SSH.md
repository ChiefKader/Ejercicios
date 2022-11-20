# SSH por parejas
### Hecho por Mohamed.

## PC Servidor
Lo primero que haremos sera crear una cuenta nueva y lo haremos con el comando:
```
sudo adduser nickfury
```
A continuación instalaremos el SSH server con el comando:
```
sudo apt-get install openssh-server
```
Una vez realizado el paso anterior procederemos a iniciar el servidor con el comado:
```
sudo systemctl start ssh
```

## PC Cliente

### Instalar Apache 
Lo primero que vamos hacer sera conectarnos a la máquina con el comando:
```
ssh nickfury@192.168.0.128
```
Seguido de esto actualizaremos los paquetes locales:
```
sudo apt update
```
A continuación instalaremos el paquete apache2:
```
sudo apt install apache2
```
### Pasar una web a un lugar del servidor
Ahora viajaremos a la carpeta www:
```
cd var/www
```
Ahora crearemos nuestra página
```
sudo touch pagina.html
```
### VirtualHost
Lo primeros que haremos sera crear el fichero en el directorio /etc/apache2/sites-available/ , donde emplearemos el nombre de pagina.conf con el dominio:
```
sudo nano /etc/apache2/sites-available/mipaginaweb.conf
```
A continuación procederemos a escribir esto:
 ```
 <VirtualHost *:80>
        ServerAdmin webmaster@localhost
        # Nuestro dominio virtual
        ServerName pagina.com
        ServerAlias www.pagina.com
        
        # Indicamos la ruta donde se aloja la web 
        DocumentRoot /var/www/pagina.com
        ErrorLog ${APACHE_LOG_DIR}/error.log
        CustomLog ${APACHE_LOG_DIR}/access.log combined
</VirtualHost>
 ```
Lo siguiente sera activar el host, con el comando:
```
sudo a2ensite pagina.conf
```
A continuación comprobaremos que nuestro sitio web este activado:
```
ls /etc/apache2/sites-enabled/
```
Ahora escribiremos el comando:
```
sudo nano /etc/hosts
```
Dentro escribiremos la IP y el dominio:
```
192.168.0.128 www.pagina.com
```
Recargaremos apache con:
```
sudo service apache2 reload
```
Por último comprobaremos que todo lo anterior esta bien hecho:
```
/etc/init.d/apache2 start
```
Ahora procederemos a introducir por la url [www.pagina.com]()





