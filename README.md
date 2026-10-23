# Parche Dev 2026

Sitio oficial del encuentro Parche Dev 2026, construido solo con HTML semántico.
Reto individual del Módulo 1 · HTML y CSS, RIWI.

Sitio publicado: https://vanemocz.github.io/parche-dev/

## Páginas

- Inicio
- Agenda
- Ponentes
- Inscripción y confirmación
- Código de conducta

## Cómo verlo en tu computador

1. Clona el repositorio.
2. Ábrelo en VS Code.
3. Abre index.html con Live Preview.

## Decisiones que tomé

- Tres decisiones que tome:
    - Listas `ul` o `ol` dependiendo de la necesidad que tuviera, si necesitaba que estuvieran enumeradas en orden o no.
    - El orden que le estaba dando al formulario, de que manera iba a ser la visual para el usuario.
    - En las tablas dependiendo si necesitaba unir filas o columnas use las etiquetas colspan y rowspan.
- Ticket 5:

1. ¿Qué aparece después del `?`?
Después del signo de interrogación `?` aparecen todos los datos del formulario (basados en el atributo `name` de cada elemento HTML), separados entre sí por el símbolos.

2. ¿Cómo se ven los espacios, las tildes y la arroba?
* La arroba (`@`): Se transforma en `%40`
* Los espacios: Se convierten en un signo de más `+` o en `%20`.
* Las tildes y caracteres especiales: Se codifican usando su equivalente en bytes UTF-8 precedidos por el símbolo `%`.

3. ¿Qué pasa con los campos que no se diligencian?
* Campos de texto, selectores o áreas de texto vacías: Se envían de todas formas, pero su valor queda vacío.
* Checkboxes y Radio Buttons no seleccionados: No se envían en absoluto. El navegador omite por completo su atributo `name` en la URL si el usuario no los marca.

4. ¿Por qué un formulario con contraseñas nunca debería usar `method="get"`?
Un formulario con contraseñas jamás debe usar `method="get"` por razones de seguridad. quedan totalmente expuestas visualmente, en el historial del navegador y registros en el servidor.

## Lo que aprendí

- Por seguridad para el formulario se deberia utilizar `method="post"`.
- La semantica en el HTML es importante para que la pagina sea entendible sin necesidad de usar CSS.
- El manejo de nav, tipos de listas, tablas, article, header, main, footer, section, button. Todos con sus caracteristicas. Tambien manejo de github para clonar el proyecto y realizar actualizaciones.

## Hecho por

Vanessa Montoya Cruz · [GitHub](https://github.com/vanemocz)