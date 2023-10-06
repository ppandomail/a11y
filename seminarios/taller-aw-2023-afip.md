# Presentación 2023

## F1 - Presentación

* Hola a todos, hoy vengo a hablar de AW, pero antes voy a presentarme.
* Mi nombre es Pablo Pandolfo trabajo en la sección Arquitectura de Componentes y soy gran defensor de la AW
* Me acompaña Luca, que les va a presentar una herramienta que venimos trabajando y permite encontrar errores de AW de acuerdo a la legislación vigente argentina.

## F2 - Nos presentamos

## F3 - Agenda

## F4 - Significado de "a11y"

* Vamos a hablar de Accesibilidad y una pregunta que me hice en su momento y que nos hacemos todos es que significa esa "a11y" que vemos cuando hablamos de Accesibilidad.
* Ese es el **acrónimo internacional de accesibilidad** porque hay 11 letras entre la "a" y la "y" de la palabra accesibilidad en ingles.
* También he visto usar **a11d** porque casualmente en español la palabra accesibilidad también hay 11 letras entre la "a" y la "d" final de la palabra accesibilidad.
* Voy a usarla varias veces dentro de la presentación.

## F5 - Problemas de accesibilidad en el mundo real

* ¿Por qué en el mundo real es tan obvio que estas 4 situaciones tienen un problema?
* Las 2 primeras imágenes vemos una rampa super empinada
* La 3ra. imagen es una rampa con al final escaleras
* La 4ta. imagen es una rampa completamente inútil y no se puede utilizar.
* Es tan obvio que en el mundo real esto es un problema pero cuando vamos al mundo virtual no lo podemos percibir tan claramente.

## F6 - Video

## F7 - Definición AW

* También llamada Accesibilidad Digital.
* Es la **práctica inclusiva de garantizar la accesibilidad a los sitios web**.
* Cuando hablamos de AW, hablamos de herramientas, de tecnologías web desarrolladas para personas con alguna discapacidad para que puedan **percibir, comprender, navegar, interactuar con la Web y contribuir con esa Web** (aportando a su vez contenidos)
* Es el **acceso universal a la Web**, independientemente del tipo de HW, SW, red, idioma, cultura, localización geográfica y capacidades de los usuarios.

## F8 - Problemas de accesibilidad web

* Les pongo un ejemplo.
* Están en una web favorita de comercio electrónico y quieren saber cuales han sido sus últimos pedidos. Entonces llaman al servicio técnico y una respuesta típica puede ser "Tienes que pulsar en el botón en la esquina superior derecha".
* O quieren cambiar el correo electrónico y no sabes como hacerlo, entonces pueden decirles  "Tienes que pulsar en el icono que tiene la forma de una rueda de motor".

## F9 - Problemas de accesibilidad web

* Pero para alguien ciego no hay esquina superior derecha, no hay un ícono que se parece a una rueda de motor.
* Todos tenemos que tener eso claro cuando desarrollemos nuestro sitios web.

## F10 - Estadísticas

* Les voy a dar un número rápido.
* En el año 2022 en el mundo éramos aproximadamente **7700 millones** de personas.
* Y más de **1300 millones** de personas viven con alguna forma de deficiencia visual.
* Es increíble que cuando creamos nuestros sitios web, cuando creamos nuestros negocios online queremos llegar a cuanto mas gente posible.
* Toda esta gente es nuestra audiencia también y eso tenemos que tenerlo presente.

## F11 - Pautas y Leyes a nivel mundial

* **W3C**: Consorcio World Wide Web, es la organización internacional que trabaja en el desarrollo de estándares web. Tiene como objetivo guiar la Web hacia su máximo potencial a través de desarrollo de protocolos y pautas que aseguren el crecimiento futuro de la Web.
* **WAI**: Iniciativa de AW, es el grupo de trabajo permanente para promover soluciones de AW. Desde **mayo de 1999** existen numerosas pautas que ayudan a los desarrolladores web a crear sitios web accesibles.
* **WCAG 2.0**: Son las Pautas de AW. Son consideradas como estándares internacionales de AW. En muchos países, la legislación sobre AW emplea las pautas como marco de referencia.

## F12 - WCAG 2.0

* Las pautas WCAG 2.0 están organizadas en **4 Principios, 12 pautas, 61 criterios y técnicas**. A su vez cada criterio tiene asociado un nivel de conformidad que puede ser A, AA o AAA.
* Los principios son:
  * **Perceptible**: imagenes con alt, videos con subtítulos.
  * **Operable**: elementos sean accesibles por teclado, tiempo suficiente para poder actuar.
  * **Comprensible**: asegurar de usar los tamaños tipográficos correctos, predecible (por ejemplo si se va hacer un cambio de una pantalla a otra, avisar al usuario que se lo va a sacar de contexto). Al completar un formulario: campos obligatorios y gestión de errores claros y no solo sean identificados por color.
  * **Robusto**: el contenido debe ser suficientemente robusto como para ser interpretado de forma fiable por una amplia variedad de aplicaciones de usuario, incluyendo los productos de apoyo.

## F13 - Legislación en Argentina

* **Ley 26653**: En Argentina, de acuerdo con la legislación vigente, todas las páginas web del Estado Nacional deben ser accesibles para las personas con discapacidad y por usuarios que posean diversas configuraciones en su equipamiento o en sus programas desde el 3 de noviembre de 2010.
* La **ONTI** es la autoridad de aplicación de la Ley.
* En setiembre de 2019 publicó la **Disposición ONTI 06/2019** que establece entre los puntos más importantes:
  * **Artículo 1:** Se aprueba las WCAG 2.0
  * **Artículo 2:** Se aprueba los criterios de conformidad de Nivel A y AA
  * **Artículo 3:** Ambos se encontrarán disponibles en el sitio web de la ONTI
  * **Artículo 4:** Puntuación: si alcanza 30 de los 38 criterios.

## F14 - Metodología de AW

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

## F15 - Testing de AW

* Ahora vamos a hablar de como testear los sitios web.
* Porque automatizar esos tests es una parte muy importante y además muy buena para liberar a nuestro equipo de testing de hacerlo todo manualmente.
* Pero esto NO es magia, esto no hace automáticamente a nuestros sitios web accesibles.
* También tenemos que tener en cuenta que sólo entre el 20% y el 50% de los errores de AW se pueden encontrar con tests automatizados.
* Y tenemos que tener presente también que estos tests automatizados forman parte de un gran proceso de testeo con el que testear manualmente es tan importante como hacerlo automatizadamente.

## F16 - Testeando con la Herramienta pa11y

* Pa11y proporciona un conjunto de herramientas gratuitas y de código abierto que ayuda a los desarrolladores y diseñadores a crear páginas web accesibles.
* Permite realizar pruebas de AW de manera automatizada.
* Toma como fuentes las WCAG 2.0 [HTML-CodeSniffer](https://squizlabs.github.io/HTML_CodeSniffer/)
* Requiere node.js
* Pa11y es una herramienta que podemos instalarla globalmente en nuestra máquina, mediante el comando:

  ```sh
  npm install -g pa11y
  ```

* O bien creando un proyecto con:

  ```sh
  mkdir prueba   # creamos el directorio
  npm init -y    # inicializamos el proyecto y se crea el archivo "package.json"
  ```

* y luego instalar el paquete pa11y en el proyecto con el comando:

  ```sh
  npm install pa11y
  ```

* Modificamos el archivo "package.json" y agregamos en script lo siguiente:

  ```json
    ...
    "scripts": {
    ...
    "start": "pa11y"
    }
    ...
  ```

* Podemos ejecutar el comando en la terminal seguido de la url del sitio web que queremos testear. Por ejemplo:

  ```sh
  npm start https://www.washington.edu/accesscomputing/AU/before.html
  ```

* Pa11y ejecuta pruebas de AW en las páginas web y nos devuelve los resultados
* Nos va a mostrar un reporte con los errores, con información de que principios de las WCAG estamos violando, cual es el elemento html que está provocando el error, pero no tenemos un link directo a ninguna documentación. En este caso es nuestro trabajo buscar cual es el error y como arreglarlo.

* El reporte lo podemos exportar a html, csv, json (por default es cli). Por ejemplo:

  ```sh
  # La opción "json" pasada al parámetro "--reporter" sobreescribe la opción de reporter predeterminada (CLI o línea de comandos). Luego indicando > reporte.json, le decimos a Pa11y que guarde el mensaje de salida o resultado en un archivo reporte.json
  npm start -- --reporter json https://www.washington.edu/accesscomputing/AU/before.html > reporte.json
  ```

* También podemos filtrar los criterios de AW según los niveles A, AA y AAA (por default es AA). Por ejemplo:

  ```sh
  npm start -- --standard WCAG2A https://www.washington.edu/accesscomputing/AU/before.html
  ```

* Observamos que de 38 errores se redujo a 34 errores.
* Otras opciones pueden ser las siguientes:

  ```sh
  # se excluyen los avisos y las advertencias, para que solo se vean los errores y poder enfocarnos en ellos.
  # "notice" informa sobre la accesibilidad de los elementos de la página web. No son críticos.
  # "warning" para que se preste atención a algo que vale la pena tomar en consideración, pero no son altamente criticos.
  # "error" son problemas críticos que deberán abordarse y solucionarse.
  npm start -- --ignore "warning;notice" URL 

  # permite hasta 10 errores en la página antes de que se considere que la página no pasó la prueba
  npm start -- --threshold 10 URL
  
  # útil si hay widgets de terceros como anuncios que no se puede controlar.
  npm start -- --hide-elements "#ads .sr-only [aria-role='presentation']" URL
  ```

* También podemos ejecutar el comando en una instancia de nuestra aplicación en nuestra máquina. No tenemos que subir nuestra aplicación a ningún servidor o a ningún entorno de desarrollo.
