# El ecosistema del aprendizaje profundo
## Introducción

Las redes neuronales se inspiran en las células del cerebro humano. En este módulo, aprenderá cómo las redes neuronales pueden mejorar enormemente la capacidad de un sistema de IA para analizar datos complejos y mejorar sus resultados mediante el método de ensayo y error.

## Inspirado en el cerebro humano

Hoy en día, el aprendizaje automático ha evolucionado hasta convertirse en una colección de potentes aplicaciones denominadas `ecosistema del aprendizaje profundo`. La base de muchas aplicaciones se llama red neuronal. Una **`red neuronal`** utiliza circuitos electrónicos inspirados en la forma en que se comunican las neuronas en el cerebro humano.

![imagen](/resources/redhumana.png)

En el cerebro, las células llamadas neuronas tienen un cuerpo celular en un extremo, donde reside el núcleo, y un largo axón que conduce a un conjunto de terminales ramificadas en el otro extremo. Las neuronas se comunican entre sí recibiendo señales en el axón, modificándolas y transmitiéndolas a través de los terminales a otras neuronas. Los investigadores calculan que un cerebro humano tiene unos 100.000 millones de neuronas, cada una conectada a otras 10.000 neuronas.

![imagen](/resources/aprendizajeprofundo.png)

En una red neuronal, un componente llamado **perceptrón** actúa como el equivalente de una sola neurona. Un **perceptrón** tiene una capa de **entrada**, una o más **capas ocultas** y una **capa de salida**. Una señal entra en la capa de entrada y las capas ocultas ejecutan algoritmos sobre la señal. Luego, el resultado se pasa a la capa de salida.

![imagen](/resources/entradabiologica.png)

`Entrada biológica`

- Una señal pasa del terminal de una neurona al axón de otra, mediante una combinación de reacciones eléctricas y químicas.

![imagen](/resources/entradarespuestabiologica.png)

`Entrada y respuesta biológica`

- Las señales entran en el cuerpo de la célula, que calcula una respuesta que luego emerge del otro extremo de la célula.

![imagen](/resources/aprendizajeprofundo.png)

`Entrada y respuesta de la red neuronal`

- Del mismo modo que una señal pasa a través de una neurona y es modificada por ella, una señal entra en la **capa de entrada** de un perceptrón y luego pasa a través de los algoritmos de los nodos de la **capa oculta** y es modificada por ellos. Luego la respuesta emerge de la capa oculta y se transmite hacia adelante desde la **capa de salida** de la neurona.

Las capas ocultas de una red neuronal se asemejan, como grupo, al largo cuerpo celular que conecta las dendritas con los axones dentro de una célula del cerebro humano. Esas capas ocultas contienen nodos. Cada nodo ejecuta un algoritmo y bits de código adicional para probar y ajustar su resultado. Cuando el valor alcanza un determinado umbral, el nodo se “activa”.

>[!NOTE]
> Un nodo suele utilizar una función sigmoidea para determinar si se debe “activar” o no. Como se ha explicado anteriormente, una función sigmoidea puede generar una respuesta binaria, como SÍ o NO. La respuesta binaria indica al nodo si se debe activar o no. Puedes pensar en el umbral como un obstáculo que una solución debe saltar para dar un resultado de SÍ.

Si hay otros nodos conectados al nodo, se activan cuando les llega la señal. Si los otros nodos alcanzan sus propios umbrales, se activan. La señal desciende en cascada a través de las capas ocultas de una forma parecida a cómo pasa una señal por el cuerpo de una célula del cerebro humano.

Tenga en cuenta que estos parecidos son solo similitudes. Las redes neuronales se inspiran en el cerebro humano, pero las actividades que se desarrollan dentro de ellas son muy diferentes.

## Una ruta por una red neuronal

El funcionamiento de una red neuronal es pura matemática. La red no “piensa”; calcula. Pero utiliza esos cálculos para crear un resultado que los humanos puedan interpretar como una respuesta o una recomendación.

Por ejemplo, imagine la siguiente situación: Marc está decidiendo si va a pedir una pizza. Marc se pregunta cómo respondería una red neuronal a la pregunta: “¿Debería pedir una pizza?”. El siguiente escenario muestra el flujo paso a paso de la toma de decisiones a medida que los distintos nodos ejecutan algoritmos y transmiten sus resultados.

1. **“¿Debería pedir una pizza?”**
2. **¿Debería pedir una pizza? Se lo preguntaré a la red neuronal.**

    ![imagen](/resources/pizza1.png)
    
    Esta red neuronal ya ha sido entrenada. Ha aprendido muchas cosas sobre el comportamiento anterior de Marc a la hora de comprar pizzas, así que está preparada para sugerir si es probable que Marc pida una hoy. Hoy, la red neuronal va a invocar tres cosas que ha observado:

    1. Marc suele realizar sus pedidos con antelación.
    2. Marc está intentando perder peso, por lo que últimamente pide pizza con menos frecuencia.
    3. El correo electrónico de Marc incluye un cupón para una pizza gratis.

    Ahora Marc pregunta: “¿Es probable que hoy pida pizza?”

3. **¿Pedido con antelación?**

    ![imagen](/resources/pizza2.png)

    Un nodo de la capa oculta busca el patrón de compra de Marc y observa que Marc siempre hace pedidos con antelación. El nodo asigna al pedido con antelación un valor de 1. (Para mayor claridad, se utilizan los valores uno (1) y cero (0).)ç

    El sistema ha aprendido algo más sobre los pedidos de Marc: Marc asigna una mayor **ponderación** a unos factores que a otros. Así, el sistema asigna a cada factor una ponderación basada en el comportamiento anterior de Marc.

    Cuanto más tiende Marc a hacer algo, mayor es la ponderación.

    Marc siempre hace pedidos con antelación, por lo que el sistema da una ponderación de 3 al factor de pedido con antelación de hoy. Multiplicando el valor inicial (1) por la ponderación (3), el nodo obtiene un valor de salida de 3.

    Hasta ahora, el valor total del factor de ordenación es:

        1 x 3 = 3

4. **¿Debería pedir ensalada?**

    ![imagen](/resources/pizza3.png)

    El siguiente nodo de la capa oculta registra que, últimamente, Marc pide ensalada la mitad de las veces. Así que el nodo asigna a la opción ensalada un valor inicial de 0,5.

    El sistema también sabe que Marc no es constante a la hora de evitar la pizza en su dieta, por lo que le da la opción de pedir una ensalada con una ponderación de 0,5.

    El valor inicial (0,5) multiplicado por la ponderación (0,5) es 0,25.

        0,5 x 0,5 = 0,25

4. **¿Cupón gratis?**

    ![imagen](/resources/pizza4.png)

    El tercer nodo de la capa oculta sabe que Marc tiene un cupón para una pizza gratis. Así que asigna al cupón un factor de 1.

    Por último, el sistema observa que Marc siempre utiliza los cupones gratuitos en cuanto los recibe. Así que el sistema multiplica el factor del cupón por una ponderación de 5:

        1 x 5 = 5

    Con estos algoritmos ya ejecutados, el sistema avanza los resultados de los tres nodos de la capa oculta al nodo de salida.
    
5. **Ponderación de las respuestas**

    ![imagen](/resources/pizza5.png)

    La capa oculta tiene que realizar un paso más: utilizar un algoritmo de activación. Se trata de un algoritmo que solo se “activará” cuando la ponderación total de los algoritmos de preferencias de Marc alcance un determinado umbral.

    Supongamos que, para la pizza, el umbral se alcanza cuando la ponderación total es mayor o igual a 6. El nodo ﬁnal suma los tres valores de los factores. El resultado es 8,25.

        3 + 0,25 + 5 = 8,25

    Este valor es mayor que el umbral de 6, así que...

    **¡hoy se cena pizza!**


Como muestra el escenario anterior, en una red neuronal, los nodos individuales de una capa trabajan en algoritmos simultáneamente. Los nodos no solo calculan, sino que también se ajustan en respuesta a factores externos. Esto es **`aprendizaje automático`**.

## El aprendizaje automático suele ser ensayo y error

Una red neuronal toma decisiones basándose en lo que aprende. Pero puede que aún se pregunte cómo empieza a aprender una red neuronal. **La respuesta es: ajustándose continuamente, en un proceso que los humanos denominan ensayo y error.**

Una vez que una red neuronal ha ingerido o ya ha aprendido cierta cantidad de datos, los almacena en su “cuerpo de información”, llamado **`corpus`**. 

Para aprender, la red neuronal compara constantemente los nuevos datos o los resultados de sus cálculos con su corpus. Si la red determina que los nuevos datos o resultados no coinciden con los patrones que ya ha establecido, los modiﬁca para conseguir un resultado mejor. A veces, para mejorar una sola comparación, la red prueba cientos o miles de modiﬁcaciones muy rápidamente y realiza ajustes. Luego realiza pruebas para determinar si la comparación está mejorando. Así, paso a paso, la máquina aprende.

### El aprendizaje automático hace muchas conjeturas

El aprendizaje automático utiliza su enorme velocidad de cálculo para hacer muchas conjeturas que lo acercan cada vez más a una respuesta. 

**Hace su primera conjetura al azar, establece esa conjetura como variable y luego comprueba la precisión de la conjetura con los datos antiguos y nuevos. Luego realiza un ajuste en la variable y vuelve a intentarlo.** 

Mediante procesos matemáticos que le ayudan a elegir los ajustes del tamaño adecuado, el sistema sigue intentándolo, acercándose cada vez más a la perfección, pero sin alcanzarla nunca del todo.

Por eso muchos sistemas de IA emiten un valor de conﬁanza junto con una respuesta o predicción. Por ejemplo, un sistema de predicción de tratamientos eficaces para un paciente con cáncer podría dar como resultado la recomendación de dos o tres enfoques, junto con una medida de la confianza que tiene en que cada tratamiento pueda funcionar. Esto refleja cómo llega el sistema a esas decisiones. El sistema también deja la decisión final en manos del médico que conoce al paciente.

Cualquier ordenador puede realizar al menos un tipo rudimentario de aprendizaje automático basado en ciclos de estimación. El aprendizaje automático clásico también puede hacerlo. Pero dependiendo de la complejidad de un problema, un ordenador convencional o incluso un sistema clásico podría tardar días (o siglos) en llegar a una conclusión.

En muchas aplicaciones modernas de la IA, los datos no estructurados implicados son lo suficientemente complejos como para abrumar incluso a un simple perceptrón, como por ejemplo, decidir si pedir pizza en una lección anterior. Así pues, un perceptrón requiere **más capacidad mental** en forma de `aprendizaje profundo`. El aprendizaje profundo se basa en múltiples capas de nodos (incluso múltiples grupos de perceptrones con múltiples capas de nodos) para terminar el trabajo en un tiempo razonable.

## De los perceptrones al aprendizaje profundo

![imagen](/resources/redneuronalprofunda.png)

Marc ha pedido una pizza utilizando un perceptrón en el que una capa oculta de nodos ha hecho la mayor parte del trabajo. Pero los sistemas avanzados de IA utilizan muchas capas ocultas cuyos algoritmos transmiten los resultados de cálculos sofisticados. 

Esto se llama `red neuronal profunda (DNN)`. Las capas de DNN se pueden organizar en grupos o en bloques elaborados de grupos para obtener mayor potencia. Las DNN pueden incluso duplicarse en equipos competidores que juzgan y aprenden de los errores de los demás, sin intervención humana. Esto crea un potente aprendizaje de refuerzo.

Ejemplos de DNN:

- **Identificación de fotos**

    Los tecnólogos pueden utilizar una DNN para examinar una foto histórica de personas o lugares desconocidos. La DNN compara lo que encuentra con millones de imágenes de su corpus y proporciona nombres completos y posibles ubicaciones.

- **Construcción de viviendas**

    Las inmobiliarias pueden utilizar una DNN para predecir la evolución de los precios de la vivienda en toda una ciudad o en un estado. Las DNN pueden ayudar a las inmobiliarias a predecir las tendencias del negocio y determinar cómo invertir en materiales y mano de obra.

- **Vehículos sin conductor**

    Los ingenieros de automoción pueden utilizar las DNN para modelar millones de situaciones de conducción y ayudar a los vehículos autónomos a navegar con seguridad.

- **Tratamiento del cáncer**

    Los radiólogos pueden utilizar las DNN para identificar variaciones en las imágenes de resonancia magnética que, de otro modo, serían invisibles para el ojo humano.

    Los radiólogos pueden recibir alertas tempranas de cánceres potencialmente tratables.