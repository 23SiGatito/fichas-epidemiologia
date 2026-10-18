# Fichas de epidemiología

Formulario para completar, generar e imprimir la ficha de investigación de arbovirosis V.03 de C.S. Amarilis.

## Uso

Abre el sitio publicado con GitHub Pages. Completa las pantallas cortas y usa **Imprimir ficha** para revisar el documento, imprimirlo o descargarlo como PDF. El botón de datos ficticios permite probar el recorrido.

## Datos de personas

Los datos del formulario permanecen en la memoria del navegador. No se envían a GitHub, Supabase ni a un servidor. No se guardan en cookies, localStorage, IndexedDB ni bases de datos. Al recargar o cerrar la página se pierden. Los PDF descargados o impresos quedan bajo control del usuario.

El repositorio incluye únicamente código, bibliotecas, la ficha original vacía y sus coordenadas de llenado. No incluye casos ni fichas completadas. El alojamiento puede conservar registros técnicos de acceso a los archivos públicos; el formulario no transmite el contenido ingresado.

## Publicación

En **Settings → Pages**, elegir **Deploy from a branch**, rama **main**, carpeta **/(root)**. Cada actualización de esta rama se publica automáticamente. No se requiere una compilación ni secretos de despliegue.

## Desarrollo

El proyecto usa HTML, CSS y JavaScript sin dependencias de compilación. Para una vista local, sirve esta carpeta con un servidor HTTP estático. El editor de coordenadas anterior es independiente y no forma parte de este formulario.

- `ui.js`: preguntas, datos en memoria y componentes base.
- `compact.js`: pantallas adaptativas, fechas separadas y lógica condicional.
- `print.js`: vínculo entre los datos y las 259 posiciones del PDF.
- `assets/plantilla.json`: posiciones originales; la impresión usa su índice estable para resolver nombres repetidos de las marcas.
- `assets/ficha-dengue.pdf`: formato original sin datos.

## Alcance

Es una herramienta de transcripción y generación de documentos. No calcula diagnósticos ni notifica automáticamente casos. La clasificación se registra según lo indicado por el profesional responsable.
