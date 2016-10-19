# Ejercicio Basico #

> @author
>> Daniel Pulido


## 2. REPOSITORIO CAMPUSCIFF ##
****
### 2.1. Crear repositorio en github ###
![picture alt](/images/1.png "Title is optional")
![picture alt](/images/2.png "Title is optional")

****
### 2.2. Clonar repositorio en local ###
![picture alt](/images/3.png "Title is optional")  
- clona rep remoto a local
git clone https://github.com/oscarpulido55/campusciff.git 

****
### 2.3 crear archivo README.md###
![picture alt](/images/4.png "Title is optional")  
Comandos en README.md

****
### 2.4. Hacer commit inicial###
![picture alt](/images/5.png "Title is optional")  

****
### 2.5 push inicial###
git push origin master 
![picture alt](/images/6.png "Title is optional")  


****
### 2.6. ignorar archivos
crear en repositorio local, privado.txt, crear carpeta llamada privada
****
### 2.7. realizar cambios para ignoar archivos ###
crear .gitignore

ya no aparecen los archivos registrados en .gitignore como monitorizados por git
****
### 2.8. añadir fichero 1.txt###
****
### 2.9. crear el tag v0.1###
****
### 2.10 subir tag v0.1###
****
### 2.11. Poner Foto en Perfil de Git-Hub, añadir clave publica, segundo factor autenticacion###
****
### 2.13. Crear una tabla MD###

****
### 2.14. agregar a asanzdiego como colaborador del repositorio###




****
## Tabla compañeros de clase ##

| Nombre 	| gitHub 				|
| -------------	| -----------------------------: 	|
|  Dann  	|  https://github.com/danciff  		|
|  Oscar Silva  |  https://github.com/Oscar91DS  	|
|  Oscar Silva  |  https://github.com/Oscar91DS  	|
|  Ivan Ortiz	|  https://github.com/ivtransgruasortiz	|

****
## Resumen de comandos ##
- para inicializar o monitorizar una carpeta
git init

- agrega a la zona monitorizada
git add

- agrega al repositorio local
git commit -m "comentario"

- muestra historial de repositorio
git log

- crea alias, comando list para ver lista de commits
git config --global alias.list 'log --oneline --decorate --graph --all'

- comando unix que crea un archivo, si no existe o cambia fecha de modificacion si existe
touch

- crear llave privada y relacionarla con llave publica en git hub
https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/

- push, pasa de rep local a remoto
git push origin master 

- clona rep remoto a local
git clone https://github.com/oscarpulido55/campusciff.git 
https://github.com/oscarpulido55/repositorio_master.git

https://github.com/oscarpulido55/campusciff2016

- crear tag
git tag -a V0.1 -m "tag volumen 0.1"

- bajar cambios de repositorio remoto a rep local y fusiona con cambios locales 
git pull

- bajar cambios de repositorio remoto a rep local no fusiona con lo local
git fetch alias-repositorio-remoto

- crear branch
git branch "nombre de la rama a crear"
--se pueden crear desde cualquier commit, parandose en el con git checkout "nombre del commit"

- ir a una rama especifica
git checkout "nombre_rama"

- mostrar ramas disponibles
git branch -v

git branch -d "nombre de rama"

git merge "nombre rama desde con la que se hace merge"

- commit con add incluido
git commit -a -m "comentario"

- mustra diferencias entre los archivos
git diff "nombre de archivo"


- clona rep remoto a local
git clone https://github.com/oscarpulido55/campusciff.git

- adiciona el archivo readme al repositorio
git add README.md 

- commit inicial del repositorio
git commit -m "commit inicial"

- push inicial al repositorio
git push origin master 



