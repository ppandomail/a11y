# Presentación 2023

## F1 - Presentación

* Hola a todos, hoy vengo a hablar de AW, pero antes voy a presentarme.
* Mi nombre es Pablo Pandolfo trabajo en la sección Arquitectura de Componentes y soy gran defensor de la AW, durante los últimos años me he dedicado a diseñar soluciones que ayudan al cumplimiento de los estándares de AW
* Me acompaña Luca, que les va a presentar una herramienta que venimos trabajando en la sección y permite encontrar errores de AW de acuerdo a la legislación vigente argentina.

## F2 - Agenda

* Esta presentación es una introducción a la AW. Veremos definiciones, normativas, metodologia de evaluación
* Al finalizar la presentación conocerán los principales problemas de AW que presentan las páginas web.
* También la herramienta que construímos que permite detectar esos problemas.

## F3 - Significado de "a11y"

* Vamos a hablar de Accesibilidad y una pregunta que me hice en su momento y que nos hacemos todos es que significa esa "a11y" que vemos cuando hablamos de Accesibilidad.
* Ese es el **acrónimo internacional de accesibilidad** porque hay 11 letras entre la "a" y la "y" de la palabra accesibilidad en ingles.
* También he visto usar **a11d** porque casualmente en español la palabra accesibilidad también hay 11 letras entre la "a" y la "d" final de la palabra accesibilidad.
* Voy a usarla varias veces dentro de la presentación.

## F4 - Problemas de accesibilidad en el mundo real

* Una señora llamada Shawn Lawton Henry, quien trabaja en la W3C WAI dijo: "Antes de comenzar con las pautas de AW, antes de estudiar los resultados de las herramientas de evaluación, es necesario primero comprender los problemas"
* "Vamus lá..."
* ¿Por qué en el mundo real es tan obvio que estas 4 situaciones tienen un problema?
* Las 2 primeras imágenes vemos una rampa super empinada
* La 3ra. imagen es una rampa con al final escaleras
* La 4ta. imagen es una rampa completamente inútil y no se puede utilizar.
* Es tan obvio que en el mundo real esto es un problema pero cuando vamos al mundo virtual no lo podemos percibir tan claramente.

## F5 - Definición AW

* Todos nosotros difícilmente podemos concebir nuestras vidas sin la Web.
  * La Web nos permite acceder a las noticias de cualquier parte del mundo.
  * La Web nos permite comunicarnos con personas de cualquier parte del mundo a través del correo electrónico, el chat o incluso mediante videoconferencia.
  * La Web nos permite comprar casi cualquier producto y recibirlo a los pocos días en casa.
  * La Web nos ofrece infinitas posibilidades de entretenimiento.
  * Y todo ello de forma instantánea, muchas veces de forma gratuita, a cualquier hora del día y desde cualquier sitio en el que exista una conexión a Internet.

* Para las personas, Internet y la Web han supuesto un gran avance.
* Por ejemplo, antes de la Web, ¿cómo leían los diarios las personas ciegas o las personas con discapacidad motora?
* Sin embargo, a pesar del gran potencial que supone la Web para las personas con discapacidad, este potencial está aún en gran medida desaprovechado.
* Por ejemplo, en algunos sitios sólo se puede navegar con el mouse por lo que las personas ciegas o las personas con discapacidad motora no lo pueden usar correctamente.
* En otros sitios web el contenido multimedia como los videos no ha sido subtitulado para las personas sordas.
* La AW tiene como objetivo lograr que las páginas web sean utilizables por el máximo número de personas.

* AW -> también llamada Accesibilidad Digital.
* Es la **práctica inclusiva de garantizar la accesibilidad a los sitios web**.
* Cuando hablamos de AW, hablamos de herramientas, de tecnologías web desarrolladas para personas con alguna discapacidad para que puedan **percibir, comprender, navegar, interactuar con la Web y contribuir con esa Web** (aportando a su vez contenidos)
* Es el **acceso universal a la Web**, independientemente del tipo de HW, SW, red, idioma, cultura, localización geográfica y capacidades de los usuarios:
  * Personas con discapacidad
  * Adultos mayores
  * Personas con necesidades específicas (temporal, por ejemplo una fractura, que dificulte usar las manos)
  * Personas con bajo nivel de alfabetización o que no dominan el idioma
  * Barreras del entorno: ruido (no permite al usuario oir el audio de un video), iluminación (dificulta la lectura), conexión a internet limitada (no permite acceder a contenido con imágenes o videos), etc.

## F6 - Problemas de accesibilidad web

* Les pongo un ejemplo...
* Están en una web favorita de comercio electrónico y quieren saber cuales han sido sus últimos pedidos. Entonces llaman al servicio técnico y una respuesta típica puede ser "Tiene que pulsar en el botón en la esquina superior derecha".
* O quieren cambiar el correo electrónico y no sabes como hacerlo, entonces pueden decirles  "Tiene que pulsar en el icono que tiene la forma de una rueda de motor".

## F7 - Problemas de accesibilidad web

* Pero para alguien ciego no hay esquina superior derecha, no hay un ícono que se parece a una rueda de motor.
* Todos tenemos que tener eso claro cuando desarrollemos nuestro sitios web.

* Ofrecer alternativas:
  * No sólo imágenes o colores, también textuales.
  * No sólo interacción con el mouse, también con el teclado.
* Es decir, diferentes presentaciones que se adapten a las necesidades de diferentes usuarios.
* Crear páginas que se transformen correctamente, páginas web que se puedan visualizar correctamente en diferentes dispositivos, diferentes colores, diferentes tamaños de letra.

## F8 - Estadísticas

* Les voy a dar un número rápido.
* En el año 2022 en el mundo éramos aproximadamente **7700 millones** de personas.
* Y más de **1300 millones** de personas viven con alguna forma de deficiencia visual.
* Es increíble que cuando creamos nuestros sitios web, cuando creamos nuestros negocios online queremos llegar a cuanto mas gente posible.
* Toda esta gente es nuestra audiencia también y eso tenemos que tenerlo presente.

## F9 - Pautas y Leyes a nivel mundial

* **W3C**:
  * Consorcio World Wide Web, es la organización internacional que trabaja en el desarrollo de estándares web.
  * Tiene como objetivo guiar la Web hacia su máximo potencial a través de desarrollo de protocolos y pautas que aseguren el crecimiento futuro de la Web.
  * Recibe el apoyo de los principales actores de la industria y los gobiernos del mundo.
* **WAI**:
  * Iniciativa de AW, es el grupo de trabajo permanente para promover soluciones de AW.
  * Desde **mayo de 1999** existen numerosas pautas que ayudan a los desarrolladores web a crear sitios web accesibles.
* **WCAG 2.0**:
  * Son las Pautas de AW.
  * Son consideradas como estándares internacionales de AW. En muchos países, la legislación sobre AW emplea las pautas del W3C como marco de referencia.

## F10 - WCAG 2.0

* Las pautas WCAG 2.0 están organizadas en **4 Principios, 12 pautas, 61 criterios de conformidad y técnicas suficientes y recomendables**. A su vez cada criterio tiene asociado un nivel de conformidad que puede ser A (básicos), AA (intermedios) o AAA (avanzados).
* Los principios son:
  * **1. Perceptible**: la información y los componentes de la interfaz de usuario deben presentarse a los usuarios de la manera en que puedan percibirlos.
  * **2. Operable**: los componentes de la interfaz de usuario y la navegación deben ser operables.
  * **3. Comprensible**: la información y el manejo de la interfaz de usuario deben ser comprensibles
  * **4. Robusto**: el contenido debe ser suficientemente robusto como para ser interpretado de forma fiable por una amplia variedad de aplicaciones de usuario, incluyendo los productos de apoyo.

## F11 - WCAG 2.0 "Perceptible"

* [1.1.1] Usar CAPTCHA con dos modalidades sensoriales diferentes: visuales (palabras distorsionadas), auditivas (pronuncian la palabra que hay que reconocer sobre un ruido de fondo), lógicas (se realiza una pregunta lógica, por ejemplo cuanto es 2+2)
* [1.1.1] Usar imágenes con texto alternativo:
  * Las imágenes decorativas (no transmiten información importante) es obligatorio incluir el atributo "alt" vacio
  * Las imágenes necesarias (transmiten información relevante) atributo "alt" con texto que describa la imagen en forma apropiada. No debe ser superior a 150 caracteres.
* [1.2.2] Audios y Videos con transcripciones y subtítulos.
* [1.4.2] Si el audio de una página suena automáticamente durante más de 3 segundos, se debe proporcionar un mecanismo para pausar o detener el audio. O controlar el volumen de sonido que es independiente del nivel de volumen global del sistema.
* [1.4.3] Usar tamaños de texto grandes y colores con mucho contraste para que sean legibles. Herramienta: Color Contrast Checker

## F12 - WCAG 2.0 "Operable"

* [2.4.2] Las páginas web tienen títulos que describen su temática o propósito.  Si la página no tiene título. el lector de pantalla anunciaría "Página 1", lo cual no dice mucho.
* [1.3.1] Navegar a través de los encabezados (H1-H6) de una página. Usándolos para marcar la estructura. Anidarlos de forma correcta, es decir, por ejemplo no pasar de H1 a H3. Tampoco pueden existir encabezados que no contengan contenidos.
* [2.4.4] Redactar textos de vinculos, títulos y botones  descriptivos. (Ejemplos de textos no descriptivos: Pinche aquí, Leer mas, ver otros, Descargar, etc.)
* [2.1.1] Diseñar para operar utilizando sólo el teclado o sólo el habla, alternativamente al  mouse o a la pantalla táctil.
* [2.4.3] Todos los elementos con los que el usuario interactúa deben recibir foco de teclado siguiendo el orden lógico de lectura (de arriba hacia abajo, izquierda a derecha). Cuando un elemento recibe foco debe ser visualmente distinguible (bordes marcados / con fondo de color) para que el usuario distinga fácilmente donde se encuentra ubicado y no se desoriente.
* [2.2.1] Tiempo suficiente para leer y usar el contenido. Se advierte al usuario antes de que el tiempo expire y se le conceden al menos 20 segundos para extender el límite temporal con una acción simple (por ejemplo, "presione la barra de espacio") y el usuario puede extender ese límite de tiempo al menos diez veces.  Excepción de tiempo real (por ejemplo, una subasta). Excepción por ser esencial: El límite de tiempo es esencial y, si se extendiera, invalidaría la actividad
* [2.3.1] No diseñar contenido de un modo que se sepa podria provocar ataques, espamos o convulsiones, por ejemplo: las página web no deberian contener nada que destelle más de 3 veces en un 1 segundo.
  * **Dato de color**: En 1997, una caricatura en la televisión de Japón, el capítulo nro. 38 de Pokémon Soldado Porygon, se ve como pikachu hace un atactrueno representado por una alternancia de luces rojas y azules proyectado en 54 planos en apenas 5 segundos, provocando convulsiones a mas de 700 niños que tuvieron que ser hospitalizados.
  
## F13 - WCAG 2.0 "Comprensible"

* Usar palabras simples y párrafos breves, separar por temas y utilizar viñetas.
* Diseñar para una lectura simple y lineal que tenga en cuenta diferentes dispositivos y tamaños de pantalla. El texto debe permitir hacer zoom hasta 200% sin superponerse y sin necesidad de hacer scrolling horizontal.
* [3.2] Diseñar formularios:
  * a una columna
  * con etiquetas: Etiquetas antes de los campos textarea, select e input de tipo texto, file, password. Etiquetas después de los campos input de tipo radio y checkbox
  * Identificar campos obligatorios, informando formato requerido y [1.4.1] y no identificar sólo por color
  * [3.3.1] Gestión de errores claros y no solo sean identificados por color: informando mediante texto, al comienzo del formulario de los errores existentes. Describiendo el problema e identificando los campos con error.

## F14 - Legislación en Argentina

* **Ley 26653**: En Argentina, de acuerdo con la legislación vigente, todas las páginas web del Estado Nacional deben ser accesibles para las personas con discapacidad y por usuarios que posean diversas configuraciones en su equipamiento o en sus programas desde el 3 de noviembre de 2010.
* Desgraciadamente en Argentina aun no se ha impuesto ninguna sanción en cuanto a AW.
* La **ONTI** es la autoridad de aplicación de la Ley.
* En setiembre de 2019 publicó la **Disposición ONTI 06/2019** que establece entre los puntos más importantes:
  * **Artículo 1:** Se aprueba las WCAG 2.0
  * **Artículo 2:** Se aprueba los criterios de conformidad de Nivel A y AA
  * **Artículo 3:** Ambos se encontrarán disponibles en el sitio web de la ONTI
  * **Artículo 4:** Puntuación: si alcanza 30 de los 38 criterios.

## F15 - Metodología de AW

* Metodología para evaluar la accesibilidad de un sitio web.
* Permite descubrir las posibles barreras o errores de accesibilidad que deben ser corregidos. La misma involucra 6 pasos:

1. **Definir el alcance de la evaluación**:
    1. Definir **que se va a evaluar**: página web, sitio web, proceso completo.
    1. Definir cuál va a ser el **nivel de conformidad** (A, AA, AAA) que se va a evaluar.
    1. Definir el listado de navegadores web, productos de apoyo u otros agentes de usuario con los que deben ser compatibles
1. **Explorar el sitio a evaluar**: permite comprender mejor el uso, propósito y funcionalidad del sitio:
    1. Identificar las páginas relevantes
    1. Identificar las funcionalidades claves del sitio
    1. Identificar los diferentes tipos de páginas
1. **Seleccionar una muestra representativa**
    1. Incluir una muestra estructurada de las páginas que se identificaron en el Paso 2: mas visitadas, funcionalidades esenciales.
    1. Incluir procesos completos en la muestra: se tienen que evaluar todas las páginas del proceso (por ejemplo, login + acceso al servicio + flujo)
1. **Evaluar la muestra seleccionada**: verificar por cada página de la muestra si cumple con los criterios de conformidad de WCAG 2.0 que se van a evaluar
1. **Registrar los resultados de la evaluación**: Se deben documentar:
    1. nombre del evaluador, solicitante, fecha
    1. alcance, muestra y resultados
1. **Corregir errores y reevaluar los pasos anteriores**: Una vez obtenido el informe con el resultado de evaluación automática y manual, se debe proceder a la corrección de los errores. Finalizada la corrección, deberán volver a ejecutarse las mismas herramientas sobre las mismas páginas para corroborar que los errores se solucionaron. Estos son los pasos: 4 y 5.

## F16 - Testing de AW

* Ahora vamos a hablar de como testear los sitios web.
* Porque automatizar esos tests es una parte muy importante y además muy buena para liberar a nuestro equipo de testing de hacerlo todo manualmente.
* Pero esto NO es magia, esto no hace automáticamente a nuestros sitios web accesibles.
* También tenemos que tener en cuenta que sólo entre el 20% y el 50% de los errores de AW se pueden encontrar con tests automatizados.
* Y tenemos que tener presente también que estos tests automatizados forman parte de un gran proceso de testeo con el que testear manualmente es tan importante como hacerlo automatizadamente.

## F17 - Testeando con la Herramienta pa11y

* Pa11y proporciona un conjunto de herramientas gratuitas y de código abierto que ayuda a los desarrolladores y diseñadores a crear páginas web accesibles.
* Permite realizar pruebas de AW de manera automatizada.
* Toma como fuentes las WCAG 2.0 [HTML-CodeSniffer](https://squizlabs.github.io/HTML_CodeSniffer/)
* Requiere node.js
* Pa11y es una herramienta que podemos instalarla globalmente en nuestra máquina, mediante el comando:

  ```sh
  npm install -g pa11y
  ```

* Pa11y ejecuta pruebas de AW en las páginas web y nos devuelve los resultados
* Nos va a mostrar un reporte con los errores, con información de que principios de las WCAG estamos violando, cual es el elemento html que está provocando el error, pero no tenemos un link directo a ninguna documentación. En este caso es nuestro trabajo buscar cual es el error y como arreglarlo.
