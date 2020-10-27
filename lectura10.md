# Deep Learning based Recommender System: A Survey and New Perspectives

## Introducción

Los sistemas de recomendación son instrumentos esenciales para diferentes industrias, como lo son la de Retail, telefonía, entretenimiento, etc. fundamentalmente porque a través de los diferentes tecnicas de recomendación (KNN, basado en contenido, basado en contexto, sistemas híbridos de recomendación, etc.) las empresas pueden anticipar, entre otras cosas, los comportamientos de consumo, preferencias, y gustos. En la actualidad las empresas buscan diferentes mecanismos que apoyen a los sistemas de recomendación a generar mejores experiencias de los usuarios, es por ello por lo que, con la incorporación del concepto de aprendizaje profundo, se busca mejorar aún más la calidad de la recomendación.

## Visión general de los sistemas de recomendación y el aprendizaje profundo

Existen en la literatura muchas definiciones sobre “Deep Learning”, que hacen referencia a diferentes enfoques, pero dado la línea de investigación que presentas los autores, sería apropiado definirlo como “El aprendizaje de múltiples niveles de representación y abstracción que ayudan a dar sentido a los datos como imágenes, sonido y texto". Esté concepto da una idea central de los temas que son tratados en el presente paper, pero sobre todo que los autores a través de un estudio sistemático tratan de sentar las bases para fomentar modelos de recomendación basados en técnicas de aprendizaje profundo. 
El campo de aplicabilidad de deep learning se enmarca en diferentes campos del conocimiento, desde la tipografía clásica, hasta la genética, donde sus principales aplicaciones se han realizado por medio del procesamiento de imágenes, sonido o audio, entre otras. 

Por otro lado, Deep Learning se asocia al concepto de “Redes Neuronales”, ya que se puede generalizar en que el deep learning es un concepto que surge de la idea de imitar el celebro a partir del uso de hardware y software, para crear una inteligencia artificial, utilizando una capacidad de abstracción jerárquica, es decir, una representación de los datos de entrada en varios “niveles”, o en varias capas, para seleccionar características que son útiles para el aprendizaje; la aplicación de las redes neuronales profundas son utilizadas como técnicas generar recomendaciones de calidad.
Ahora bien, las redes neuronales como técnica para la generación de recomendaciones son eficientes cuando se tiene un gran número de capaz, o neuronas por capa, ya que esto permitirá que se cuente con mayores pesos sobre las representaciones de los inputs, lo que hará que el entrenamiento sea más exhaustivo, pero a su vez el sistema le costará más aprender y por ende el entrenamiento se vuelve mas complejo.

Al analizar los aspectos más relevantes sobre los modelos de recomendación basados en aprendizaje profundo, nos encontramos con las arquitecturas y algoritmos de aprendizaje que utiliza Deep learning, los cuales se basan en las utilizadas por redes neuronales comunes, destacándose en cuanto a la cantidad de capaz de salida, manejo del error en las salidas de las capaz ocultas, y al método de aprendizaje que se utilice. 
El concepto de deep learning puede clasificarse de varias formas, ya que convoca a muchos otros conceptos, sin embargo, se puede destacar el tipo de entrenamiento de las arquitecturas, como también, el tipo de redes que la conforman, es por ello que los diferentes algoritmos de entrenamiento y/o aprendizaje permiten acaparar un gran número de aplicaciones, pero también esto requiere un gran conjunto de datasets de alta calidad tanto para ser usados en el entrenamiento como en las pruebas, ya que sin esta fuente de información valiosa, la arquitectura, el tipo de red, la cantidad de capas ocultas, entre otros parámetros, no generarían buenos resultados, sobre todo para los sistemas de recomendación. Es por ello por lo que los autores plantean tres tipos de limitaciones que van de la mano a los anteriormente descrito.


Las arquitecturas y algoritmos de aprendizaje del deep learning se basan, en su mayoría, redes neuronales “comunes”, comenzando con algoritmos de entrenamiento simples las cuales están compuestas por algoritmos más complejos, en este sentido los autores hacen referencia a categorías o tipos de entrenamiento, los cuales se diferencian por el nivel de control que se tiene sobre el entrenamiento en si mismo, estos son: el supervisado, no supervisado y el híbrido. por otro lado, surge la idea de que dependiendo del tipo de entrenamiento que se realice, será el tipo de algoritmo al cual se entrene. Los autores hacen referencia a diferentes métodos de aprendizaje profundo para lograr recomendaciones de calidad, es así el caso de MLP (retropropagación) que es un algoritmo de entrenamiento que se encarga de propagar el error de la capa del output hacia las capas ocultas, con el fin de calcular los pesos de esas capaz, donde el método de aprendizaje es supervisado.
el método de autoencoder (no supervisado) posee una arquitectura muy similar a la de MLP, pero con algunas diferencias, estas son que en la capa oculta posee menos neuronas que en la capa de salida, y la cantidad de capas en el input son las mismas que en el output. Ambos aspectos hacen que la dimensión de los datos se comprima lo que favorece el entrenamiento y aprendizaje, de ahí su nombre “encoder”.
El método CNN es una red multicapa jerarquizada, que extrae ciertas características de sus capas ocultas, las cuales se organizan en capas convolucionales, submuestreo, y totalmente conectadas. Lo interesante de esté método es que no posee restricciones sobre la dimensión de los datos de entrada o de entrenamiento, lo que sugiere un resultado ajustado, pero con baja resolución, ya que normalmente se utiliza esté método en extracción de características de imágenes. 

Por ultimo, se puede concluir para está primera parte del paper, que es fundamental el uso de los diferentes tipos de aprendizajes, tanto no supervisado, para extraer características, como supervisado, para poder clasificar esas características. También se debe relevar la idea de que no se puede afirmar que un método es mejor que otro, ya que todo depende del diseño y la experiencia que se tenga para entrenar dichas redes, así como también las diferentes formas que se puede optimizar un determinado código, con el fin de implementar arquitecturas que logren imitar de manera más precisa el comportamiento del cerebro.


## Referencias:

Deng, L., & Yu, D. (2014). Deep learning: methods and applications. Foundations and trends in signal processing, 7(3–4), 197-387.

Restrepo Arteaga, G. J. P. (2015). Aplicación del aprendizaje profundo (deep learning) al procesamiento de señales digitales (Bachelor's thesis, Universidad Autónoma de Occidente).