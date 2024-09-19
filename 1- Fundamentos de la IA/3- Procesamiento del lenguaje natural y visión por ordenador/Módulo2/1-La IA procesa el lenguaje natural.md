# La IA procesa el lenguaje natural

## Segmentación de oraciones y señales en NLP

`Procesamiento de lenguaje natural`

Los ordenadores funcionan mejor con datos estructurados, en los que todo está perfectamente agrupado y etiquetado. Por desgracia para las máquinas, el lenguaje humano es cualquier cosa menos estructurado. Lleva casi toda su vida utilizando el lenguaje. Su cerebro lo consigue a través de algunos de los circuitos neuronales más complicados de la Tierra. Pero es muy difícil crear máquinas que puedan trabajar con el lenguaje humano.

**En NLP, las máquinas segmentan las oraciones y extraen significado de "señales" del lenguaje humano.**
El lenguaje humano no está estructurado. Aunque se rige por reglas gramaticales, nuestra lengua expresa la información de muchas formas confusas. A diferencia de la información estructurada, que puede organizarse en tablas o matrices con filas y columnas perfectamente etiquetadas, la información no estructurada es desordenada y difícil de entender. 

Para ver el motivo, vamos a estudiar este famoso chiste de Groucho Marx.

```
One morning I shot an elephant in my pajamas. (Una mañana, disparé a un elefante en pijama.) How he got in  my pajamas, I don’t know. (¿Cómo se metió en mi pijama? Nunca lo sabré.)

Adaptación de Grouch Marx, cómico y estrella de cine del siglo XX
```

Para abordar el "desorden" de la información no estructurada, los ordenadores comienzan con una oración cada vez. Esto se denomina `segmentación de oraciones`. A continuación, los ordenadores dividen la información en pequeños fragmentos de información, denominados `señales` (`tokens`), que se pueden clasificar individualmente. Una vez que las señales del texto se han clasificado en una estructura según su significado, NLP puede trabajar con ellas. 

Las siguientes actividades muestran cómo el chiste de Groucho Marx puede dividirse en señales de categorías útiles denominadas `entidades` y `relaciones`. Aprenderá lo que significan estas palabras a medida que continúe.

### Actividad 1: Entidades

- Una **entidad** es un sustantivo que representa una persona, un lugar o una cosa. No es un adjetivo, un verbo ni otro artículo del discurso.

- Recordemos la cita de Groucho Marx: “One morning, I shot an elephant in my pajamas. How he got my pajamas, I don’t know.” (Una mañana, disparé a un elefante en pijama. ¿Cómo se metió en mi pijama? Nunca lo sabré.) 

### Actividad 2: Relaciones

- Una **relación** es un grupo de dos o más entidades que tienen una fuerte conexión entre sí.

- Recordemos la cita de Groucho Marx: "One morning, I shot an elephant in my pajamas. How he got in my pajamas, I don't know" (Una mañana me desperté y maté a un elefante en pijama. ¿Cómo se metió en mi pijama? Nunca lo sabré).

---


Una vez que la IA ha clasificado las entidades y relaciones en el texto o el habla, puede empezar a estructurar la información como paso previo para comprenderla. Su cerebro, por cierto, hace lo mismo, lo que puede haberte ayudado a encontrar entidades y relaciones en las actividades anteriores.

Por ejemplo, examine estas dos oraciones: “Armen broke the glass. He always breaks the glass. (Armen ha roto el vídrio. Siempre rompe el vídrio.)” Fíjese en que hay una relación entre las dos frases: la palabra “he” está relacionada con la palabra “Armen”. La máquina usa NLP para identificar esta relación.

---

### Actividad 3: Conceptos

- Un **concepto** es algo implícito en una oración pero que no se dice realmente. Esto es más complicado porque implica emparejar ideas en lugar de las palabras especíﬁcas que aparecen en la frase.

- Recordemos, una vez más, la frase de Groucho Marx: “One morning, **I shot an elephant in my pajamas**. How he got my pajamas, I don't know”. (Una mañana me desperté y maté a un elefante en pijama. ¿Cómo se metió en mi pijama? Nunca lo sabré). 

## Detección de emociones y análisis de opinión

`La detección de emociones y el análisis de opinión no es lo mismo.`

Aunque las emociones y las opiniones se refieren a sentimientos más que a hechos o acciones, distinguirlas puede ayudar a un sistema de IA a entender mejor una oración.

- La **detección de emociones** identifica distintos tipos de emoción humana. 

        Por ejemplo, después de leer la valoración y los comentarios de un usuario en una encuesta de satisfacción del cliente en línea, puede determinar si la emoción que se expresa es ira, felicidad o miedo.

        Podemos entrenar la IA para clasificar las emociones. Identificar la señal emocional adecuada puede marcar una gran diferencia cuando un sistema de IA lee un mensaje en las redes sociales o en un chat de atención al cliente, donde las distintas emociones cambian considerablemente el significado de una frase.

- El **análisis de opinión** no es una emoción específica, al menos no como los expertos informáticos utilizan el término. Es una medida de la intensidad de una emoción. 

        Puede pensar en una opinión como una escala móvil entre positivo y negativo, con el valor neutro en el medio. 

        El análisis de opinión es una manera de evaluar si los datos son positivos, negativos o neutros. 

## El problema de la clasificación

`El lenguaje humano dificulta la clasificación`

He aquí un antiguo acertijo:

    Why does your nose run and your feet smell? (en inglés, “run” puede significar “correr” o “gotear”; “smell” puede significar “oler” o “apestar”)

El lenguaje humano está lleno de términos ambiguos o con doble sentido. Esto se denomina **un problema de clasificación**. En el acertijo " “How come your nose smells and your feet **run**?", run y **smell** tienen dos significados cada uno. 

- "A runny nose" significa que tiene un resfriado y necesita pañuelos para limpiarse la nariz, pero "run" también significa "correr". 
- "A smelly foot" significa que el pie apesta, pero "smell" también significa "oler".  

Puede que solo tarde un momento en entender el chiste, pero un sistema de IA podría tener dificultades para clasificar sus elementos. Veamos estos ejemplos:

- Puede enviar una caja en tren.
- Cuando un edificio se quema, se quema. 
- Puede completar un formulario rellenándolo. 

La clasificación puede ser más difícil para un sistema de IA que identificar señales, ya que gran parte de la clasificación depende del contexto en el que se encuentra una frase. Compare por ejemplo **He ido  al muelle a enviar un paquete** y **He ido a la estación a enviar un paquete**. 

Ambas frases indican dónde comienza el trayecto de un paquete, pero ninguna especiﬁca cómo viajará. Un sistema de IA debe asociar la palabra **barco** con la palabra **estación** o **muelle**, y luego relacionar esa asociación con el concepto adecuado: tren o barco.

¿Cómo resuelve este problema un sistema de inteligencia artificial? Tras analizar varios miles de casos en los que el envío desde un muelle da lugar a un viaje en barco, mientras que el envío desde una estación da lugar a un envío en tren, el sistema de IA identiﬁca la frecuencia con la que se vinculan los lugares y los tipos de viaje. El sistema mejora poco a poco en la clasificación y comete menos errores. Sin embargo, al igual que ocurre con los humanos, la clasificación de un sistema de IA nunca será perfecta al 100 %. (Por eso, los sistemas de IA bien diseñados no solo dan una respuesta, sino también un valor de conﬁanza).

Como ha aprendido, pasar de las señales y la clasificación a responder preguntas (o ganar un debate) es una tarea compleja. Pero no basta con conseguir que una máquina comprenda. 
