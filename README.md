# Comandos básicos de Git y GitHub

En este documento encontrarás una lista de comandos básicos de Git y GitHub que te ayudarán a empezar con el control de versiones y la colaboración en proyectos.

## Configurar Git

```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tu@email.com"
```

## Crear un repositorio

```bash

git init
git clone <URL>
```

## Hacer cambios

``` bash

git status
git add <nombre_archivo>
git add .
git commit -m "Mensaje de commit"
```

## Trabajar con ramas

``` bash

git branch
git branch <nombre_rama>
git checkout <nombre_rama>
git merge <nombre_rama>
```

## Sincronizar con repositorios remotos

```bash

git remote add origin <URL>
git push -u origin <nombre_rama>
git pull origin <nombre_rama>
git fetch origin
```
## Otros comandos útiles

``` bash

git log
git diff
git reset <nombre_archivo>
git reset --hard
```

¡Espero que esta guía te sea útil para empezar a utilizar Git y GitHub en tus proyectos! Si tienes alguna pregunta, no dudes en contactarme.
Asegúrate de reemplazar `<URL>` con la URL de tu repositorio y `<nombre_archivo>` y `<nombre

