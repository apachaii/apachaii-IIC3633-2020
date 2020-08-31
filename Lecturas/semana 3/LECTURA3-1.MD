
# Critica: Performance of recommender algorithms on top-n recommendation tasks


Este articulo llamado *“Performance of Recommender Algorithms on Top-N Recommendation Tasks”* nos habla del problema que existe en los sistemas recomendadores comerciales cuyos algoritmos utilizan el error cuadratico medio (RMSE) como principal métrica de evaluación , el autor también repasa a algunos de los algoritmos más *“nuevos”* (en la época donde se escribe el paper) y nos señala que algoritmos como MovieAvg o TopPop tienen un desempeño similar a estos algoritmos mas sofisticados. Otro aspecto importante que autor nos sugiere tiene que ver con que utilizar las llamadas *“Accuracy measures”* es un mejor y más natural criterio de evaluación que RMSE, ya que evalúan directamente la calidad de las recomendaciones top-N. Finalmente el autor cierra afirmando en base a la experimentación que KNN basado en correlación (correlation-based kNN ) tiene un buen desempeño.


Uno de los aspectos que no me gustó de este articulo tiene que ver con la forma en como se presenta la información, encontré que fue un poco desordenada la estructura en comparación con otros Paper de área, lo que hace difícil poder seguir el hilo conductor del mismo, un ejemplo de esto es que en el Paper se cita a las figuras que están al final del artículo, lo que obliga a lector a tener que dejar de leer, ir a las ultimas paginas donde están todos los gráficos juntos, analizarlo y luego volver a encontrar el párrafo donde se estaba, esto me parece engorroso y es en general algo que considero se debería tomar como lo que no se debe hacer en un Paper.


Respecto al contenido, los experimentos me parecen interesantes, el dataset de Netflix es un dataset muy validado por la comunidad científica, ya que se utiliza para probar y medir distintos sistemas recomendadores tanto de filtrado colaborativo como de contenido personalizado. La critica que se la hace al error cuadrático medio me parece que es correcta considerando que si bien es cierto es algo bastante sencillo para evaluaciones, tiene una serie de problemas como por ejemplo su desempeño en valores atípicos, además existen métodos mejores para sistemas más robustos, algunas de ellas basadas en Deep learning.


Para finalizar, creo que es importante destacar que RMSE no es una panacea, y es bueno saber que su desempeño no es siempre el mejor, también es importante el conocer que algoritmos mas tradicionales pueden hacer frente a algoritmos más sofisticados (considerando que el contexto es el año 2010), sin embargo, siento que el autor descuido la forma en como presentar su investigación al tener el formato del articulo de una manera tan poco amigable y desordenada, lo cual creo es importante mantener en este tipo de trabajos.


