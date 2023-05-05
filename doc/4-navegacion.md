# Navegación accesible

* Redacta vínculos, títulos y botones descriptivos.
* Verifica que el título de la página exista y sea descriptivo del contenido.
  * Página 1     vs  Resultados Elecciones Argentina Noviembre 2021
  * Introducción vs  Introducción a la programación funcional  

    ```html
    <title>Accesibilidad Web: ¿Qué es?</title>
    ```

* Verifica que el contenido con movimiento o parpadeante dure más de 5 cinco segundos y pueda ser pausado, detenido u ocultado.
* Verifica que si existe contenido que se actualiza automáticamente, que este contenido pueda ser pausado, detenido u ocultado.
* Verifica que no exista contenido que destelle o parpadee más de 3 veces por segundo.

* Verifica la existencia de al menos un encabezado "h1"
* Verifica que la jerarquia de encabezados sea lógica y que no se salten niveles. La web debe seguir un orden lógico, no podes saltar de un título 1 a un título 3, ya que eso dificulta el uso de lectores de pantalla.

* Verifica que cualquier visitante puede entender el propósito del enlace al leerlo.
* Evita el "haz click aqui" además de no ser accesible para aquellos que navegan por teclado y lector de pantalla, tampoco es usable, dado que ya todos sabemos que un texto subrayado significa que es posible hacer click sobre él, en cambio sería usable si nos contara qué vamos a ver, o qué pasará si hacemos click en él.

    ```html
  <a href="glosario.php" target="_blank" title="Se abre en ventana nueva"> Glosario de términos de accesibilidad (PDF, 100KB)</a>
  ```inos de accesibilidad</a>
    ```

* Verifica que toda la funcionalidad de la página esté disponible navegando sólo con el teclado.
* Verifica que todos los elementos sean accesibles mediante la tecla "TAB"
* Verifica que los elementos de las listas desplegables sean navegables mediante las teclas "arriba", "abajo", "izquierda" y "derecha"
  
* Todos los elementos con los que el usuario interactúa deben recibir foco de teclado siguiendo el orden lógico de lectura (de arriba hacia abajo, izquierda a derecha).

* Verifica que cuando un elemento recibe foco debe ser visualmente distinguible (mediante bordes, subrayado o resaltado) para que el usuario distinga fácilmente donde se encuentra ubicado.

* Verifica que el foco nunca queda en un elemento sin que la tecla TAB permite avanzar al próximo elemento o retroceder al anterior.

* Verifica que el orden de tabulación sea el mismo que el orden lógico de lectura.

* Verifica que las imágenes que sean enlaces, tengan un foco visual y sean activables presionando la tecla ENTER.

* Los enlaces que permiten saltar al contenido principal ayudan a los usuarios que navegan con teclado y/o usan lector de pantallas para que no tengan que hacer excesivas pulsaciones u oir todo el contenido para llegar al contenido principal.

* Usa breadcrumbs.
