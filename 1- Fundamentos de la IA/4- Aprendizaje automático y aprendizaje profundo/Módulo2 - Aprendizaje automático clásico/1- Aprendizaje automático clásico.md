# Aprendizaje automático clásico
El `aprendizaje automático clásico` comenzó en la década de 1950. Los sistemas de IA **aprendían** ingiriendo datos y mejorando en el reconocimiento de patrones. Los sistemas de IA podían predecir cosas como la distancia entre puntos o la intensidad de los valores.

Como todo aprendizaje automático, el clásico depende de algoritmos. Recordemos que los algoritmos son expresiones matemáticas que generan un resultado. El aprendizaje automático clásico utiliza un pequeño número de algoritmos en una disposición relativamente sencilla. A veces, los algoritmos de aprendizaje automático son **binarios**, lo que significa que solo generan uno de dos valores. Los resultados binarios típicos pueden ser un **1** o un **0**, un **SÍ** o un **NO**, y un **VERDADERO** o un **FALSO**.

Otros algoritmos del aprendizaje clásico son más complicados. Por ejemplo, su resultado podría representarse como una posición en un gráfico multidimensional en lugar de “este punto” o “aquel punto”. Estos son tres algoritmos típicos que se utilizan en la informática clásica:

- Árbol de decisión
- Regresión lineal
- Regresión logística

## Árbol de decisión

Un `árbol de decisión` es un algoritmo de **aprendizaje supervisado**. Funciona como un *diagrama de flujo*. Un diagrama de flujo es como un árbol de decisión invertido. El diagrama de flujo tiene un **nodo raíz** (donde empieza el diagrama), ramas que conectan con **nodos internos** y más ramas que conectan con **nodos hoja**.

![árbol](/resources/arbol.png)

¿Cómo utiliza un árbol de decisión un sistema de aprendizaje automático clásico? Comienza con un conjunto conocido de datos, como este.


| Día  | Previsión | Temperatura | Nivel de humedad | Viento  | ¿Hacer surf? |
|------|-----------|-------------|------------------|---------|--------------|
| D1   | Soleado   | Calor       | Alto             | Débil   | No           |
| D2   | Soleado   | Calor       | Alto             | Fuerte  | No           |
| D3   | Nublado   | Calor       | Alto             | Débil   | Sí           |
| D4   | Lluvia    | Suave       | Alto             | Débil   | Sí           |
| D5   | Lluvia    | Frío        | Normal           | Débil   | Sí           |
| D6   | Lluvia    | Frío        | Normal           | Fuerte  | No           |
| D7   | Nublado   | Frío        | Normal           | Débil   | Sí           |
| D8   | Soleado   | Suave       | Alto             | Débil   | No           |
| D9   | Soleado   | Frío        | Normal           | Débil   | Sí           |
| D10  | Lluvia    | Suave       | Normal           | Fuerte  | Sí           |
| D11  | Soleado   | Suave       | Normal           | Fuerte  | Sí           |
| D12  | Nublado   | Suave       | Alto             | Fuerte  | Sí           |

Con algunos cálculos matemáticos, un sistema clásico de IA puede digerir esta tabla más información adicional sobre fechas y olas, posiblemente de otra fuente. Luego el sistema puede hacer una predicción razonablemente precisa sobre si ir a hacer surf hoy, o cualquier otro día.

## Regresión lineal
La `regresión lineal` es otro tipo de algoritmo. Se refiere a datos que **pueden representarse gráficamente como una línea recta**. Por ejemplo, una empresa podría pensar que un mayor gasto en publicidad conduce a un aumento de las ventas. Esto podría representarse gráficamente como una serie de puntos que forman una línea recta ascendente, como se muestra aquí.

![imagen](/resources/regresión.png)

Como sugiere el gráfico, a medida que aumenta la publicidad, también lo hacen las ventas. Hay muchos resultados posibles (diferentes cantidades de publicidad conducen a diferentes cantidades de ventas), pero el cambio sube en el gráfico en línea recta.

La situación se complica si las ventas reales de una empresa muestran datos diferentes para productos diferentes, en lugares diferentes, en fechas diferentes, etc. Con un gran número de variables e instancias, el gráfico se convierte en una masa de puntos que no forman una línea recta. Si no se ajusta, el gráfico resultante es demasiado general para ayudar a una empresa a tomar una buena decisión. Ahí es donde la `regresión lineal` puede ayudar. La **regresión lineal puede aprender todas las variables y luego calcular una predicción razonablemente precisa** de cómo influirá la publicidad en las ventas en un momento y lugar determinados del futuro.

En efecto, la regresión lineal *resuelve la masa de puntos en una línea “más probable”* que puede utilizarse para una *predicción simple*.

## Regresión logística
En algunas situaciones, una relación no se desarrolla en línea recta. A veces, *un sistema utiliza valores que requieren un tipo de resultado especíﬁco y limitado, como algo entre 0 y 1 (o NO y SÍ)*. En esta situación, un gráfico puede formar lo que se denomina una **función sigmoidea**, o una curva en forma de S, como se muestra en este ejemplo. Para cualquier conjunto de variables, el resultado (que es un punto de la curva S) está comprendido entre 0 y 1.

![imagen](/resources/regresionlog.png)

He aquí un ejemplo real. Consulte el gráfico anterior. Supongamos que quiere saber cuántas horas tiene que estudiar para aprobar un examen. Tiene el número de horas de estudio y el resultado de aprobado o suspenso de otros 10 estudiantes. “Horas de estudio” es una cantidad variable, en este caso comprendida entre 1 y 5 horas. Aprobar el examen es una cuestión NO o SÍ (REPROBADO o APROBADO).

Si se trazan estos dos factores juntos como una regresión logística, se obtiene una curva en S en la que 0 horas de estudio dan como resultado una probabilidad muy baja de aprobar, mientras que 5,5 horas dan como resultado una probabilidad muy alta. Como se muestra en el gráfico, la variable “Horas de estudio” está en el eje x. Los valores del eje y representan los valores de la variable “Probabilidad de aprobar un examen”.

    He aquí otra forma de interpretar el gráfico: predice que estudiar al menos 4 horas le ofrece muchas posibilidades de aprobar el examen.

### Comparación entre la regresión lineal y logística
Las `regresiones lineal` y `logística` resultan útiles en los siguientes casos:

- Una `regresión lineal` responde a una pregunta como “Si esto aumenta en X, ¿cuánto aumentará Y?”.
- Una `regresión logística` responde a una pregunta del tipo “Si esto aumenta en X, ¿el valor de Y se acercará más a 0 o a 1?”.

## El aprendizaje automático clásico no está obsoleto

El `aprendizaje automático clásico` puede verse superado, en algunas tareas, por métodos más nuevos que forman parte del ecosistema del aprendizaje profundo. Pero sigue habiendo razones para utilizar el aprendizaje automático clásico. Esto incluye:

- **Trabajar con datos estructurados**

    El aprendizaje automático clásico se utiliza principalmente con datos estructurados procedentes de bases de datos, como las horas estudiadas en comparación con las calificaciones obtenidas.

- **Menor coste de funcionamiento**

    El aprendizaje automático clásico requiere menos potencia de cálculo que los ecosistemas de aprendizaje profundo. Pueden funcionar en ordenadores menos caros con procesadores menos potentes, lo que abarata el precio para pequeñas empresas, comunidades o sistemas sanitarios que comparten el tiempo de uso en acuerdos de pago por uso.

- **Más fácil de interpretar**

    Las redes profundas son tan complejas que ni siquiera los investigadores de IA acaban de entender lo que ocurre en su interior. Por lo tanto, los investigadores de IA no siempre son capaces de determinar cuándo los sistemas de redes profundas están generando resultados no válidos. En comparación con estos misterios, los resultados clásicos pueden ser más fáciles de depurar y es más sencillo comprobar su exactitud y falta de sesgo.