![logo_aitex.png](nodejs/images/logo_aitex.png "Logotipo de Aitex" "width:70px;float:right")
#Proyecto departamento de desarrollo con Node.js + .NET

##Introdución
Tengamos en cuenta que el mundo web va evolucionando constantemente. Antes disponíamos de tres lenguajes de desarrollo en el servidor web: **[PHP][enlacePHP]**, **[J2EE][enlaceJ2EE]** o **[ASPx][enlaceASPNET]**. Todos ellos comparten HTML + JavaScript (librerías importantes **[jQuery][enlaceJQUERY]** y **[Knockout][enlaceKNOCKOUT]**).
> **Php:** es un lenguaje de programación para el lado der servidor utilizado para el desarrollo web de contenido dinámico *(fuente: Wikipedia)*.
  
> **J2EE:** *"Java Platform Enterprise Edition"* es una plataforma de programación para desarrollar y ejecutar software de aplicación en Java *(fuente: Wikipedia)*.  
  
> **ASPx:** es un framework para aplicaciones web de Microsoft. Utilizado para construir sitios web dinámicos, aplicaciones web y servicios web XML *(fuente: Wikipedia)*.  
  
> **Knockout:** es una implementación idependiente de JavaScript del modelo-vista-controlador (o MVC) con plantillas, es decir, es una librería para JavaScript que facilita crear interfaces de usuario con un modelo subyacente limpio *(fuente: Wikipedia)*.  

Con el tiempo se ha demostrado que el nivel de mantenimiento y de actualización es francamente complicado, sobre todo por el temido JavaScript. Actualmente el poco deseado JavaScript se ha vuelto imprescindible en todos nuestros **desarrollos Web**, el motivo principal es la intención de que toda aplicación web se parezca más a las aplicaciones de escritorio. Aquí entra el concepto de **[aplicación Web SPA][enlaceWEBSPA]**.  

Existen múltiples frameworks que facilitan obtener nuestas SPA, pero ninguna de ellas se obtienen mediante la programación en el servidor. Mientras que en la actualidad se comunican principalmente gracias a **[HttpRequest .Net][enlaceHTTPREQUEST]**.  

La elección del back-end la tenemos clara (al trabajar con ***.NET antes del 2004***), nos faltaría elegir con qué framework o librerías deberemos utilizar en el front-end para obtener nuesta SPA.  

###¿Qué front-end elegir?
En nuestro caso hemos visto [Angular.js][enlaceANGULAR] (con [Pedro Hurtado][enlacePEDROHURTADO]) y [React.js][enlaceREACT] (con [Eduard Tomás][enlaceEDUARD]), seleccionando finalmente **React.js**. ¿Qué ha motivado dicha elección? 
1. [Desconfianza][enlaceDESCONF] ya que la versión 2.0 de Angular.js:
	+ Es incompatible con la versión 1.0.
	+ No soporta navegadores recientes como Internet Explorer 10.
	+ Nuevo lenguaje de programación por encima de JavaScript.
	+ ***¡Es un nuevo framework construido desde cero!***.  

2. Curva de aprendizaje alta.

####Uso de Visuatl Studio + Reasct.js
En un principio podríamos haber utilizado [Reactjs.Net][enlaceREACTJSNET], pero queríamos aprovechar las sinergias del opensource y no tener ataduras en el front-end.  

[Link](https://example.org/ "title" target="_blank" onclick="window.open()"  
Enlace prueba 1 [Googgle.es](http://www.google.es target="_blank")  
Enlace de prueba [linkPRUEBA](http://www.cipfpbatoi.es "" target="_blank")

##Tecnologías utilizadas
+ Node.js versión 4.4.0 LTS
+ "npm" versión 2.14.20
+ Paquetes "npm": browserify, gulp, watchify, react-router, react.js, flux.
+ React 0.5.17
+ Visual Studio Community 2015

##Esquema del proyecto
1. **Node JS.**  
	+ [¿Qué es Node.js?](nodejs/1_what_is_node.md)  
	+ [Instalar Node.js](nodejs/2_install_nodejs.md)
	+ [Primer proyecto en Node.js](nodejs/3_first_proyect.md)
	+ [Instalar módulos en Node.js](nodejs/4_install_nodejs_modules.md)  

2. **Paquetes utilizados**
	+ [Browserify](nodejs_packages/browserify) 
	+ [Watchify](nodejs_packages/browserify)

3. **Gestor de paquetes para Nodejs: "npm"**.  

	+ [¿Qué es "npm"?](nodejs/what_is_node.md)  
	+ [Sintaxis en npm](npm/syntax.md)

4. **Visual Studio Express 2015**  

	+ [Instalar Node.js Tools en Visual Studio](visualStudio/pluginNodejs.md)  

##Referencias
+ [Documentación de Node.js](https://nodejs.org/dist/latest-v4.x/docs/api/)
+ [Obtener Visual Studio Express](https://www.visualstudio.com/es-es/features/node-js-vs.aspx)

<!-- Referencias y enlaces utilizados en el texto -->
[enlacePHP]:http://php.net/manual/es/index.php
[enlaceJ2EE]:http://www.oracle.com/technetwork/java/javaee/overview/index.html
[enlaceASPNET]:http://www.asp.net/
[enlaceJQUERY]:http://jquery.com/
[enlaceKNOCKOUT]:http://knockoutjs.com/
[enlaceWEBSPA]:http://www.campusmvp.es/recursos/post/Video-que-son-las-Single-Page-Applications.aspx
[enlaceHTTPREQUEST]:https://es.wikipedia.org/wiki/XMLHttpRequest
[enlaceANGULAR]:https://angularjs.org/
[enlacePEDROHURTADO]:https://es.linkedin.com/in/pedro-hurtado-4149782b
[enlaceREACT]:https://facebook.github.io/react/
[enlaceEDUARD]:https://es.linkedin.com/in/etomas/es
[enlaceDESCONF]:https://www.campusmvp.es/recursos/post/191%3bDebo-aprender-AngularJS-ahora-o-esperar-a-AngularJS-20.aspx
[enlaceREACTJSNET]:http://reactjs.net/
