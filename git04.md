### Crear y ver tags 
```
git tag superRelease
```
```
git tag
```
### Borrar tags
```
git tag -d superRelease
```
### Crear tag anotado y espesificar el commit por el hash
```
git tag -a v1.0.0 -m "Versión 1.0.0"
```
```
git tag -a v0.1.0 345d7de -m "Versión alfa"
```
### Subir tags
```
git push --tags 
```
### Ver informacion de un tag
```
git show v1.0.0
```
