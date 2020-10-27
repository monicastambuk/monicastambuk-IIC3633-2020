# Deep Learning based Recommender System: A Survey and New Perspectives (Parte II)

A continuación, se abordan algunas de las técnicas o enfoques de deep learning en redes neuronales que son tratadas en el artículo, para luego hacer una conclusión integradora en cuanto a lo presentado por los autores, como preguntas que pueden orientar a futuros trabajos.

Las redes neuronales recurrentes (RNN) son consideradas como otro tipo de redes de Deep learning supervisado como no supervisado. Cuando se habla del modo de aprendizaje no supervisado, el RNN se utiliza para predecir datos secuenciales los que utilizan información existente o anterior. Los RNN son muy eficientes al momento de modelar datos secuenciales, pero a su vez son muy difíciles de entrenar, porque al tener que modelar datos como textos, o discursos hace que RNN le cueste capturar las dependencias a largo plazo, dando lugar a la desaparición del gradiente. Dado el dinamismo de RNN es que hoy en día estos problemas pueden ser tratados más fácilmente utilizando información de segundo orden o estimaciones de curvatura estocástica, así como también se podría mejorar la recomendación utilizando algoritmos de optimización para el entrenamiento de RNNs generativos.

La recomendación secuencial con identificador de usuario (RRN) son construidas sobre RNN, por lo que se basan en arquitectura a la lógica de funcionamiento de estos. Los RRN son capaces de modelar la evolución estacional de los ítems, y los cambios de las preferencias de los usuarios, a lo largo del tiempo. 
Si pensamos en construir un modelo de recomendación basado en RRN, donde se asocie las variables (ítems/usuario) observadas (variables latentes) a un objeto de revisión que se vincule con la predicción de la calificación, según las relaciones de asociación significativas que encuentre, hace que RNN sea eficiente para recomendaciones que se basan en sesiones durante ciertos periodos prediciendo las preguntas que los usuarios podrían hacer basándose en su comportamiento más reciente, lo cual resulta apropiado para usuarios que normalmente están realizando interacciones, pero no así para usuarios que no interactúan cíclicamente, haciendo que la recomendación cometa imprecisiones.

La máquina de Boltzmann restringida (RBM) es un algoritmo de aprendizaje estocástico que deriva de la estadística, en esencia en RBN las neuronas constituyen una estructura recurrente operando de manera binaria, las cuales se pueden clasificar en dos grupos funcionales: visibles y ocultas. Las neuronas visibles proveen una interfase entre la red y el ambiente en el cual operan, mientras que las neuronas ocultas actúan libremente sin interactuar directamente con el entorno (De la Rosa, 2014).

A lo largo de esta revisión, se revela la importancia de la construcción de algoritmos en deep learning que contengan parámetros de aprendizaje bien definidos en las capas de entrada, profundas y de salida, con el fin de minimizar las dificultades de optimización de cada uno de los enfoques de redes neuronales revisados en este documento.

También los autores dejan en evidencia que el aprendizaje profundo es una tecnología emergente. A pesar de los prometedores resultados reportados hasta ahora, es necesario llevar a cabo más trabajo e integrar la experiencia que se ha tenido hasta ahora en aprendizaje profundo, en cuanto a las técnicas que son utilizadas las que buscan mejorar el rendimiento de los modelos de deep learning en aplicaciones más desafiantes como es en inteligencia artificial.

Algunas consideraciones que se deben tener en cuenta al momento de trabajar con los diferentes enfoques explicados en el artículo son la escalabilidad de los datos, el preentrenamiento, entrenamientos paralelos, utilización de clusters de datos para reducir el tamaño del datasets, y con ello alcanzar una mejor optimización de la red neuronal, entre otras.

Por otro lado, el artículo explica como se ha trabajado en métodos de aprendizaje profundo que procesan datasets de alta densidad que logran hacer razonamientos complejos, así como de aquellos que van más allá del tema de reconocimiento de patrones, mediante métodos de aprendizaje supervisados, no supervisados o híbridos. 

El gran desafío de está área del conocimiento es reunir las ventajas de todas las técnicas de aprendizaje profundo tratadas en el artículo, que sirvan como plataforma para así alcanzar fronteras del conocimiento que aún no han sido exploradas con éxito, y con ello poder responder algún día a las siguientes preguntas: ¿Cómo pueden actuar modelos de neurociencia sobre la estructura jerárquica del cerebro, para ayudar a mejorar las arquitecturas de aprendizaje profundo?, o ¿Cómo pueden los diferentes estilos de aprendizaje de los seres humanos diseñar algoritmos de aprendizaje profundo más efectivos y más robustos?

## Referencias.

De la Rosa M, E. D. (2014). El aprendizaje profundo para la identificación de sistemas no lineales. Centro de investigación y de estudios avanzados del Instituto Politécnico Nacional, México DF.

Deng, L., & Yu, D. (2014). Deep learning: methods and applications. Foundations and trends in signal processing, 7(3–4), 197-387.
