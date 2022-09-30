# GitHub
### Mohamed Abdelkader

Se trata de una plataforma que sirve para crear proyectos abiertos de herramientas y aplicaciones, y
se caracteriza por sus funciones colaborativas que ayudan a que todos te puedan ayudar o aconsejar
para mejorar el código.Los proyectos que sean abiertos pueden ser revisados y descargados por cualquier
usuario, lo que ayuda a mejorar y crear ramificaciones a partir de él. Y si
quieres también puedes hacer que tu código sea privado.

### Instalacion GitHub
1. Lo primero que debemos de hacer sera crear una cuenta en [GitHub](https://github.com/).
2. Una vez ello el paso anterior, abriremos la terminal de Linux(Ctrl+T).
3. Y escribiremos...
```  
$ sudo apt update
$ sudo apt install git
```
4. Finalmente comprobaremos si se ha instalado correctamente y en que version. 
```  
$ git --version
```

### Creacion de un archivo
Vamos a crear un archivo de GitHub en **C**
* Abrimos la terminal.
* $ mkdir tempGitHub
* $ cd tempGitHub
* $ touch temp.c
* $ gedit temp.c
* A continuación abriremos cualquier editor de textos y escribiremos el contenido de nuestro programa.
```
#include <stdio.h>
int main(){
    printf(“Hola Mundo”);
    return 0;
}
```
Cerraremos el Gedit e iremos a la terminal; hecho esto tendremos que estar situados en el directorio tempGitHub y procederemos a configurarlo.
```
$ git config --global user.email “<tuCorreoElectrónicoEnGitHub>”
$ git config --global user.name “<tuNombreEnGitHub>”
```
>Si se produce el caso de que pida un token deberemos de ir a [**GitHub**](https://github.com/) --> **Settings**(de la cuenta) --> **Developer Settings** -->**Personal access tokens** --> **Generate new token**

Continuaremos iniciando un nuevo repositorio en GitHub y subiendo el actual directorio
```
$ git init
$ git add .
$ git commit -m “Subida del archivo de prueba”
$ git push
```
#### Comandos
> **git init**: crea un nuevo repositorio de Git.

> **git add**: añade un cambio del directorio de trabajo en el entorno de ensayo.

> **git commit -m “String”**: Sirve para sobrescribir un archivo existente o escribir uno nuevo.

> **git push**: te permite subir los commits desde tu rama (branch) local en tu repositorio git local al repositorio remoto.

## Conclusión
En mi opinión GitHub me ha parecido una buena aplicación web ya que al ser colaborativa puedes recibir consejos o ayuda de los demas en tus proyectos o también aprender de los suyos, además es bastante fácil de usar.No obstante el proceso de instalación puede paracer un poco complejo la primera vez.

#### Webrafía
* [Xataka](https://www.xataka.com/basics/que-github-que-que-le-ofrece-a-desarrolladores)
* [Atlassian](https://www.atlassian.com/es/git/tutorials/saving-changes)
* [freeCodeCamp](https://www.atlassian.com/es/git/tutorials/saving-changes)
* GitHub:Introducción(_classroom_).
