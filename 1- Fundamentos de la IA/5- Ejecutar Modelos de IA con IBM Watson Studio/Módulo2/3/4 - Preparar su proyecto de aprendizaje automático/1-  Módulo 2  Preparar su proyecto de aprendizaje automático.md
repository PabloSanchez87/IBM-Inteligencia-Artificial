# Preparar su proyecto de aprendizaje automático
Imagine que es un prometedor programador en busca de su gran oportunidad. Ayer recibió una llamada de un gran banco alemán. "Unas horas más tarde usted está cruzando el océano en un avión transcontinental." Esta podría ser su oportunidad para hacerse un nombre en el aprendizaje automático de IA. Ha inclinado el asiento hacia delante y ha estudiado el material que le ha enviado el banco.

![imagen](/resources/avion.png)

## Una gran oportunidad

El banco quiere protegerse del riesgo de conceder préstamos que no se devuelven.

- Está preparando el lanzamiento de un nuevo sitio web en el que los clientes podrán presentar solicitudes de préstamos de hasta
10.000 € y, si su crédito es sólido, obtener una aprobación instantánea.

- Por un lado, esto atraerá a clientes que quieran solicitar préstamos rápidamente, sin muchas complicaciones.

- Por otra parte, el banco casi no tendrá tiempo de investigar el riesgo crediticio de cada solicitante y rechazar a los que podrían dejar su préstamo impagado, lo que en última instancia costaría al banco millones de euros.

El banco quiere que dirija el desarrollo de un sistema de aprendizaje automático de IA que pueda **predecir rápidamente el riesgo de conceder un préstamo** a cada cliente que lo solicite.

## El ámbito de su experimento
Utilizando una simulación de IBM Watson Studio, creará un modelo de aprendizaje automático de IA, entrenará algoritmos en el mismo conjunto de datos de préstamos bancarios e impagos y luego los probará de forma competitiva, utilizando datos adicionales, para ver cuál predice los impagos con mayor precisión.

## Tu conjunto de datos 
- Utilizará datos de un banco alemán real ﬁccionados para esta simulación.
- El archivo contiene registros de cinco mil préstamos anteriores.
- Cada registro incluye muchos datos, como la calificación crediticia del cliente, los saldos de sus cuentas bancarias, la finalidad del préstamo, etc., y si el prestatario pagó o no el préstamo.

## Su lista de tareas pendientes
Usando IBM Watson Studio y un conjunto de datos, simulará los siguientes pasos.

1. Configurar un nuevo proyecto en IBM Watson Studio.
2. Crear un modelo de aprendizaje diseñado para pronosticar si es más probable que un solicitante devuelva un préstamo o lo deje de pagar.
3. Entrenar su modelo sobre el 90 % de su conjunto de datos, incluidos los resultados de los préstamos.
4. Probar el modelo sobre un conjunto de datos de prueba (el 10 % restante de los datos del conjunto de datos) para ver qué algoritmo da las mejores predicciones.
4. Guardar el modelo final más fiable como un cuaderno Jupyter.