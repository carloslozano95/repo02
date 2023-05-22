# Primeros pasos repositorio GIT
## Inicialización de repositorio  
Para empezar creamos una carpeta para guardar nuestro repositorio, una vez creada nos situaremos en ella y ejecutaremos el comando:
```
git init nombredelrepositorio
```
Con esto lo que generamos es la inicialización de nuestro repositorio  
## Visualización de estado de la rama
Para ver el estado que tenemos en la rama, tendremos que ejecutar este comando:
```
git status
```
El cual nos mostrará en que estado se encuentra.
## Añadir ficheros al repositorio
Antes de hacer nuestro commit, debemos añadir nuestros archivos para que se quedan en "Staged", si quieres añadir todos los archivos tendrás que añadir:
```
git add .
```
Si únicamente quieres hacer el añadido de:
```
git add nombredearchivo
```
## Comando COMMIT
Si queremos ejecutar un commit para enviar nuestros cambios a nuestro repositorio local será de esta forma:
```
git commit -m "Comentario para el commit"
```
Si queremos 
Una vez enviamos en commit nuestros archivos, se quedan en "commited" y ya lo tendremos en nuestro repositorio local.
## Comando PUSH
Con el comando push lo que hacemos es enviar nuestros archivos hacía el repositorio de la nube.
```
git push 
```
## Comando PULL
Si queremos descargar los archivos que hay actualmente en la nube (por si hay alguna nueva actualización) tendremos que ejecutar este comando:
```
git pull
```
## Comando REMOTE
Con este comando vemos lo que tenemos en remoto:
```
git remote -v
```
## Comando CLONE
Para clonar un repositorio que tenemos en la nube, deberemos utilizar el siguiente comando:
```
git clone URL_del_repositorio
```