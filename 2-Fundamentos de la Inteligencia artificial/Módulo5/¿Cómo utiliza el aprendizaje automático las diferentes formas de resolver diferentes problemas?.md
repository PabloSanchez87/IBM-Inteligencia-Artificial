# ¿Cómo utiliza el aprendizaje automático las diferentes formas de resolver diferentes problemas?
El aprendizaje automático resuelve problemas de tres formas: 
- Aprendizaje supervisado
- Aprendizaje no supervisado
- Aprendizaje de refuerzo
---

## Aprendizaje supervisado

El `aprendizaje supervisado` consiste en proporcionar a la IA suficientes ejemplos para hacer predicciones precisas. 

Todos los algoritmos de aprendizaje supervisado necesitan **datos etiquetados**. Los datos etiquetados son datos que se agrupan en muestras etiquetadas con una o más etiquetas. Es decir, para aplicar el aprendizaje supervisado tiene que decirle al modelo:

1. Cuáles son las características principales de una cosa, también llamadas rasgos
2. Qué es realmente esa cosa

Por ejemplo, la información puede consistir en dibujos y fotos de animales, algunos de los cuales son perros y están etiquetados como "perro". La máquina aprenderá identificando un patrón correspondiente a "perro". Cuando la máquina vea una nueva foto de un perro y se le pregunte "¿Qué es esto?", responderá "perro" con gran exactitud. Esto se denomina **problema de clasificación**.

## Aprendizaje no supervisado
En el `aprendizaje no supervisado`, una persona proporciona a una máquina una gran cantidad de información, formula una pregunta y luego deja que la máquina descubra por sí misma cómo responder a la pregunta. 

Por ejemplo, la máquina puede recibir muchas fotos y artículos sobre perros. Clasificará y agrupará la información sobre todos ellos. Cuando se le muestre una nueva foto de un perro, la máquina podrá identificar la foto como un perro, con una precisión razonable.

```
Se produce un aprendizaje no supervisado cuando no se da al algoritmo un resultado específico de tipo "incorrecto" o "correcto". En su lugar, se dan al algoritmo datos no etiquetados.
```	

**El aprendizaje no supervisado es útil cuando no se sabe cómo clasificar los datos.** 

Por ejemplo, imagine que trabaja para una entidad bancaria y dispone de un gran conjunto de datos financieros de clientes. No sabe qué tipo de grupos o categorías utilizar para organizar los datos. En este caso, un algoritmo de aprendizaje no supervisado podría encontrar agrupaciones naturales de clientes similares en una base de datos, y luego podría describirlas y etiquetarlas. 

Este tipo de aprendizaje tiene la capacidad de descubrir similitudes y diferencias en la información, lo que lo convierte en una solución ideal para el análisis exploratorio de datos, las estrategias de venta cruzada, la segmentación de clientes y el reconocimiento de imágenes.

## Aprendizaje de refuerzo

El` aprendizaje de refuerzo` es un modelo de aprendizaje automático similar al aprendizaje supervisado, pero el algoritmo no se entrena utilizando datos de muestra. Este modelo aprende sobre la marcha con el método de ensayo y error. Se refuerza una secuencia de resultados correctos para elaborar la mejor recomendación para un problema determinado. La base del aprendizaje de refuerzo es recompensar el comportamiento "correcto" y castigar el "incorrecto".

Quizás se pregunte qué significa "recompensar" a una máquina. Buena pregunta. Recompensar a una máquina significa dar a su agente un refuerzo positivo por hacer lo "correcto" y un refuerzo negativo por hacer lo "incorrecto". 

Cuando una máquina aprende por ensayo  y error, intenta una **predicción** y luego la compara con los datos de su **corpus**. 

- Cada vez que la comparación es positiva, la máquina recibe una respuesta positiva (una recompensa).
- Cada vez que la comparación es negativa, la máquina recibe una retroalimentación negativa (una penalización).

Con el tiempo, las predicciones de una máquina serán cada vez más precisas. Lo logra **automáticamente**, basándose en la información recibida, en lugar de mediante la intervención humana.