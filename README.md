# Blockmaker Academy: Ejercicios de HTML

## Para Empezar

Primero, necesitaras clonar or descargar el repositorio.

```bash
git clone https://github.com/blockmaker-academy/html.git
```

### Para ejecutar el código HTML en Visual Studio Code con Live Server, sigue estos pasos:

1. En Visual Studio Code instala la extensión "Live Server" desde la pestaña de extensiones en el menú lateral izquierdo de Visual Studio Code.

2. Haz clic derecho en el archivo HTML que deseas ejecutar y selecciona "Abrir con Live Server".

3. El navegador se abrirá automáticamente y mostrará la página HTML en vivo. Si realizas cambios en el código HTML, la página se actualizará automáticamente en el navegador.

#### NOTA: Es importante tener en cuenta que la extensión Live Server solo funciona si tienes una conexión a Internet activa y permite la visualización de archivos locales en el navegador.

<hr/>

## Ejercicio 1: Etiquetas y Atributos

Crea un documento HTML con la estructura básica y añade los siguientes elementos:

- Un icono para la pestaña del navegador usando `<link>`.
- Un encabezado `<h1>` con el texto "Mi sitio web"
- Un párrafo `<p>` con el texto "Bienvenidos a mi sitio web"
- Una imagen `<img>` con un atributo `src` que apunte a una imagen de tu elección.

## Ejercicio 2: Enlaces

Crea dos nuevos documento HTML con la estructura básica, uno que sea index.html y otro sea contacto.html, y añade los siguientes elementos:

- En la página principal un enlace `<a>` que apunte a la página principal de Google (https://www.google.com).
- En la página un enlace `<a>` que apunte a una página interna de tu sitio web llamada "contacto.html". Añade el texto "Contacto" dentro del enlace.
- En la página contacto.html un enlace `<a>` que apunte a una página interna de tu sitio web llamada "index.html". Añade el texto "Inicio" dentro del enlace.

## Ejercicio 3: Listas

Crea un nuevo documento HTML con la estructura básica y añade los siguientes elementos:

- Una lista desordenada `<ul>` con tres elementos `<li>`. Añade el texto que desees a cada uno de ellos.
- Una lista ordenada `<ol>` con tres elementos `<li>`. Añade el texto que desees a cada uno de ellos.
- Una lista de definición `<dl>` con tres elementos `<dt>` y `<dd>`. Añade el texto que desees a cada uno de ellos.

## Ejercicio 4: Tablas

Crea un nuevo documento HTML con la estructura básica y añade una tabla `<table>` con tres filas `<tr>`, tres columnas de encabezado `<th>` y tres columnas de datos `<td>`. Añade el texto que desees a cada celda.

## Ejercicio 5: Formularios

Crea un nuevo documento HTML con la estructura básica y añade un formulario `<form>` con los siguientes campos:

- Un campo de texto `<input>` para el nombre con el atributo `name` establecido como "nombre".
- Un campo de texto `<input>` para el correo electrónico con el atributo `name` establecido como "email".
- Un campo de selección `<select>` para la edad con el atributo `name` establecido como "edad". Añade opciones para diferentes edades.
- Un campo de selección mediante input de tipo radio para el sexo con el atributo name establecido como "sexo". Añade opciones para seleccionar entre "Masculino", "Femenino" o "Otro".
- Un campo de contraseña `<input>` para la contraseña con el atributo `name` establecido como "contraseña".
- Un campo de confirmación de contraseña `<input>` para la confirmación de contraseña con el atributo `name` establecido como "confirmación de contraseña".
- Un botón `<input>` de tipo "submit" con el valor "Enviar".

## Ejercicio 6: Validación de formularios

Añade validación a los campos del formulario del ejercicio anterior utilizando atributos de html. Verifica que los campos de texto no estén vacíos y que la contraseña y la confirmación de contraseña tengan la misma longitud.

## Ejercicio Bonus: Crear un sitio web personal

Crea un sitio web personal utilizando los conocimientos de HTML que has aprendido. El sitio web debe incluir las siguientes páginas:

1. Inicio - La página de inicio debe incluir un encabezado `<h1>` con tu nombre y un párrafo `<p>` que te describa brevemente. También debe tener un enlace `<a>` a la página de contacto.

2. Proyectos - Crea una página para mostrar tus proyectos. Incluye una lista desordenada `<ul>` con al menos tres proyectos, cada uno con un título `<h2>`, una breve descripción `<p>` y un enlace `<a>` al proyecto en sí. Asegúrate de que los enlaces abran en una nueva pestaña del navegador utilizando el atributo target="\_blank".

3. Contacto - La página de contacto debe incluir un formulario `<form>` con los siguientes campos:

- Un campo de texto `<input>` para el nombre con el atributo name establecido como "nombre".
- Un campo de texto `<input>` para el correo electrónico con el atributo name establecido como "email".
- Un campo de selección `<select>` para el asunto con el atributo name establecido como "asunto". Añade opciones para diferentes asuntos.
- Un campo de texto grande `<textarea>` para el mensaje con el atributo name establecido como "mensaje".
- Un botón `<input>` de tipo "submit" con el valor "Enviar".

4. Acerca de mí - Crea una página para contarnos más sobre ti. Incluye una lista de definición `<dl>` con al menos tres elementos `<dt>` y `<dd>`. Utiliza los elementos `<dt>` para enumerar tus habilidades o intereses y los elementos `<dd>` para proporcionar más información sobre ellos.

5. Utiliza en cada pàgina estructura semantica correcta y añade un header y un footer para todas ellas.

6. Asegúrate de que todas las páginas tengan un icono para la pestaña del navegador usando `<link>` y que estén vinculadas entre sí mediante enlaces `<a>` en la parte superior o inferior de cada página.

¡Buena suerte y diviértete creando tu sitio web personal!

<hr/>

## Author

[Alex Muñoz](https://github.com/alexmf91)

## License

[MIT](https://choosealicense.com/licenses/mit/)
