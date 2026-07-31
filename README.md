# Aprendiendo GIT & GITHUB
## 1. Inicializar el Repositorio GIT (local)
```
git init
```
- Este comando permite inicializar el repositorio.

## 2. Enviar archivos al Área de Preparación (Index)
```
git add .
``` 
- Enviar todos los archivos modificados.

o
```
git add index.html README.md
``` 
- Seleccionar los archivos.
## 3. Asignar una descripción a los archivos agregados
```
git commit -m "proyecto base"
```
# Publicación en GITHUB
- Crear un repositorio en GITHUB.

## Asociar el repositorio (local) con el repositorio (remoto)
```
git remote add origin https://github.com/shecidxd/ramas-git-fullstack.git
```
## Verificar si ya está asociado (local con el remoto)
```
git remote -v
```

## Subir o publicar todos los cambios a GITHUB
```
git push origin master
```
## Para crear una nueva rama
```
git branch
git branch desarrollo
```