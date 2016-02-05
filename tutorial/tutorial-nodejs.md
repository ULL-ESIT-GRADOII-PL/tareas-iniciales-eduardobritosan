#Tutorial Node.js

##Introduccion

Node.js es un entorno en tiempo de ejecucion cuyo principal objetivo es el desarrollo de aplicaciones en JavaScript para la capa del servidor.
Tiene la particularidad que el codigo se ejecuta en el servidor, a diferencia de la mayoria de codigo JavaScript, que se ejecuta en el navegador.

##npm

"node package manager" es el sistema gestor de paquetes por defecto de Node.js, se encarga de la instalacion, actualizacion, eliminacion y configuracion de paquetes funcionales en el entorno, a la vez que se encarga de mantener la usabilidad, resolver dependencias, agrupamiento de paquetes, comprobacion de la suma de verificacion (checksum) para evitar diferencias entre la version local de un paquete y la oficial, entre multiples otras funcionalidades.

###package.json

Es un fichero unico que se encuentra normalmente en la raiz del proyecto y contiene varios metadatos relevantes para el mismo. Este fichero provee de informacion a npm para permitir identificarlo y para saber lidiar con las dependencias del proyecto. Tambien contiene metadatos como la descripcion del proyecto, la version, informacion de licencias e incluso informacion de configuracion.

Aqui un ejemplo de su sintaxis:

![](/images/package-json.png)

##Instalacion

Para su instalacion, en Ubuntu 14.04, solo se debe ejecutar el comando

    sudo apt-get install node

Para comprobar la instalacion, ejecutar los siguientes comandos:

![](/images/node+npm.png "")


####Autor

#####Eduardo Ernesto Brito Sanchez - alu0100783315
