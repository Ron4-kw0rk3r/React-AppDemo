# Make app reactDemo

1. First app make instruccions create app

Concepto:
primero preparamos el entorno de desarrollo para organizar el primer avance 
## @@Segun estas instrucciones ya se tendria instaldo node si no es el caso puede de saltar este paso

## abrir una terminal o  si estas en windows 

tambien puedes de descargar el ejecutable en la pagina oficial 
link: https://nodejs.org/en/download/prebuilt-installer

## Terminal (ejecutar como administrador) 

### installs fnm (Fast Node Manager)
<code> winget install Schniz.fnm</code> 

### download and install Node.js

<code> fnm use --install-if-missing 20 </code>

### verifies the right Node.js version is in the environment

<code> node -v # should print `v20.16.0` </code>

### verifies the right npm version is in the environmen
<code> npm -v # should print `10.8.1` </code>


continuando inicie un projecto en react

paso 1. 

en la terminal ejecute: 
"$" -> crea una carpeta 
"$" mkdir  myapp
"$" npx create-react-app myapp

### comandos adicionales:

npm start

npm run build 

--> esto solo si quiere de construirlo y tener un enlace en local: """
    npm install -g serve

    serve -s build 
"""

npm test

npm run eject 


Happy Hacking ::

