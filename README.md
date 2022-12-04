# GIT y Github

## Comprobar que Git esté comprobado

git -v
git version 2.38.1.windows.1

## Configuración Global

git config --gobal user.name "Alonso Lavado"
git config --global user.email "example@example.com"

## Crear un repositorio desde Github

## Inicializar git

git init

## Enlazar nuestro repositorio remoto

git remote add origin "https://github.com/Alonso0894/my-first-website.git"

## Definir rama principal

git branch -M main

## Subir los cambios

git add --all o git add . 
git commit -m "my first commit"
git push origin main

## Revisar el status

git status