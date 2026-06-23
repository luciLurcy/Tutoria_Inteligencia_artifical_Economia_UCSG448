# Comparación de Modelos y Optimización de Pipeline en el Dataset Titanic

Este repositorio contiene el desarrollo del trabajo de tutoría de la materia Inteligencia Artificial de la Universidad Católica Santiago de Guayaquil.

## Objetivo del proyecto

El objetivo principal es construir un proyecto completo de Machine Learning usando el dataset Titanic, con el fin de predecir si un pasajero sobrevivió o no al hundimiento.

El trabajo no se limita a entrenar un solo modelo. Se busca construir un flujo completo y ordenado que incluya limpieza de datos, feature engineering, uso de Pipeline, comparación de modelos, búsqueda de hiperparámetros, evaluación con métricas completas y análisis de overfitting.

## Problema a resolver

El problema consiste en una tarea de clasificación binaria. La variable objetivo es `survived`, donde:

* `1` significa que el pasajero sobrevivió.
* `0` significa que el pasajero no sobrevivió.

A partir de variables como sexo, edad, clase del pasajero, tarifa pagada, familiares a bordo y otras características, se entrenarán diferentes modelos para comparar su desempeño predictivo.

## Modelos a comparar

En el proyecto se compararán al menos cuatro modelos de clasificación:

* Decision Tree Classifier
* Random Forest Classifier
* Gradient Boosting Classifier
* Logistic Regression

## Metodología general

El proyecto seguirá un flujo de Machine Learning estructurado:

1. Carga y exploración inicial del dataset.
2. Separación entre variables predictoras y variable objetivo.
3. División entre conjunto de entrenamiento y conjunto de prueba.
4. Creación de nuevas variables mediante feature engineering.
5. Construcción de un Pipeline con preprocesamiento.
6. Entrenamiento de varios modelos de clasificación.
7. Búsqueda de hiperparámetros en al menos dos modelos.
8. Evaluación comparativa con métricas completas.
9. Análisis de overfitting.
10. Interpretación de resultados y conclusiones.

## Métricas de evaluación

Los modelos serán evaluados usando:

* Accuracy
* Precision macro
* Recall macro
* F1-score macro
* AUC-ROC

Además, se incluirán gráficos como la matriz de confusión, la curva ROC conjunta de los modelos y la importancia de variables del mejor modelo.

## Estructura esperada del repositorio

* `Tutoría_Economía_UCSG148.ipynb`: notebook principal del proyecto.
* `Informe.pdf`: informe corto con metodología, resultados y conclusiones.
* `requirements.txt`: librerías necesarias para ejecutar el proyecto.
* `figures/`: carpeta para guardar gráficos relevantes.

## Estado del proyecto

Proyecto finalizado
