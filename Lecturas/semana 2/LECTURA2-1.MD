
# Critica: Collaborative Filtering for Implicit Feedback Datasets


El Paper trata sobre sistemas recomendadores de filtrado colaborativo basado en feedback implícito, esto en la práctica nos significa un plus importante respecto al paper de la semana pasada (Collaborative filtering for implicit feedback datasets) ya que esta vez se considera información que no necesariamente está disponible a simple vista, lo que por cierto es una realidad en gran parte de la data existente



El modelo explicado en este Paper parte de la premisa de comprar modelos clásicos como *Neighborhood* o Latent factor models en contra parte con el modelo propio, este último es una versión (a mi juicio) mejorada de  *matrix factorization*, y digo mejorada porque contiene algo que es importante en la industria en la actualidad, la personalizacion o almenos lo intenta de una manera más literal que  *matrix factorization* clasico, en esa línea el método que se utiliza para poder llevar a cabo esto me parece bastante inteligente, utilizar un método que funciona y tratar de mejorarlo es algo que me parece interesante, sin embargo me quedan algunas dudas respecto al costo computacional, en general en mi experiencia los métodos basados en gradiente tienden a consumir recursos en exceso, sería interesante ver un método que incorpore  por ejemplo algoritmos bioinspirados que dan un rendimiento bastante bueno en conjunto de datos grandes.


Respecto a la experimentación me pareció que la metodología utilizada y el dataset estuvieron bien para efectos de demostración, sin embargo (y llevándolo nuevamente al mundo de la industria) me gustaría verlo en un dataset de ecomerce, donde se utilicen variables como cliks, el tiempo que el usuario ve un producto , lo que escribe en el buscador , la frecuencia de compra en una marca, etc. siento que este modelo en especial puede ser de gran utilidad en ese mundo donde existe una gran cantidad de feedback implícito, personalmente creo que esto podría ser de mucha utilidad en este campo que actualmente está en auge debido a la pandemia, además de que permitiría validar el modelo con un enfoque productivo.

Finalmente, y para cerrar la crítica, me parece que en cuanto a contenido el Paper es bastante completo, tal vez un poco enredado para explicar algunos aspectos, pero en general se entiende, también creo que sería interesante poder utilizar el modelo propuesto con un datasets distintos que nos permitan validar y probar el comportamiento en otros contextos.
