
# BPR: Bayesian Personalized Ranking from Implicit Feedback

El artículo habla sobre optimización de recomendadores utilizando una aproximación Bayesiana para realizar recomendaciones personalizadas con feedback implícito. En base a esto puedo hacer una conexión con el artículo anterior (2-1), el cual hablaba de recomendación implícita, pero que no utilizaba una aproximación Bayesiana. 

Encuentro muy interesante la implementación de la aproximación Bayesiana a este tipo de algoritmos dada a la misma naturaleza del pensamiento Bayesiano. Realizar relaciones para determinar predicciones en base a consecuencias y causas para un usuario dado me parece muy lógico de utilizar.

Se muestra que la eficacia de optimizar dichos algoritmos populares como kNN o MF con un aproximaciones Bayesianas entrega mejores resultados que utilizando métodos como WR o SVD, los cuales tienen otro tipo de aproximación matemática.

No logré comprender por qué el subconjunto de pares de Items '>u' tenía que ser un orden total. Quizás podrían haber ahondado respecto a aquel asunto mientras explicaban su metodología, ya que si bien es mencionado, no encontré una explicación para las aseveraciones que indicaban respecto a ello.

Al igual que en la lectura anterior, no se realiza una evaluación en la velocidad de entrenamiento ni throughput del sistema recomendador resultante como en las lecturas de la semana pasada, lo que encuentro un punto importante para su implementación. Si bien realizan una comparación con user-wise stochastic descent, podrían compararlo con el tiempo de optimización de los otros algoritmos con los que comparan. Al menos aquella sección me pareció confusa.

Por último, me pareció muy bien que utilizasen datasets de diferentes naturalezas para realizar tareas diferentes como ranking y recomendación utilizando su algoritmo, ya que con eso pueden mostrar cómo su enfoque de optimización funciona en más de un tipo de experimento.