# Apuntes

### Básicos
`cd ss` -> cambiarse de lugar en el directorio

`git init` -> inicializar repositorio, o reiniciarlo si ya había uno

`clear` -> limpiar terminal

`ls` -> ver los archivos de la carpeta donde estamos ahora

### Archivos
`git status` -> preguntar por el estado en donde se encuentra el repositorio actual

`git log` -> lista los commit realizados, con el id, el mensaje y la fecha

`git log --oneline` -> lista los commits sólo con el id y el mensaje

`git add .` -> pone todos los archivos y carpetas en seguimiento

`git add <archivo>` -> pone un archivo en seguimiento

`git reset --hard <archivo>` -> descarta los cambios del archivo

### Commit
`git commit -m "<mensaje>"` -> hacer un commit con su mensaje

`git commit -am "<mensaje>"` -> `git add` + `git commit -m "<mensaje>"`

`git commit --amend` -> rectificar mensaje del commit anterior. Si hay archivos en el Staging Area, también se rectificará con los archivos nuevos

### Repositorios
`config --global core.editor "nano"` -> configurar el editor a nano

`git push -u origin master` -> subir la información de la rama master de repositorio local -> al remoto

`git remote add origin "<URL>"` -> configurar el repositorio remoto

`git remote rm origin` -> para eliminar el vinculo que tengo con el repositorio remoto

`git remote -v` -> devuelve la url del repositorio remoto

`git remote` -> te dice la conexion con la que estas conectado al repositorio actual

`git clone <URL>` -> clonar un repositorio en la máquina local

`git pull` -> traer los cambios del repositorio remoto al local

`git push` -> subir cambios al repositorio remoto

### Etiquetas
`git tag 20230515v1 -m "<nombre de etiqueta>"` -> crear etiqueta

`git push --tags` -> subir las etiquetas al repositorio remoto

### Ramas
`git branch` -> devuelve el nombre de la rama en la que estás

`git branch <nombre>` -> crea una rama nueva

`git checkout <rama>` o `switch html/main/master` -> cambiar de rama

`git merge <versión>` -> fusionar los cambios hechos en la rama `<versión>` a la rama actual

`git branch -d <versión>` -> para eliminar la rama (tienen que estar fusionadas)

`git branch -D <versión>` -> para eliminar la rama (no tienen que estar fusionadas)

`git branch --merged` -> para ver las ramas que se han fusionado

`git branch --no-merged` -> para ver las ramas que no se han fusionado
