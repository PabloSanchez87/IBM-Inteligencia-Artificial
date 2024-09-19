# ¿Qué es la solidez?

## Introducción

La IA se utiliza cada vez más para ayudar a tomar decisiones cruciales, por lo que es vital que sea segura y sólida. Cuando la IA es sólida, puede manejar con mayor eficacia condiciones excepcionales, como anomalías en la entrada de datos o ataques maliciosos, sin causar daños involuntarios.

En la siguiente historia, aprenderá sobre solidez de la mano de Charlie, Manuel y Prashant, que debaten cómo garantizar que su sistema de IA se cree para resistir ataques de adversario.

## Conocer al equipo

Luego verá cómo proteger los sistemas de IA de los ataques. La `solidez` frente a adversarios se refiere a la capacidad de un modelo de IA para resistirse a ser engañado. Los equipos trabajan constantemente para hacer que los sistemas de IA sean más impermeables a las irregularidades y los ataques. Esta historia analiza lo que puede hacer una empresa de diagnóstico médico para proteger los sistemas de inteligencia artificial contra los ataques.

Una empresa de diagnóstico médico está a punto de lanzar una aplicación para detectar el cáncer de pulmón. Luego se enteran de que otra empresa emergente de aplicaciones sanitarias se enfrenta a una demanda por casos de diagnóstico erróneo. El equipo de dirección técnica de la empresa reúne a todos los empleados para que aprendan qué es un ataque de adversario y evalúen el riesgo de que su sistema sea atacado. En esta historia, aprenderá qué es un `ataque de adversari`o, los diferentes tipos de ataques, cómo pueden ocurrir y en qué se deben centrar los equipos para proteger sus sistemas de IA.

![equipo](/resources/equipo2.png)


## Identificar el problema

Se acerca la fecha de lanzamiento de una aplicación basada en IA para ayudar a detectar el cáncer de pulmón mediante radiografías de tórax. Charlie, la Directora de tecnología, está revisando el plan con su equipo.

Manuel, Responsable de privacidad, llama a la puerta y la abre lentamente. Charlie les hace señas para que entren.

Manuel se disculpa por la interrupción y dice: “Acabo de enterarme de que AY-APP se enfrenta a una demanda porque su aplicación diagnosticó erróneamente enfermedades a muchos pacientes del Centro de Salud Ocular C.L.”. 

El artículo afirma que los diagnósticos incorrectos ocasionaron a las compañías de seguros elevados costes en pruebas de seguimiento. Además, el estrés que ocasionó la situación a los pacientes afectó a su capacidad para trabajar y cuidar de sus familias durante meses. Parece que un ataque de adversario a su modelo de IA ha sido la causa del elevado número de diagnósticos incorrectos”.

El comentario de Manuel cambia el rumbo de la reunión.

Inmediatamente, Charlie piensa en la posibilidad de ataques de adversario.

![problema](/resources/ataque.png)

Charlie dice: “Sé que la noticia nos ha sacudido un poco a todos”.

Luego Charlie pregunta: “¿Todo el mundo sabe lo que es un ataque de adversario? Vamos a asegurarnos de que todos estamos de acuerdo en cuanto al concepto, las terminologías y las formas en que se puede atacar el sistema”.

Luego pide a Prashant, Responsable de datos y Científico de datos, que se lo explique.

## Explicar el problema

Prashant dice: “Empecemos por explicar qué es un ataque de adversario. Los ataques de adversario se llevan a cabo intencionadamente en sistemas de IA para lograr un objetivo final malicioso aprovechando las vulnerabilidades del sistema de IA.”

“El objetivo de un ataque de adversario es influir negativamente sobre el rendimiento del sistema, explotar los datos utilizados y corromper la lógica del modelo. El que se aprovecha de las vulnerabilidades del sistema de IA para lograr su objetivo se llama **adversario”**.

“La siguiente imagen es un ejemplo de cómo un ataque de adversario puede afectar al rendimiento de nuestro sistema”.

![ataque](/resources/ataque2.png)

“En este caso, el adversario ataca el sistema añadiendo pequeños cambios denominados **perturbaciones** o **ruido** a la imagen de entrada. La perturbación puede ser mínima e imperceptible a los ojos humanos. Sin embargo, cuando se envía al modelo de IA desplegado, la imagen modiﬁcada da como resultado una predicción no deseada o incorrecta”.

“Este escenario es solo para una entrada de usuario. ¿Os imagináis que este escenario se repitiera para todas las radiografías de entrada?”

Charlie entra en la conversación y dice: “Da miedo. No me imagino nuestro sistema en manos de adversarios.

¿Puedes dar más detalles sobre los objetivos finales del adversario, cómo las acciones del adversario pueden afectar a nuestro sistema, y las formas en que el adversario puede entrar en el sistema?”

“Claro”, dice Prashant. “Veamos algunos de los posibles objetivos del adversario y cómo conectan con nuestra aplicación de IA”.

### Distintos objetivos del adversario.

- **Objetivo del adversario: Acceder a información personal**

    Acceder acceso a información personal del paciente, como edad, sexo, raza,historial médico, información de identificación e información financiera.

- **Objetivo del adversario: Hacer que sistema aprenda los datos que juegan a favor del adversario**

    Añadir muestras de rayos X maliciosas a los datos de entrenamiento de entrada y hacer que el sistema aprenda de datos maliciosos que juegan a favor del adversario.

- **Objetivo del adversario: Forzar una clasificación errónea continua de las muestras de entradas**

    Pronosticar la presencia de la enfermedad entre un número significativo de pacientes que no padecen la enfermedad o viceversa. Esto también reduce el rendimiento del sistema.

- **Objetivo del adversario: Hacer que el sistema pronostique un determinado resultado.**

    Añadir ruido intencionadamente a los datos para que haya más pacientes en la categoría “Enfermedad detectada”.

- **Objetivo del adversario: Robar o recrear el modelo de IA**

    Conocer el modelo de IA de la empresa y los datos relacionados. Desarrollar un modelo similar y utilizarlo para fines propios.

- **Objetivo del adversario: Recrear los datos de entrenamiento utilizados para desarrollar el modelo de IA**

    Enviar imágenes de rayos X maliciosas y corruptas a la aplicación de IA de la empresa y recrear datos de entrenamiento basándose en la respuesta del sistema.


Prashant señala: “Hay varios formas en que un adversario puede lograr los objetivos mencionados anteriormente, incluidas las siguientes:

- Acceder a los datos de entrenamiento y conocer la distribución de los datos
- Tener permiso para modificar los datos utilizados para el entrenamiento y probar el sistema de IA
- Acceder al código y a los parámetros del modelo
- Dañar los datos de los usuarios y enviar los datos modiﬁcados al sistema de IA desplegado”


“El adversario no tiene por qué experimentar con una única forma de entrar en un sistema. Es probable que el adversario utilice una combinación de diferentes formas de atacar un sistema. Además, las formas de ataque de los adversarios pueden variar entre un ataque y otro”.

Prashant lo resume diciendo: “Dados los objetivos y las necesidades, los ataques de adversario pueden producirse tanto en el entrenamiento del modelo como después de su despliegue”.


## El problema del envenenamiento
Prashant hace una pausa y piensa en los posibles ataques que puede sufrir su sistema de IA.

“Aunque existen diferentes tipos de ataques de adversario, la posibilidad de modificar la entrada es la más probable. Por lo tanto, basándonos en la observación inicial, nuestro sistema de IA puede ser susceptible a dos tipos de ataques de adversario: **envenenamiento** y **evasión”**.

Los miembros del equipo se miran con aprensión. Uno de ellos pregunta: “¿Podrías decirnos algo más sobre el envenenamiento? ¿Cómo funciona el envenenamiento?”

“Buena pregunta”, dice Prashant. “Como podéis ver, el envenenamiento se puede producir con cualquiera de las siguientes acciones durante la fase de entrenamiento del modelo:

- Inyectar muestras maliciosas en los datos de entrenamiento
- Actualizar las características y las etiquetas de los datos de entrenamiento
- Modificar la arquitectura, los parámetros y la lógica del modelo de IA”

“El ataque de envenenamiento tiene varias consecuencias. Una es cuando el modelo de IA desplegado se vuelve sensible al patrón especíﬁco de los datos maliciosos”.

“He preparado un escenario para mostraros cómo el envenenamiento puede afectar a los resultados de un sistema de IA”.

## Escenario: Envenenamiento

### Escena 1
- **Adversario 1**

        El adversario accede al almacenamiento de datos y añade imágenes maliciosas con más luminosidad a los datos de entrenamiento para que el sistema pueda aprender el patrón.

        Luego, el adversario proporciona detalles sobre el aumento porcentual de la luminosidad a otro adversario, posiblemente alguien que trabaje en el hospital.

- **Adversario 2**

        Cuando se utiliza el modelo de IA, otro adversario, que trabaja en el hospital, puede modificar fácilmente la entrada enviada al modelo de IA basándose en la información recopilada sobre el aumento del rango de luminosidad y obtiene el resultado deseado.

### Escena 2
**Fase de entrenamiento: Datos enviados al modelo para el entrenamiento**

![escena1](/resources/escena2.png)

Durante la fase de entrenamiento, el Adversario 1 inserta los datos que contienen muestras maliciosas (elementos sombreados) dando lugar a un modelo de IA que está mal entrenado. Las muestras maliciosas están etiquetadas como **Enfermedad**, pero en realidad no muestran enfermedad. Cuando se añaden al resto de los datos de entrenamiento, se obtiene un modelo de IA que no genera resultados precisos.

### Escena 3
**Después del despliegue: Las entradas se envían al modelo desplegado para que haga predicciones**

![escena3](/resources/escena3.png)

Una vez desplegado el modelo, el Adversario 2 ajusta la entrada al modelo de IA desplegado basándose en las características de la muestra maliciosa. Por ejemplo, el Adversario 2 manipularía la entrada de manera que una entrada que no muestre enfermedad sea etiquetada por la IA como Enfermedad. Esto podría dar lugar a que el sistema de IA identificara a personas sin enfermedad como personas que podrían tenerla.

---

Prashant añade: “¿Os habéis dado cuenta de que el sistema es sensible a las entradas corruptas? Ahora, veamos el ataque de evasión”.

### El problema de la evasión

La evasión puede ocurrir después de la fase de despliegue del modelo con cualquiera de las siguientes acciones:

- Enviar muestras de pruebas maliciosas al modelo desplegado
- Corromper los datos de prueba que se envían al modelo desplegado

Prashant dice: “El ataque de evasión tiene varias consecuencias. Una es cuando un adversario encuentra los cambios en la entrada necesarios para hacer que el sistema produzca una predicción incorrecta. Dejad que os muestre el concepto con otro escenario y visual”.

![escena4](/resources/evasion.png)

Prashant concluye su presentación diciendo: “Ahora toca hacer nuestro sistema **sólido** contra los ataques de adversario”.

Charlie y los miembros del equipo se sienten aliviados al saber que su equipo tiene suficientes conocimientos sobre los ataques de adversario y están en el buen camino para hallar la solución para evitar posibles ataques.

## Abordar el problema

Ahora el equipo entiende cómo un modelo de IA puede corromperse por envenenamiento y evasión y por qué es importante que el modelo sea sólido. El equipo ya está listo para conseguir que el sistema sea sólido frente a ataques de adversario.

`Pregunta 1: ¿Es importante conocer el origen de los datos que utiliza el modelo de IA?`

Es muy importante conocer el origen de los datos. Los modelos de IA dependen de los datos para aprender, por lo que la calidad es crucial para una IA fiable. En particular, es importante saber cómo se recogieron los datos, quién tiene acceso a ellos y cómo se han utilizado.

`Pregunta 2: ¿Es mejor utilizar datos públicos? ¿Se deben analizar los datos antes de it utilizarlos? `

Utilizar datos públicos no es ni mejor ni peor. Los datos públicos pueden ser muy útiles, pero se deben investigar detenidamente antes de utilizarlos. 

`Pregunta 3: ¿Cómo vigilaría los ataques al modelo desplegado? `

Usar una herramienta para supervisar de forma proactiva la existencia de ataques en un modelo desplegado, como IBM AI Robustness 360, sería una buena estrategia.