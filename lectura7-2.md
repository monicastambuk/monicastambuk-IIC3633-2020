# Multi-Armed Recommender System Bandit Ensembles

Los Sistemas de Recomendación tienen como principal objetivo brindar a los usuarios resultados de búsqueda cercanos o adaptados a sus necesidades, realizando predicciones de sus preferencias y entregando aquellos ítems que podrían acercarse más a lo esperado (Chesani, 2002), (Mizhquero, 2009). 


Los sistemas de recomendación híbridos combinan múltiples técnicas de recomendación con la intención de tratar, eliminar o manejar las fallas que se producen si se utilizara una sola técnica de recomendación. La idea acá es que la combinación de técnicas como la basada en contenido, y el filtrado colaborativo proporcione recomendaciones y por ende predicciones más precisas y efectivas. para ello los autores utilizan implementaciones separadas de algoritmos o combinaciones de resultados obtenidos de diversas estrategias, lo que permite la tarea de recomendación se transforme en una acción cíclica donde una gran parte de la entrada del sistema se recoge de la reacción de los usuarios a las recomendaciones que se entregan. El proceso cíclico otorga la oportunidad de que el sistema aprenda y logre realizar recomendaciones mas eficaces, dada la combinación de los algoritmos combinados, y con ello mejorar la recomendación progresivamente.


La perspectiva de los autores sobre las diferentes técnicas de recomendación, como KNN, Thompson, most popular, matrix factorization, ramdon, dynamic ensemble, y ｮ -greedy bandit, que son utilizadas en la experimentación, indican que a partir de estos modelos se debe elegir cual es el siguiente a utilizar a partir de sus recomednaciones anteriores, ya que el conjunto de modelos reducirá progresivamente el tráfico que es asignado para esa recomendación en particular. Por otro lado, es interesante relevar que, si un modelo es mejor que los demás, automáticamente The Bandit reducirá al mínimo la fracción de usuarios de ese modelo en particular, para así seleccionar otras opciones de recomendación para el usuario.


En contraste, considero que al proponer en el paper que la utilización de métodos aislados realmente no beneficia a la recomendación y por ende el feedback de los usuarios, es muy certera, por lo que concluyo que The Bandit es capaz de obtener mejores resultados de manera combindad que utilizando algoritmos por separado, solo se debe tener presente que está experimentación se realizo offline, lo que podría generar sesgos en los feedback, ya que realiza la evaluación de la recomendación con datos ya registrados o que se encuentran en la base de datos del sistema, lo que podría generar problemas de input a nuevos usuarios, nuevos ítems y por tanto a elevar el costo para la obtención de nuevos feedback.


## Referencias.

Chesani, F. (2002). Recommmendation Systems. Corso di laurea in Ingegneria Informatica.

Mizhquero, K. (2009). Análisis , Diseño e Implementación de un Sistema Adaptivo de Recomendación de Información Basado en Mashups. Revista Tecnológica ESPOL.
