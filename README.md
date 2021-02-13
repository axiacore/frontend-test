# Prueba técnica frontend
Prueba técnica que se realiza a los candidatos al cargo de Frontend Developer.

### Objetivo
Realizar la maquetación (HTML y CSS) y realizar la funcionalidad de filtros en Javascript del siguiente prototipo

[Ver prototipo](https://www.figma.com/proto/iAtVRRkGIwqbbz2LGApCtY/Frontend-Test?node-id=73%3A303&viewport=-555%2C2051%2C1.1058835983276367&scaling=scale-down "Prototipo")

[Ver archivo de diseño](https://www.figma.com/file/iAtVRRkGIwqbbz2LGApCtY/Frontend-Test?node-id=0%3A1 "Archivo de diseño")

### Funcionamiento de filtros
Tener en cuenta los siguientes requerimientos para realizar la funcionalidad de los filtros:
* Al hacer clic en el botón de filtrar se despliega un modal con las opciones para filtrar
* Se pueden seleccionar varias opciones
* Al seleccionar una se activa el botón de limpiar y se muestra el número de opciones seleccionadas en el botón de filtrar
* Al hace clic en el botón de filtrar se cierra el modal y se muestran los productos que cumplen con los filtros seleccionados
* Al hacer clic en el botón de limpiar quita las opciones seleccionados del formulario de filtros y carga el listado con todas las opciones
* Son tres opciones de filtro: ```Rubia (id=1)```, ```Morena (id=2)``` y ```Roja (id=3)```

### Requisitos técnicos
* Usar sass para crear los estilos, compilar los archivos sass a css localmente y agregarlos al proyecto. (solo se revisan los archivos sass).
* El Js debe ser escrito en ES6. Y debe contruir una clase Js para el funcionamiento de los filtros. (No se debe usar ningún framework para Js como Jquery u otros)
* Para la construcción del listado de los productos usar el archivo ```products.json``` que esta en este repositorio, usando la libreria [Handlebars](https://handlebarsjs.com/ "Ir a Handlebars").
* Para usar librerias de terceros usar [CDNJS](https://cdnjs.com/ "Ir a CDNJS").
* Usar HTML5 y CSS3.
* Puede usar cualquier framework frontend para apoyarse en la maquetación.

### Responsive
El prototipo dado esta diseñado en mobile, a pesar de no tener la versión desktop debe ser responsive. Ej: en pantallas desktop el grid de productos puede cambiar a 4 columnas.

### Recursos
* En la carpeta ```img``` encuentra las imagenes de los productos.
* En la carpeta ```svg``` encuentra las iconos. 

### Bonus
Al realizar uno o todos los puntos siguientes son puntos extras al calificar el resultado de la prueba:
* Si se recarga la página y se tenian filtros aplicados, estos se deben de conservar.
