# Collaborative Filtering for Implicit Feedback Datasets

El paper aborda el escenario de realizar recomendaciones mediante un feedback implícito y no explicito. Es decir, poder implementar un sistema recomendador que no funcione con un rating explicito indicado por el usuario, como lo sería, por ejemplo, colocar una calificación en estrellas a una película en Netflix. Se explica que para dicho fin es necesario registrar diferentes tipos de datos de los usuarios para realizar dichos cálculos, como lo sería el tiempo de interacción con el contenido, clicks, compras realizadas, entre otras.

Encuentro altamente interesante poder realizar recomendaciones al no contar con el feedback directo del usuario, lo que corresponde a la mayor parte de los casos como es indicado en el artículo. 

Un aspecto del artículo que llamó mi atención fue que el algoritmo fue planteado matemáticamente junto a su complejidad, sin embargo después el algoritmo propuesto no fue comparado con los demás ni en tiempo de entrenamiento ni en tiempo de ejecución. Esto me generó dudas respecto a la eficiencia de dicha implementación. Este punto lo encuentro muy interesante también por la lectura de la semana anterior, en donde el tiempo de recomendación era un punto clave al momento de evaluar el algoritmo.

Hubiese sido interesante ver una comparación de complejidad matemáticamente en los otros métodos indicados.

Por último, encontré que la forma de mostrar ejemplos de recomendaciones en base al motivo de la recomendación no queda tan evidente al mostrarlo como una tabla. Quizás podría haber sido implementado alguna visualización en base a clustering para mostrar relaciones formada. Quizás se puede deber a que no accedí a algún resultado completo de su experimento y allí dichos datos pueden ser mejor visualizados y explorados.