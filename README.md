<h1 align="center"> Titanic 2.0 </h1>

Este proyecto tiene el análisis, procesamiento de datos y la implementación de varios modelos de machine learning para predecir la probabilidad de supervivencia de los pasajeros del Titanic usando el famosos [Titanic Dataset](https://www.kaggle.com/c/titanic)
de Kaggle.

El proyecto es un **rediseño completo** y una **versión mejorada** del proyecto que realicé anteriormente: [Titanic-Survivor-Project](https://github.com/rodrigoalegre210/Titanic-Survivors-Project)

En esta versión se exploran técnicas avanzadas de análisis de datos y machine learning para desarrollar un modelo predictivo que determine si un pasajero del Titanic sobrevivió o no, basado en características como su edad, clase,
género, tarifa del boleto, y otros factores disponibles en el dataset.

Se probaron diferentes modelos de machine learning, se aplicaron técnicas de imputación de datos nulos, se analizaron outliers y se implementaron transformaciones de normalización y escalado.

#### Modelos de Machine Learning.

* **Regresión Logística**

  **Accuracy**: 0.8156
  **AUC-ROC**: 0.8050

  La regresión logística se comportó bien, mostrando un equilibrio entre precisión y recall. La matriz de confusión mostró 14 falsos positivos y 19 falsos negativos. En general, el modelo es bastante interpretable y eficaz para el objetivo que buscamos.
