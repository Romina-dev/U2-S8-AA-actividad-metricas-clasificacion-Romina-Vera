# Análisis y Optimización de un Modelo de Clasificación sobre el Dataset Breast Cancer Wisconsin

## Descripción

Este repositorio contiene el desarrollo de una actividad práctica de Aprendizaje Automático enfocada en la evaluación y optimización de modelos de clasificación utilizando Regresión Logística.

Para el análisis se empleó el conjunto de datos Breast Cancer Wisconsin de Scikit-Learn, aplicando técnicas de entrenamiento, evaluación, validación cruzada y optimización de hiperparámetros con el fin de analizar el desempeño del modelo en un problema de clasificación binaria.

---

## Contenido del Repositorio

* Notebook de análisis y desarrollo que contiene la implementación completa de la práctica, incluyendo exploración de datos, entrenamiento del modelo, evaluación mediante métricas de clasificación, validación cruzada, optimización de hiperparámetros y ajuste del umbral de decisión.

* Informe académico que contiene la investigación teórica sobre métricas de clasificación, análisis de resultados obtenidos y conclusiones de la actividad.

---

## Conjunto de Datos

### Breast Cancer Wisconsin Dataset

Características principales:

* 569 registros.
* 30 variables predictoras numéricas.
* Problema de clasificación binaria:

  * 0 = Maligno
  * 1 = Benigno

Este conjunto de datos es ampliamente utilizado para la evaluación de algoritmos de clasificación supervisada en el área de aprendizaje automático.

---

## Actividades Desarrolladas

* Exploración y análisis del conjunto de datos.
* División de los datos en entrenamiento y prueba.
* Entrenamiento de un modelo de Regresión Logística.
* Generación e interpretación de la matriz de confusión.
* Evaluación mediante Accuracy, Precision, Recall, F1-Score y AUC-ROC.
* Aplicación de validación cruzada K-Fold.
* Optimización de hiperparámetros mediante GridSearchCV y RandomizedSearchCV.
* Ajuste del umbral de decisión y análisis de su impacto en las métricas de clasificación.

---

## Tecnologías Utilizadas

### Entorno de trabajo

* Google Colab
* Jupyter Notebook

### Lenguaje de programación

* Python 3

### Bibliotecas utilizadas

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

## Resumen de Resultados

Los resultados obtenidos evidenciaron un alto desempeño del modelo de Regresión Logística en la clasificación de tumores benignos y malignos. La validación cruzada mostró estabilidad en el rendimiento del clasificador y la optimización de hiperparámetros permitió identificar configuraciones con mejores resultados.

Asimismo, el análisis del umbral de decisión permitió observar cómo varían la Precisión y el Recall según el criterio de clasificación utilizado, demostrando la importancia de seleccionar adecuadamente el umbral de decisión de acuerdo con el contexto del problema.
