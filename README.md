### Inicia repositorio
``
git init
``
### Git add
``
git add .
git add -A
``
### Agrega todos los txt del repositorio
``
gir add "*.txt"
``
### Agrega txt en el directorio actual
``
git add *.txt
``
### Agrega tedos los archivos
``
git add --all
``
### Agrega los archivos que listemos
``
git add lista de archivos
``
### Agrega los archivos que listemos dentro la carpeta pdf
``
git add pdfs/**.pdf
``
### Agrega toda la carpeta pdf
``
git add pdfs/
``
### git status
``
git status
``
``
``
### Reconstruye al ultimo commit
``
git checkout -- .
``
### git log
``
git log
``
# 
``
git log --oneline 
``
#
``
git log --oneline --decorate --all --graph
``
#
``
git status -s
``
#
``
git status -s -b
``
### Desacer commit
``
git commit --amend -m "Actualizamos el readme"
``
``
git reset --soft HEAD^
``
``
git commit -am "Actualizamos el readme"
``

### reset a un determinado punto
``
git reset --soft 187a36d
``
### punto al cual mevernos mexclando archivos, los rchivos aun contienen las cambios
``
git reset --mixed 560f332 
``
### regresar pero quitar cambios posteriores
``
git reset --hard
``
### registro de lo que secedo en el repositorio
``
git reflog
``
### regresa aunsque se haya "borrado" la historia
``
git reset --hard 6cf8bf4
``
### renombrar archivos
``
git mv destruir-mundo.txt salvar-mundo.txt
``
### remever archivos
``
git rm salvar-mundo.txt
``
### Despues de renombrar o eliminar archivos fuera de git
``
git add -u
git add -A
``
## Ramas
``
git branch rama-villanos
``
### Ver ramas y cambiar de rama
``
git branch
git checkout rama-villanos
``
### Ver diferencias de ramas
``
git diff rama-villanos master 
``
### Añadir a la rama master otra rama
``
git merge rama-villanos
``
### borrar rama
``
git branch -d rama-villanos
``
### forzar borrar rama
``
git branch -D rama
``
### Efectuar cambios en el servidor
``
git push origin :rama-misiones
git push origin :rama-villanos
git remote prune origin
``
### Crear rama y ir a la rama
``
git checkout -b rama-villano
``
## Tags
### crear y ver tags 
``
git tag superRelease
git tag
``
### borrar tags
``
git tag -d superRelease
``
### crear tag anotado y espesificar elcamit por el hash
``
git tag -a v1.0.0 -m "Versión 1.0.0"
git tag -a v0.1.0 345d7de -m "Versión alfa"
``
### subir tags
``
git push --tags 
``
### ver informacion de un tag
``
git show v1.0.0
``
### git stash
``
git stash
git stash list
``
### extae el ultimo elemento del stash y lo borra
``
git stash pop
``
### Remueve ultimo stash
``
git stash drop
``
### git reverse
``
git rebase master
``
### Git push
``
git push
``
### git fetch
``
git fetch
``
### Git pull
``
git pull
``
### Ver a donde apunta el repositorio
``
git remote -v
``
### Agregar upstream
``
git remote add upstream https://github.com/Klerith/legion-del-mal.git
``
### Verificar cambios en el upstream
``
git fetch upstream master
``
### Obtener cambios del upstream
``
git pull upstream master
``
