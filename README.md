# Curso de CSS GridLayout Básico
Repostorio para el curso de CSS Grid Layout
## Introducción 
### ¿Qué es CSS Grid Layout?
Es una especificación de Css que nacio por la necesidad de hacer layouts más dinamicos. Introdujo un sistema de grilla, con columnas y filas, podemos jugar con las posiciones y como se alinean.
Ventas: Es mas sencillo cambiar lo elementos y crear layouts mas sencillamente.
### Conceptos para comenzar
* Contenedor: Es el elemento que se va a convertir en una grilla.
* Item: elementos que estaran dentro del contenedor se llamaran "Grid Items".
* Lineas: Son elementos que delimitan o dividen los elementos de una grilla, las tenemos vertical y se cuentan de arriba hacia abajo y horizontales que se cuentan de izquierda a derecha.
* Rows: Filas.
* Columsn: Columnas.
* Celda: Unidad minima dentro de la grilla. 
* Track: Grupo de celda en una misma fila o columna.
* Area: Grupo de celdas que estan en varias filas y/o columnas.
### Propiedades del contenedor
* `display: grid`  Convertir el contenedor en grid.
* `grid-template-columns: 100px 200px 300px` Nos permite especificar cuantas columnas y de que ancho, en este ejemplo tiene tres columnas de tres tamaños diferentes.
* `grid-template-rows: 150px 250px` Define cuantas filas y de que tamaño tendra la grilla. Esto es cuando sabemos cuando sabemos la cantidad de columnas que tendra la grilla en el ejemplo tiene 2 columnas de difente tamaño.
* `grid-auto-rows: 100px` Define el tamaño de cada fila que se cree. En este ejemplo cada fila que se cree sera de 100px;
* `grid-auto-columns: 100px` Define el tamaño de cada columna nueva que se cree. En este ejemplo sera de 100px;
> Siempre se llenan las columanas primero y las filas despues
* `grid-auto-flow: column` Modificamos como orden se llena nuestra grilla. En el ejemplo creara nuevos columnas de haber espacio. 
* `column-gap: 10px` Deja un espacio de 10px entre columnas.
* `row-gap: 10px` Deja un espacio de 10px entre filas.
* `gap: 10px` Deja un espacio entre filas y columnas.
### Propiedades de alineación
> Alinear el contenido de la grilla en el espacio.
* `justify-items: start|end|center|stretch` Alinear contenido dentro de la grilla de forma horizontal.
* `align-items: start|end|center|stretch` Alinear contenido dentro de la grilla de forma vertical.
* `place-items` Alinear el contenido de manera vertical y horizontal.
> Alinear el contenedor en el espacio
* `justify-content: start|end|center|stretch|space-around|space-between|space-evenly` Alinea la grilla como un bloque.
> Alineacion a los hijos de la grilla o Grid items
* `justify-self: start|end|center|stretch` Alinea una celda horizontalmente.
* `align-self: start|end|center|stretch` Alinea una celda verticalmete.
* `place-self` Alinea una celda vertical y horizontalmente.
