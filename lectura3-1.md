#Performance of Recommender Algorithms on Top-N Recommendation Tasks

En sistemas de recomendación el objetivo central es encontrar unos pocos ítems específicos que se supone son los más atractivos para un usuario determinado, dado esto el paper se centra en la recomendación de los Top-N donde su trabajo es reproducir una lista de los mejores ítems que serán recomendados a un usuario en particular, teniendo como métrica de medición la precisión, ya que esta es más adecuada que RMSE.

La contribución que buscan los autores con esté paper es mostrar que no existe una relación entre las métricas de error y métricas de precisión; a su vez proponen un conjunto de pruebas que sirven para evitar el sesgo de las métricas de precisión, y finalmente realizan diferentes pruebas con algoritmos ya existentes, con el fin de mejoran el rendimiento de Top-N (con mayor popularidad/mayor número de calificaciones).

En cuanto a la metodología utilizada para el análisis del conjunto de datos de Netflix y Movienles, los autores muestran que recomendar ítems populares no es necesariamente provechoso, y normalmente no trae beneficios para los usuarios, por lo que recomendar ítems menos conocidos añade mayor novedad y calificación, pero esto requiere evaluar la “precisión” con que esas recomendaciones son realizadas. 

Es interesante como los autores a partir de los diferentes métodos de recomendación (KNN, CF, Matricial, etc.) y su integración, logran inferir como la precisión y las métricas de error (RMSE) pueden llegar a ser determinantes al momento de realizar recomendación Top-N, donde se esta más interesado en una correcta clasificación de los ítems, (no necesariamente deben ser los más populares), sin importan que la predicción de esa clasificación sea exacta para un determinado usuario. 