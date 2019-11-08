# Analista de Sistemas - Programacion Web I
## TP [NOTA 2] - Fecha de entrega: 8 de Noviembre

## Objetivos

Que el alumnx aplique las buenas prácticas vistas en clase y el correcto uso de la librería Bootstrap - herramienta de la práctica profesional https://getbootstrap.com/ - como plantilla para maquetar las versiones móvil-tablet-escritorio de un sitio web.

La temática del sitio es libre, pero tiene que ser un sitio como “Web Personal” (puede ser propio, de alguna celebridad, famoso o personaje de ficción) y su navegación del tipo “one page scroll” (la barra de navegación vincula a distintas áreas en un mismo documento).


## MODALIDAD

De carácter individual y obligatorio. Para la fecha de entrega el alumnx debe adjuntar a la tarea de classroom **[TP/NOTA 2] Web Personal en BS4**, un archivo comprimida (formato .zip ó .rar) con el nombre “comision_Nombre_Alumno” que contenga:

  -  [x] una carpeta “web-nombre_apellido” con los archivos correspondientes a resolver las consignas de TP.

  - [x] Crear un archivo INFO.txt con los datos del alumnx
    + nombre apellido,
    + carrera y comisión,
    + navegador que se usó para testear
    + y cantidad de horas aprox. dedicadas al trabajo práctico

---

#  Consignas TP

## Contenidos Finales (sin cuerpos de lorem ú otros textos ni imágenes de molde):

  * Redacción de textos coherentes

  * imágenes en formatos y resoluciones apropiadas

## Secciones obligatorias (son 5 en total):

* [x] Como inicio puede ser un diseño de portada con el título y texto introductorio correspondiente, tiene que entenderse sobre quién es el sitio.

* [x] Al menos 2(dos) secciones -pueden ser más- con información adicional. Tienen que ser coherentes a la temática del sitio, por ej: en el caso de su web personal “Formación Académica”, “Aficiones/Hobbies“, si se tratara de un músico podrían ser “Discografía”, “Premios y Reconocimientos”, etc.

* [x] En otra tiene que mostrarse una galería de fotos usando el sistema de grillas ó las card-columns (cada foto tiene que contar con una imagen de miniatura que al hacerle click enlace a una imagen de mayor resolución)
una sección con un formulario referido a la temática (ej: de contacto, ó suscripción, ó una encuesta, etc)

---

## Pauta Técnica

* La navegación del sitio será de tipo “one page scroll” (todas las secciones en un mismo documento), contando con el index.html como documento de inicio. 

* El documento html deberá ser válido según los estándares de la w3c para la especificación HTML5. https://validator.w3.org. 

* Se tiene que poder navegar a cada sección del documento desde un menú principal (se recomienda el componente navbar)

* Todo recurso gráfico debe quedar dentro de la carpeta “imagenes”, por ejemplo: las fotos de la galeria, el logo, aquellas que pueden ser contenido en un carrusel, es decir, las que se incrustan desde el html con la etiqueta <img>.

* El sitio tiene que ser responsive, su contenido tiene que adaptarse al área del viewport, estableciendo variaciones adecuadas para los contextos móvil-tablet-escritorio. Para ello, declarar la meta tag correspondiente, y vincular los recursos para trabajar con los estilos necesarios - sólo usando las clases disponibles en bootstrap:

    + Usar el sistema de grillas para la diagramación en columnas y sus variaciones en los distintos dispositivos.

    + Para esta entrega es importante trabajar desde el documento html con los nombres de clases y bloques html que ofrece la librería, hacer uso de las referencias en clase,  catálogos de consulta, y documentación oficial  https://getbootstrap.com/

    + Recuerda que se puede verificar con el emulador móvil del navegador (una de las opciones en el inspector de elementos Ctrl+Shift+I) ó redimensionando la ventana.

---

## PONDERACIÓN DE NOTA

* Incluir el favicon.ico.

* Recursos Gráficos optimizados para el contexto de adaptación, por ejemplo: si se implementa la etiqueta <picture>, considerar el set de imágenes necesario para los distintos contextos (movil y tablet con sus variantes para retina y escritorio).

* Uso (con criterio) de los nombres de clase y componentes interactivos que ofrece bootstrap, extendiendo los ejemplos de cursada (tienen los catálogos interactivos y atajos por extensión para alivianar la consulta a la documentación).
