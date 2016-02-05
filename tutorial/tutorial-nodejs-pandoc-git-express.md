#Tutorial Tareas Iniciales PL 15-16

##Git

Es un software de control de versiones desarrollado por Linus Torvalds, desarrollador del kernel Linux.

###Instalacion

En el poco comun caso en el que git no este instalado por defecto en una maquina Ubuntu 14.04, la solucion es ejecutar el comando:

    sudo apt-get install git

Tras esto, el software de control de versiones Git estara instalado.

Para comprobar si se ha instalado correctamente, ejecutar:

![](/images/gitVersion.png)

##Node.js

Node.js es un entorno en tiempo de ejecucion cuyo principal objetivo es el desarrollo de aplicaciones en JavaScript para la capa del servidor.
Tiene la particularidad que el codigo se ejecuta en el servidor, a diferencia de la mayoria de codigo JavaScript, que se ejecuta en el navegador.

###Instalacion

Para su instalacion, en Ubuntu 14.04, solo se debe ejecutar el comando

    sudo apt-get install node

Para comprobar la instalacion, ejecutar los siguientes comandos:

![](/images/node+npm.png "")


##Express.js

Express.js es un framework de servidor de aplicaciones web para Node.js. Esta disenado para construir aplicaciones web tanto de una pagina, varias paginas o hibridas.

###Instalacion

El proceso de instalacion requiere la previa configuracion e instalacion de Node.js, ademas de una estructura ya creada a traves del comando

    npm init

Tras estos dos pasos, lo unico necesario para la instalacion de Express.js es ejecutar en la terminal:

    sudo npm install express --save

Importante el --save puesto que este ya lo incluye en las dependencias del package.json de manera automatica.
La salida sera algo por el estilo:

![](/images/express.png)

##Pandoc

Se trata de un conversor de lenguajes de marcado, que a su vez son una forma de codificar un documento que ademas del texto incorpora etiquetas, que proveen de informacion adicional. En el caso de este tutorial, se enfocara en la conversion de Markdown a HTML.

###Instalacion

Para Ubuntu 14.04, se descarga el siguiente paquete .deb y se instala a traves del Centro de Software de Ubuntu:

https://github.com/jgm/pandoc/releases/download/1.16.0.2/pandoc-1.16.0.2-1-amd64.deb

Para comprobar la instalacion, realizar esto:

![](/images/pandoc-install.png)


####Autor

#####Eduardo Ernesto Brito Sanchez - alu0100783315

#####[G+](https://plus.google.com/+EduardoBritoSan)
