### Parte del desarrollo de una web ecommerce de ordenadores con HTML, CSS y JavaScript
Todas la páginas contienen la misma barra de navegación y pie de página y están realizadas haciendo uso de Bootsrap 5 (para todas las páginas) y fontawesome (para iconos), JQuery y Sweetalert2 (para la página laptop-list.html)

### 1. Pantalla listado de ordenadores
 La página laptop-list.html representa una página donde el contenido principal será una tabla que muestre ordenadores. Cada fila de la tabla representa un ordenador, en cada columna de cada fila se mostrarán los campos del ordenador: id, imagen,modelo, fabricante, precio, ram (el descripción no lo incluimos en esta tabla).

### 2. Pantalla edición ordenador
La página lap-top-detail.html representa una página donde se puede crear o editar un ordenador, el contenido central será un formulario que permita rellenar los campos del ordenador: modelo, fabricante (selector con 4 o 5 opciones de fabricantes), precio, ram, descripción, imagen. Sólo hay un enlace a esta página desde el primer ordenador que aparece en la lista ya que los demás los cargaremos dinámicamente cuando avancemos en el curso

### 3. Pantalla vista ordenador
La página laptop-view representa una página donde visualizamos los datos de un ordendador al cual se ha llegado desde el listado de ordenadores haciendo click sobre su nombre, imagen o botón Ver. Aquí simplemente mostramos todos los datos del ordenador: id, modelo,fabricante (enlace a la pantalla fabricante), precio, ram, descripción, imagen. Usar el diseño y elementos html que se quiera.

### 4. Pantalla vista fabricante
la página manufacturer-view.html es similar a la de laptop-view pero con datos del fabricante.

### 5. Pantalla iniciar sesión
La página sign-in.html es una página con un formulario que solicita usuario y contraseña, con botón para iniciar sesión. No está conectada con backend por lo que no realiza ninguna acción, servirá para posteriores prácticas.

### 6. Pantalla registrarse:
La página sign-up.html es una página con un formulario que solicita los campos para registrar un usuario: nombre, apellido, email, teléfono y password, con botón para registrarse. No está conectada con backend por lo que no realiza ninguna acción, servirá para posteriores prácticas.

