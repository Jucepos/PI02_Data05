# <h1 align=center> **Bienvenidos a mi PI - Machine Learning** :construction_worker:</h1>

INTRODUCCIÓN: :arrow_down:

Descripción del problema 
***
Un importante Centro de Salud lo ha contratado con el fin de poder predecir si un paciente tendrá una estancia hospitalaria prolongada o no, utilizando la información contenida en el dataset asociado, la cual recaba una muestra histórica de sus pacientes, para poder administrar la demanda de camas en el hospital según la condición de los pacientes recientemente ingresados.

Para esto, se define que un paciente posee estancia hospitalaria prolongada si ha estado hospitalizado más de 8 días. Por lo que debe generar dicha variable categórica y luego categorizar los pacientes según las variables que usted considere necesarias, justificando dicha elección.​

En este repo encontraran:

🔸 Archivo principal comentado: datathon.ipynb

🔸 Archivo con los datasets: datasets/....

🔸 Archivo con predicciones: Jucepos.csv

***
OBJETIVOS: :arrow_down:

​ Se proveen los siguientes archivos para realizar el proyecto:

'hospitalizaciones_train.csv': Contiene 410000 registros y 15 dimensiones, el cual incluye la información numérica de la cantidad de días de estancia hospitalaria.
'hospitalizaciones_test.csv': Contiene 90000 registros y 14 dimensiones, el cual no incluye la información de la cantidad de días de estancia hospitalaria.​

***
:bangbang: Resolucion :bangbang:

En este caso decidi hacer una técnica de aprendizaje automático supervisada basada en árboles de decisión (Random Forest).

Uno de los problemas que aparecía con la creación de un árbol de decisión es que si le damos la profundidad suficiente, el árbol tiende a “memorizar” las soluciones en vez de generalizar el aprendizaje. Es decir, a padecer de overfitting. La solución para evitar esto es la de crear muchos árboles y que trabajen en conjunto.

Ventajas
***
🔸 Funciona bien -aún- sin ajuste de hiperparámetros
🔸 Funciona bien para problemas de clasificación y también de regresión.
🔸 Al utilizar múltiples árboles se reduce considerablemente el riesgo de overfiting

Desventajas
***
🔸 Es mucho más “costo” de crear y ejecutar que “un sólo árbol” de decisión.
🔸 Puede requerir muchísimo tiempo de entrenamiento
🔸 Random Forest no funciona bien con datasets pequeños.

***
Herramientas utilizadas: :arrow_down:

🔸 Python

🔸 Pandas

🔸 Matplotlib

🔸 Seaborn

🔸 Scikit-learn

