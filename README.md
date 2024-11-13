https://github.com/Lopeez29/HtmlPractica1.git

# README - Estilos CSS para la Página Comparador de Artículos

Este README detalla los estilos CSS utilizados en la página de "Comparador de Artículos".
Cada sección y clase tiene una función específica para estructurar y dar estilo a los diferentes componentes de la página.
A continuación se explican los estilos implementados:
### Índice

- [Estilos Generales](#estilos-generales)
- [Estilos del Header](#estilos-del-header)
- [Estilos del Footer](#estilos-del-footer)
- [Estilos del Contenido Principal](#estilos-del-contenido-principal)
- [Estilos del Menú Izquierdo](#estilos-del-menú-izquierdo)
- [Estilos de Comparación de Artículos](#estilos-de-comparación-de-artículos)

* Selector Universal: Reinicia márgenes y padding predeterminados para un control total de los elementos y configura box-sizing a border-box para que padding y bordes no alteren el tamaño especificado.
* body, html Selector Combinado: Establece la altura completa para el cuerpo de la página.
  .main-container: Un contenedor principal que organiza todos los elementos con una estructura de columna y una altura mínima del 100% del viewport, asegurando que el footer esté al final de la página.
* .header: Estilo del encabezado, con distribución horizontal (flex) entre los elementos, color de fondo verde y espacio entre los elementos (gap).
* .nombresHeader: Contiene los nombres en el header con centrado y espacio entre ellos (gap)
* .imagenHeader: Un contenedor simulado para una imagen, con tamaño fijo y color de fondo azul, centrado de contenido, y un borde negro.
* .footer: Estilo para el pie de página, con fondo verde, centrado de contenido, y padding para separación del borde.
* .contenidoPagina: Contenedor para el contenido principal, con flex-grow para expandirse y ocupar el espacio vertical disponible.
* .textoPrincipal: Contenedor principal del texto con un estilo limpio, fondo azul claro y alineación centrada de los artículos.
* .menuIzq: Menú lateral izquierdo que ocupa el 20% del ancho de la pantalla y el 100% de la altura del viewport.
* .menu-item: Estilo de los botones del menú, con borde, fondo blanco y transición suave al cambiar de color al pasar el cursor.
* .comparador: Contenedor para los resultados de la comparación de artículos, con fondo beige claro, alineación centrada y altura completa.
* .articulos: Contenedor para cada artículo comparado, con espacio entre artículos (gap).
* .articulo: Estilo individual de cada artículo, con borde ligero y fondo blanco.
* #otros: Resalta el botón “Otros” del menú izquierdo en color rojo y cambia a gris al pasar el cursor.
