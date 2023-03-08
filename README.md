# Comandos basicos para git

# Configuración en git (local)

1. Ver configuración general 
```bash
git config -l 
```
2. Cambiar el correo  
```bashn
git config --global user.email "name@gmail.com"
````
3. Cambiar nombre de usuario 
```bash
git config --global user.name "name"
```
----
# Crear un repositorio 

1. Inicializar el repositorio
```bash
git init
```
2. Añadir los archivos existentes 
```bash
git add .
```
3. Crear el primer commit
```bash
git commit -m "Initial commit"
```
---
# Conectar el repositorio con Github


1. Traer la última versión de github
```bash
git pull origin main
```
2. enviar la última versión de local a github 
```bash
git push origin main 
```

----

# Otros
* Ver el estado del repositorio
```bash
git status
```
* Ver todos los commits en el repositorio
```bash
git log 
```
* Crear una llave ssh 
```bash
ssh-keygen -t rsa -b 4096 -C "and@gmail.com"
```
* Ver los repositorios asociados
```bash
git remote -v 
```
* Cambiar dirección del repositorio (ssh)
```bash
git remote set-url origin git@github.com:aplatag/example-page-js.git
```

