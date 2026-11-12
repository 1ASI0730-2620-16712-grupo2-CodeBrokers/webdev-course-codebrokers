# Guion detallado — Lección 1: Introducción al desarrollo web

**Duración:** 10 minutos · **Público:** 12 a 17 años · **Editor:** CodePen (https://codepen.io/pen)


## Diapositiva 1 · 00:00–02:00 — Introducción

**Narración sugerida:**

¡Hola a todos! Bienvenidos a nuestra primera clase de desarrollo web.

Antes de comenzar, quiero hacerles una pregunta: ¿alguna vez han utilizado Internet para ver videos en YouTube, buscar información para una tarea, escuchar música o conocer las novedades de sus videojuegos favoritos?

Seguramente sí. Hoy en día utilizamos Internet para muchísimas actividades, desde estudiar y comunicarnos hasta divertirnos y aprender cosas nuevas.

Pero ¿alguna vez se han preguntado cómo se crean las páginas que visitamos todos los días?

Por ejemplo, cuando entramos a una página de videojuegos, podemos encontrar títulos, imágenes, descripciones y enlaces que nos llevan a otras secciones.

Todos esos elementos forman parte de una página web.

Una página web es un documento digital que nuestro navegador interpreta y muestra en pantalla. Un navegador es un programa como Google Chrome, Mozilla Firefox o Microsoft Edge, que nos permite visitar y visualizar páginas web.

Ahora imaginen que ustedes pudieran crear una página sobre su videojuego favorito, su mascota, su deporte preferido o incluso una página donde se presenten y compartan sus pasatiempos.

¡Pues eso es exactamente lo que vamos a aprender!

Durante este curso conoceremos las herramientas básicas que se utilizan para crear páginas web. Y lo mejor es que no necesitan experiencia previa en programación.

Tampoco tendrán que instalar programas complicados. Solamente necesitaremos nuestro navegador y una herramienta gratuita que funciona en Internet.

Al terminar esta primera lección, habrán escrito sus primeras líneas de código y podrán observar cómo se convierten en una página web.

Así que prepárense, porque hoy comenzaremos nuestra aventura en el desarrollo web.

---

## Diapositiva 2 · 02:00–04:30 — Concepto nuevo: HTML y CSS

**Narración sugerida:**

Ahora que sabemos qué es una página web, vamos a descubrir cómo podemos construir una.

Para ello, necesitamos conocer dos tecnologías muy importantes: HTML y CSS.

Aunque sus nombres pueden parecer un poco complicados, vamos a entenderlos utilizando un ejemplo muy sencillo.

Imaginen que queremos construir una casa.

¿Qué necesitamos primero?

Necesitamos una estructura: paredes, puertas, ventanas, habitaciones y un techo.

Sin esa estructura, no tendríamos una casa organizada.

En el desarrollo web ocurre algo parecido.

HTML es el lenguaje que utilizamos para organizar y dar significado al contenido de nuestra página web.

Por ejemplo, con HTML podemos indicar que un texto será un título principal, que otro será un párrafo o que queremos mostrar una imagen.

También podemos crear listas, enlaces y otros elementos que iremos conociendo durante el curso.

Ahora imaginemos que nuestra casa ya está construida.

Tenemos las paredes, las puertas y las ventanas, pero todavía se ve bastante sencilla.

¿Qué podríamos hacer para mejorarla?

Podríamos pintar las paredes, elegir los colores de las habitaciones, colocar muebles y decorar los espacios.

Aquí es donde entra CSS.

CSS es el lenguaje que nos permite controlar la apariencia de nuestra página web.

Con CSS podemos cambiar los colores, modificar el tamaño de las letras, agregar fondos, colocar bordes y organizar los elementos de una manera más atractiva.

Veamos un ejemplo.

Supongamos que queremos crear una página sobre nuestro videojuego favorito.

Con HTML podemos escribir un título que diga: "Mi videojuego favorito".

También podemos agregar un párrafo explicando por qué nos gusta tanto.

Pero, si queremos que el título aparezca de color azul, tenga letras grandes y esté centrado, podemos utilizar CSS.

Entonces, recuerden esta diferencia:

**HTML organiza y da significado al contenido de nuestra página, mientras que CSS controla cómo se presenta visualmente.**

Ambos trabajan juntos.

HTML nos permite construir la estructura y CSS nos ayuda a mejorar su apariencia.

Y ahora que conocemos estos conceptos, vamos a escribir nuestro primer código.

---

## Diapositiva 3 · 04:30–08:00 — Demostración en CodePen

**Narración sugerida:**

¡Llegó el momento de poner en práctica lo que acabamos de aprender!

Vamos a utilizar una herramienta llamada CodePen.

CodePen es un editor de código que funciona directamente desde nuestro navegador. Esto significa que podemos escribir HTML y CSS sin necesidad de descargar o instalar ningún programa.

Primero, vamos a abrir nuestro navegador y escribir la siguiente dirección:

https://codepen.io/pen/

Una vez que ingresamos, podemos observar diferentes secciones.

Tenemos un panel llamado HTML, otro llamado CSS y uno llamado JavaScript.

Por ahora no vamos a utilizar JavaScript, porque primero aprenderemos los fundamentos de HTML y CSS.

También encontraremos una sección donde podremos visualizar el resultado de nuestro código.

Esto es muy útil porque nos permite observar inmediatamente cómo cambia nuestra página mientras escribimos.

Ahora vamos a dirigirnos al panel HTML.

Escribiremos nuestra primera etiqueta, que se llama `h1`.

Esta etiqueta se utiliza para representar el título principal de una página o sección.

Primero escribimos el símbolo de menor que, luego h1 y finalmente el símbolo de mayor que.

Después colocamos el texto que queremos mostrar.

En nuestro caso escribiremos: "¡Hola, mundo!".

Finalmente, cerramos la etiqueta escribiendo una barra antes de h1.

Observemos lo que sucede.

¡Nuestro título aparece en pantalla!

Acabamos de crear nuestro primer elemento HTML.

Ahora vamos a agregar otro elemento.

Esta vez utilizaremos la etiqueta `p`, que sirve para representar un párrafo.

Dentro escribiremos: "Estoy aprendiendo desarrollo web".

Cerramos nuestra etiqueta y observamos nuevamente el resultado.

Ahora tenemos un título y un párrafo.

¿Se dan cuenta de lo sencillo que puede ser comenzar?

Con solamente dos elementos HTML ya hemos creado el contenido de nuestra primera página.

Vamos a realizar un pequeño cambio.

En lugar de escribir "¡Hola, mundo!", cambiaremos nuestro título por "Bienvenidos a mi página web".

Observen cómo el resultado se actualiza.

Esto sucede porque CodePen interpreta nuestro código y muestra una vista previa de la página.

Ahora vamos a probar algo más.

Entraremos al panel CSS y escribiremos una regla sencilla para cambiar el color del título.

Utilizaremos el selector `h1`, abriremos las llaves y escribiremos la propiedad `color` con el valor `blue`.

Cerramos la regla y observamos el resultado.

¡Nuestro título ahora aparece de color azul!

Esto demuestra la diferencia entre HTML y CSS.

HTML nos permitió crear el título y el párrafo, mientras que CSS nos permitió modificar la apariencia del título.

Más adelante aprenderemos muchas otras propiedades para personalizar nuestras páginas.


## Diapositiva 4 · 08:00–10:00 — Práctica y cierre

**Narración sugerida:**

¡Muy bien! Ya hemos aprendido cómo crear un título, agregar un párrafo y modificar el color utilizando CSS.

Ahora llegó el momento de que ustedes lo intenten.

Vamos a realizar una pequeña actividad.

Imaginen que quieren crear una página sobre algo que les guste mucho.

Puede ser su videojuego favorito, su mascota, su deporte preferido, una película o incluso su personaje favorito.

Primero, quiero que cambien el título de nuestra página.

Por ejemplo, si les gustan los videojuegos, podrían escribir: "Mi videojuego favorito".

Después, vamos a modificar el párrafo.

Podríamos escribir algo como: "Me gustan los videojuegos de aventuras porque puedo explorar nuevos mundos y superar desafíos".

Ahora observen el resultado.

¡Acaban de personalizar su primera página web!

También pueden experimentar cambiando el color del título.

Por ejemplo, donde escribimos `blue`, pueden probar con `red` para utilizar el color rojo o `green` para utilizar el color verde.

Voy a dejar unos segundos para que puedan intentarlo.

Si necesitan más tiempo, pueden pausar el video y continuar cuando hayan terminado.

**[Pausa de 10 a 15 segundos.]**

¿Lo consiguieron?

¡Excelente trabajo!

Si el resultado no aparece como esperaban, no se preocupen.

Es normal cometer errores cuando estamos aprendiendo a programar.

Revisen que las etiquetas estén correctamente escritas, que hayan colocado los símbolos de apertura y cierre y que la regla CSS tenga sus llaves.

Recuerden que aprender a programar requiere práctica, paciencia y curiosidad.

Antes de terminar, repasemos lo que aprendimos hoy.

Primero, descubrimos que una página web es un documento digital que podemos visualizar utilizando un navegador.

Después, conocimos HTML, que nos permite organizar el contenido de una página.

También aprendimos que CSS nos ayuda a modificar su apariencia mediante colores y otros estilos.

Finalmente, utilizamos CodePen para escribir nuestras primeras líneas de código y observar el resultado.

En nuestra siguiente lección aprenderemos más sobre las etiquetas HTML y comenzaremos a construir una página de presentación personal.

¡Muchas gracias por acompañarme en esta primera clase!

Recuerden seguir practicando y experimentando con sus propias ideas.

¡Nos vemos en la siguiente lección!



