# ¿Cómo aprenden las máquinas?

## Las máquinas aprenden de tres formas generales
Los sistemas de IA utilizan `algoritmos` para predecir y clasificar puntos de datos recopilados tanto de bases de datos informáticas como de fenómenos naturales. Pero los algoritmos tienen tres formas generales en las que pueden `aprender` de estos datos para obtener mejores resultados y proporcionar mejores predicciones:

- Aprendizaje supervisado
- Aprendizaje no supervisado
- Aprendizaje de refuerzo

## Aprendizaje supervisado

En el `aprendizaje supervisado`, los humanos dan a un sistema de IA lo que se llama **datos estructurados**. Se trata de un conjunto de datos y cifras organizados en categorías ordenadas y etiquetadas, de la misma forma en que podría poner información meteorológica en una tabla.

![imagen](/resources/tablaAS.png)

Usando la forma en que se han estructurado los datos, el sistema de IA puede detectar patrones (como los cambios de temperatura de un día a otro en la tabla anterior) y usar esos patrones para predecir datos futuros (como las temperaturas durante la semana siguiente).

Los datos estructurados también pueden tomar la forma de imágenes. Si, por ejemplo, los datos incluyen fotos de flores, algunas de las cuales son rosas y están etiquetadas como rosas, la máquina aprenderá cosas sobre la disposición de los píxeles en esas fotos. Más tarde, cuando vea una nueva foto de rosa y se le pregunte *“¿Qué es esto?”, responderá “rosa”.*

![imagen](/resources/rosa.png)

Como pronto descubrirá, la máquina nunca dará este resultado con absoluta confianza. El sistema dará un valor de confianza para indicar, por ejemplo, que podría predecir con un **85 % de certeza que su respuesta es correcta**. **Cuantos más datos ingiera el sistema, mayor será su precisión.**

## Aprendizaje no supervisado

>![NOTE]
> Suele resultar cómodo referirse a las plantas o a su comportamiento en términos que implican facultades de razonamiento. Por supuesto, las plantas no razonan, por muy razonables que parezcan ser muchas de sus acciones, y atribuirles tales cualidades es cargarlas con atributos absolutamente ajenos al mundo de las plantas.

- Fuente: [Project Gutenberg royalty-texto libre](https://www.gutenberg.org/)

A diferencia del aprendizaje supervisado, el `aprendizaje no supervisado` entrena una máquina con datos no etiquetados, como el texto de un libro. 

Entrenar un sistema de IA con datos no etiquetados es **más difícil** porque el sistema no puede hacer predicciones hasta que haya estructurado los propios datos. En el ejemplo del libro, estructurar los datos implicaría dividir el texto y encontrar relaciones entre palabras y frases. Así pues, los algoritmos exploran los datos y tratan de encontrar una estructura.

Por ejemplo, un sistema puede recibir muchos artículos sobre diferentes tipos de plantas y formar sus propias conclusiones sobre sus atributos. Cuando el sistema ingiere texto nuevo que describe una planta, la identifica y le otorga un valor de confianza.

## Aprendizaje de refuerzo

Con el `aprendizaje de refuerzo`, una máquina no recibe información específica que ingerir. Aprende mediante el **sistema de ensayo y error**. Los algoritmos de la máquina son recompensados cuando realiza una acción correcta y penalizados cuando no es así.

![imagen](/resources/perro.png)