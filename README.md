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

  El modelo de Regresión Logística se comportó bien, mostrando un equilibrio entre precisión y recall. La matriz de confusión mostró 14 falsos positivos y 19 falsos negativos. En general, el modelo es bastante interpretable y eficaz para el objetivo que buscamos.

* **Random Forest**

  **Accuracy**: 0.8045
  **AUC-ROC**: 0.7914

  El modelo de Random Forest tuvo un rendimiento un poco menor al de Regresión Logística. Aunque la capacidad para manejar relaciones no lineales es un punto fuerte para este modelo, no superó significativamente a los otros modelos.

* **Gradient Boosting**

  **Accuracy**: 0.8045
  **AUC-ROC**: 0.7855

  El modelo de Gradient Boosting tuvo resultados casi iguales al modelo de Random Forest, con la diferencia de un ligero descenso en la métrica AUC-ROC. Este modelo es robusto para manejar interacciones entre variables y es más propenso
  a generar predicciones precisas con hiperparametros ajustados.

#### Estructura del proyecto.

**EDA1.ipynb**: Exploración inicial de los datos (distribución, primeras visualizaciones).  
**EDA2.ipynb**: Visualizaciones más avanzadas y análisis de correlaciones entre variables.  
**ingenieria_caracteristicas.ipynb**: Creación de nuevas características para los modelos.  
**outliers.ipynb**: Detección y análisis de outliers en las variables numéricas.  
**valores_nulos.ipynb**: Manejo de los valores nulos con técnicas de imputación avanzadas.  
**1_regresion_logistica.ipynb**: Modelo de Regresión Logística.  
**2_random_forest.ipynb**: Modelo de Random Forest.  
**3_gradient_boosting.ipynb**: Modelo de Gradient Boosting.  

<img src="Diagrama Titanic.png" alt="Diagrama">
