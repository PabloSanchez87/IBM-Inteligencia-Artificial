# ¿Qué es la explicabilidad?

## Introducción

Un sistema de IA es explicable cuando la gente corriente, que no tiene una formación especial en IA, puede entender cómo y por qué el sistema ha llegado a una predicción o recomendación concreta. La explicabilidad es como mostrar su trabajo en un problema de matemáticas para que todo el mundo pueda ver los pasos que ha dado para llegar a la respuesta.

En la siguiente historia, aprenderá sobre explicabilidad con Olivia, Clara y Luan mientras responden a las opiniones de los clientes sobre las recomendaciones de productos generadas por su sistema de IA.

## Conocer al equipo

Tras implantar un sistema de recomendación de productos basado en IA, una empresa de comercio en línea se da cuenta de que los clientes quieren saber por qué y cómo se les recomiendan los productos. El equipo de ciencia de datos se dedica a investigar cómo explicar los modelos de diferentes maneras que sean relevantes para los distintos usuarios. El equipo también genera una serie de preguntas en las que pensar a la hora de resolver este tipo de problemas.

![equipo](/resources/equipo3.png)

## Identificar el problema

Una empresa de comercio en línea ha integrado recientemente un sistema de recomendación de productos basado en IA para mejorar la experiencia de compra del cliente.

Tras lanzar una función de recomendación de productos basada en IA, el equipo de Ciencia de datos recopila datos e inicia el análisis de los comentarios.

![problema](/resources/problema2.png)

Estas son algunas de las preguntas de los clientes sobre las recomendaciones:

![problema](/resources/preguntas.png)

El equipo de Ciencia de datos crea un informe con los comentarios recibidos y lo envía por correo electrónico a Olivia.

Casualmente, Olivia está leyendo un artículo sobre la importancia de crear sistemas de IA fiables para que las empresas puedan seguir siendo competitivas en el mercado, ganarse la confianza de los clientes y crear confianza en la IA fiable.

Olivia recibe el correo electrónico del equipo y queda gratamente sorprendida por la puntualidad del informe. Se pregunta si el equipo de Ciencia de datos debería dedicar tiempo a añadir una nueva función para explicar de dónde vienen las recomendaciones.

Olivia envía una invitación de reunión al equipo, convocando una sesión de “brainstorming” para debatir el tema.

Olivia comienza la reunión dando las gracias a su equipo de ciencia de datos por el informe. Explica la importancia y la necesidad de crear sistemas de IA fiables. Luego escribe en la pizarra de la sala: “Una IA fiable no es un extra, sino un requisito esencial”.

El equipo empieza a comprender que la fiabilidad de la IA puede ser más importante de lo que pensaban en un principio.

## Explicar el problema
Cuando Olivia se vuelve hacia el equipo, oye dos voces al mismo tiempo.

Clara pregunta: “Entonces, ¿deberíamos centrarnos en hacer que nuestro modelo sea interpretable?”.

Luan pregunta: “¿Deberíamos centrarnos en la explicabilidad de la decisión del modelo?”.

Olivia cree que estas preguntas son una buena manera de guiar al equipo en la dirección correcta.

“¡Excelentes preguntas!” exclama Oliva. “Pero primero tenemos que entender lo que significa cada término. Tanto la **explicabilidad** como la **interpretabilidad** son formas de entender cómo funciona el modelo”.

“La **interpretabilidad** es el grado en que un observador puede entender la causa de una decisión. Es el porcentaje de éxito con el que los humanos pueden predecir el resultado de una salida de IA, mientras que la **explicabilidad** va un paso más allá y examina cómo el sistema de IA ha llegado a un resultado”.

“Ahora vamos a ver un escenario que conectará esos términos con nuestro sistema para que podamos entenderlos mejor”.

## Escenario: Recomendaciones para comercios

Olivia dice al equipo: “Aquí tenemos un escenario que conectará los términos con nuestra aplicación para que podamos entenderlos mejor”.

### Escena 1
Imagine que un cliente busca “proteína en polvo”. El sistema de inteligencia artificial le recomienda tres proteínas en polvo basándose en las anteriores pautas de compra del cliente. La información utilizada como entrada para el sistema de recomendación es:

- Indicador sin azúcar (Sí/No)
- Sabor (chocolate, vainilla y sin sabor)

### Escena 2

![escena2](/resources/escena2-2.png)

Aquí hay dos modelos recomendación, el Modelo A y el Modelo B. Cada modelo proporciona tres recomendaciones de productos (P2, P4 y P5).

El Modelo A utiliza un simple árbol de decisión para generar los productos que recomendar. El Modelo B usa una red neuronal para generar tres recomendaciones, pero no hay forma de saber qué llevó al modelo a generar las recomendaciones.

### Escena 3
Olivia dice: “Clara, si te pido que me expliques el porqué de las recomendaciones, ¿qué flujo del modelo te resultaría más fácil de entender y explicar?”.

### Escena 4
“Desde luego, el Modelo A”, responde Clara. “Puedo seguir fácilmente el flujo y entender la razón de una decisión. El Modelo B se parece más a un laberinto. Es difícil seguir lo que está pasando”.

### Escena 5
“¡Perfecto!” Dice Olivia. “El Modelo A se puede interpretar porque se puede rastrear y comprender fácilmente el motivo de la recomendación. Sin embargo, se necesitan métodos explicables o nuevas técnicas para rastrear y comprender el razonamiento que subyace a las recomendaciones del Modelo B”.

### Escena 6
“Estoy de acuerdo con Olivia”, dice Luan, “pero yo hago tanto de validador de modelos como de científico de datos. No creo que podamos utilizar las mismas explicaciones para todos los usuarios del modelo de IA. Supongo que las explicaciones deben cambiar según los usuarios”.

### Escena 7
“Eso es cierto, Luan. ¿Puedes explicar al equipo a qué te refieres?”. pregunta Oliva.

### Escena 8
“Bueno, solo estoy pensando en voz alta”, dice Luan, “pero entre las posibles personas que pueden necesitar y utilizar explicaciones de modelos están las siguientes:

- Usuarios de las recomendaciones del sitio web
- Encargados de aprobar los modelos (interno)
- Auditores de modelos (externo)
- Científicos de datos y validadores de modelos”

## Explicaciones del modelo
Veamos ahora cómo cambian las explicaciones sobre las recomendaciones para cada persona que ha mencionado Luan.

![escena9](/resources/modelo.png)

- `Abrazar el descubrimiento`

    Es posible que los usuarios quieran entender cómo el sistema de IA les hace recomendaciones específicas. También les gustaría saber qué medidas pueden tomar para recibir recomendaciones parecidas o distintas en el futuro.

    ![abrazar](/resources/abrazar.png)

- `Aprobadores y auditores`

    Es posible que los aprobadores y los auditores deseen comprender los pasos generales de la toma de decisiones sobre el modelo en función de las características. Tanto los aprobadores como los auditores pueden acabar cotejándolo con las explicaciones de usuarios aleatorios. El objetivo puede ser evaluar el modelo con respecto a los requisitos normativos o las políticas internas.

    ![aprobadores](/resources/aprobadores.png)

- `Científicos de datos y validadores de modelos`

    Es posible que los científicos de datos y los validadores de modelos deseen conocer el rendimiento general del modelo, el efecto de las características en el rendimiento y otros tipos de explicaciones para evaluar el modelo.

    ![científicos](/resources/cientificos.png)

Olivia y Clara agradecen a Luan la explicación y están de acuerdo en que la correlación será útil para diseñar los próximos pasos para hacer que el modelo sea explicable. Juntos, el equipo concluye la sesión de “brainstorming” y planifica la próxima reunión para diseñar el plan de desarrollo e implementación.

## Abordar el problema

Gracias a Luan, Olivia y Clara están listas para ponerse a trabajar para aumentar la explicabilidad de su modelo de IA. Ahora el equipo comprende la importancia de asegurarse de que todos, no solo los clientes, puedan comprender cómo y por qué los sistemas de IA generan determinadas predicciones o recomendaciones.

## Reflexión: Explicabilidad en IA

`Pregunta 1: ¿Cómo puede saber el equipo quién está involucrado en el desarrollo y la implementación del sistema de IA y cada uno de sus roles?`

Es importante definir roles antes de empezar a trabajar en el proyecto, después de la etapa de debate comercial. Recuerde que formar un equipo diverso e inclusivo, que incluya una comunidad diversa de partes interesadas, ayuda a construir sistemas más fiables.

`Pregunta 2: ¿Cómo puede recopilar el equipo el tipo de explicaciones que cada persona intentará obtener del modelo?`

En primer lugar, el equipo debe definir las personas y los tipos de explicaciones que necesita cada una. Luego, los miembros del equipo pueden pensar sobre cómo compartir esas explicaciones con las diferentes personas sin restar valor a su experiencia de usuario.

`Pregunta 3: ¿Qué método de explicación se adaptará mejor a las expectativas de cada persona?`

Los métodos de explicación son distintos para los distintos consumidores. Comprender las necesidades y los objetivos del consumidor ayuda a elegir el método adecuado. El pensamiento de diseño puede ayudar al equipo a tener en cuenta las necesidades y los objetivos del consumidor.