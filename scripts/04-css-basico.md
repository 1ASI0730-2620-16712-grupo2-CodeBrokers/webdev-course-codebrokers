# Guion completo — Lección 4: Colores y fuentes con CSS

Duración total: unos 10 minutos. Público: estudiantes de 12 a 17 años.

Ritmo de lectura: unas 130 palabras por minuto, más pausas y el tiempo de escribir código. Lee con calma; si te sobra tiempo, alarga las pausas. No aceleres.

Antes de grabar:
- Ten la presentación abierta en la diapositiva 1.
- En otra pestaña, ten CodePen abierto con el HTML de partida en el panel HTML y el panel CSS solo con el comentario `/* Cambia el fondo, la fuente y el color del título */`.
- Sube el zoom del navegador (Ctrl + +) para que el código se lea bien.
- En el HTML, usa el nombre "Alex" y no el tuyo: el video no debe llevar nombres de autores.

Los textos entre corchetes son acciones, no se leen.

---

## Diapositiva 1 · ¿Qué cambia CSS? · 0:00 – 2:00

[Muestra la diapositiva 1.]

Hola, bienvenido a la lección cuatro. En las lecciones anteriores construimos una página web con HTML: pusimos títulos, párrafos, una lista, una imagen y un enlace. La página ya funciona, tiene contenido… pero seamos sinceros: se ve bastante simple. Todo el texto es negro, el fondo es blanco y la letra es la que el navegador elige por defecto.

Te hago una pregunta. Piensa en tu página web favorita, la que más visitas. ¿Se ve así de simple? Seguramente no. Tiene colores, tipos de letra especiales, cosas ordenadas en distintas partes de la pantalla. Tómate unos segundos y piensa: ¿qué colores usa esa página?

[Pausa de 10 a 15 segundos.]

Todo eso que acabas de imaginar se hace con CSS. CSS significa "hojas de estilo en cascada", pero lo importante es la idea: HTML se encarga del contenido, es decir, de qué hay en la página; y CSS se encarga de la apariencia, es decir, de cómo se ve.

[Señala las dos tarjetas: HTML – Contenido y CSS – Apariencia.]

Una forma fácil de recordarlo: imagina una casa. HTML son las paredes, las puertas y las ventanas. CSS es la pintura, la decoración y los muebles. La casa existe sin pintura, pero con pintura se ve mucho mejor.

Y algo muy bueno: cuando cambiamos el CSS, el contenido no se toca. El texto sigue siendo el mismo; solo cambia cómo se presenta. Además, en CodePen vamos a ver los cambios en tiempo real, en cuanto escribimos.

---

## Diapositiva 2 · La anatomía de una regla CSS · 2:00 – 4:30

[Pasa a la diapositiva 2.]

Antes de escribir código, vamos a entender cómo se escribe una instrucción en CSS. A cada instrucción la llamamos "regla", y toda regla tiene tres partes: el selector, la propiedad y el valor.

[Señala el código de la diapositiva: `h1 { color: royalblue; font-size: 32px; }`.]

Mira este ejemplo. Lo primero que aparece es `h1`. Eso es el selector. El selector responde a la pregunta: ¿a qué elemento le quiero cambiar el estilo? Aquí elegimos el `h1`, que es el título principal de la página.

Después vienen unas llaves, una que abre y otra que cierra. Todo lo que pongamos dentro de las llaves se aplica al elemento que elegimos.

Dentro de las llaves está `color`. Eso es la propiedad. La propiedad responde a: ¿qué aspecto quiero cambiar? Puede ser el color, el tamaño, la fuente, el fondo…

Luego vienen los dos puntos y después `royalblue`. Eso es el valor. El valor responde a: ¿cómo quiero que se vea? En este caso, azul real.

Y al final hay un punto y coma. El punto y coma es como el punto final de una oración: le dice al navegador "aquí termina esta instrucción". Si te olvidas del punto y coma, la siguiente línea puede dejar de funcionar, así que es un error muy común. Fíjate siempre en él.

Dentro de una misma regla podemos poner varias propiedades. En el ejemplo también hay `font-size: 32px;`, que cambia el tamaño de la letra a 32 píxeles.

Veamos un ejemplo distinto para repetir la idea. Si escribo `p { color: green; }`, ¿qué crees que pasa? El selector es `p`, o sea, los párrafos; la propiedad es `color` y el valor es `green`. Todos los párrafos se pondrían verdes.

Y si quiero cambiar toda la página, puedo usar el selector `body`, que representa todo el cuerpo de la página. Lo que le pongamos a `body` afecta a toda el área visible.

Resumiendo: selector, qué elemento; propiedad, qué aspecto; valor, cómo se verá.

---

## Diapositiva 3 · Colores y fuentes (demostración en CodePen) · 4:30 – 8:00

[Muestra un momento la diapositiva 3 y luego cambia a la pestaña de CodePen.]

Ahora vamos a practicarlo de verdad. Estas son las tres propiedades que vamos a usar: `background-color` cambia el color de fondo, `color` cambia el color del texto y `font-family` cambia el tipo de letra.

[Cambia a CodePen.]

Este es CodePen. A la izquierda está el panel HTML, con la página que hicimos en las lecciones anteriores. Al lado está el panel CSS, que por ahora solo tiene un comentario. Abajo vemos el resultado. Como ves, todo es blanco y negro.

Empecemos por el fondo de toda la página. Escribo el selector `body`, abro llaves…

[Escribe despacio: `body {` y Enter.]

…ahora la propiedad `background-color`, dos puntos, y el valor. Voy a usar un código de color: numeral, `e8f4ff`. Punto y coma.

[Escribe `background-color: #e8f4ff;` y cierra la llave. Señala la vista previa.]

¿Qué cambió? El fondo ahora es azul muy clarito. Esos códigos que empiezan con numeral se llaman colores hexadecimales. Cada combinación de números y letras es un color distinto. No hace falta aprenderlos de memoria: hay selectores de color en internet que te dan el código. También puedes usar nombres en inglés, como `red`, `blue` o `lightblue`.

Ahora cambiemos la fuente. Dentro del mismo `body`, debajo de la línea anterior, escribo `font-family: Arial, sans-serif;`.

[Escribe la línea dentro del bloque `body`. Señala la vista previa.]

Mira el texto: la letra cambió, ahora se ve más limpia. ¿Por qué puse dos nombres? Primero pido Arial. Si por alguna razón la computadora no tiene Arial, el navegador usa cualquier letra de tipo `sans-serif`, que son las letras sin "patitas". Es como un plan B.

Ahora le damos personalidad al título. Escribo una regla nueva con el selector `h1`…

[Escribe `h1 {` y Enter.]

…`color`, dos puntos, numeral `2563eb`, punto y coma.

[Escribe `color: #2563eb;`. Señala el título.]

El título ahora es azul. Y lo hagamos más grande: `font-size: 32px;`.

[Escribe `font-size: 32px;` y cierra la llave.]

Para que el efecto se note bien, voy a cambiar el color un momento a rojo.

[Cambia temporalmente `#2563eb` por `red`. Señala la vista previa.]

¿Lo ves? Cambia al instante. Lo dejo otra vez en azul.

[Vuelve a `#2563eb`.]

Por último, los párrafos. Escribo `p`, llaves, `color: #333333;`.

[Escribe la regla `p { color: #333333; }`.]

Ese es un gris muy oscuro. Muchas páginas usan este gris en lugar de negro puro porque cansa menos la vista al leer.

[Haz zoom o recorre el código terminado.]

Repasemos lo que escribimos: tres reglas. Una para `body`, con el fondo y la fuente. Una para `h1`, con el color y el tamaño del título. Y una para `p`, con el color de los párrafos. Fíjate que no tocamos ni una línea del HTML: todo el cambio fue en el CSS.

---

## Diapositiva 4 · Reto: personaliza tu página · 8:00 – 10:00

[Vuelve a la presentación y muestra la diapositiva 4.]

Ahora te toca a ti. Este es el reto: personaliza tu propia página.

Primero, elige tus colores. Pero ojo con algo importante: el contraste. El texto tiene que leerse bien sobre el fondo. Letras amarillas sobre fondo blanco, por ejemplo, casi no se leen. Busca un fondo claro con letras oscuras, o un fondo oscuro con letras claras.

Segundo, prueba una fuente sencilla. Además de Arial, puedes probar `Verdana`, `Georgia` o `Courier New`, y ver cuál te gusta más.

Tercero, cambia el tamaño del título con `font-size`. Prueba con 40 píxeles, o con 24, y mira la diferencia.

Pausa el video ahora y hazlo en tu CodePen. Yo te espero.

[Silencio de 30 a 45 segundos. Si quieres, muestra en CodePen un ejemplo tuyo con otros colores mientras esperas.]

¿Cómo te fue? Una forma de comprobar que lo hiciste bien: tu página debe verse distinta, el texto se debe leer sin esfuerzo y el código CSS debe tener sus llaves y sus puntos y coma en su lugar. Si algo no cambia, revisa primero el punto y coma y que el nombre de la propiedad esté bien escrito.

Recuerda la idea más importante de hoy: HTML es el contenido y CSS es la apariencia. Una regla CSS tiene selector, propiedad y valor.

En la próxima lección vamos a ir un paso más allá con CSS: vamos a aprender a centrar elementos y a usar bordes y espacios para ordenar mejor la página. ¡Nos vemos!

[Fin de la grabación.]

---

## Tiempos de referencia

| Parte | Tiempo | Duración |
|---|---|---|
| Diapositiva 1: ¿Qué cambia CSS? | 0:00 – 2:00 | 2 min, con pausa de 10–15 s |
| Diapositiva 2: Anatomía de una regla | 2:00 – 4:30 | 2 min 30 s |
| Diapositiva 3: Demostración en CodePen | 4:30 – 8:00 | 3 min 30 s, escribiendo en vivo |
| Diapositiva 4: Reto y cierre | 8:00 – 10:00 | 2 min, con pausa de 30–45 s |

Consejo: ensaya una vez con cronómetro. Si terminas antes de tiempo, explica con más calma cada cambio en CodePen o alarga la pausa del reto.
