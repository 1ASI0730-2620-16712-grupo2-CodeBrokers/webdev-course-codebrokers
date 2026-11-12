# Fundamentos de Desarrollo Web

## Resumen del curso
Curso de aproximadamente 60 minutos para estudiantes de secundaria (12 a 17 años) sin experiencia previa. No requiere instalaciones; se usa CodePen en el navegador.

**Duración:** 60 minutos  
**Repositorio:** [webdev-course-codebrokers](https://github.com/1ASI0730-2620-16712-grupo2-CodeBrokers/webdev-course-codebrokers)  
**Lista de reproducción (todas las lecciones):** [Ver en YouTube](https://www.youtube.com/playlist?list=PLBOlMzt5HmbA)  
## Secuencia de lecciones

### Lección 01: Introducción al desarrollo web (10 minutos)

- **Descripción:** Explica qué es una página web, cómo el navegador muestra su contenido y qué papel cumplen HTML (el contenido) y CSS (el estilo). Presenta CodePen como editor en línea y escribe las primeras líneas de código.
- **Video no listado:** [Ver la lección](https://youtu.be/eXcOFFXNIks)
- **Práctica precargada:** [Abrir práctica en CodePen](https://codepen.io/Harold-11/pen/QwpYPYN)
- **Consejos clave:** HTML define el contenido de la página y CSS su apariencia. En CodePen, el resultado se actualiza al escribir, sin instalar nada. Observa la vista previa después de cada cambio.
- **Actividad práctica:** Cambia el título y el párrafo por tu propio tema favorito y prueba otro color para el título.
- **Código inicial:** `starter-files/01-introduccion/`
- **Código completado:** `completed-examples/01-introduccion/`

### Lección 02: Introducción a HTML (11 minutos)

- **Descripción:** Presenta las etiquetas HTML y su estructura de apertura y cierre. Crea una primera página con un título principal (`h1`), subtítulos (`h2`) y párrafos (`p`).
- **Video no listado:** [Ver la lección](https://youtu.be/_y3fC_iGIXs)
- **Práctica precargada:** [Abrir práctica en CodePen](https://codepen.io/Harold-11/pen/pveGBGN)
- **Consejos clave:** Cada etiqueta se abre con `<etiqueta>` y se cierra con `</etiqueta>`. Usa un solo `h1` para el título principal y `h2` para las secciones. Escribe cada párrafo dentro de su propio `p`.
- **Actividad práctica:** Cambia el título, agrega una sección nueva con un `h2` y escribe dos párrafos sobre ti.

### Lección 03: Listas, imágenes y enlaces (10 minutos)

- **Descripción:** Aprende a organizar contenido mediante listas, insertar imágenes con descripciones alternativas y crear enlaces a otras páginas. La lección incluye una demostración en CodePen y un reto para personalizar una página de perfil.
- **Video no listado:** [Ver la lección](https://youtu.be/J6KQvsXZelI)
- **Práctica precargada:** [Abrir práctica en CodePen](https://codepen.io/Harold-11/pen/ZYewZwy)
- **Consejos clave:** Utiliza `ul` para listas sin numeración, `ol` para listas numeradas y `li` para sus elementos. Inserta imágenes con `img`, indicando su dirección en `src` y una descripción alternativa en `alt`. Crea enlaces con `a` y define su destino mediante `href`.
- **Actividad práctica:** Personaliza tres pasatiempos, modifica el texto de un enlace y revisa la descripción alternativa de la imagen.
- **Código inicial:** `starter-files/03-elementos-html/`
- **Código completado:** `completed-examples/03-elementos-html/`

### Lección 04: Colores y tipografías (10 minutos)

- **Descripción:** Introduce CSS como el lenguaje que define la apariencia de una página. Explica la estructura de una regla (selector, propiedad y valor) y aplica color de fondo, color de texto, tipo de letra y tamaño del título. La lección incluye una demostración en CodePen y un reto para personalizar la página.
- **Video no listado:** [Ver la lección](https://youtu.be/gtJtEZPMuBE)
- **Práctica precargada:** [Abrir práctica en CodePen](https://codepen.io/Harold-11/pen/rayPbPG)
- **Consejos clave:** Toda regla CSS tiene selector, propiedad y valor, y cada declaración termina en punto y coma. Usa `background-color` para el fondo, `color` para el texto, `font-family` para el tipo de letra y `font-size` para el tamaño. Cuida el contraste entre el texto y el fondo.
- **Actividad práctica:** Elige un color de fondo y de texto con buen contraste, prueba otra fuente sencilla y cambia el tamaño del título.
- **Código inicial:** `starter-files/04-css-basico/`
- **Código completado:** `completed-examples/04-css-basico/`

### Lección 05: Centrado, espacios y bordes (10 minutos)

- **Descripción:** Presenta el modelo de caja de CSS: `padding` (espacio interior), `border` (contorno) y `margin` (espacio exterior). Agrupa el contenido en una tarjeta, limita su ancho con `max-width`, la centra con `margin: auto` y redondea sus esquinas con `border-radius`. La lección incluye una demostración en CodePen y un reto para personalizar la tarjeta.
- **Video no listado:** [Ver la lección](https://youtu.be/Z188cCXJOPA)
- **Práctica precargada:** [Abrir práctica en CodePen](https://codepen.io/Harold-11/pen/myWoEap)
- **Consejos clave:** `padding` es el espacio dentro de la caja, `border` su contorno y `margin` el espacio fuera de ella. Con `max-width` y `margin: 30px auto` un bloque queda centrado. Si el estilo no se aplica, revisa que el nombre de la clase coincida entre HTML y CSS y que el selector empiece con punto (`.tarjeta`).
- **Actividad práctica:** Cambia el color y grosor del borde, el redondeo de las esquinas y el espacio interno de la tarjeta.
- **Código inicial:** `starter-files/05-diseno-css/`
- **Código completado:** `completed-examples/05-diseno-css/`

### Lección 06: Proyecto final y errores comunes (13 minutos)

- **Descripción:** Integra todo lo aprendido para completar una página de perfil: un saludo con una frase de presentación, subtítulos con color, un enlace convertido en botón y un pie de página. Luego muestra, provocándolos a propósito, los tres errores más comunes de principiantes y cómo corregirlos, y cierra con recomendaciones para seguir aprendiendo.
- **Video no listado:** [Ver la lección](https://youtu.be/8U8XC7L6cr8)
- **Práctica precargada:** [Abrir práctica en CodePen](https://codepen.io/Harold-11/pen/bNqzZQQ)
- **Consejos clave:** Usa clases (`class` en HTML y `.nombre` en CSS) para dar estilo solo a los elementos que quieras. Cierra cada etiqueta que abres, revisa letra por letra los atributos como `src` y `href`, y verifica que cada `{` tenga su `}` en CSS. Prueba cada cambio apenas lo haces. Para seguir aprendiendo, consulta MDN y valida tu HTML en el validador del W3C.
- **Actividad práctica:** Crea un perfil sobre tu tema favorito (un personaje, un deporte, un videojuego o tu música) cambiando los textos, la imagen, los colores y el botón.
- **Código inicial:** `starter-files/06-proyecto-final/`
- **Código completado:** `completed-examples/06-proyecto-final/`
