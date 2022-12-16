# PI02_Data05

Uno de los problemas que aparecía con la creación de un árbol de decisión es que si le damos la profundidad suficiente, el árbol tiende a “memorizar” las soluciones en vez de generalizar el aprendizaje. Es decir, a padecer de overfitting. La solución para evitar esto es la de crear muchos árboles y que trabajen en conjunto.

Ventajas
funciona bien -aún- sin ajuste de hiperparámetros
funciona bien para problemas de clasificación y también de regresión.
al utilizar múltiples árboles se reduce considerablemente el riesgo de overfiting

Desventajas
es mucho más “costo” de crear y ejecutar que “un sólo árbol” de decisión.
Puede requerir muchísimo tiempo de entrenamiento
OJO! Random Forest no funciona bien con datasets pequeños.
