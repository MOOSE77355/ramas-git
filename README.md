# Aprendiendo Git  & Github
## 1. Inicializar el repositorio

```
git init
```
- este comando permite incializar el repositorio

## 2. Enviar archivos al Área de preparacion (index)

```
git add .
```
-enviar todos los archivos modificados
o
```
git add index.html README.md
```
-seleccionar los archivos

## 3. Asignar una descripción a los archivos añadidos

```
git commit -m "proyecto base"
```
# Publicación en Github
- Crear un repositorio en Github

## Asociar el Repositorio Local con el Repositorio Remoto Github

```
git remote add origin https://github.com/MOOSE77355/ramas-git.git
```

## Verificar si ya esta asociado el repositorio local con el remoto

```
git remote -v
```

## Subir/publicar todos los cambios a Github

```
git push origin master
```

## Para crear una nueva rama 
```
git branch
git branch desarrollo
git branch
```

## Cambiar ala nueva rama
```
git switch desarrollo
git checkout desarrollo
```
- modificamos el codigo fuente 
- registrar los cambios con:
```
git add .
git commit -m "descripción"
```

-Luego realizamos el git push a github
```
git push origin desarrollo
```