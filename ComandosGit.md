# Comandos de Git

## Comando para ve la version de git

```terminal

git -v
git --version

```

- git -v
- git --version

## Comando par ala configuración inicial de git

- git config --global user.name "My name"
- git config --global user.email "My email"

## Comando para editar o ver la configuración de git

Para salir del edit ctrl + o y ctrl + x y si es VIM esc y :wq

- git config --global --edit
- git config --global --list

## Como inciar git en un directorio

- git init

## Comando para saber el estado de nuestros arcchivos

- git status

## Comando para listar las versiones de mi proyecto

- git log
- git log --oneline

## Pasos para crear una version de nuetro código

1. Agregar todos los archivos al commit

- git add . //  Agrega todos los archivos
- git add *.js // Agregar todos los archivos con la extensión js
- git add index.js // Agregar un archivo

2. Tomar la foto del codigo (Crear una nueva versión)

- git commit -m "Nombre del commit"
