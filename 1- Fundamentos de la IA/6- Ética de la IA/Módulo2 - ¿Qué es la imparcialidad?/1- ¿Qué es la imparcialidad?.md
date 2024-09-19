# ¿Qué es la imparcialidad?

## Introducción

En IA, **imparcialidad** es el tratamiento equitativo de individuos o grupos de individuos. La imparcialidad se consigue cuando se mitigan los **sesgos** no deseados. En IA, el sesgo es un error sistemático que se ha diseñado, intencionadamente o no, de forma que pueda generar decisiones injustas. El sesgo se puede encontrar en el sistema de IA, en los datos utilizados para entrenar y probar el sistema, o incluso en ambos. El sesgo puede surgir en un sistema de IA debido a expectativas culturales, limitaciones técnicas o contextos de implantación imprevistos.

En la siguiente historia, Jordan, Priscilla y Nischal, empleados de una gran entidad bancaria nacional, le hablarán de imparcialidad y parcialidad al descubrir un problema de imparcialidad en un sistema de IA.

## Conocer al equipo

¿Qué se entiende por imparcialidad en los sistemas de IA? Esta historia analiza una gran entidad bancaria nacional y algunos de los problemas de imparcialidad que deben tenerse en cuenta y tratarse al implantar sistemas de IA.

La entidad se está preparando para implantar un sistema de IA que les ayude a identificar a los candidatos de mayor valor en su bolsa de ascensos, y Priscilla se da cuenta de que la mayoría de los candidatos pertenecen a una misma raza. Comienzan a revisar el sistema para entender qué está provocando el resultado y descubren que el sistema está sesgado. Esta historia abarca conceptos básicos sobre el sesgo en el contexto de la imparcialidad, y cómo puede entrar el sesgo en un sistema. La historia también ofrece una serie de preguntas sobre las que reflexionar.

![equipo](/resources/equipo.png)

## Identificar el problema

Jordan ha asumido un nuevo rol como responsable de datos de la entidad bancaria. Antes de que Jordan se incorporara, la empresa había estado probando un nuevo sistema de IA, el primero de su clase, para ayudar a su grupo de PeopleOps a identificar candidatos de alto valor en su grupo de ascensos para el año en curso.

El sistema parece funcionar, así que el equipo comparte la lista de ascensos con Priscilla, la Directora de operaciones de personal. En primer lugar, Priscilla mira la lista junto a la información demográfica de los candidatos. Al examinar la lista, algo llama su atención. Priscilla advierte que un número desproporcionado de los candidatos ascendidos son blancos. Está sorprendida porque había recomendado específicamente a un empleado no blanco que ya desempeñaba el trabajo del siguiente nivel y que parecía el perfil perfecto para un ascenso, pero esa persona no está en la lista de ascensos. Llama a Jordan para empezar a investigar.

![problema](/resources/problema.png)

Jordan pide al equipo de ciencia de datos que investigue sobre lo que preocupa a Priscilla. Como primer paso, el equipo de ciencia de datos analiza rápidamente los datos sobre ascensos de 5 años utilizados para entrenar el sistema de IA.

En la tabla siguiente figura una muestra de los datos que recogieron:

| Atributos del empleado  | Empleado 1 | Empleado 2 | Empleado ... |
|-------------------------|------------|------------|--------------|
| **ID de empleado**       | 1          | 2          | ...          |
| **Departamento**         | Datos e IA | Datos e IA | ...          |
| **Cualificación**        | Máster     | Doctorado  | ...          |
| **Raza**                 | Blanca     | No blanca  | ...          |
| **Años de antigüedad**   | 10         | 12         | ...          |
| **Valoración media**     |            |            | ...          |
| **Decisión sobre ascenso** | Sí        | No         | ...          |


El equipo recopila sus hallazgos iniciales en un gráfico que muestra los datos de ascensos y la raza de los candidatos:

![gráfico](/resources/ascensos.png) 

Al observar el gráfico, Jordan se da cuenta de que históricamente ha habido un número desproporcionadamente mayor de candidatos blancos que de no blancos en el grupo ﬁnal de candidatos a ascensos. Se les ocurre que el sistema podría tener un problema de imparcialidad que diera lugar a prejuicios basados en la raza.

Jordan reúne al equipo para hablar sobre el primer problema que han detectado y planificar lo que tienen que hacer a continuación.

Como primer paso para abordar el dilema, Jordan pregunta al equipo si creen que mantener el sistema de IA tiene valor para la empresa.

Jordan pregunta: “¿Creéis que deberíamos seguir utilizando la IA para ayudar en el proceso de ascensos?”.

Tras pensárselo un momento, Priscilla asiente con la cabeza.

“Si se hace bien y de forma que los miembros del equipo de PeopleOps puedan confiar, nos ahorrará tiempo y podría ayudarnos a que nuestro proceso de ascensos sea más justo”, afirma Priscilla.

Jordan, Priscilla y Nischal coinciden en que el valor de la IA está ahí, si se aplica correctamente.

## Explicar el problema
1. Al día siguiente, Nischal y el equipo de PeopleOps se reúnen en la sala de reuniones. Nischal inicia el debate con el término sesgo.

    Jordan pregunta a Nischal: “¿Puedes explicar el significado de sesgo en el contexto de la imparcialidad?”.  

2. Nischal explica lo siguiente: “El sesgo, en general, es un error sistemático, pero en el contexto de la imparcialidad, el problema gira en torno al sesgo no deseado. El sesgo no deseado da a algunos grupos o individuos una ventaja sistemática y a otros grupos o individuos una desventaja sistemática”.

    Continúa diciendo: “Entiendo que he utilizado algunos términos nuevos. Voy a explicarlos uno por uno”.

3. Nischal presenta una diapositiva con la deﬁnición del sesgo y frases destacadas.

    *El sesgo no deseado da a los grupos privilegiados una ventaja sistemática y a los grupos no privilegiados una desventaja sistemática.*

4. Priscilla pregunta: “¿Por qué dividir a la población en grupos?”

5. Nischal explica: “La razón de utilizar grupos es sencilla: mitigar la disparidad de resultados entre los grupos. En otras palabras, para obtener un resultado equitativo entre los grupos”.

    Nischal continúa: “Dividimos la población en grupos basándonos en uno o más atributos de los datos que podrían introducir disparidad o desigualdad en el resultado. El atributo que separa a la población en grupos se denomina atributo protegido. Algunos de los atributos protegidos que se suelen utilizar son raza, edad, sexo al nacer, identidad de género y origen étnico. Pero no hay un conjunto deﬁnido de atributos protegidos”.

    >[!Note] 
    > por motivos legales y otros motivos políticos, los atributos protegidos no se suelen mantener en el conjunto de datos. En estos casos, el equipo podría imputarlos (plagados de sus propios sesgos) o podría utilizar las estadísticas de conjuntos de datos demográficos mediante un [enfoque de aprendizaje por transferencia](https://dl.acm.org/doi/10.1145/3306618.3314236)

6. “Tradicionalmente, si un grupo recibe un resultado más favorable o ventajoso que otro grupo, se puede introducir sesgo y generar un resultado injusto. El grupo que tradicionalmente recibe resultados más favorables se denomina grupo **privilegiado**. El grupo que tradicionalmente recibe menos o ningún resultado favorable se denomina grupo no privilegiado. El objetivo de la imparcialidad en la IA es minimizar el impacto de los sesgos no deseados en el sistema”, concluye Nischal.

7. Nischal presenta el siguiente gráfico, que representa 5 años de datos de ascensos, divididos por razas, para explicar el problema de la imparcialidad. 

    Nischal señala el gráfico: “En nuestros datos, la **raza** es uno de los posibles atributos protegidos”.

    ![gráfico](/resources/raza.png)

8. Nischal continúa preguntando al equipo: “¿Veis al patrón?”

    “Los candidatos blancos tienen un mayor porcentaje de ascensos que los no blancos. Hemos introducido estos datos de 5 años en nuestro sistema de IA, que solo ha seleccionado al 2 % de los candidatos no blancos para un ascenso en 2022. El sistema de IA ha hecho su selección basándose en el historial de ascensos de la empresa”.

9. El equipo ha podido al fin vincular el concepto con su aplicación de ascensos. Jordan se une a la conversación y dice: “Así que, en nuestra aplicación de ascensos,

    - Los empleados blancos están en el grupo privilegiado.
    - Los empleados no blancos están en el grupo no privilegiado.
    - La raza, cuando se utiliza para dividir a la población en grupos, introduce disparidad, y es el atributo protegido”.

10. Nischal conﬁrma la conclusión de Jordan y concluye el análisis inicial diciendo: “Hay muchas formas a través de las cuales el sesgo puede entrar en el sistema de IA. Tenemos que investigar más a fondo cómo entró el sesgo en el sistema de ascensos. El tipo de imparcialidad (grupal, individual o ambas) en el que centrarse depende del problema. Hay muchos factores que pueden influir en la selección de los atributos protegidos, como los principios de la organización, el enfoque de la aplicación y la normativa. 

    El equipo debe tener en cuenta todos los factores y elegir cuidadosamente los atributos protegidos. El equipo de ciencia de datos debe diseñar una forma de `comprobar los sesgos a lo largo del ciclo de vida de la IA` y tomar las medidas de mitigación necesarias. Abordar los problemas de imparcialidad es un deporte de equipo”.

## Abordar el problema

El equipo ha identificado que el problema del modelo de IA es de **imparcialidad**. Para lograr la imparcialidad, hay que reducir los sesgos no deseados. En IA, el sesgo es un error sistemático que, intencionadamente o no, puede influir en un sistema de IA de forma que pueda generar decisiones injustas. 

El sesgo se puede encontrar tanto en el sistema de IA como en los datos utilizados para entrenarlo y probarlo. Según los datos proporcionados al sistema de IA, se habían introducido sesgos que afectaban a los resultados del sistema.

## Reflexión: La imparcialidad en la IA

`Pregunta 1: ¿Existe un paso para analizar las consecuencias intencionadas y no intencionadas de la aplicación utilizando un enfoque de pensamiento de diseño? ¿Cree que este paso es necesario?`

Sí, es muy importante entender los efectos conocidos y ocultos de las aplicaciones para mitigar daños importantes. Una forma de entender mejor los efectos conocidos y ocultos es tener en cuenta los niveles de efectos. Cuando se consideran los niveles de efecto, se piensa en el efecto principal de la aplicación (su impacto previsto), sus efectos secundarios (impactos imprevistos conocidos o predecibles) y sus efectos terciarios (posibles impactos impredecibles o imprevistos no intencionados). Tener en cuenta los niveles efectos con un equipo diverso e inclusivo ayuda a identificar una gama más amplia de impactos potenciales, incluidos daños potenciales.

`Pregunta 2: ¿Qué atributo del conjunto de datos de esta historia puede introducir un sesgo no deseado?`

El atributo “Raza del empleado”

`Pregunta 3: ¿Hay alguna forma de mitigar los prejuicios en todas las fases del ciclo de vida de la IA (desde el desarrollo hasta la implantación)? ¿Cómo lo haría?`

Sí, hay muchas formas de mitigar el sesgo durante el ciclo de vida de la IA. A lo largo del ciclo de vida de la IA, es fundamental trabajar con un equipo diverso e integrador cuyos conocimientos colectivos ayuden a identificar mejor los posibles problemas de sesgo. Los modelos de IA extraen patrones clave a partir de los datos de entrenamiento para tomar decisiones y hacer predicciones. Por lo tanto, es importante seleccionar datos de calidad que sean relevantes, precisos, completos y representativos, ya que el uso de datos de calidad ayudará a reducir los problemas de sesgo más adelante en el ciclo de vida. Cuando un modelo de IA pasa a producción, también es muy importante utilizar herramientas para detectar, medir y mitigar el sesgo de forma continua, ya que permite identificar, comprender y corregir los problemas de forma proactiva y continua.

`Pregunta 4: ¿Cómo se puede tratar el sesgo observado?`

Hay muchas formas de mitigar el sesgo observado. El primer paso es investigar dónde y por qué el modelo muestra un sesgo no deseado. Luego, puede revisar los datos y el etiquetado de datos y corregir los problemas detectados. También puede comprobar si es necesario volver a entrenar el modelo.