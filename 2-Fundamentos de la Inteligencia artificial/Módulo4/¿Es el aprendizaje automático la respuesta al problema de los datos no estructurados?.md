# ¿Es el aprendizaje automático la respuesta al problema de los datos no estructurados?

## ¿Cómo aborda un problema el aprendizaje automático?
`Dos formas de resolver los problemas de los datos oscuros`

Si la IA no depende de instrucciones de programación para trabajar con datos no estructurados, ¿cómo lo hace? El aprendizaje automático puede analizar datos oscuros con mucha más rapidez que un ordenador programable. 

Para ver por qué, consideremos el problema de encontrar una ruta a través del tráfico de una gran ciudad utilizando un sistema de navegación. Se trata de un problema de datos oscuros porque para resolverlo no solo hay que trabajar con un mapa complicado de las calles, sino también con variables cambiantes como el tiempo, los atascos y los accidentes. Veamos cómo dos sistemas diferentes podrían intentar resolver este problema.

- `Ordenador programable`

    Los investigadores podrían cargar en el ordenador una base de datos completa de todas las rutas posibles a través de la ciudad. Se trata de una enorme colección de datos estructurados.

    Luego tendrían que añadir muchos más datos que describieran las condiciones meteorológicas y de tráfico actuales. Esto tendría que revisarse cada pocos minutos para toda la ciudad.

    Luego podrían utilizar un ordenador programable para buscar entre los datos hasta encontrar una ruta de principio a fin. Todo el proyecto requeriría gran cantidad de recursos y de tiempo, si es que se pudiera llevar a cabo.

    ![alt text](/resources/ordandorprogramable.png)

- `IA con aprendizaje automático`

    La IA con aprendizaje automático trataría el problema como se escala un árbol. El sistema intentaría una ruta, como si empezara en la base del tronco. Al llegar a una rama, el sistema se bifurcaría en una dirección y seguiría haciéndolo hasta llegar a un callejón sin salida o al destino deseado.

    Lo haría una y otra vez, y luego compararía las mejores rutas para identificar la más corta. Aunque el trabajo parezca repetitivo, requiere menos recursos y puede completarse más rápidamente.

    ![alt text](/resources/IAaprendizaje.png)

## El proceso de aprendizaje automático es completamente diferente

El proceso de aprendizaje automático tiene ventajas:

- No necesita una base de datos con todas las rutas posibles entre un lugar y otro. Solo necesita saber dónde están los lugares en el mapa.
- Puede responder rápidamente a los problemas de tráfico porque no necesita almacenar rutas alternativas para cada posible situación de tráfico. Observa dónde hay atascos y encuentra la forma de evitarlos mediante ensayo y error.
- Puede trabajar muy rápido. Mientras prueba giros individuales de uno en uno, puede realizar millones de cálculos minúsculos.

Pero el aprendizaje automático tiene otras dos ventajas de las que carecen los ordenadores programables:

- **El aprendizaje automático puede pronosticar.** Eso ya lo sabe. Una máquina puede determinar: “Según el tráfico ahora mismo, es probable que esta ruta sea más rápida que aquella”. Lo sabe porque ha comparado las rutas a medida que las creaba.
- **¡El aprendizaje automático aprende!** Puede darse cuenta de que su coche se ha retrasado por un desvío temporal y ajustar sus recomendaciones para ayudar a otros conductores.

## El aprendizaje automático utiliza el cálculo probabilístico

Hay otras dos formas de comparar los sistemas clásicos y los de aprendizaje automático. Uno es `determinista` y el otro es `probabilístico`.

Veamos qué significan estas dos palabras.

Para un sistema `determinista`, debe existir una enorme estructura predeterminada de rutas, una gigantesca base de datos de posibilidades a partir de la cual la máquina pueda hacer su elección. Si una ruta determinada conduce al destino, la máquina la marca como “SÍ”. Si no es así, la marca como “NO”. Se trata básicamente de un **pensamiento binario**: encendido o apagado, sí o no. Esta es la esencia de un programa informático. La respuesta es verdadera o falsa, no un valor de confianza.

El **aprendizaje automático** es `probabilístico`. Nunca dice “SI” o “NO”. El aprendizaje automático es analógico (como las olas que suben y bajan gradualmente) en lugar de binario (como las flechas que apuntan hacia arriba y hacia abajo). El aprendizaje automático construye todas las rutas posibles hacia un destino y las compara en tiempo real, incluidas todas las variables, como los cambios del tráfico. 

Por lo tanto, un sistema de aprendizaje automático no dice: "Esta es la ruta más rápida”. Dice algo así como: *“Estoy seguro al 84 % de que esta ruta le llevará allí en menos tiempo”*. Puede que lo haya visto usted mismo si ha viajado en un coche con un sistema de navegación GPS actualizado que le ofrece dos o tres opciones con tiempos estimados.

### Si el aprendizaje automático solo ofrece probabilidades, ¿quién toma la decisión ﬁnal?

Esto puede ser literalmente una cuestión de vida o muerte. Supongamos que tiene una enfermedad grave y su médico le deja elegir. ¿Quiere que su médico le prescriba un tratamiento o prefiere el tratamiento que un sistema de aprendizaje automático determine que tiene más probabilidades de éxito?

#### <u>Reflexión</u>

Como sabe, el GPS ofrece diferentes rutas para elegir. El aprendizaje automático deja espacio para que los humanos tomen la decisión final. Usted, o un experto, pueden elegir qué camino tomar basándose en los posibles resultados y en su experiencia personal.

Piense en cómo podría funcionar un sistema de aprendizaje automático con la pregunta médica mencionada anteriormente. Cuando un médico se plantea cómo tratar a un paciente con cáncer, la IA ingiere su historial médico completo, además de todos los trabajos de investigación sobre este cáncer publicados en los últimos años. Esto le lleva unos segundos.

Pero la IA no dice “Haga esto” o “Haga aquello”. Esa sería una solución determinista que excluiría al médico y al paciente de la decisión.

La IA, en cambio, ofrece una declaración probabilística del tipo: “Hay un 92 % de probabilidades de que este tratamiento funcione, y un 87 % de probabilidades de que este otro tratamiento funcione”. Esto es lo que implicaría llevar a cabo cada opción de tratamiento”. Ahora el médico puede consultarle y tomar juntos una decisión. En otras palabras, la IA, el médico y usted han formado una alianza en la que las máquinas predicen pero los humanos juzgan.

### El aprendizaje automático facilita una provechosa asociación entre tecnología y humanos

Los sistemas de IA y los humanos destacan en distintos temas. Por ejemplo, usted, como persona, podría ser muy bueno imaginando posibilidades, mientras que la IA destaca en la identificación de patrones.

## ¿Tiene sentido el sentido común?

Resulta que en ámbitos que van desde la medicina y la educación hasta los estudios sociales y la administración pública, las mejores decisiones se toman equilibrando fuerzas humanas y las de las máquinas. Pero recuerde que hay otra capacidad elusiva pero vital que también debe tenerse en cuenta:` el sentido común.` 

Es posible que conozca gente con mucho sentido común y entienda su valor. También puede que haya visto o leído resultados de máquinas que no tienen sentido. Sin embargo, ambas partes pueden contribuir.

El `sentido común` se basa en muchas generalizaciones complejas combinadas con compasión y abstracciones. Actualmente, solo los humanos son capaces de utilizar bien el sentido común. El problema es que el sentido común suele estar contaminado por prejuicios que pueden distorsionar su juicio. Los sistemas de IA pueden equilibrarlo. Siempre que los sistemas de IA reciban datos imparciales y estén entrenados para ello, podrán hacer recomendaciones libres de prejuicios. La colaboración entre humanos y máquinas puede conducir a decisiones sensatas.