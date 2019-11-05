Ejercicio de evaluación final módulo 1 Cristina Ferrer Carballo. Grupo mañana. Promoción Hamilton.

Nos proponen un ejercicio de una página y se nos pide que por lo menos contenga lo sigiuiente:
Usar Sass.
Usar flexbox y CSS Grid.
Usar media queries.
Resolver algunas interacciones usando transiciones.
Con respecto a la maquetación:

1. El botón de hamburguesa (en la esquina superior izquierda) debe estar fijo en la parte superior de la
   pantalla y no debe desaparecer al hacer scroll.
2. Primer módulo (Anonymous proxy): debe estar maquetado con flexbox y debe ocupar el alto de la
   ventana del navegador.
3. Segundo módulo (Looking Through A Window): se puede maquetar usando las propiedades de CSS
   que se deseen.
4. Tercer módulo (3 Reasons To Purchase): los 3 elementos del listado deben estar maquetados con
   CSS Grid.
5. Cuarto módulo (footer): se debe maquetar usando flexbox.

   Tres interacciones:

6. El botón de flecha del módulo hero debe enlazar a la sección "3 Reasons To Purchase".
7. El botón de flecha del footer debe enlazar hasta el inicio de la página.
8. En el hover de los botones ("Go" y "3 Reasons To Purchase") se debe incluir una transición que
   dejamos a vuestra elección (en el color, tamaño, etc.).
9. BONUS: hacer una pequeña animación en el botón del footer.

A continuación expongo parte por parte como he considerado resolver el ejercicio:

He devidido en partials el index.html, en total:
4 partials.
header
main section
aside
footer

HEADER:
He incluido el icono hamburguesa, la foto de fondo, el texto con el título, el subtítulo y el botón.
AL contenedor header le he dado 3 elementos:

- Hamburguesa
- Texto (título + subtítulo)
- Botón

Utilizando el display Flex he podido colocar los elementos tal y como se solicitaba.
A la hamburguesa le he dado una posición fija.
El botón cumple su función de llevarte a otra parte de la página.

MAIN SECTION:
He utilizado la etiqueta MAIN ya que considero que es la sección principal de la página.
He utilizado el display Flex ya que era una opción más adecuada para este contenedor ya que contiene 4 elementos que se comportan de manera parecida.

ASIDE:
La siguiente sección le he dado una etiqueta ASIDE porque según tal y como entiendo la página esta parte es de importancia secundaria.
EN este caso el ejercicio solicitaba GRID y por lo tanto el display a toda la sección ha sido GRID.
He utilizado la opción de auto al grid template column y al grid template row ya que he podido ver que podía utilizar todo el espacio y después arreglar con paddings en cada una de las celdas.
A
FOOTER:
En el footer he utilizado display flex, el mayor reto ha sido cambiar a la opción tablet y ordenador ya que el orden cambiaba pero utilzando la opción ORDER que te permite flex he podido hacerlo.

Con respecto a los botones he utilizado en dos la etiqueta botón porque para centrar el contenido me resulta más eficiente.
