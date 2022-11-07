# SSH por parejas
### Mohamed y Diego.

## PC Servidor
Lo primero que haremos sera crear una cuenta nueva y lo haremos con el comando:
```
sudo adduser nombreNuevoUsuario
```
A continuación instalaremos el SSH server con el comando:
```
sudo apt-get install openssh-server
```
Una vez realizado el paso anterior procederemos a iniciar el servidor
```
sudo systemctl start ssh
```
