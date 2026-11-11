# Guion detallado — Lección 6: Proyecto final y errores comunes

**Duración:** 13 minutos · **Público:** 12 a 17 años · **Editor:** CodePen (https://codepen.io/pen)

## Material de esta lección

- Diapositivas: `presentation/Integrante_06.pptx`
- Inicio: `starter-files/06-proyecto-final/` (es el código final de la lección 5)
- Solución: `completed-examples/06-proyecto-final/`
- Práctica precargada en CodePen: https://codepen.io/Harold-11/pen/bNqzZQQ

## Parte 1 · Diapositiva 1 — Nuestro proyecto completo

Hoy vamos a juntar todo lo aprendido para crear una página de perfil completa. A la derecha se ve cómo quedará. Los títulos y párrafos se vieron en la lección 2; las listas, imágenes y enlaces en la lección 3; y los colores y la tarjeta en las lecciones 4 y 5.

## Parte 2 · Diapositiva 2 — Construyamos el perfil

Partimos de la página de la lección anterior y le agregamos cuatro cosas: un saludo, color en los subtítulos, un botón y un pie de página.

## Parte 3 · Demostración en CodePen

1. **Saludo:** se cambia el `h1` por `¡Hola, Soy Alex!` y se agrega `<p class="intro">Bienvenido a mi primera página web</p>`. En CSS, `.intro { font-size: 18px; }` agranda solo esa frase.
2. **Subtítulos:** `h2 { color: #2563eb; }` pone los subtítulos en azul.
3. **Botón:** el enlace recibe `class="boton"`. En CSS se le da `display: inline-block`, `padding: 12px 20px`, fondo azul, letras blancas, bordes redondeados y `text-decoration: none` para quitar el subrayado.
4. **Pie de página:** se agrega `<footer> Hecho con HTML Y CSS </footer>` y se le da `margin-top`, color gris y un tamaño de letra menor.

## Parte 4 · Diapositiva 3 — Errores comunes

Al programar todos nos equivocamos; lo importante es encontrar el error. Se cometen a propósito los tres errores más comunes.

## Parte 5 · Errores en vivo en CodePen

1. **Etiqueta sin cerrar:** al borrar `</h2>` de "Sobre mí", el texto de abajo se vuelve un título. Todo lo que se abre, se cierra.
2. **Atributo mal escrito:** al cambiar `src` por `scr`, la imagen desaparece. Hay que revisar letra por letra.
3. **Llave olvidada:** al borrar la `}` de la regla de `h1`, los estilos que vienen después dejan de funcionar. Cada `{` necesita su `}`.

Consejo: probar cada cambio apenas se hace y, si algo se rompe, revisar lo último que se cambió.

## Parte 6 · Diapositiva 4 — ¡Lo lograste!

Reto final: crear un perfil sobre un tema favorito (un personaje, un deporte, un videojuego o música) cambiando textos, imagen, colores y botón. Pausa para practicar. Para seguir aprendiendo: MDN (guía gratuita en español) y el validador de HTML del W3C.

## Parte 7 · Diapositiva 5 — Cierre

HTML es el contenido y CSS es el estilo.
