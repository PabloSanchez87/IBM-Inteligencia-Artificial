# NLP convierte señales en significado

## Estructura de un chatbot

Si alguna vez ha pulsado un botón de chat en Internet y se ha encontrado con un chatbot no humano, es posible que se haya dado cuenta de dos cosas:

- Cuando se hace una pregunta clara relacionada con el propósito del sitio web, como preguntar a un chatbot de compras “¿Cómo puedo obtener un reembolso?”, por lo general le da una respuesta relacionado con su pregunta.
- Cuando se hace una pregunta que no está clara o no está relacionada con el propósito del sitio web, como preguntarle al chatbot de compras “¿Tiene entradas para mi hermana?”, la respuesta será más bien del tipo “Lo siento, no he entendido su pregunta”.

Esto se debe a que el chatbot está programado para responder solo a determinadas preguntas sobre un tema concreto.

Incluso con esta limitación, los chatbots son útiles en campos que van desde la venta al por menor a la medicina de atención inmediata. Puede interactuar con un chatbot en línea en cualquier momento. Un chatbot siempre está listo para escuchar su pregunta (aunque no pueda responderle). Algunas instituciones utilizan chatbots a menudo porque no se limitan a emitir anuncios como los de la televisión. Cuando la gente interactúa con ellos, los chatbots escuchan y responden a preguntas repetitivas que, de no ser así, la empresa tendría que pagar a humanos para que se ocuparan de ellas.

Los chatbots trabajan con **pocos datos**. Esto significa que su escala es mucho más limitada. El chatbot de una cadena de cines puede tener que responder solo a preguntas sobre títulos, lugares y horarios de las películas, mientras que una IA más general que busque en las redes sociales puede tener que responder a preguntas generales sobre lo que piensan millones de personas. Los investigadores de IA dicen que los chatbots “ se meriendan los datos pequeños”.

## Un chatbot tiene un “frontend” y un “backend”

- El `frontend` de un chatbot es el canal de mensajería. El frontend interactúa con la persona que hace las preguntas, tanto escuchando (o leyendo) como hablando (o presentando texto).

- El `backend` de un chatbot es donde tiene lugar el trabajo duro. El backend desarrolla la lógica de la aplicación y tiene memoria suficiente para recordar partes anteriores de una conversación a medida que se desarrolla el diálogo.

## El backend del chatbot
`El backend de un chatbot hace el trabajo duro de entender y responder`

Supongamos que parte del trabajo de un chatbot es ayudarle cuando ha perdido u olvidado su contraseña. Podría escribir: “¿Cómo puedo restablecer mi contraseña?”, lo que sería fácil de gestionar para el chatbot. Para describir esa acción, un programador de chatbot podría pensar en términos como:

```	
IF pregunta = “Cómo puedo restablecer mi contraseña”
THEN respuesta = “Así se crea una nueva contraseña”
```	

Pero no siempre es fácil entender a los humanos. Pueden preguntar o escribir:

- “¿Cómo es que no puedo iniciar sesión en mi cuenta?”
- “He olvidado mi @#$ contraseña”
- “Dice que mi contraseña es incorrecta”. 
- “Olvidedo contsña”

Esto indica que una respuesta de chatbot (“Así se crea una nueva contraseña”) puede ser activada por un gran número de consultas de usuario (incluidas todas las enumeradas, y más).

Este es el gran trabajo que hacen los algoritmos llamados `clasificadores`. Los clasificadores pueden correlacionar muchas formas distintas de formular una pregunta con un conjunto muy reducido de respuestas. ¿Cuán pequeño? Algunos chatbots de comercios minoristas responden a cientos de preguntas diferentes con solo cinco o seis respuestas posibles. Las preguntas que los chatbots no pueden responder se envían a representantes humanos de atención al cliente.

## Intenciones, entidades y diálogo
`El backend de un chatbot suele constar de tres partes: intenciones, entidades y diálogo.`

Los chatbots entienden una pregunta dividiéndola en partes y relacionando esas partes con cosas de su memoria. El objetivo de un `chatbot` es identificar lo que se denominan `entidades` e `intenciones`, y luego utilizar lo que ha encontrado para activar un `diálogo`. ¿Qué significan estos términos?

- `Intención`

    Una **intención** es un propósito: la razón por la cual un usuario contacta con el chatbot. Piense en ello como verbo: una especie de acción. Un usuario puede tener la intención de presentar una queja, preguntar una dirección o hablar con un vendedor.

    Una institución puede tener muchas intenciones de clientes o socios que le gustaría que un chatbot gestionara. Suponga que le contratan para ayudar a crear un chatbot para una cadena de restaurantes. Una posible intención sería averiguar cuándo abren los restaurantes. En primer lugar, puede hablar con alguien que haya respondido a muchas de estas preguntas por teléfono. Luego su trabajo consistirá en hacer una lista de todas las formas en que una persona puede preguntar cuándo abren los restaurantes. La siguiente tabla ofrece varios ejemplos de posibles entradas de usuario que corresponden a este tipo de intención.

    ![alt text](/resources/tabla.png)

    Una vez que tenga una lista de las intenciones que quiere que cumpla su chatbot, estará listo para continuar.

- `Entidad`

    Si un usuario pregunta: “¿Cuál es el horario del restaurante de Austin?”, la **intención** es proporcionar el horario de apertura y Austin es la **entidad**. Un chatbot necesita una lista completa de entidades para resultar útil.

    En la siguiente tabla encontrará ejemplos de entidades que se corresponden con la intención y las posibles entradas de usuarios del ejemplo anterior de la cadena de restaurantes.

    ![alt text](/resources/tabla2.png)

    Ahora que ya conoce las entidades y las intenciones, hablemos de los diálogos.

- `Diálogo`

    Un **diálogo** es un diagrama de flujo, una estructura de árbol IF / THEN que ilustra cómo responderá una máquina a las intenciones del usuario. Un diálogo es lo que responde la máquina después de que un humano haga una pregunta. Aunque un humano utilice frases atropelladas, mala gramática, expresiones de mensajería de chat, etc., la inteligencia artiﬁcial permite al NLP entender lo suficientemente como para responder.

    El diálogo representa cada una de las posibles palabras o frases que puede introducir un usuario, la respuesta adecuada para el chatbot y las muchas posibles respuestas posteriores que puede dar el usuario. Eso es demasiado para que lo muestre un diagrama de flujo normal (podría necesitar tres o cuatro dimensiones), así que el software de chatbot condensa cada momento de la conversación en un **nodo**. Un nodo contiene una declaración del chatbot y una larga lista ampliable de posibles respuestas.

    Planificar este diagrama de flujo sería toda una aventura. Tendría que asignar una respuesta a cada posible entrada del usuario después del saludo del chatbot. En el ejemplo de los horarios de los restaurantes, todas las preguntas posibles sobre los horarios de un restaurante darían lugar a una única respuesta. Esto continuaría para la siguiente pregunta (quizás para la dirección del restaurante), y así sucesivamente. Se asignaría un gran número de posibles preguntas a un pequeño número de posibles respuestas hasta que la conversación finalizara. (Spoiler: ayuda que los asistentes virtuales de hoy en día ya hayan sido entrenados en Wikipedia, así que saben, por ejemplo, la diferencia entre creerse un sabio y ser un sabio).

## Ejemplo de análisis NLP

`Las intenciones, las entidades y los diálogos facilitan el trabajo del NLP`

En un ordenador convencional, el código del programa es inmenso, pero no gestionaría bien las intenciones, las entidades y los diálogos. Un ordenador convencional necesitaría una línea IF / THEN para cada uno de los miles de modos en que puede formularse una pregunta. A menos que un humano comparara perfectamente con una de esas líneas, el ordenador fallaría.

Pero la combinación de NLP con intenciones, entidades y diálogo de un sistema de IA puede hacer que esto funcione rápidamente. El NLP analiza los componentes de la frase y luego utiliza procesos como la puntuación de párrafos y de evidencia para clasificar los componentes de la frase en función de las posibles respuestas del chatbot. El resultado es que cuando un usuario humano hace una pregunta, el sistema de IA proporciona la respuesta con la mayor conﬁanza.

Piense en Staples, la empresa de suministros de oficina que cuenta con el botón Easy. Suponga que un cliente solicita un chatbot en el sitio web de Staples. El frontend del chatbot recibe la consulta del cliente y la reenvía al backend del chatbot. Allí, IBM Watson Assistant ejecuta el NLP para entender las intenciones del humano en relación con el pedido de un producto o el seguimiento de un envío.

Si el cliente dice: “Quiero hacer otro pedido de bolígrafos negros”, el chatbot averigua qué significa eso. Luego utiliza servicios cognitivos para consultar el historial de compras del cliente. En cuestión de segundos, el sistema está ayudando al cliente comprar más bolígrafos.

El chatbot de Staples solo sabe cinco cosas, pero las sabe bien. Da soporte a las ventas en línea las 24 horas del día, ofreciendo a quienes llaman un servicio ininterrumpido y dejando al personal libre para realizar otras tareas. Esto es muy valorado tanto por los clientes como por la empresa.
