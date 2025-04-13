Instalación de Git:

sudo apt update
sudo apt install git
git --version

Configuración de Git:

git config --global user.name "Cristian Serrano"
git config --global user.email "cristianserrano@daw.com"
git config --global core.editor "nano"

Comandos útiles:

git add archivo.txt
git commit -m "Mensaje"
git push origin main
git pull origin main

Ramas:

git checkout -b nueva-rama
git checkout main
git merge nueva-rama

