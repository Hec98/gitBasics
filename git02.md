### Reconstruye al ultimo commit
``
git checkout -- .
``
### git log
``
git log
``
### git log en una sola linea 
``
git log --oneline 
``
### git log decorado
``
git log --oneline --decorate --all --graph
``
### git status
``
git status -s
``
``
git status -s -b
``
### Corregir texto del commit
``
git commit --amend -m "Actualizamos el readme"
``
### Desacer commit
``
git reset --soft HEAD^
``
``
git commit -am "Actualizamos el readme"
``
### Reset a un determinado punto
``
git reset --soft 187a36d
``
### Punto al cual movernos mexclando archivos, los archivos aun contienen los cambios
``
git reset --mixed 560f332 
``
### Regresar pero quitar cambios posteriores
``
git reset --hard
``
### Registro de lo que sucedido en el repositorio
``
git reflog
``
### Regresa aunque se haya "borrado" la historia
``
git reset --hard 6cf8bf4
``
### Renombrar archivos
``
git mv destruir-mundo.txt salvar-mundo.txt
``
### Remover archivos
``
git rm salvar-mundo.txt
``
### Despues de renombrar o eliminar archivos fuera de git
``
git add -u
``
``
git add -A
``
