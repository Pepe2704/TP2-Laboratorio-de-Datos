============================================================
TRABAJO PRÁCTICO N2
============================================================

El README va a estar separado en varios incisos para la comodidad de la lectura.

Comentario: Los resultados se pueden acceder mediante el explorador de variables pero se pueden imprimir en la consola "descomentando" los prints.

------------------------------------------------------------
1) Datos del grupo
------------------------------------------------------------

GRUPO: 11
INTEGRANTES DEL TRABAJO: Blumenthal, Sanchez, Soldatich

------------------------------------------------------------
2) Bibliotecas a importar
------------------------------------------------------------

Para la ejecución del código, se necesita importar las siguientes bibliotecas de Python:

# import:
- matplotlib.pyplot
- seaborn
- numpy
- pandas

# from:
- sklearn.tree import DecisionTreeClassifier
- sklearn.neighbors import KNeighborsClassifier
- sklearn.model_selection import train_test_split
- sklearn import metrics
- sklearn.model_selection import cross_val_score
- sklearn.metrics import confusion_matrix as cm
- sklearn.metrics import accuracy_score, precision_score, recall_score

Para su instalación completa, escribir y ejecutar la siguiente línea:

    pip install numpy pandas matplotlib scikit-learn

------------------------------------------------------------
3) Instrucciones de ejecución
------------------------------------------------------------

*) Tener el archivo "Fashion-MNIST.csv" instalado en la misma carpeta donde se encuentre el código.

*) Abrir el código en un IDE (recomendamos Spyder).

*) Se recomienda ejecutar el código mediante celdas, ya que la demora desde la linea 267 hasta 287 dura aproximadamente 8min con Intel i5 - 10400f.

*) Revisar los resultados una vez finalizado su ejecución (en la parte de gráficos y explorador de variables).

-------------------------------------------------------------
4) ¿Qué realiza el archivo?
-------------------------------------------------------------

I) Análisis exploratorio con gráficos sobre la media y desviación estándar de los pixeles.
II) Clasificación binaria de imágenes a partir de dos subconjuntos de pixeles usando un modelo kNN.
III) Clasificación multiclase de imágenes usando árbol de decisiones aplicando los siguientes conceptos:
	*) División de los datos en desarrollo y validación.
	*) Entrenamiento de los árboles con distintos hiperparámetros.
	*) Validación cruzada y elección del mejor modelo.
	*) Entrenamiento del mejor modelo con los datos de desarrollo y validación con datos del held-out.
	*) Evaluación del rendimiento del modelo con matriz de confusión, precisión y recall.
