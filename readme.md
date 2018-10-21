# Maquetación - Front End B-learning

## Pre-maquetado de página Tía Tomate

PREMAQUETADO:

*Información entregada por el cliente*

- Desea mostrar la pasión que sienten por sus tomates.
- Dar énfasis a la compra de sus productos
- Mostrar el logo de la empresa

< Requerimientos Generales> 
	-La página tendrá una barra de navegacion con logo e items.
	-Un Footer con link a redes sociales
	-tendrá 4 secciones:
		- un header con un título principal
		- una sección de tipo blog para mostrar su producto
		- una seccion Nosotros; estará separado de un título y una descripción biográfica de los dueños. tambien habrá una foto de ellos.
		- la cuarta sección invitará a comprar el producto con un botón.

< Requerimientos Técnicos>
	-el icono de la empresa se ubicará en la barra de navegación y en el footer.
	-la barra de navegación será de color blanco para resaltar el logo de la empresa.
	-la sección tipo blog tendrá sistema de grillas con dos columas para agregar imagen y párrafo por separado.
	-la sección Nosotros, tendrá una imagen de la dueña, y a la derecha de la imagen habrá una breve biografía. Reperitemos esto con el segundo dueño. las imágenes de esta sección serán más pequeñas.
	-La sección para comprar el producto, sólo llevará un título acompañando un botón para comprar. esta sección llebará un background rojo en todo el ancho de la web para resaltar la sección.
	-Para la estructura HTML las secciones tendrán el sisguiente nombre de bloque.
		-navbar: para el bloque barra de navegación
		-header: para el bloque de cabecera
		-blog: para el bloque de los productos
		-features: para el bloque de nosotros
		-negocio: para el bloque de compra de producto
		-footer: para el bloque footer.

	-Utilizaremos Metodología BEM para la creación de clases, por ejemplo;
	<div class="navbar">
		<div class="navbar_logo"></div>
	</div>

< Requerimientos Visuales>
	-El layout utilizará Bootstrap.
	-Fuentes: utilizaremos google fonts.
		- para el título usaremos Raleway-bold,
		- para el parrafo utilizaremos Raleway extralight
	-Colores:
		-para el bacground de los titulos usaremos #e56353
		-para el blog utilizaremos #707070
		-para la seccion nosotros utilizaremos #fafafa


#Estructura del directorio:
	-Assets:
		-css
			-estilo.css
			-bootstrap.min.css
		-img
			-imagenes.jpg
		-fonts
		-colors
		-js
			-bootstrap.min.js
			-jquery.js
			-funciones.js
	-index.html
	-readme.md







