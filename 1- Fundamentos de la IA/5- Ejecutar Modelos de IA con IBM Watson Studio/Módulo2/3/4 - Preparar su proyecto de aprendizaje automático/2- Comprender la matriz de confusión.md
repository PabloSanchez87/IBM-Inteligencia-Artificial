# Comprender la matriz de confusión

El servicio AutoAI ha generado un proyecto ganador. Cuando ha seleccionado este proyecto, ha podido obtener información sobre el mismo, incluida la matriz de confusión. La matriz de confusión le permite calcular el rendimiento de su modelo. Echemos un vistazo. Acercar para examinar de cerca.

![imagen](/resources/matriz.png)

En el gráfico se puede ver que el modelo tiene una precisión de **0,784** en los datos de Prueba. Eso significa:

- Alrededor del **78 %** de las veces, el modelo predice con exactitud si alguien es un riesgo bueno para un préstamo.
- Aproximadamente el **22 %** de las veces, el modelo hace una predicción inexacta.

Esta información es valiosa.

Pero esto es solo una visión general. ¿Qué tipo de errores está cometiendo la IA? Ahí es donde entra la matriz de confusión. La matriz de confusión es una representación visual del rendimiento del modelo de IA. Examina los resultados **Observados** frente a los **Previstos**.

## Términos

Para comprender la matriz de confusión, deberá entender algunos términos.

![imagen](/resources/terminos.png)

## Resultados

Ahora que entiende la estructura de la matriz de confusión, vamos a examinar la matriz de confusión que ha generado su experimento.

![imagen](/resources/matriz2.png)

IBM Watson codifica por colores la matriz de confusión para facilitar su lectura. El verde indica más correcto y el azul indica menos correcto. ¿Cuál sería su conclusión?

- El sombreado verde de las celdas Verdadero positivo y Verdadero negativo le indica que su modelo es muy bueno para predecir Sin riesgo cuando la persona no constituye un riesgo (Verdadero positivo) y Riesgo cuando la persona constituye un riesgo (Verdadero negativo).
- Sin embargo, el modelo de IA no es tan bueno cuando se trata de falsos positivos (predecir que alguien constituye un riesgo cuando no es así) y falsos negativos (predecir que alguien no constituye un riesgo cuando es así).

El equipo está impresionado con la velocidad y la precisión del modelo. Pero quieren que el modelo sea aún más preciso. Lo tiene en cuenta y les dice que el conjunto de datos que ha utilizado para crear el modelo era pequeño y que, con más entrenamiento, el modelo de IA debería ser más preciso. El equipo sonríe. Hay muchos datos en sus registros; están ansiosos por obtener el modelo y empezar a trabajar con él.

## ¡Buen trabajo!

Ha creado un modelo de IA con cuatro algoritmos, los ha entrenado con el conjunto de datos del banco y luego ha ejecutado cada algoritmo para obtener las predicciones sobre los solicitantes con más probabilidades de no devolver sus préstamos.

Ha sido un trabajo complicado. Reúne a sus compañeros informáticos y les hace un repaso rápido de sus pasos.

- Ha utilizado AutoAI para construir sus modelos, asociándolos con el servicio de aprendizaje automático que había creado anteriormente.
- Ha creado un experimento, adjuntando y conﬁgurando sus datos.
- Ha seleccionado una columna predecible en el conjunto de datos como eje X.
- Ha ejecutado el experimento.
- Ha mostrado la matriz de confusión, lista para aplicarla en la última parte de su proceso.