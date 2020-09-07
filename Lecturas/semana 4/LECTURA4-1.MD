
# Critica: Content-based recommendation systems on The adaptive web
 

Esta crítica trata sobre un capítulo “Content-based recommendation systems” del libro “The adaptive web”, es un libro escrito Xu, W., Liu, X., & Gong, Y en 2003, el libro habla principalmente de sistemas recomendadores basados en contenido, el autor sitúa el contexto de aplicaciones web que tienen este sipo de sistemas recomendadores y los problemas que enfrentan muchas veces debido a que parte importante de la información es texto no estructurado. El autor entrega una serie de algoritmos (bastante basicos) para poder dar solución a esta problemática, aunque debido en parte a la época en que fue escrito no da una solución concreta a la problemática.



Una de las cosas que el capítulo es como se mencionó antes, el hecho de que muchas veces se tiene que extraer información desde texto no estructurado para poder entrenar sistemas recomendadores, acá el autor da una serie de algoritmos mezclados con formas de aplicación que intentan dar una solución a este problema, sin embargo, en mi opinión el autor se salta en gran medida todo el proceso de procesamiento de lenguaje natural, siendo este ítem extremadamente problema considerando que el capítulo le da bastante énfasis al tema, por ejemplo no vi en mi lectura ninguna mención a bags of Word o tokenization , estos son de lo más básico que se puede realizar en problemas de NLP, por lo que siento que hizo falta verlos en el capítulo. 



Otro tema importante tiene que ver con cómo se trabaja el contenido, en general en NLP, cuando el dominio es demasiado amplio se pierde Accuracy en el camino, el autor hace referencia a este problema, pero no ahonda en este, una solución que pienso podría dar solución es utilizar taxonomía, utilizando terminología de ese dominio en específico, de esta manera se acota el problema a un conjunto más pequeño, y el comportamiento de los algoritmos mejora considerablemente. esto ya se utilizan en problemas actuales. Otro aspecto importante en esa misma línea es el uso de algoritmos de NLP modernos, sería interesante poder ver el desempeño de algoirtmos como bert u otros que han salido en los últimos años, donde el NLP ha tenido un auge importante, y donde el texto no estructurado ya es más “simple” de analizar.



Para concluir, la discusión que plantea el autor es interesante, sin embargo, el capítulo del libro no toca en profundidad el problema desde una perspectiva técnica, es probable que sea en parte debido a que en aquellos años el NLP aún era algo complejo y no se tenía los avances de hoy en día, donde podemos hacer análisis de texto de manera relativamente simple, llegando incluso a sustentar sistemas como por ejemplo GPT 3.
