# AE6 | LND | Adrián Peña González

## Información general

El header se repite en todos los ficheros .html y tiene su propio fichero .css que contiene todo lo necesario para que funcione en cualquier fichero del proyecto.

También he utilizado un fichero *global.css* para aplicar *border-style: border-box;* en todos los ficheros, así como poner los márgenes a 0 o aplicar el estilo de los títulos de cada sección (excepto en el index, que no tiene dicho título).

Todos los botones de la web tienen funcionalidades *hover*.

## Index

Para ajustar la imagen de bienvenida he utilizado *object-fit: cover*;, que permite recortar la imagen y que se ajuste a los límites de la caja que la contiene. Además, tambien he utilizado *object-position:* para posicionar la imagen de forma correcta. 

La sección principal de la página está divida en dos cajas contiguas, en la de la izquierda encontramos el texto y el botón de compra, que lleva al fichero *tienda.html*, y en la izquierda las 3 imágenes que se pedían.

## Sobre nosotros

La sección principal está dividida en 2 cajas paralelas, una contiene la imagen y la otra el contenido de la sección.

Para ajustar la imagen he seguido el mismo procediminto que para la imagen del index, también he utilizado porcentajes en el *width* para que el tamaño de la imagen se reajuste dependiendo de las dimensiones de la ventana.

## Cursos

En este caso, para la sección principal tenemos 2 elementos posicionados uno encima del otro, y utilizamos los margenes (en el caso del texto), y *float* en el caso de las imagenes para posicionar el contenido de los elementos.

## Tienda

Para esta seccion he utilizado 4 cajas dentro de la sección principal. Estas cajas tienen *display: inline* para que se muestren una al lado de otra y contienen todo el contenido de cada elemento (la imagen, el titulo del producto, su precio y el botón para agregarlo al carrito).

## Contacto

Por último, esta sección también está dividida en dos cajas que se posicionan una al lado de la otra utilizando *float*. La parte izquierda contiene el texto, el e-mail y las redes sociales. Para las redes sociales utilizo una nueva caja que se posiciona de manera relativa, para poder posicionar las imágenes que contenga de forma relativa a dicha caja, y que las imágenes no se muevan respecto a sí mismas si se redimensiona la ventana.

Para el formulario he utilizado expresiones regulares en los campos e-mail y telefono, y además he cambiado el mensaje que se muestra si no se valida el campo. El campo TEMA es un menú desplegable, para el que he utilizado los atributos *selected* y *disabled* para simular un *placeholder*.


