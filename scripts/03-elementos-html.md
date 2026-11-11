# Guion detallado — Integrante 3

**Lección 3: Listas, imágenes y enlaces** · Duración objetivo: 10 minutos · Público: 12 a 17 años

> **Nota de producción:** Los tiempos son orientativos e incluyen explicación pausada, escritura del código, comprobaciones y práctica. Las indicaciones de pantalla y acciones no se leen en voz alta. Usar las cuatro diapositivas correspondientes a la lección 3: listas, imágenes, enlaces y reto.

## Diapositiva 1 · 00:00–01:15 — Organiza tus gustos

**Narración sugerida:** ¡Hola! En las lecciones anteriores aprendimos a colocar títulos y párrafos en una página web. Ahora vamos a añadir una lista de pasatiempos, una imagen y un enlace para visitar otra página.

Si queremos mostrar nuestros tres pasatiempos favoritos, ¿cómo podríamos organizarlos para que se lean fácilmente?

Podemos utilizar una lista, colocando cada pasatiempo en una línea. HTML nos ofrece dos tipos: `ul` crea una lista sin numeración y `ol` crea una lista numerada.

Una lista sin numeración sirve cuando el orden no es importante, como una lista de gustos. Una lista numerada sirve para presentar una secuencia, como los pasos de una receta.

En ambos casos, cada elemento se escribe dentro de una etiqueta `li`. Primero abrimos la lista, después escribimos sus elementos y finalmente cerramos la lista.

**En pantalla:** Mostrar la diapositiva “Organiza tus gustos”. Señalar `ul`, `ol` y `li`. Dejar unos segundos para responder la pregunta y resaltar las etiquetas de apertura y cierre.

## Diapositiva 2 · 01:15–02:30 — Una imagen vale mil palabras

**Narración sugerida:** Para mostrar una imagen utilizamos la etiqueta `img`. Esta etiqueta no necesita una etiqueta de cierre.

El atributo `src` indica dónde está la imagen. En nuestro ejemplo utilizaremos una dirección de Internet. Si esa dirección está mal escrita o deja de estar disponible, la imagen puede no aparecer.

El atributo `alt` contiene una descripción alternativa. Ayuda a comprender el contenido cuando la imagen no puede verse y permite que los lectores de pantalla comuniquen esa información.

Por ejemplo, si mostramos un perro jugando con una pelota, podemos escribir esa descripción en `alt`, en lugar de colocar solamente la palabra “foto”.

**En pantalla:** Mostrar la diapositiva “Una imagen vale mil palabras”. Resaltar `img`, `src` y `alt`, relacionando cada atributo con su función.

## Diapositiva 3 · 02:30–03:30 — Conecta con enlaces

**Narración sugerida:** Para conectar nuestra página con otra utilizamos la etiqueta `a`. En su apertura colocamos el atributo `href`, que indica la dirección de destino.

El texto escrito entre la apertura y el cierre es lo que verá la persona. Por ejemplo, podemos mostrar “Visitar Wikipedia” y colocar la dirección de Wikipedia en `href`.

Podemos cambiar el texto visible sin cambiar el destino.

Recuerda esta diferencia: `src` indica qué imagen queremos cargar y `href` indica adónde queremos ir al pulsar un enlace.

**En pantalla:** Mostrar la diapositiva “Conecta con enlaces”. Señalar por separado la dirección de destino y el texto visible.

## Diapositiva 4 · 03:30–04:00 — Reto: comparte tus intereses

**Narración sugerida:** Nuestro reto será completar una página con tres pasatiempos, una imagen con descripción alternativa y un enlace educativo.

Primero lo construiremos juntos. Después podrás cambiar los pasatiempos y personalizar el contenido.

Vamos a abrir CodePen para ver cómo cada etiqueta se convierte en una parte de nuestra página.

**En pantalla:** Mostrar la diapositiva “Reto: comparte tus intereses” y pasar al editor en línea.

## Demostración en CodePen · 04:00–08:45 — Construcción del ejemplo

### Preparación de la página

**Narración sugerida:** Aquí tenemos nuestro punto de partida. En el panel HTML aparece el contenido de la página y, en la vista previa, podemos observar cómo lo muestra el navegador.

Ya contamos con un título, un subtítulo y dos párrafos sobre un personaje de ejemplo llamado Alex.

Hoy trabajaremos en HTML. Los estilos con CSS los veremos en las siguientes lecciones.

Este comentario nos indica dónde continuar. Los comentarios permiten dejar indicaciones en el código y no se muestran como contenido en la página.

**Acciones:** Abrir la práctica con el contenido de `starter-files/03-elementos-html/html.txt`. Dejar CSS y JavaScript vacíos. Aumentar el zoom y localizar el comentario dentro de `main`. Eliminar el comentario para añadir los nuevos elementos.

### Añadir una lista

**Narración sugerida:** Primero añadimos un subtítulo con `h2`. Después abrimos una lista con `ul` y escribimos tres elementos `li`, uno por cada pasatiempo. Finalmente, cerramos la lista.

**Código que se escribe:**

```html
<h2>Mis pasatiempos</h2>

<ul>
  <li>Jugar videojuegos</li>
  <li>Escuchar música</li>
  <li>Leer historias</li>
</ul>
```

**Narración sugerida:** Los pasatiempos aparecen separados y con una viñeta delante. Vamos a comprobar qué ocurre si cambiamos la lista por `ol`.

Ahora aparecen números. No los hemos escrito manualmente: el navegador los genera porque utilizamos una lista ordenada.

Para nuestros pasatiempos mantendremos una lista sin numeración, porque no estamos indicando pasos.

**Acciones:** Mostrar el resultado. Cambiar temporalmente `<ul>` y `</ul>` por `<ol>` y `</ol>`. Comparar la numeración y restaurar `ul`.

### Añadir una imagen

**Narración sugerida:** Ahora añadimos otro subtítulo y una etiqueta `img`. Aunque repartimos sus atributos en varias líneas para leerlos mejor, todos pertenecen a la misma etiqueta.

En `src` colocamos la dirección de una imagen de ejemplo. En `alt` describimos su contenido.

Los atributos `width` y `height` indican el ancho y el alto. Aquí usamos 300 y 180 píxeles.

**Código que se escribe:**

```html
<h2>Mi imagen favorita</h2>

<img
  src="https://placehold.co/300x180/png?text=Mi+imagen"
  alt="Imagen de ejemplo con el texto Mi imagen"
  width="300"
  height="180"
>
```

**Narración sugerida:** La imagen ya aparece en nuestra página. Como está alojada en Internet, su carga depende de que la dirección esté disponible.

Si no aparece, revisa que el valor de `src` esté bien escrito y entre comillas. Recuerda que `img` no lleva etiqueta de cierre.

**Acciones:** Mostrar la imagen y resaltar `src`, `alt`, `width` y `height`. No utilizar imágenes personales de menores.

### Añadir un enlace

**Narración sugerida:** Terminaremos añadiendo un enlace dentro de un párrafo para mostrarlo separado del contenido anterior.

La etiqueta `a` crea el enlace y `href` contiene su destino. Entre la apertura y el cierre escribimos el texto que verá la persona.

**Código que se escribe:**

```html
<p>
  <a href="https://www.wikipedia.org/">
    Visitar Wikipedia
  </a>
</p>
```

**Narración sugerida:** Vamos a cambiar “Visitar Wikipedia” por “Explorar Wikipedia”. El texto visible cambia, pero el destino sigue siendo el mismo porque no hemos modificado `href`.

Ahora comprobaremos que el enlace funciona.

**Acciones:** Cambiar el texto visible, abrir el enlace en otra pestaña, comprobar el destino y regresar al editor.

### Revisar el resultado

**Narración sugerida:** Nuestra página ahora contiene tres pasatiempos, una imagen con descripción alternativa y un enlace.

Cada elemento de la lista está dentro de `li`. La imagen utiliza `src` para indicar qué recurso cargar y `alt` para describirlo. El enlace utiliza `href` para indicar su destino.

**En pantalla:** Mostrar el código y la vista previa. Comparar el resultado con `completed-examples/03-elementos-html/`.

## Práctica y cierre · 08:45–10:00 — Personalización del contenido

**Narración sugerida:** Ahora te toca practicar. Cambia los tres pasatiempos por actividades que te gusten y modifica el texto del enlace para que siga describiendo su destino.

Revisa también el texto alternativo. Si cambias la imagen por otra, actualiza su descripción.

Pausa el video y realiza los cambios en la práctica que encontrarás enlazada en la descripción.

Para comprobar tu trabajo, observa si aparecen los tres elementos, si la imagen carga y si el enlace abre el destino esperado.

Si algo falla, revisa las etiquetas, las comillas y las direcciones.

Ya sabes añadir listas, imágenes y enlaces a una página web. En la siguiente lección aprenderás a cambiar su apariencia con CSS. ¡Nos vemos!

**En pantalla:** Mostrar el reto y dejar una pausa breve. Repasar el resultado y cerrar enlazando con la siguiente lección.

## Material de esta lección

- Diapositivas: `presentaciones/Integrante_03.pptx` — versión corregida con las cuatro diapositivas de la lección 3.
- Inicio: `starter-files/03-elementos-html/html.txt` y `css.txt`.
- Solución: `completed-examples/03-elementos-html/html.txt` y `css.txt`.
- Vista previa: `completed-examples/03-elementos-html/vista-previa.html`.
- Enlace de CodePen precargado: **[PENDIENTE: colocar URL real de la práctica inicial]**.
- Enlace del video no listado: **[PENDIENTE: colocar URL real de YouTube]**.

## Lista de revisión

- [ ] Explicación entendible para principiantes.
- [ ] Diapositivas correspondientes a la lección 3.
- [ ] Código escrito y probado en el editor en línea.
- [ ] Texto en pantalla, anotaciones y narración en off.
- [ ] Pausa para la práctica.
- [ ] Grabación legible y voz clara.
- [ ] Sin nombres de autores ni branding en el contenido educativo o código.
- [ ] Práctica inicial accesible mediante su enlace.
- [ ] Enlace de la práctica incluido en la descripción del video.
- [ ] Video publicado como no listado.
- [ ] Enlaces reales registrados en el plan del curso.