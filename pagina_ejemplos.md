#Encabezado 1
##Encabezado 2
###Encabezado 3
####Encabezado 4
#####Encabezado 5
######Encabezado 6

Otros dos tipos de encabezados:

Encabezado1  
===  
Encabezado2  
---  

**negrita**  
__negrita__  
*cursiva*  
_cursiva_  
++subrayado++  
~~tachado~~  
==resaltado==  
^superíndice^  
~Subíndice~  

Imagen con propiedades CSS  
Podremos utilizar las propiedades "width", "height", "float" para situar la imagen y darle un tamaño:  
![imagen.png](http://img.youtube.com/vi/StTqXEQ2l-Y/0.jpg "imagen de prueba" "width:120px;clear:both")  

Para el logotipo de nuestra empresa o proyecto:  

![logo_aitex.png](logo_aitex.png "Logotipo de Aitex" "width:50px")  


IMAGEN+VIDEO EMBEBIDO  
[![Everything Is AWESOME](http://img.youtube.com/vi/StTqXEQ2l-Y/0.jpg)](https://www.youtube.com/watch?v=StTqXEQ2l-Y "Everything Is AWESOME")

@[Otro ejemplo](content-url 'stylesheets')
@[](http://www.youtube.com/watch?v=jo_B4LTHi3I)
@[](https://www.mozilla.org/es-ES/firefox/new/ 'width:300px')


- Elemento 1  
- Elemento 2  
- Elemento 3  
+ Elemento 4  
+ Elemento 5  


1. Elemento 1
2. Elemento 2
3. Elemento 3


1. Elemento A  
	- Otro elemento
	- segundo elemento
		- a
		- b
			+ otro
			+ otro más
		- c 	
1. 	Elemento B
		- elemento
			1. elemento	
			2. elemento

Lista de tareas
- [ ] Tarea 1
- [x] Tarea 2
	- [ ] Tarea a
	- [ ] Tarea b
- [ ] Tarea 3

Para enlaces:  
[batoi](http://www.cipfpbatoi.es)  
[yahoo][enlace1]
[enlace1]: http://www.yahoo.es    
Enlace a google <http://www.google.es>  

Código en una línea `> sudo apt-get update`  

Código en un bloque de línea  
podemos indicar el tipo de código: bash, c, cpp, cs, css, diff, http, html, ini, java, javascript, json, markdown, perl, php, python, ruby, sql, xml.  
```css
.container {
	display: none;
    color: blue;
}
```


Ecuaciones y fórmulas matemáticas, en bloque  
$$
\begin{aligned}
\dot{x} & = \sigma(y-x) \\
\dot{y} & = \rho x - y - xz \\
\dot{z} & = -\beta z + xy
\end{aligned} 
$$

Y en línea
$$$x=2$$$

$x^2$ or $$x^2$$


Tablas  
Pondremos los ":" para alinear el contenido de las columnas, podremos poner dentro de las columnas además del texto, imágenes, etc. Utilizaremos los "-" para separar la cabecera de la tabla de las celdas y con "|" delimitaremos dichas celdas.

| column A| column B |column C|
|:--------|:--------:|--------:|
|1234 | 1234|abcd |
|zxcv| bnm| qwer|

Disponemos de una página con un generador de tablas para "Markdown" en [Markdown Tables Generator][enlaceTablas]

[enlaceTablas]: (http://www.tablesgenerator.com/markdown_tables)



Tipos de separaciones  

Separación de página

***  
* * *  

Separación de sección

---  
- - -  


Tabla de contenidos, recoge los encabezados ya introducidos y los muestra, podemos usar [TOC] o [toc] además de poder indicarle propiedades CSS `[TOC "float:left"]`

[TOC]


Para comentarios utilizaremos `<!-- -->` para que no se muestre después en la ventana del navegador cuando se visualice la página.

Para el texto preformateado, pondremos delante de cada línea cuatro espacios:

    200 ml      Milk
    1 copa de	cocoa
    1 saco de	sugar


Para citas o blockquotes
> Esto es una cita
> >admite anidamiento también

Uso de diagramas:  

```
graph TD;
  A-->B;
  A-->D;
  B-->C;
  D-->C;
```

