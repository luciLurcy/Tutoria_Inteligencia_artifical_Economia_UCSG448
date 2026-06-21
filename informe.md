# Informe del Proyecto: Comparación de Modelos y Optimización de Pipeline en el Dataset Titanic

## 1. Introducción

Este proyecto tiene como objetivo predecir la supervivencia de los pasajeros del Titanic mediante modelos de clasificación de Machine Learning. La variable objetivo del análisis es `survived`, donde el valor 1 indica que el pasajero sobrevivió y el valor 0 indica que no sobrevivió.

El trabajo va más allá de un primer clasificador básico, porque incorpora un flujo completo de Machine Learning. Esto incluye exploración inicial de los datos, feature engineering, construcción de un Pipeline, comparación de varios modelos, búsqueda de hiperparámetros, evaluación con métricas completas y análisis de overfitting.

## 2. Feature engineering aplicado

En esta sección se describirán las nuevas variables creadas a partir de las variables originales del dataset Titanic. El objetivo del feature engineering es generar información adicional que pueda ayudar a los modelos a mejorar su capacidad predictiva.

Las variables creadas serán justificadas según su relación posible con la supervivencia de los pasajeros. Por ejemplo, se analizará si viajar solo o acompañado, el tamaño del grupo familiar, la tarifa pagada por persona o la disponibilidad de información sobre la cabina pueden aportar información relevante para el modelo.

## 3. Metodología

El proyecto seguirá una metodología ordenada para evitar errores durante el entrenamiento y la evaluación de los modelos. Primero se realizará la separación entre variables predictoras y variable objetivo. Luego se dividirá el dataset en conjunto de entrenamiento y conjunto de prueba.

El preprocesamiento se realizará dentro de un Pipeline de scikit-learn, incluyendo imputación de valores faltantes, escalado de variables numéricas y codificación de variables categóricas. Esto permite reducir el riesgo de data leakage y garantiza que los modelos sean evaluados bajo condiciones comparables.

## 4. Modelos comparados

Se compararán al menos cuatro modelos de clasificación:

* Decision Tree Classifier
* Random Forest Classifier
* Gradient Boosting Classifier
* Logistic Regression

Estos modelos serán entrenados bajo el mismo esquema de preprocesamiento para que la comparación sea justa.

## 5. Búsqueda de hiperparámetros

Para al menos dos modelos se aplicará búsqueda de hiperparámetros mediante GridSearchCV o RandomizedSearchCV con validación cruzada de 5 particiones. Se reportarán los hiperparámetros explorados, los mejores valores encontrados y la métrica usada para seleccionar el mejor modelo.

## 6. Resultados

En esta sección se presentará una tabla comparativa con las métricas de evaluación de todos los modelos. Las métricas consideradas serán accuracy, precision macro, recall macro, F1-score macro y AUC-ROC.

También se incluirán gráficos relevantes, como la matriz de confusión del mejor modelo, la curva ROC conjunta de todos los modelos y la importancia de variables del modelo seleccionado.

## 7. Análisis de overfitting

Se analizará si los modelos presentan señales de overfitting comparando el rendimiento en entrenamiento con el rendimiento obtenido mediante validación cruzada. Un modelo presentará señales de overfitting si obtiene un resultado muy alto en entrenamiento, pero un resultado considerablemente menor en validación.

## 8. Conclusiones

En esta sección se indicará cuál modelo se recomienda y por qué. La elección no se basará únicamente en accuracy, sino también en métricas como AUC-ROC, F1-score macro, estabilidad del modelo y presencia o ausencia de overfitting.

También se mencionarán las limitaciones del análisis y posibles mejoras futuras, como probar más modelos, crear nuevas variables o aplicar técnicas adicionales de validación.
