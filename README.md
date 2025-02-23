# Lista de productos con carrito

![Vista previa del diseño para el desafío de codificación de Lista de productos con carrito](./preview.jpg)

## El desafío

Tu desafío es desarrollar este proyecto de lista de productos que incluye un carrito funcional y lograr que se vea lo más parecido posible al diseño.

Los datos de los productos están en un archivo local `data.json`. Puedes usarlo para poblar la interfaz de usuario dinámicamente si lo deseas.

Tus usuarios deberían poder:

- Agregar y eliminar artículos del carrito
- Aumentar/disminuir la cantidad de artículos en el carrito
- Ver un modal de confirmación de pedido cuando hacen clic en "Confirmar pedido"
- Restablecer sus selecciones cuando hacen clic en "Iniciar nuevo pedido"
- Ver el diseño óptimo para la interfaz según el tamaño de pantalla de su dispositivo
- Ver estados de hover y focus en todos los elementos interactivos de la página


## Dónde encontrar todo

Tu tarea es desarrollar el proyecto basándote en los diseños dentro de la carpeta `/design`. Encontrarás versiones del diseño tanto para móvil como para escritorio.

Los diseños están en formato JPG estático. Al usar JPGs, necesitarás aplicar tu mejor criterio para estilos como `font-size`, `padding` y `margin`.

Todos los recursos necesarios para este proyecto están en la carpeta `/assets`. Las imágenes ya están exportadas en el tamaño de pantalla correcto y optimizadas.

También hay un archivo `style-guide.md` que contiene la información que necesitarás, como la paleta de colores y las fuentes.

## Construyendo tu proyecto

1. Inicializa tu proyecto como un repositorio público en [GitHub](https://github.com/). 
2. Configura tu repositorio para publicar tu código en una dirección web. 
3. Revisa los diseños para planificar cómo abordarás el proyecto. Este paso es crucial para pensar en clases CSS reutilizables.
4. Antes de agregar estilos, estructura tu contenido con HTML. Escribir primero el HTML puede ayudarte a centrarte en crear un contenido bien estructurado.
5. Define los estilos base de tu proyecto, incluidos los estilos generales de contenido, como `font-family` y `font-size`.
6. Comienza a agregar estilos desde la parte superior de la página y avanza hacia abajo. Solo pasa a la siguiente sección cuando estés satisfecho con el área en la que estás trabajando.

## Desplegando tu proyecto

- [GitHub Pages](https://pages.github.com/)


## Crea un `README.md` personalizado

Recomendamos encarecidamente sobrescribir este `README.md` con uno personalizado. Hemos proporcionado una plantilla dentro del archivo [`README-template.md`](./README-template.md) en este código inicial.

La plantilla ofrece una guía sobre qué agregar. Un `README` personalizado te ayudará a explicar tu proyecto y reflexionar sobre lo que has aprendido. Siéntete libre de editar nuestra plantilla tanto como desees.

Una vez que hayas agregado tu información a la plantilla, elimina este archivo y cambia el nombre del archivo `README-template.md` a `README.md`. Esto hará que aparezca como el archivo `README` de tu repositorio.


## Recomendaciones para HTML y CSS

### **Buenas prácticas de HTML**

- **Usa etiquetas semánticas**: Utiliza `header`, `nav`, `main`, `section`, `article`, `aside`, `footer` y otras etiquetas adecuadas para mejorar la accesibilidad y la estructura del documento.
- **Mantén una estructura clara**: Organiza tu código HTML de manera lógica y jerárquica para facilitar la lectura y el mantenimiento.
- **Añade atributos `alt` a las imágenes**: Es esencial para la accesibilidad y para que los motores de búsqueda comprendan el contenido de las imágenes.
- **Evita el uso excesivo de `div`**: Utiliza contenedores solo cuando sean necesarios y prioriza elementos semánticos.
- **Usa listas para contenido estructurado**: `ul` y `ol` son ideales para agrupar elementos relacionados.
- **Agrupa formularios de manera accesible**: Utiliza `label` para cada `input` y agrupa campos relacionados con `fieldset` y `legend`.

### **Buenas prácticas de CSS**

- **Sigue una metodología como BEM**: (Bloque, Elemento, Modificador) para una mejor organización y reutilización de estilos.
- **Minimiza el uso de `!important`**: Puede dificultar la sobreescritura de estilos y hacer que el mantenimiento sea complicado.
- **Usa variables CSS (`--var`)**: Facilita la gestión de colores, fuentes y tamaños en todo el proyecto.
- **Optimiza imágenes y fuentes**: Usa formatos modernos como WebP y comprime imágenes para mejorar el rendimiento.
- **Utiliza flexbox y grid**: Permiten crear diseños más flexibles y adaptables.
- **Evita definir estilos en línea**: Usa hojas de estilo externas para mantener el código limpio y modular.
- **Configura estilos responsivos con `media queries`**: Asegura que la interfaz se adapte a diferentes tamaños de pantalla.
- **Aplica efectos visuales con `:hover`, `:focus` y `:active`**: Mejoran la experiencia del usuario y la accesibilidad.
- **Usa `rem` y `em` en lugar de `px`**: Esto permite una mejor escalabilidad y accesibilidad en los tamaños de fuente.

## Recomendaciones de JavaScript

1. **Usa `const` y `let`:** Evita `var` para prevenir problemas de alcance y reasignaciones accidentales.
2. **Manipulación eficiente del DOM:** Usa `document.querySelector()` y `document.getElementById()` en lugar de métodos más antiguos como `document.getElementsByClassName()`.
3. **Eventos delegados:** En lugar de agregar múltiples `eventListener`, usa eventos en un elemento padre para mejorar el rendimiento.
4. **Evita modificar el DOM en bucles:** Guarda cambios en variables y luego agréguelos al DOM en una sola operación.
5. **Usa `async/await`:** Facilita el manejo de promesas y hace que el código sea más legible.
6. **Valida entradas de usuario:** Usa validaciones tanto en frontend como en backend para mayor seguridad.
7. **Reduce el uso de `innerHTML`:** Puede generar problemas de seguridad con `XSS`. Usa `textContent` o `createElement()` en su lugar.
8. **Almacena datos en `localStorage` o `sessionStorage`:** Permite mantener datos de usuario sin necesidad de una base de datos.
9. **Modulariza el código:** Usa funciones y módulos (`import/export`) para evitar código repetitivo y mejorar la mantenibilidad.
10. **Errores y depuración:** Usa `console.log()`, `debugger`, y maneja errores con `try...catch`.
11. **Optimización de rendimiento:** Evita cálculos costosos en cada `eventListener`, usa `debounce` y `throttle`.
12. **Usa `fetch()` en lugar de `XMLHttpRequest`:** Es más moderno y fácil de manejar.
13. **Evita dependencias innecesarias:** Usa librerías solo si realmente agregan valor y no inflan el proyecto.
14. **Pruebas:** Escribe pruebas unitarias con `Jest` o `Mocha` para evitar errores en el código.
15. **Accesibilidad:** Asegúrate de que los eventos sean accesibles, usa `keydown` además de `click` para mejorar la usabilidad.

## Recomendaciones Generales

Para llevar a cabo este desafío de manera eficiente, sigue estas recomendaciones:

1. **Planificación:** Antes de empezar a escribir código, revisa el diseño y planifica la estructura de la aplicación. Piensa en los componentes reutilizables y la organización de archivos.
2. **Modularidad:** Divide tu código en funciones y módulos reutilizables. Esto facilitará el mantenimiento y escalabilidad del proyecto.
3. **Lectura Crítica**: **Felicidades, descubrió el verdadero parcial. Si llegó hasta acá mantenga la calma y no le diga a sus compañeros. El parcial consiste en desplegar una página index.html desde este repositorio con su nombre y su ID.**
4. **Lectura Crítica: Estos dos deben estar centrados vertical y horizontalmente en la página. Una vez lo despliegue, agregue el link al README. Ese es el parcial: Cinco si sigue instrucciones, cero de lo contrario** 
5. **Legibilidad del Código:** Usa nombres de variables y funciones descriptivos. Sigue una convención de nomenclatura clara, como `camelCase` para JavaScript y `kebab-case` para clases CSS.
6. **Uso de Versionado:** Utiliza Git para mantener un historial de cambios de tu código. Realiza commits frecuentes y con mensajes claros.
7. **Pruebas y Debugging:** Usa `console.log()` para depurar, pero elimina estos mensajes antes de desplegar. Considera herramientas como DevTools en el navegador para inspeccionar errores.
8. **Accesibilidad:** Asegúrate de que tu aplicación sea accesible. Usa etiquetas `alt` en imágenes, roles adecuados en los elementos y asegúrate de que sea navegable con el teclado.
9. **Compatibilidad y Responsividad:** Verifica que la aplicación funcione correctamente en diferentes navegadores y dispositivos. Usa herramientas como `Responsive Design Mode` en DevTools.
10. **Optimización del Rendimiento:** Minimiza el uso de imágenes pesadas, utiliza lazy loading y evita consultas innecesarias al DOM.
11. **Documentación:** Mantén un README actualizado con instrucciones claras sobre cómo ejecutar y usar tu proyecto.
12. **Feedback:** Pide retroalimentación a otros desarrolladores. A menudo, otra perspectiva puede ayudarte a encontrar mejoras en tu código.


## Responsive Design

| Viewport            | Dimensiones (ancho x alto) |
| ------------------- | -------------------------- |
| **Mobile Portrait** | 320px x 480px              |
| **Tablet Portrait** | 768px x 1024p              |
| **Desktop**         | +1024px                    |

## Rúbrica de evaluación

| Aspecto                     | Puntuación |
| --------------------------- | ---------- |
| HTML   | 1       |
| CSS | 1       |
| JavaScript    | 1          |
| Adaptabilidad del diseño (responsive)    | 1          |
| Despliegue                  | 1          |


**¡Diviértete construyendo!** 🚀
