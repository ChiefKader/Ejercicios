# Apache

resumen  
resumen  
resumen  
resumen  
resumen

#### Palabras clave

**palabra clave**: .

**palabra clave**: .

**palabra clave**: .

**palabra clave**: .



#### Webrafía
* [Digital Ocean](https://www.digitalocean.com/community/tutorials/how-to-install-the-apache-web-server-on-ubuntu-20-04-es)
* [LinuxConfig](https://linuxconfig.org/firewall-ufw-status-inactive-on-ubuntu-20-04-focal-fossa-linux)
* []()

mohamed93@usuario-OptiPlex-380:~$ sudo apt update
[sudo] contraseña para mohamed93: 
Des:1 https://deb.nodesource.com/node_16.x focal InRelease [4.583 B]
Des:2 https://download.docker.com/linux/ubuntu focal InRelease [57,7 kB]       
Obj:3 http://ppa.launchpad.net/inkscape.dev/stable/ubuntu focal InRelease      
Des:4 http://security.ubuntu.com/ubuntu focal-security InRelease [114 kB]      
Obj:5 http://es.archive.ubuntu.com/ubuntu focal InRelease                      
Des:6 https://packages.microsoft.com/repos/vscode stable InRelease [3.959 B]   
Des:7 http://es.archive.ubuntu.com/ubuntu focal-updates InRelease [114 kB]     
Des:8 http://es.archive.ubuntu.com/ubuntu focal-backports InRelease [108 kB]
Des:9 http://security.ubuntu.com/ubuntu focal-security/main amd64 Packages [1.777 kB]
Des:10 https://deb.nodesource.com/node_16.x focal/main amd64 Packages [772 B]
Des:11 https://packages.microsoft.com/repos/vscode stable/main amd64 Packages [328 kB]
Des:12 http://security.ubuntu.com/ubuntu focal-security/main i386 Packages [502 kB]
Des:13 http://es.archive.ubuntu.com/ubuntu focal-updates/main amd64 Packages [2.151 kB]
Des:14 http://security.ubuntu.com/ubuntu focal-security/main Translation-en [295 kB]
Des:15 http://security.ubuntu.com/ubuntu focal-security/main amd64 c-n-f Metadata [11,1 kB]
Des:16 http://security.ubuntu.com/ubuntu focal-security/restricted amd64 Packages [1.239 kB]
Des:17 http://security.ubuntu.com/ubuntu focal-security/restricted Translation-en [176 kB]
Des:18 http://security.ubuntu.com/ubuntu focal-security/universe i386 Packages [564 kB]
Des:19 http://security.ubuntu.com/ubuntu focal-security/universe amd64 Packages [735 kB]
Des:20 http://security.ubuntu.com/ubuntu focal-security/universe Translation-en [135 kB]
Des:21 http://security.ubuntu.com/ubuntu focal-security/universe amd64 c-n-f Metadata [15,2 kB]
Des:22 http://es.archive.ubuntu.com/ubuntu focal-updates/main i386 Packages [733 kB]
Des:23 http://es.archive.ubuntu.com/ubuntu focal-updates/main Translation-en [379 kB]
Des:24 http://es.archive.ubuntu.com/ubuntu focal-updates/main amd64 c-n-f Metadata [16,0 kB]
Des:25 http://es.archive.ubuntu.com/ubuntu focal-updates/restricted amd64 Packages [1.328 kB]
Des:26 http://es.archive.ubuntu.com/ubuntu focal-updates/restricted Translation-en [188 kB]
Des:27 http://es.archive.ubuntu.com/ubuntu focal-updates/universe i386 Packages [695 kB]
Des:28 http://es.archive.ubuntu.com/ubuntu focal-updates/universe amd64 Packages [964 kB]
Des:29 http://es.archive.ubuntu.com/ubuntu focal-updates/universe Translation-en [220 kB]
Des:30 http://es.archive.ubuntu.com/ubuntu focal-updates/universe amd64 c-n-f Metadata [21,6 kB]
Des:31 http://es.archive.ubuntu.com/ubuntu focal-updates/multiverse i386 Packages [8.448 B]
Des:32 http://es.archive.ubuntu.com/ubuntu focal-updates/multiverse amd64 Packages [24,4 kB]
Des:33 http://es.archive.ubuntu.com/ubuntu focal-backports/universe amd64 Packages [23,9 kB]
Des:34 http://es.archive.ubuntu.com/ubuntu focal-backports/universe i386 Packages [13,5 kB]
Des:35 http://es.archive.ubuntu.com/ubuntu focal-backports/universe amd64 c-n-f Metadata [860 B]
Descargados 12,9 MB en 5s (2.692 kB/s)                                         
Leyendo lista de paquetes... Hecho
Creando árbol de dependencias       
Leyendo la información de estado... Hecho
Se pueden actualizar 78 paquetes. Ejecute «apt list --upgradable» para verlos.
W: El objetivo Packages (stable/binary-amd64/Packages) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
W: El objetivo Packages (stable/binary-all/Packages) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
W: El objetivo Translations (stable/i18n/Translation-es_ES) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
W: El objetivo Translations (stable/i18n/Translation-es) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
W: El objetivo Translations (stable/i18n/Translation-en) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
W: El objetivo CNF (stable/cnf/Commands-amd64) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
W: El objetivo CNF (stable/cnf/Commands-all) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
W: El objetivo Packages (stable/binary-amd64/Packages) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
W: El objetivo Packages (stable/binary-all/Packages) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
W: El objetivo Translations (stable/i18n/Translation-es_ES) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
W: El objetivo Translations (stable/i18n/Translation-es) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
W: El objetivo Translations (stable/i18n/Translation-en) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
W: El objetivo CNF (stable/cnf/Commands-amd64) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
W: El objetivo CNF (stable/cnf/Commands-all) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
mohamed93@usuario-OptiPlex-380:~$ sudo apt install apache2
Leyendo lista de paquetes... Hecho
Creando árbol de dependencias       
Leyendo la información de estado... Hecho
apache2 ya está en su versión más reciente (2.4.41-4ubuntu3.12).
Los paquetes indicados a continuación se instalaron de forma automática y ya no son necesarios.
  chromium-codecs-ffmpeg-extra gstreamer1.0-vaapi libc-ares2 libfwupdplugin1
  libgstreamer-plugins-bad1.0-0 libllvm11 linux-headers-5.13.0-27-generic
  linux-hwe-5.13-headers-5.13.0-27 linux-image-5.13.0-27-generic
  linux-modules-5.13.0-27-generic linux-modules-extra-5.13.0-27-generic
  nodejs-doc
Utilice «sudo apt autoremove» para eliminarlos.
0 actualizados, 0 nuevos se instalarán, 0 para eliminar y 78 no actualizados.
mohamed93@usuario-OptiPlex-380:~$ sudo ufw app list
Aplicaciones disponibles:
  Apache
  Apache Full
  Apache Secure
  CUPS
  OpenSSH
mohamed93@usuario-OptiPlex-380:~$ sudo ufw allow 'Apache'
Omitiendo adición de regla ya existente
Omitiendo adición de regla ya existente (v6)
mohamed93@usuario-OptiPlex-380:~$ sudo ufw status
Estado: inactivo
mohamed93@usuario-OptiPlex-380:~$ sudo apt remove apache2
Leyendo lista de paquetes... Hecho
Creando árbol de dependencias       
Leyendo la información de estado... Hecho
Los paquetes indicados a continuación se instalaron de forma automática y ya no son necesarios.
  apache2-data apache2-utils chromium-codecs-ffmpeg-extra gstreamer1.0-vaapi
  libc-ares2 libfwupdplugin1 libgstreamer-plugins-bad1.0-0 libllvm11
  linux-headers-5.13.0-27-generic linux-hwe-5.13-headers-5.13.0-27
  linux-image-5.13.0-27-generic linux-modules-5.13.0-27-generic
  linux-modules-extra-5.13.0-27-generic nodejs-doc
Utilice «sudo apt autoremove» para eliminarlos.
Los siguientes paquetes se ELIMINARÁN:
  apache2
0 actualizados, 0 nuevos se instalarán, 1 para eliminar y 78 no actualizados.
Se liberarán 543 kB después de esta operación.
¿Desea continuar? [S/n] s
(Leyendo la base de datos ... 412984 ficheros o directorios instalados actualmen
te.)
Desinstalando apache2 (2.4.41-4ubuntu3.12) ...
Procesando disparadores para man-db (2.9.1-1) ...
Procesando disparadores para ufw (0.36-6ubuntu1) ...
Se han actualizado las reglas para el perfil «Apache»

mohamed93@usuario-OptiPlex-380:~$ sudo apt update
Obj:1 https://deb.nodesource.com/node_16.x focal InRelease
Obj:2 https://download.docker.com/linux/ubuntu focal InRelease                 
Obj:3 http://es.archive.ubuntu.com/ubuntu focal InRelease                      
Obj:4 http://ppa.launchpad.net/inkscape.dev/stable/ubuntu focal InRelease      
Des:5 http://es.archive.ubuntu.com/ubuntu focal-updates InRelease [114 kB]     
Obj:6 http://security.ubuntu.com/ubuntu focal-security InRelease               
Obj:7 https://packages.microsoft.com/repos/vscode stable InRelease             
Des:8 http://es.archive.ubuntu.com/ubuntu focal-backports InRelease [108 kB]
Descargados 222 kB en 2s (148 kB/s)
Leyendo lista de paquetes... Hecho
Creando árbol de dependencias       
Leyendo la información de estado... Hecho
Se pueden actualizar 78 paquetes. Ejecute «apt list --upgradable» para verlos.
W: El objetivo Packages (stable/binary-amd64/Packages) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
W: El objetivo Packages (stable/binary-all/Packages) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
W: El objetivo Translations (stable/i18n/Translation-es_ES) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
W: El objetivo Translations (stable/i18n/Translation-es) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
W: El objetivo Translations (stable/i18n/Translation-en) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
W: El objetivo CNF (stable/cnf/Commands-amd64) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
W: El objetivo CNF (stable/cnf/Commands-all) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
W: El objetivo Packages (stable/binary-amd64/Packages) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
W: El objetivo Packages (stable/binary-all/Packages) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
W: El objetivo Translations (stable/i18n/Translation-es_ES) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
W: El objetivo Translations (stable/i18n/Translation-es) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
W: El objetivo Translations (stable/i18n/Translation-en) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
W: El objetivo CNF (stable/cnf/Commands-amd64) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
W: El objetivo CNF (stable/cnf/Commands-all) está configurado varias veces en /etc/apt/sources.list:58 y /etc/apt/sources.list.d/docker.list:1
mohamed93@usuario-OptiPlex-380:~$ sudo apt install apache2
Leyendo lista de paquetes... Hecho
Creando árbol de dependencias       
Leyendo la información de estado... Hecho
Los paquetes indicados a continuación se instalaron de forma automática y ya no son necesarios.
  chromium-codecs-ffmpeg-extra gstreamer1.0-vaapi libc-ares2 libfwupdplugin1
  libgstreamer-plugins-bad1.0-0 libllvm11 linux-headers-5.13.0-27-generic
  linux-hwe-5.13-headers-5.13.0-27 linux-image-5.13.0-27-generic
  linux-modules-5.13.0-27-generic linux-modules-extra-5.13.0-27-generic
  nodejs-doc
Utilice «sudo apt autoremove» para eliminarlos.
Paquetes sugeridos:
  apache2-doc apache2-suexec-pristine | apache2-suexec-custom
Se instalarán los siguientes paquetes NUEVOS:
  apache2
0 actualizados, 1 nuevos se instalarán, 0 para eliminar y 78 no actualizados.
Se necesita descargar 95,6 kB de archivos.
Se utilizarán 543 kB de espacio de disco adicional después de esta operación.
Des:1 http://es.archive.ubuntu.com/ubuntu focal-updates/main amd64 apache2 amd64 2.4.41-4ubuntu3.12 [95,6 kB]
Descargados 95,6 kB en 0s (243 kB/s)
Seleccionando el paquete apache2 previamente no seleccionado.
(Leyendo la base de datos ... 412934 ficheros o directorios instalados actualmen
te.)
Preparando para desempaquetar .../apache2_2.4.41-4ubuntu3.12_amd64.deb ...
Desempaquetando apache2 (2.4.41-4ubuntu3.12) ...
Configurando apache2 (2.4.41-4ubuntu3.12) ...
Procesando disparadores para systemd (245.4-4ubuntu3.17) ...
Procesando disparadores para man-db (2.9.1-1) ...
Procesando disparadores para ufw (0.36-6ubuntu1) ...
Se han actualizado las reglas para el perfil «Apache»

mohamed93@usuario-OptiPlex-380:~$ sudo ufw app list
Aplicaciones disponibles:
  Apache
  Apache Full
  Apache Secure
  CUPS
  OpenSSH
mohamed93@usuario-OptiPlex-380:~$ sudo ufw allow 'Apache'
Omitiendo adición de regla ya existente
Omitiendo adición de regla ya existente (v6)
mohamed93@usuario-OptiPlex-380:~$ sudo ufw status
Estado: inactivo
mohamed93@usuario-OptiPlex-380:~$ sudo ufw enable
El cortafuegos está activo y habilitado en el arranque del sistema
mohamed93@usuario-OptiPlex-380:~$ sudo ufw status
Estado: activo

Hasta                      Acción      Desde
-----                      ------      -----
Apache                     ALLOW       Anywhere                  
Apache (v6)                ALLOW       Anywhere (v6)             

mohamed93@usuario-OptiPlex-380:~$ sudo systemctl status apache2
● apache2.service - The Apache HTTP Server
     Loaded: loaded (/lib/systemd/system/apache2.service; disabled; vendor pres>
     Active: inactive (dead)
       Docs: https://httpd.apache.org/docs/2.4/

mohamed93@usuario-OptiPlex-380:~$ hostname -I
192.168.0.144 172.17.0.1 
mohamed93@usuario-OptiPlex-380:~$ ^C
mohamed93@usuario-OptiPlex-380:~$ hostname -I
192.168.0.144 172.17.0.1 
mohamed93@usuario-OptiPlex-380:~$ curl -4 icanhazip.com
62.43.207.80
mohamed93@usuario-OptiPlex-380:~$ sudo systemctl start apache2
[sudo] contraseña para mohamed93: 
Lo siento, pruebe otra vez.
[sudo] contraseña para mohamed93: 
mohamed93@usuario-OptiPlex-380:~$ sudo systemctl status apache2
● apache2.service - The Apache HTTP Server
     Loaded: loaded (/lib/systemd/system/apache2.service; disabled; vendor preset: enabled)
     Active: active (running) since Mon 2022-10-10 18:21:12 CEST; 6s ago
       Docs: https://httpd.apache.org/docs/2.4/
    Process: 7728 ExecStart=/usr/sbin/apachectl start (code=exited, status=0/SUCCESS)
   Main PID: 7739 (apache2)
      Tasks: 6 (limit: 4561)
     Memory: 6.3M
     CGroup: /system.slice/apache2.service
             ├─7739 /usr/sbin/apache2 -k start
             ├─7740 /usr/sbin/apache2 -k start
             ├─7741 /usr/sbin/apache2 -k start
             ├─7742 /usr/sbin/apache2 -k start
             ├─7743 /usr/sbin/apache2 -k start
             └─7744 /usr/sbin/apache2 -k start

oct 10 18:21:12 usuario-OptiPlex-380 systemd[1]: Starting The Apache HTTP Server...
oct 10 18:21:12 usuario-OptiPlex-380 apachectl[7738]: [Mon Oct 10 18:21:12.643490 2022] [core:error] [p>
oct 10 18:21:12 usuario-OptiPlex-380 apachectl[7738]: AH00558: apache2: Could not reliably determine th>
oct 10 18:21:12 usuario-OptiPlex-380 systemd[1]: Started The Apache HTTP Server.
...skipping...
● apache2.service - The Apache HTTP Server
     Loaded: loaded (/lib/systemd/system/apache2.service; disabled; vendor preset: enabled)
     Active: active (running) since Mon 2022-10-10 18:21:12 CEST; 6s ago
       Docs: https://httpd.apache.org/docs/2.4/
    Process: 7728 ExecStart=/usr/sbin/apachectl start (code=exited, status=0/SUCCESS)
   Main PID: 7739 (apache2)
      Tasks: 6 (limit: 4561)
     Memory: 6.3M
     CGroup: /system.slice/apache2.service
             ├─7739 /usr/sbin/apache2 -k start
             ├─7740 /usr/sbin/apache2 -k start
             ├─7741 /usr/sbin/apache2 -k start
             ├─7742 /usr/sbin/apache2 -k start
             ├─7743 /usr/sbin/apache2 -k start
             └─7744 /usr/sbin/apache2 -k start

oct 10 18:21:12 usuario-OptiPlex-380 systemd[1]: Starting The Apache HTTP Server...
oct 10 18:21:12 usuario-OptiPlex-380 apachectl[7738]: [Mon Oct 10 18:21:12.643490 2022] [core:error] [p>
oct 10 18:21:12 usuario-OptiPlex-380 apachectl[7738]: AH00558: apache2: Could not reliably determine th>
oct 10 18:21:12 usuario-OptiPlex-380 systemd[1]: Started The Apache HTTP Server.
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~

mohamed93@usuario-OptiPlex-380:~$ hostname -I
192.168.0.144 172.17.0.1 
mohamed93@usuario-OptiPlex-380:~$ cd /var/www/html
mohamed93@usuario-OptiPlex-380:/var/www/html$ ls
index.html  info.php
mohamed93@usuario-OptiPlex-380:/var/www/html$ sudo chown mohamed93 -R /var/www/html
mohamed93@usuario-OptiPlex-380:/var/www/html$ ls -l
total 8
-rw-r--r-- 1 mohamed93 www-data 26 nov 19  2021 index.html
-rw-r--r-- 1 mohamed93 root     20 nov  5  2021 info.php
mohamed93@usuario-OptiPlex-380:/var/www/html$ sudo chmod 777 -R /car/www/html
chmod: no se puede acceder a '/car/www/html': No existe el archivo o el directorio
mohamed93@usuario-OptiPlex-380:/var/www/html$ sudo chmod 777 -R /var/www/html
mohamed93@usuario-OptiPlex-380:/var/www/html$ ls -l
total 8
-rwxrwxrwx 1 mohamed93 www-data 26 nov 19  2021 index.html
-rwxrwxrwx 1 mohamed93 root     20 nov  5  2021 info.php
mohamed93@usuario-OptiPlex-380:/var/www/html$ 
