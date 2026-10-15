# Aprendiendo GIT & Github
## 1. Inicializar el repositorio git (local)
```
git init
```
- este comando permite inicializar el repositorio 

## 2. Enviar archivos al Area de preparacion (index)

```
git add .
```
-eviar todos los archivos modificados
o
```
git add index.html README.md
```
-seleccionar los archivos

## 3. Asignar una descrepcion a los archivos agregados
```
git commit -m "proyecto base"
```
# Publicacion en GITHUB
-Crear un repositorio en Github

## Asociar el repositorio (local) con el repositorio (remoto) GITHUB

```
git remote add origin https://github.com/ronaldCE/ramas-git-fullstack.git
```
## Verificar si ya esta asociado (local con el remoto)
```
git remote -v
``` 

## Subir o publicar todos los cambios a Github

```
git push origin master
```

## Crear una nueva rama

```
git branch
git branch desarrollo
git branch 
```
## cambiar a la nueva rama
```
git switch desarrollo
git checkout desarrollo
```