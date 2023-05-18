# Prueba Toolbox 
## Nodejs & React

Este es el repositorio principal, ya que el backend y la parte de frontend se realizaron en otro repositorio para 
unificar la prueba técnica se crearon los submódulos.

### Clonar los sudmodulos git

Dentro de la carpeta principal, abrir el terminal y ejecutar el siguiente comando para instalar todos los submódulos 
proporcionados.

> git submodule update --init --recursive

### Instalación Nodejs

Una vez que tenga instaladas las dos carpetas, podrá ingresar a la carpeta <b>backfilecsv</b> y actualizar la rama e 
instalar los módulos necesarios.

> cd backfilecsv
> 
> git checkout master
> 
> git pull
> 
> npm install

Cuando se hayan instalado todos los módulos necesarios, podrá ejecutar el siguiente comando para ejecutar el proyecto.

> npm start

Podrá ingresar a http//:localhost:5050 en el navegador y se abrirá la documentación del swagger-> http://localhost:5050/api-docs/

Mientras el proyecto se está ejecutando, podrá visualizar los tipos de solicitudes (requests) que se le están haciendo 
al servidor.

* Para correr las pruebas unitatrias se tenria que correr en el termonal con el siguiente comando

> npm test

### Instalación de React

Dentro de la carpeta raíz del repositorio principal, diríjase a la carpeta <b>frontfiletool</b>.

> cd frontfiletool
> 
> git checkout master
> 
> git pull
> 
> npm install
> 
> npm start
>
Y se abrirá el navegador.