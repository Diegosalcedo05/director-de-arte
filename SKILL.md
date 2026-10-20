---
name: director-de-arte
description: Director de arte para cualquier diseño que Claude haga — posters, flyers, posts y carruseles, menús, presentaciones, videos animados, logos, páginas. Antes de diseñar, entrevista al usuario (una pregunta a la vez), busca referencias reales en la web, propone 2-3 direcciones visuales para elegir, consigue imágenes o b-roll si hacen falta, diseña, y se revisa con capturas antes de entregar. Úsala siempre que el usuario pida diseñar o rediseñar algo visual ("hazme una página", "una presentación de", "un video animado", "que se vea profesional", "que no parezca hecho con IA", "mi diseño se ve feo/de kinder/genérico"), aunque no la mencione.
---

# Director de arte

Claude diseña "de kinder" por tres razones, y esta skill ataca las tres:

1. **Diseña sin preguntar.** No sabe para quién es, qué debe sentir el que lo ve ni qué marca existe, así que
   rellena con lo genérico: degradado morado, emojis de icono, tarjetas iguales en fila, "Bienvenido a…".
2. **Diseña sin mirar.** Un diseñador de verdad abre 10 referencias antes de dibujar una línea. Claude inventa de memoria.
3. **No revisa lo que hizo.** Entrega sin ver el resultado renderizado.

El proceso tiene 6 pasos. **No te saltes los primeros tres**, aunque el pedido parezca simple: ahí está la diferencia.

## Paso 1 · Entrevista (una pregunta por mensaje)

Antes de escribir código o diseñar nada, pregunta. Una pregunta a la vez, en lenguaje normal, con opciones cuando
ayuden (si tienes una herramienta de preguntas con opciones, úsala; siempre deja la opción de escribir otra cosa).
Si el usuario ya respondió algo en su pedido, no lo vuelvas a preguntar. Normalmente son 6-8 preguntas; agrega
otras si una respuesta abre una duda real (ej. "¿la página es para vender en línea o para que vayan al local?").

1. **Qué es:** el negocio, producto o tema, en una frase. Y qué lo hace distinto de su competencia.
2. **Para quién:** quién lo va a ver (ej. "papás de 30-45 que buscan dónde festejar") y desde dónde (celular,
   proyector en una junta, TikTok…).
3. **Qué debe sentir el que lo ve:** confianza, antojo, lujo, urgencia, diversión, calma… (ofrece 4 opciones).
4. **Qué debe hacer:** la acción principal (escribir por WhatsApp, reservar, comprar, quedarse viendo, aprobar
   un presupuesto).
5. **Ejemplo o estilo a seguir (la más importante):** "¿Tienes algo que quieras que se parezca? Una página, una
   cuenta de Instagram, un video, una captura, aunque sea de otro giro." Si manda un link, ábrelo; si manda una
   imagen o video, míralo. Extrae su ADN visual (tipografía, paleta con hex, uso de foto, ritmo, recurso firma) y
   díselo en 3 líneas para confirmar que entendiste. Pregunta también qué **odia** ver.
6. **Marca existente:** ¿hay logo, colores, tipografía? Si dice que sí, pídeselos (ruta o link).
7. **Imágenes / b-roll:** ¿tiene fotos o videos reales? Si no, ofrece: (a) fotos libres de derechos, (b) imágenes
   generadas con IA si hay una herramienta conectada, (c) diseño solo tipográfico o ilustrado. En video: ¿quiere
   b-roll real, capturas de pantalla o todo animado?
8. **Contenido:** ¿tiene ya los textos (precios, servicios, horarios) o los propones tú? Si los propones, márcalos
   como borrador para que los confirme.

Si el usuario dice "tú decide" o "sorpréndeme", no preguntes más: decide con criterio, dilo en una línea y sigue.

**Si dio un ejemplo a seguir**, ese ejemplo es la base de la dirección principal del paso 3: las otras dos
direcciones son alternativas, no lo reemplazan. Inspírate en su lenguaje visual sin copiar textos, logos ni fotos.

## Paso 2 · Referencias reales

Busca en la web (WebSearch / navegador) **5-8 referencias reales** del mismo giro o formato y de su nivel deseado:
sitios de negocios premium del giro, galerías (Awwwards, Land-book, Godly, Mobbin, Behance, Dribbble), decks
conocidos, reels de motion design. Abre las mejores y anota **qué hacen concretamente**: tipografía (serif/sans,
tamaños), paleta (con hex si puedes), cómo usan la foto, cuánto aire dejan, cómo se mueven.

No copies ninguna: extrae patrones. Si el usuario dio una referencia, esa pesa más que todas.

## Paso 3 · Tres direcciones, el usuario elige

Propón **2-3 direcciones distintas** (no variaciones de la misma). Cada una en 4 líneas:

- **Nombre y sensación** (ej. "Mercado nocturno: cálido, ruidoso, con antojo").
- **Tipografías** (titular + texto; de Google Fonts u otra fuente libre) y **paleta** (3-5 hex, uno dominante).
- **Recurso firma:** el elemento que la hace memorable (fotos recortadas a sangre, números gigantes, papel picado, grano…).
- **Referencia en la que se inspira** (link).

Si puedes, muéstralas como un mini tablero visual (una página HTML simple con muestras de color y tipografía) en vez
de solo texto. Espera a que elija (o mezcle). Ver `references/direcciones.md` para armar direcciones con carácter.

## Paso 4 · Imágenes y b-roll

Según lo que respondió en el paso 1:

- **Fotos reales del usuario:** úsalas; recórtalas y gradúalas para que se vean de la misma familia.
- **Libres de derechos:** Unsplash, Pexels o Pixabay; descarga en buena resolución y guarda el crédito.
- **Generadas con IA:** solo si hay una herramienta conectada; escribe prompts en el estilo de la dirección elegida
  (misma luz, misma paleta) para que no parezcan de bancos distintos.
- **Logos de marcas:** de su fuente oficial o de Simple Icons, nunca dibujados a mano.
- **Video:** b-roll real (clips libres o capturas de pantalla reales) antes que íconos animados.

Nunca uses imágenes de placeholder grises ni "Lorem ipsum" en la entrega. Si falta una foto, dilo y deja el diseño
funcionando sin ella.

## Paso 5 · Diseñar

Construye con la herramienta que toque (HTML/CSS, React, el generador de presentaciones o de video que haya). Reglas:

- **La dirección elegida manda.** Tipografía, paleta y recurso firma consistentes en todas las secciones/slides/escenas.
- **Jerarquía brutal:** un titular claramente más grande que todo; un solo color de acento; un CTA evidente.
- **Aire:** márgenes generosos; menos elementos y más grandes.
- **Texto real y específico** del negocio (precios, horarios, zona, nombres de platillos), nunca genérico.
- Pasa el checklist de `references/anti-kinder.md` mientras diseñas, no solo al final.

## Paso 6 · Revisarse con capturas antes de entregar

Renderiza y **mira** el resultado: capturas de la página (escritorio y celular), de cada slide, o de varios segundos
del video. Busca: texto encimado o cortado, contraste bajo, elementos desalineados, algo que se vea genérico. Corrige y
vuelve a capturar. Entrega con 1-2 capturas y una línea por decisión importante ("serif grande porque las referencias
premium del giro lo usan").

Si el usuario pide cambios, que los diga con palabras simples ("más aire", "menos colores", "la foto más grande"):
aplícalos y vuelve a capturar.
