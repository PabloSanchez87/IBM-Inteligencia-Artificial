# IA generativa
La inteligencia artificial (IA) generativa es un tipo de IA potente y apasionante que genera contenido nuevo y original, como imágenes, música, vídeos, datos, código, respuestas a preguntas y muchísimas otras cosas. 

Es una tecnología que está revolucionando la forma en que las personas viven, trabajan y disfrutan de su tiempo libre.

## ¿Qué es la IA generativa?

La `IA generativa` es un tipo de inteligencia artificial que crea contenido *nuevo y original* que nunca nadie ha visto anteriormente. 

- La mayoría de los sistemas de IA son modelos de IA discriminativos, que pronostican y clasifican los datos.
- Por el contrario, los modelos de IA generativa son un tipo de sistema de IA de aprendizaje profundo que utiliza algoritmos para generar contenido a partir de una solicitud que se ha presentado, de ahí el nombre de IA generativa. 

Por ejemplo, un modelo discriminativo podría distinguir una bicicleta de un camión y un modelo generativo podría generar una nueva imagen que se asemejara a una bicicleta.

Entonces, lo que distingue la IA generativa de otros sistemas de IA es su capacidad para generar contenido nuevo y que se considera creativo, como imágenes, vídeos, música, datos sintéticos, ensayos, respuestas a preguntas y más. 

## ¿Cómo funciona la IA generativa?

Piense en la IA generativa como un artista virtual. Al igual que un artista humano, necesita inspiración y herramientas para crear algo exclusivo. Sin embargo, en lugar de usar pintura y un lienzo, la IA generativa usa algoritmos y conjuntos de datos.

Este es el proceso general de la IA generativa. 

1️⃣ Primero, una persona alimenta a la IA con una gran cantidad de datos. Datos que podrían ser cualquier cosa, desde imágenes y sonidos hasta texto y números.

2️⃣ A continuación, la IA analiza estos datos, buscando patrones y relaciones entre las diferentes piezas de información. La red neuronal se entrena sobre la base de un conjunto de datos con ejemplos del tipo de resultado que se pretende generar, como imágenes o texto. Durante el proceso entrenamiento, la red neuronal aprende a identificar patrones y relaciones en los datos de entrada y utilizarlos para generar nuevos resultados que sean similares, pero no idénticos, a los ejemplos con los que fue entrenado.

3️⃣ Luego, la IA usa lo que ha aprendido para crear algo nuevo. La red neuronal genera nuevos resultados especificando un valor inicial aleatorio. El valor inicial sirve como punto de inicio para el proceso de generación. La red neuronal procesa el valor inicial y genera nuevos resultados que se basan en los patrones y relaciones que ha aprendido durante el entrenamiento. Por ejemplo, si alguien suministró a la IA una serie de imágenes de perros, podría utilizar sus conocimientos de diferentes razas de perros para crear una imagen de un nuevo perro que no existe en la vida real.

La IA generativa también puede completar tareas más complejas, como grabar historias o componer música. En estos casos, la IA analiza los patrones del lenguaje o la música para crear algo completamente nuevo.

Por supuesto, no toda la IA generativa es perfecta. Como sucede con artistas humanos, a veces los resultados pueden ser un poco extraños o inesperados. Sin embargo, a medida que esta tecnología mejore, no dude que podrá contemplar creaciones aún más impresionantes de IA generativa en el futuro.


## Tipos de modelos de IA generativa 

Veamos los tres principales tipos de modelos generativos de IA: 

- **`Codificador automático variable (VAE)`**

    Considere los modelos de `codificador automático variable (VAE)` como un habilidoso artista que puede mirar una pintura, crear rápidamente un boceto de una versión simplificada de la misma y, a continuación, recrear de la nueva pintura usando solo ese boceto simplificado como referencia. El artista captura los elementos esenciales de la pintura y luego los usa para crear una nueva obra de arte.

    Los `VAE` utilizan un proceso similar. La red "codificadora" comprime los datos de entrada en una representación de una dimensión inferior y la red "decodificadora" reconstruye los datos originales de esta representación comprimida. Esto permite que los VAE capturen la estructura y los patrones subyacentes en los datos, que más tarde pueden generar nuevo datos similares

    ![imagen](/resources/vae.png)

- **`Red generativa antagónica (GAN)`**

    Considere el modelo de `red generativa antagónica (GAN)` como una competición entre un hábil falsificador (el generador) y un talentoso crítico de arte (el discriminador). El falsificador crea pinturas falsas, mientras que el crítico trata de determinar si cada pintura es genuina o una falsificación. A medida que el falsificador mejora su técnica, el crítico se vuelve más perspicaz y este ciclo continúa hasta que el falsificador puede crear falsificaciones casi perfectas.

    En las `GAN`, el generador crea nuevos datos, mientras que el discriminador evalúa la calidad de los datos generados. El generador trata de crear datos que sean lo suficientemente reales para engañar al discriminador, mientras que el discriminador aprende a distinguir mejor entre datos reales y generados. Esta competencia lleva al generador a crear contenido cada vez más realista.

    ![imagen](/resources/gan.png)

- **`Autorregresivo`**

    Imagine un `modelo autorregresivo` como un hábil narrador que escucha el comienzo de una historia y luego la continúa prediciendo lo que va a pasar basándose en las palabras y los eventos que han ocurrido hasta el momento. El narrador utiliza su conocimiento del lenguaje, la gramática y las convenciones de narración de historias para crear una continuación coherente y atractiva de la historia.

    Los `modelos autorregresivos` generan nuevo contenido al predecir el siguiente elemento de un secuencia basándose en los elementos anteriores. Son particularmente adecuados para generar texto porque pueden modelar las probabilidades condicionales de palabras y caracteres en una oración.

    ![imagen](/resources/autoregenerativo.png)


## Ejemplos de aplicaciones de IA generativa

La IA generativa está revolucionando la forma en que las personas viven, trabajan y disfrutan de su tiempo libre. Revisemos los siguientes ejemplos de sistemas y aplicaciones de IA generativa. 

- `CHATGPT`

    OpenAI ha lanzado ChatGPT, un chatbot de IA, en noviembre de 2022. Capaz de interactuar usando lenguaje natural conversacional, esta herramienta de IA va más allá de las tradicionales respuestas del motor de búsqueda que simplemente lista los resultados relacionados. En cambio, ChatGPT sigue las instrucciones especificadas en la solicitud y proporciona una respuesta detallada. Por ejemplo, con ChatGPT, una persona puede especificar la solicitud de texto "Escribe un poema sobre gatos" y el resultado será un poema sobre gatos, en lugar de una lista de sitios web sobre gatos.

- `IBM Watson Discovery`

    IBM Watson Discovery utiliza tecnologías fundamentales, como grandes modelos de lenguaje (LLM), para obtener información relevante sobre qué es lo que no sabemos que no sabemos. Se utiliza ampliamente en investigación genómica para descubrir qué aminoácidos podrían esconderse dentro de la proteína que no se conocían antes y poner de relieve la relación de varios actores o entidades en cuestiones relacionadas con la seguridad de gobierno.

- `DALL-E`

    Desarrollados por OpenAI, se trata de modelos de IA generativa que utilizan texto como entrada en lenguaje natural para generar imágenes digitales. La primera versión de DALL-E solo podía representar imágenes creadas por IA de forma caricaturesca, pero la última versión puede generar imágenes mucho más realistas debido a algoritmos de procesamiento de imágenes mejorados.

- `Bard`

    Bard es una herramienta de IA generativa que Google lanzó, con una capacidad inicial limitada, en marzo de 2023. Bard se basa en modelo BERT (Bidirectional Encoder Representations from Transformers) de Google. No se trata de IA generativa; Google lo desarrolló más bien para procesamiento de lenguaje natural (NLP), especialmente por su capacidad para interpretar los matices de las palabras búsqueda de un usuario. Bard se basa en la funcionalidad de BERT de interacciones de lenguaje natural con la funcionalidad de IA generativa de Bard para generar nuevo contenido. Por ejemplo, los músicos pueden utilizar Bard para componer música y letras.

## Usos industriales de la IA generativa

Ya se está viendo el impacto de la IA generativa, y seguirá aumentando, en una gran diversidad de sectores, entre ellos, deportes, entretenimiento, atención sanitaria, comercio minorista, distribución, banca, fabricación, ingeniería, seguridad, medios de comunicación, agricultura, y la lista continúa y seguirá ampliándose. 

- **Deportes**

En los deportes, la IA generativa puede ayudar a mejorar rendimiento deportivo y fortalecer el vínculo con los aficionados. 

Una aplicación de la IA generativa en el deporte es la creación de planes entrenamiento personalizados. Al analizar los datos biométricos de un atleta, la IA generativa puede crear planes de entrenamiento personalizados que se adapten al nivel físico y los objetivos del atleta. Esta tecnología puede mejorar rendimiento atlético al proporcionar a los deportistas regímenes entrenamiento específicos y eficientes. 

Otra aplicación de la IA generativa en el deporte, en torno al vínculo con los aficionados, es la creación de modelos 3D realistas de los deportistas para utilizar en vídeos deportivos y experiencias de realidad virtual. Mediante el uso de IA generativa, los desarrolladores de juegos pueden crear deportistas virtuales muy realistas y personalizados que pueden interactuar con los usuarios en tiempo real. Esta tecnología puede estimular el vínculo con los aficionados proporcionando a los usuarios experiencias deportivas inmersivas y atractivas. 

La IA generativa puede analizar datos deportivos e identificar patrones y tendencias que pueden poner de relieve estrategias para el entrenamiento y la selección de jugadores. 

En general, la IA generativa tiene el potencial de transformar la forma en que las personas juegan, entrenan y experimentan los deportes, aflorando nuevos niveles de personalización, eficiencia y vinculación.

    Caso práctico 

    Los Miami Dolphins, un equipo de fútbol americano de los Estados Unidos, están utilizando la IA generativa para mejorar el rendimiento de los jugadores y prevenir las lesiones. Están colaborando con una compañía llamada Blue River Technology para desarrollar un sistema de visión por computador que utiliza la IA generativa para analizar secuencias de vídeo de los jugadores e identificar áreas de mejora. El sistema analiza los movimientos del cuerpo de los jugadores e identifica las áreas que podrían estar en riesgo de lesión. Al utilizar la IA generativa de esta manera, los Miami Dolphins pueden anticipar una posible lesión antes de que se convierta en un problema grave, lo que les permite tomar medidas proactivas para prevenir lesiones y mejorar el rendimiento de los jugadores. 

    Esta tecnología tiene el potencial de transformar la forma en que los equipos abordan la salud y el rendimiento de los jugadores, mejorando la calidad general del juego y reduciendo el riesgo de lesiones de los deportistas.


- **Ocio**

En el sector del ocio, la IA generativa puede crear experiencias nuevas e inmersivas para los usuarios. 

Una aplicación de la IA generativa en el sector del ocio es la creación de una amplia variedad de personajes y entornos virtuales, muy realistas y personalizados para videojuegos y experiencias de realidad virtual. Por ejemplo, la IA generativa puede crear expresiones faciales y movimientos del cuerpo realistas para personajes virtuales, mejorando la experiencia y la inmersión del usuario. 


Otra aplicación de la IA generativa en el entretenimiento es la generación de listas de reproducción de música personalizadas. Al analizar el historial de reproducciones y preferencias de un usuario, la IA generativa puede crear listas de reproducción de música exclusivas y personalizadas que satisfagan los gustos de cada persona. 

Esta tecnología puede ampliar la experiencia del usuario mediante la creación de experiencias musicales altamente personalizadas y atractivas. 

    Caso práctico

    Amper Music utiliza IA generativa para crear música original para videojuegos, películas y otros proyectos multimedia. Su plataforma permite a los usuarios entrar parámetros como el estado de ánimo, el género y el ritmo, con los que genera una pieza musical exclusiva y original en tiempo real. Genera música utilizando un modelo generativo que se entrena en un gran conjunto de datos de estructuras y patrones musicales. Mediante el uso de la IA generativa para crear música, Amper Music puede ofrecer composiciones originales y altamente personalizables adaptadas a las necesidades del proyecto de cada persona. 

    Esta tecnología tiene el potencial de transformar la creación de música para proyectos multimedia, permitiendo una producción musical más eficiente y personalizada.

- **Asistencia médica**
En asistencia médica, la IA generativa puede ayudar a mejorar el diagnóstico de enfermedades, imágenes médicas y medicina personalizada. 

Una aplicación de la IA generativa es la generación de imágenes médicas sintéticas, que pueden entrenar algoritmos de aprendizaje automático y mejorar el diagnóstico de las enfermedades. Por ejemplo, la IA generativa puede generar imágenes médicas sintéticas de enfermedades raras, que pueden ser difíciles de obtener en la vida real.
 
Otra aplicación de la IA generativa en la atención sanitaria es la creación de simulaciones médicas. Estas simulaciones pueden ayudar en la formación de los profesionales de atención sanitaria y reducir los errores médicos. Al generar datos de paciente sintéticos, la IA generativa también puede entrenar modelos predictivos y mejorar la medicina personalizada. 

La IA generativa tiene el potencial de transformar la atención sanitaria al permitir la creación de simulaciones médicas realistas, mejorar el diagnóstico de enfermedades y mejorar la medicina personalizada.

    Caso práctico

    PathAI utiliza la IA generativa para mejorar la exactitud del diagnóstico de enfermedades a través del análisis de imágenes médicas. Concretamente, PathAI ha desarrollado un algoritmo de aprendizaje profundo que puede detectar con precisión células cancerígenas en imágenes de patología digital. Este algoritmo fue entrenado con un vasto conjunto de datos de imágenes de patología utilizando un modelo generativo de autocodificador variable (VAE). El VAE aprendió la estructura subyacente de las imágenes de patología para generar imágenes sintéticas que se asemejaran a las imágenes reales del conjunto de entrenamiento. Al entrenar su algoritmo con imágenes tanto reales como sintéticas, PathAI pudo mejorar la exactitud de su algoritmo de detección del cáncer. 

    Esta tecnología tiene el potencial de mejorar la exactitud y velocidad del diagnóstico del cáncer y, en última instancia, mejorar los resultados en los pacientes.

- **Empresarial**

En la empresa, la IA generativa puede ayudar a mejorar la toma de decisiones, personalizar las experiencias del cliente y optimizar la eficiencia operativa. 

Una aplicación de IA generativa en la empresa es la generación de datos sintéticos. Al generar datos sintéticos, las empresas pueden aumentar sus conjuntos de datos existentes y mejorar la exactitud de los modelos predictivos. Por ejemplo, una institución financiera podría generar datos financieros sintéticos para entrenar sus modelos predictivos y mejorar la gestión del riesgo. 

Otra aplicación de la IA generativa en la empresa es la creación de recomendaciones de producto personalizadas. Al analizar el historial de compras y las preferencias de un cliente, la IA generativa puede crear recomendaciones de producto personalizadas a la medida de cada cliente. Esta tecnología puede mejorar la satisfacción del cliente y aumentar las ventas. 

Las personas también están utilizando la IA generativa para mejorar la eficiencia operativa mediante la creación de datos sintéticos para prueba y validación. 

La IA generativa tiene el potencial de transformar la forma en que operan las empresas al mejorar la toma de decisiones, optimizar las experiencias del cliente y aumentar la eficiencia.

    Caso práctico

    Syntiant utiliza la IA generativa para desarrollar chips de aprendizaje profundo de bajo consumo y alto rendimiento para una diversidad de industrias, incluidos dispositivos de hogar inteligentes, dispositivos portátiles y dispositivos controlados por voz. Sus chips de aprendizaje profundo están diseñados para procesar los datos en el propio dispositivo, en lugar de depender de procesos basados en la nube, lo cual puede reducir la latencia y mejorar la privacidad. Para entrenar sus modelos de aprendizaje profundo, Syntiant utiliza un red generativa antagónica (GAN) para crear datos sintéticos, generando nuevas muestras de datos que son similares a los data de entrenamiento. Al entrenar sus modelos tanto con datos reales como sintéticos, Syntiant pudo mejorar la exactitud de sus chips de aprendizaje profundo, haciéndolos más fiables y eficientes. 

    Esta tecnología tiene el potencial de transformar la forma en que las empresas diseñan y fabrican los chips de aprendizaje profundo, dando a luz una nueva generación de dispositivos de bajo consumo y alto rendimiento.

## Limitaciones de la IA generativa

A medida que profundiza en el mundo de la IA generativa, es crucial tener en cuenta las limitaciones y las inquietudes éticas que rodean a estas tecnologías innovadoras. Con modelos como GPT-4, que transforman la forma en que se crea contenido, desde texto e imágenes hasta música, es esencial mantener el equilibrio entre su extraordinario potencial y la necesidad de hacer un uso responsable y equitativo. 

Analice estos desafíos y dilemas éticos cruciales que surgen al aprovechar el potencial de la IA generativa.

### `Limitaciones de la IA generativa`

- **Falta de originalidad:** 

    Los modelos de IA generativa se basan en grandes conjuntos de datos para aprender y generar contenido. Como resultado, es posible que no generen contenido totalmente original sino que imiten patrones a partir de los datos de entrenamiento, lo que puede comportar una falta de creatividad e innovación.

- **Imperfección:** 

    Si bien los modelos de IA generativa se están volviendo cada vez más sofisticados, todavía tienen dificultades para comprender los matices y pueden generar contenido incompleto o sin sentido.

- **Sesgo:** 

    Los modelos generativos de IA pueden perpetuar los sesgos existentes presentes en los datos de entrenamiento, lo cual puede generar contenido sesgado que podría reforzar estereotipos y comportamientos discriminatorios.

- **Recursos computacionales:** 
    
    El entrenamiento y la implementación de modelos de IA generativa requiere una potencia computacional significativa, que puede ser costosa y levantar preocupaciones medioambientales, como el consumo de energía y las emisiones de carbono.


### `Preocupaciones éticas de la IA generativa`

- `Desinformación y contenido falso:` 

    La IA generativa puede crear contenido falso convincente, como la falsificación de vídeos o artículos de noticias falsas, que pueden llevar a la difusión de información errónea y tener graves consecuencias para las personas y las sociedades.

- `Propiedad intelectual y copyright:` 

    La IA generativa puede generar contenido que se asemeja a material protegido por derechos de autor. Esto plantea dudas sobre los derechos propiedad intelectual y sus posibles vulneraciones.

- `Privacidad:` 

    La IA generativa puede crear imágenes y texto realistas sobre las personas, violando potencialmente su privacidad y dañando su reputación.

- `Pérdida del factor humano:` 

    A medida que la IA generativa se vuelve más predominante, existe el riesgo de perder el factor humano en varios dominios creativos, que puede llevar al declive en la apreciación del arte y la cultura creados por humanos.

- `Desempleo y pérdida de puestos de trabajo:` 

    El auge de la IA generativa podría acrecentar la pérdida de puestos del trabajo en las industrias creativas, ya que las máquinas asumen tareas que antes realizaban las personas.
   
**En general, si bien la IA generativa tiene muchas aplicaciones y beneficios potenciales, es importante ser consciente de sus limitaciones y defectos para utilizarla de manera efectiva y ética.**

La IA generativa es una herramienta que está disponible para todos. Entonces, considérela como un cambio real en nuestra forma de pensar.

A medida que los estudiantes utilicen IA generativa, deberán considerar sus limitaciones. Por ejemplo, los estudiantes deberán revisar el contenido generado para evaluar si hay sesgos, errores, omisiones, información errónea o falta de originalidad. El estudiante también deberá tomar acciones correctivas para abordar estas cuestiones.

Además, los instructores conocen la fácil accesibilidad de la IA generativa y su potencial, por lo que las tareas del alumno pueden cambiar de escribir una redacción a evaluar la redacción que la IA generativa ha creado y analizar las limitaciones que incluye, sus implicaciones relacionadas y proporcionar soluciones.