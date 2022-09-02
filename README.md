# Mi Primer dia con Git/Github

Comando para configurar el usario y el correo
* para ver la version de Git

``` bash
git --version
```

* para configurar correo

``` bash
git config --global user.email "email"
```

* para poder configurar el username

``` bash
git config --global user.name "username"
```
* esto  sirve para empezar a usar el control de versiones
``` bash
git init
```
* para ver el estado de los archivos
``` bash
git status
```

* para agrgar los archivos a la memoria de la pc
``` bash
git add .
```

* crear el registro de los cambios realizados en el main o master
``` bash
git commit -m "comentario"
```

* para ver registros que quedan guardados
``` bash
git log
```

* para cambiar de master a main
``` bash
 git branch -M main
```

* se utiliza para agregar la url a github
``` bash
 git remote add origin https://github.com/jparedes23/Codigo_pc.git
```

* se utilizar para dar autorizacion al github para subir tu proyecto
``` bash
  git push origin main
```
* se utiliza para clonar o descargar archivos desde GitHub....
``` bash
  git clone https://github.com/jparedes23/Codigo_pc.git
```