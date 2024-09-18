# Apuntes

### Básicos
`cd ss` -> cambiarse de lugar en el directorio

`git init` -> reiniciarlo, crear un nuevo repositorio

`git` -> indica qué no se llevó al Staying Area

`clear` -> limpiralo todo

`ls` -> ver los archivos de la carpeta donde estamos ahora

### Archivos
`git status -s` -> preguntar por el estado en donde se encuentra el repositorio actual

`git log --oneline` -> lista los commit realizados, con las horas y el dia, y el mensaje

`git log` -> muestra los datos de cada commit realizado

`git add archivo` -> pone todos los archivos y carpetas en seguimiento

`git reset --hard nombre` -> deja el archivo como estaba al principio

`git add .` -> añade todos los archivos y carpetas en seguimiento

### Commit
`git commit -m ""` -> captura instantánea, crear nueva versión

`git commit -am "Cuarta versión"` -> git add + git commit -m

`git commit --amend` -> rectificar comentario editor, cambiar nombre versión

### Repositorios
`config --global core.editor "nano"` -> de bit a nano

`git push -u origin master` -> subir la información de la rama master de repositorio local -> al remoto

`git remote add origin ""` -> abreviatura de todo el truñaco

`git remote rm origin` -> para eliminar el vinculo que tengo con el usuario remoto

`git remote -v` -> para vinculos con repositorios remotos (te da la url)

`git remote` -> te dice la conexion con la que estas conectado al repositorio actual

`git pull` -> traer los cambios del repositorio remoto al local

### Etiquetas
`git tag 20230515v1 -m "Versión 1 San Isidro"` -> crear etiqueta

`git push --tags` -> sube las etiquetas al repositorio

`git push` -> empujar repositorio al lugar deseado

`git clone "enlace copiado"` -> clonar proyecto, sirve para proteger información por si se borra

### Ramas
`git branch` -> enseña la rama en la que estas

`git branch nombre` -> crea la rama

`git checkout` o `switch html/main/master` -> cambiar de rama

`git merge versión` -> fusionar los cambios hechos en la rama "html" a la rama actual

`git branch -d versión` -> para eliminar la rama (tienen que estar fusionadas)

`git branch -D versión` -> para eliminar la rama (no tienen que estar fusionadas)

`git branch --merged` -> para ver las ramas que se han fusionado

`git branch --no-merged` -> para ver las ramas que no se han fusionado
