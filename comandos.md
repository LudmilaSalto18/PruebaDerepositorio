#creacion
git init# crear un reposotorio local vacio en el directorio global
#esto se alamacen en el directorio git.

 #esto se almacena en el directorio .git
 git status# este es el mas usados de todos. Nos dice la  rama en la que nos encontramos 
 #nos encontramos y los ficheron que contienen el stage junto a su estado.
 #(new/modified/deleted). Ademas avisa de ficheros sin sengumiento por git.
 #(untracked) o ficheros con conflictos.

 #flujo entre working/stage/repo
git add <lista de ficheros> # Manda uno o varios ficheros separados por.
#espacio o un directorio al stagin area.Recien añadido un nuevo fichero
#al repositorio, eto se encuentra en estado "Untracked" y debemos hacer
#un primer add. Podriamos usar el caracter "." si queremos enviar todos los.
#ficheros del directorio de trabajo que tiene algun cambio
#tambien admite comodis ej: git add *.js

git commit -m "descripcion breve" #Registra definitivamente los cambios que.
#previamente estaban en el stage