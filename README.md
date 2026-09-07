# Mi Primera Página

Este repositorio contiene mis primeros pasos con HTML, CSS y JavaScript, como parte del **Taller Introducción a Aplicaciones Web**.

## Parte Teórica

### 1. ¿Qué es HTML y cuál es su función en la web?
HTML (*HyperText Markup Language*) es el lenguaje de marcado utilizado para estructurar el contenido de las páginas web. Define elementos como títulos, párrafos, imágenes y enlaces, indicando al navegador cómo organizar y mostrar la información.

### 2. ¿Qué es una etiqueta HTML y cuáles son las más comunes?
Una etiqueta HTML es un elemento delimitado por `<` y `>` que le indica al navegador cómo interpretar una parte del contenido. Algunas de las más comunes son:
- `<h1>` a `<h6>`: encabezados
- `<p>`: párrafos
- `<a>`: enlaces
- `<img>`: imágenes
- `<div>` y `<span>`: contenedores
- `<ul>`, `<ol>`, `<li>`: listas
- `<button>`: botones

### 3. ¿Qué es un atributo de una etiqueta HTML y cuáles son los más comunes?
Un atributo es información adicional que se agrega dentro de la etiqueta de apertura para modificar su comportamiento o características. Algunos comunes son:
- `href`: URL de destino en un enlace
- `src`: ruta de un recurso (imagen, script)
- `alt`: texto alternativo de una imagen
- `class` e `id`: identificadores para CSS/JS
- `style`: estilos en línea

### 4. ¿Qué es CSS y cómo se utiliza para el diseño web?
CSS (*Cascading Style Sheets*) es el lenguaje que permite definir el estilo visual de una página HTML: colores, tipografías, tamaños, espaciados y disposición de los elementos. Se puede aplicar mediante un archivo externo enlazado con `<link>`, dentro de una etiqueta `<style>` o directamente en el atributo `style` de un elemento.

### 5. ¿Qué es una propiedad en CSS y cuáles son las más comunes?
Una propiedad es la característica de un elemento que se desea modificar (por ejemplo el color o el tamaño). Algunas comunes son:
- `color`
- `background-color`
- `font-size`
- `font-family`
- `text-align`
- `margin` y `padding`
- `border`

### 6. ¿Qué es un selector en CSS y qué tipos existen?
Un selector indica a qué elemento(s) HTML se le aplicarán las reglas de estilo. Tipos principales:
- **Selector de etiqueta**: `p { }`
- **Selector de clase**: `.mi-clase { }`
- **Selector de id**: `#mi-id { }`
- **Selector universal**: `* { }`
- **Selectores combinados/descendientes**: `div p { }`

### 7. ¿Qué es JavaScript y cómo añade interactividad a las páginas web?
JavaScript es un lenguaje de programación que se ejecuta en el navegador y permite modificar el contenido, responder a eventos del usuario (clics, teclas, formularios) y actualizar la página sin necesidad de recargarla, dando vida e interactividad a los sitios web.

### 8. ¿Cuáles son los tipos de datos primitivos en JavaScript?
- `String` (cadenas de texto)
- `Number` (números)
- `Boolean` (verdadero/falso)
- `Undefined`
- `Null`
- `BigInt`
- `Symbol`

### 9. ¿Cómo funcionan las estructuras de control de flujo como if, else, switch y bucles en JavaScript?
Las estructuras condicionales (`if`, `else if`, `else`, `switch`) permiten ejecutar distintos bloques de código según se cumpla o no una condición. Los bucles (`for`, `while`, `do...while`) permiten repetir un bloque de código mientras se cumpla una condición, recorriendo listas o repitiendo tareas.

### 10. ¿Por qué es importante usar nombres significativos para variables y métodos?
Porque hacen que el código sea más legible, fácil de mantener y de entender tanto para uno mismo como para otras personas que trabajen en el proyecto, reduciendo errores y el tiempo necesario para comprender qué hace cada parte del programa.

### 11. ¿Qué es una variable de entorno y por qué son importantes?
Una variable de entorno es un valor configurado fuera del código fuente (a nivel del sistema operativo o del entorno de ejecución) que puede ser utilizado por una aplicación, por ejemplo claves de API, rutas o configuraciones sensibles. Son importantes porque permiten separar la configuración de los datos sensibles del código, facilitando la seguridad y la portabilidad entre entornos (desarrollo, pruebas, producción).

### 12. ¿Qué son las herramientas de desarrollo de Chrome y cómo se accede a ellas?
Son un conjunto de utilidades integradas en el navegador Chrome que permiten inspeccionar, depurar y analizar páginas web. Se accede a ellas con la tecla `F12`, con `Ctrl + Shift + I` (o `Cmd + Option + I` en Mac), o haciendo clic derecho sobre la página y seleccionando "Inspeccionar".

### 13. ¿Qué se puede hacer en el panel "Elements" de las herramientas de desarrollo?
Permite ver y modificar en tiempo real el HTML y el CSS de la página, inspeccionar la estructura del DOM, probar cambios de estilo al instante y entender cómo están construidos los distintos elementos visuales.

### 14. ¿Cómo se utiliza el panel "Console" y para qué es útil?
El panel "Console" muestra mensajes generados por `console.log()`, errores y advertencias de JavaScript. También permite ejecutar código JavaScript directamente. Es útil para depurar errores y probar fragmentos de código rápidamente.

### 15. ¿Qué información se puede obtener del panel "Network" y por qué es importante?
Muestra todas las solicitudes de red que realiza la página (archivos, imágenes, peticiones a APIs), su tiempo de carga, tamaño y estado. Es importante para analizar el rendimiento de la página y detectar errores en la carga de recursos.

## Parte Práctica
La solución de la parte práctica se encuentra en los archivos:
- `index.html`
- `styles.css`
- `script.js`
