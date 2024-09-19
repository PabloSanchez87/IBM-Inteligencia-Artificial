# ¿Qué es la privacidad?

## Introducción

Los datos son el centro de la IA. Puesto que la IA ingiere tantos datos para aprender, identificar patrones y hacer predicciones o recomendaciones, debe priorizar y salvaguardar la privacidad de todos los datos con los que entra en contacto.

En la siguiente historia, aprenderá sobre la privacidad con Kamal, Nia y Adrian, quienes aprenden a proteger la privacidad mientras desarrollan un sistema de IA.

## Conocer al equipo
¿Qué importancia tiene la privacidad? Esta historia analiza una gran institución educativa y cómo se debe tratar la privacidad al desarrollar sistemas de IA. 

Una gran institución educativa quiere ampliar su alcance ofreciendo cursos en línea. Mientras desarrolla un modelo de IA para recomendar planes de estudios de aprendizaje personalizados, el equipo se encuentra con algunos problemas relacionados con la privacidad de los datos y la privacidad de la IA. Esta historia explica cómo el equipo aprende sobre los problemas de privacidad y cómo se puede proteger la privacidad.

![equipo](/resources/equipo5.png)

## Explicar el problema

Una institución educativa quiere ampliar su alcance con un campus global en línea. Después de analizar el mercado, el equipo de desarrollo empresarial de la institución propone crear experiencias de aprendizaje personalizadas para cada estudiante. El equipo cree que la forma más eficaz de hacerlo es usar un modelo de IA para crear planes de estudio de aprendizaje personalizados. Llaman al equipo de ciencia de datos de la institución para crear un modelo de IA de prueba de concepto utilizando datos de muestra recopilados de los datos del portal de aprendizaje de la institución.

Cuando finaliza la prueba de concepto, los equipos de desarrollo comercial y ciencia de datos se reúnen para revisar el modelo de IA.

Durante la presentación, un plan de estudios de aprendizaje de muestra generado por el modelo de IA cambia el curso de la reunión:

“Kamal, no se nos ha informado de que los datos de nuestro portal de aprendizaje se usarían para crear el modelo de IA. Me preocupa, porque pensaba que esos datos eran privados. Tenemos que asegurarnos de que se respete la privacidad de los usuarios. ¿Nos puedes hablar sobre la protección de la privacidad de este modelo de IA?”

Kamal responde: “Si me dais un momento, vuelvo con la respuesta. Me gustaría consultarlo con mi equipo”.

![problema](/resources/privacidad.png)

## Identificar el problema

Kamal se reúne con el equipo para comentar la información que ha recibido sobre la prueba de concepto. Rápidamente, se da cuenta de que necesita más información sobre los conceptos básicos de la privacidad para poder determinar las protecciones adecuadas que se deben implantar. Pide a Nia, del Equipo de privacidad de datos, y a Adrian, del Equipo de desarrollo de IA, que aclaren algunos términos y conceptos básicos.

### El problema de la privacidad de los datos

Nia explica: “Las personas pueden proteger la información o los datos relacionados con ellas. Además, en algunos países, las personas tienen derecho a la privacidad de los datos; aunque es importante recordar que la definición de privacidad y los tipos de datos que se aplican varían de un país a otro. [En este mapa](https://www.cnil.fr/en/data-protection-around-the-world) se muestra cómo varía la normativa sobre privacidad en el mundo."

“Para que tengas una idea general sobre la privacidad, consideremos dos tipos de datos. `La información personal (PI)` es la información relacionada con un individuo identificado o identificable, como un nombre o código postal. `La información personal confidencial (SPI)` es información que, si se ve comprometida, podría usarse indebidamente para dañar u ocasionar problemas a una persona, como un número de cuenta bancaria o una fecha de nacimiento. ¿Cómo clasificarías estos tipos de información?” 

Kamal pregunta: “Gracias, Nia. Pero, ¿qué tiene esto que ver con la IA?”

Adrian, del Equipo de desarrollo de IA dice: “Buena pregunta, Kamal. Como los modelos de aprendizaje automático que impulsan la IA a menudo necesitan ser entrenados utilizando información personal o confidencial, es fundamental que los sistemas de IA prioricen y protejan la privacidad. Si se entrena a un modelo con información personal o confidencial sin aplicar ningún control de privacidad, entonces podría ser vulnerable a infracciones o ataques”.

Kamal pregunta: “¿Infracciones y ataques? ¿Puedes darnos un ejemplo?”

Adrian explica: “Pongamos un ejemplo de un tipo de ataque a la privacidad: **`el ataque por inferencia de pertenencia`**. En un ataque de inferencia de pertenencia, un atacante intenta determinar si un individuo específico formaba parte del conjunto de datos de entrenamiento.

Puesto que los datos de las personas incluidas en el conjunto de datos de entrenamiento se ven comprometidos, se viola su privacidad. Por lo tanto, cuando desarrollamos un sistema de IA o entrenamos un nuevo modelo, nuestro objetivo debe ser preservar y proteger la privacidad de las personas en la medida de los posible”.

Kamal pregunta: “¿Y qué podemos hacer para proteger la privacidad?”

### El problema de la privacidad de los datos

Adrian responde: “Hay varios controles de privacidad que se pueden aplicar para reforzar la IA contra posibles vulneraciones de datos confidenciales. Dos que se implantan durante el entrenamiento del modelo son **`la anonimización del modelo y la privacidad diferencial`**. Uno que se implanta después del entrenamiento del modelo es la minimización de datos. Vamos a examinar cada uno de ellos”.

- `Anominizacion del modelo(durante el entrenamiento)`

    El objetivo de la anonimización del modelo es anonimizar los datos de entrenamiento con la mínima pérdida de precisión. Al fin y al cabo, si el modelo se entrena con datos anónimos, entonces el modelo en sí es anónimo y hay poco riesgo para los datos personales utilizados durante el entrenamiento.

- `Privacidad diferencial(después del entrenamiento)`

    En la privacidad diferencial, se añade ruido aleatorio durante el entrenamiento del modelo para reducir el impacto de un solo individuo en los resultados del modelo y para garantizar que no se pueda identificar a un individuo en el conjunto de datos de entrenamiento.

- `Minimización de datos(después del entrenamiento)`

    La minimización de datos significa que solo se recopilan los datos que se necesitan. Este control ayuda a prevenir vulneraciones de la privacidad ya que limita la cantidad de datos personales que se recopilan en primer lugar y garantiza que los datos recopilados tengan la granularidad necesaria. Por ejemplo, minimización de datos podría significar que solo se recopila el código postal de una persona en lugar de su dirección completa, o solo su año de nacimiento en lugar de la fecha completa.


Adrian concluye: “Al aplicar controles de privacidad como la anonimización del modelo y la privacidad diferencial durante el entrenamiento del modelo, y la minimización de datos después del entrenamiento del modelo, podemos reforzar nuestros modelos contra las vulneraciones de datos personales y proteger la privacidad de las personas”.

Kamal agradece a Nia y Adrian por su ayuda y programa otra reunión con el equipo de dirección para hablar sobre los controles de privacidad que implementarán en el sistema de IA.

## Abordar el problema

Ahora, el equipo conoce los conceptos sobre información personal y confidencial y entiende que información que parece inofensiva puede usarse para identificar a las personas. Proteger los datos personales y el modelo de IA es importante tanto para la empresa como para sus usuarios.

## Reflexión: Privacidad en IA
`Pregunta 1: ¿Cómo puede poner el modelo a disponibilidad del público introducir un riesgo para la privacidad?`

Si un atacante tiene acceso a un modelo, es posible que pueda deducir las personas que se incluyeron en los datos de entrenamiento. Por eso es tan importante aplicar controles de privacidad de IA: cuando los datos de entrenamiento se han anonimizado o se les ha añadido ruido, es mucho más difícil para los atacantes determinar quién se incluyó en los datos de entrenamiento durante un ataque de inferencia de pertenencia.

`Pregunta 2: Si existe riesgo cuando se utiliza información personal, ¿vale la pena utilizarla?`

Sí, vale la pena utilizarla incluso si implica un riesgo. Se puede utilizar información personal para entrenar modelos en las circunstancias adecuadas, siempre que se apliquen técnicas de privacidad a los datos para conservar la privacidad de las personas cuyos datos se han utilizado.

`Pregunta 3: ¿Cuál sería otro ejemplo de minimización de datos?`

Usar el sector al que pertenece una persona en lugar de la empresa o el cargo, usar el código de área de una persona en lugar del número de teléfono, usar preguntas de tipo sí/no en lugar de reunir detalles concretos (por ejemplo, preguntar “¿Se graduó de la escuela secundaria? Sí/No” en lugar de preguntar el nombre del instituto o la fecha en que se graduó la persona).

