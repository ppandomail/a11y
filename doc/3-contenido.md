# Contenido accesible

## Texto

* Usa palabras simples, evitando abreviaciones y tecnicismos.
* Sé inclusivo en el vocabulario es accesible sólo si escribes utilizando caracteres que pueden ser interpretados por lectores de pantalla, y por personas con algún tipo de discapacidad cognitiva o dislexia. Por ejemplo: ell@s, todxs, no son legibles.
  * Por ejemplo: en lugar de escribir los viajerxs o viajer@s, podrias escribir "las personas que viajan".
* Usa párrafos breves, separa por temas y utiliza viñetas.
* Se recomienda para los textos tipografía sans serif. Ejemplo: Arial.
* Tene en cuenta distintos dispositivos y tamaños de pantalla.
* Usa tamaños de texto grandes.
* El texto debe permitir hacer zoom hasta 200% sin superponerse y sin necesidad de hacer scrolling horizontal.
* Marca el idioma:

    ```html
    <html lang="es">
    </html>
    ```

## Imágenes

* Usa texto alternativo en las imágenes para que todos puedan comprender la información que transmite.

  * como equivalente funcional:

    ```html
    <img src="lupa.png" alt="buscar" />
    <img src="ejemplos/telefono.png" alt="llamar por teléfono"/>
    ```

  * imágenes decorativas, pueden marcarse como decorativas:

    ```html
    <img src="ejemplos/separador-decorativo.png" alt=""/>
    ```

## Multimedia

* El contenido de sólo audio debe tener transcripción.
* Los videos deben tener subtítulos (caption) que además de los diálogos incluyan una transcripción de los sonidos que aportan información.

    ```html
    <video  width="320" height="240">  
        <source type="video/mp4" src="/my_video_file.mp4" >   
        <track src="/captions_file.vtt" label="English" kind="captions" srclang="en-us" default >
        <track src="/French_captions_file.vtt" label="French" kind="subtitles" srclang="fr" >
    </video>
    ```

* Los videos (sin audio) deben tener una descripción auditiva o una transcripción.

## Tablas

* Con título de la tabla (tags:caption y summary)

## Formularios

* Situa las etiquetas antes de los campo de texto, área de texto y listas.
* Situa las etiquetas después de los botones de radio y las casillas de verificación.
* Utiliza las etiquetas "label" y "placeholder" en cada "input" ayudará a completar la información.
* Verifica que cada elemento tenga una etiqueta asociada utilizando "label", "for" e "id"

  ```html
    <label for="nombre">Nombre: </label>
    <input type="text" name="nombre" id="nombre" />
  ```

* Verifica que los campos obligatorios estén claramente indicados. Por ejemplo, no es correcto que estén indicados utilizando solamente color rojo. Un indicador claro puede ser un "*", indicando que los "campos marcados con asterisco son obligatorios".
* Verifica que las instrucciones para completar el formulario sean provistas en la parte superior del mismo y no al final. Esto incluye el formato de los datos que se espera que el usuario introduzca. Ejemplo: "Fecha de nacimiento (DD/MM/AAAA)".

* Verifica que los mensajes de error sean claros y guíen al usuario para entenderlos y solucionarlos.
* Verifica que los mensajes de error no sólo sean identificados por color.
* Verifica que los mensajes de error sean fácilmente localizables. Es mejor que los errores del formulario aparezcan en la parte superior, antes y no al final del mismo.
* Verifica que los campos sin error conserven los datos que el usuario ingresó correctamente, de modo que no tenga que completarlos nuevamente.
