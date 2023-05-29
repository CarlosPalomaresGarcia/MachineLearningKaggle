# Machine Learning Project

A continuación, se detallan los pasos seguidos durante el proceso, incluyendo la limpieza de datos, la revisión de la colinealidad, la prueba de varios modelos de Machine Learning (Regresión Lineal, Árbol de Decisión y Random Forest) y la predicción de precios.

## Descripción del proyecto
El objetivo principal de este proyecto es desarrollar un modelo de Machine Learning capaz de predecir el precio de laptops. Para lograr esto, se utilizaron técnicas de análisis de datos y modelos de regresión.

## Pasos seguidos
### 1. Limpieza de datos
El primer paso consistió en realizar la limpieza de los datos para garantizar la calidad de los mismos. Esto incluyó:

Transformar variables categóricas en variables numéricas utilizando la codificación one-hot encoding.
Eliminacion de columnas innecesarias.

### 2. Revisar colinealidad
La colinealidad se refiere a la alta correlación entre variables predictoras en un modelo de Machine Learning. Para evitar problemas de multicolinealidad, se realizó un análisis de correlación entre las variables y se tomaron medidas para reducir o eliminar las variables altamente correlacionadas.

### 3. Prueba de varios modelos de Machine Learning

Se probaron diferentes modelos de Machine Learning para encontrar aquel que mejor se ajustara a los datos y proporcionara las mejores predicciones de precios de laptops. Los modelos evaluados incluyeron:

Regresión Lineal: Se utilizó un modelo de regresión lineal para establecer una relación lineal entre las variables predictoras y la variable objetivo (precio de la laptop).
Árbol de Decisión: Se implementó un árbol de decisión, el cual divide el conjunto de datos en ramas basadas en condiciones para realizar predicciones.
Random Forest: Se empleó el algoritmo de Random Forest, que combina múltiples árboles de decisión para obtener predicciones más precisas.

### 4. Predicción de precios
Una vez entrenados los modelos, se realizaron predicciones de precios utilizando el conjunto de datos de prueba. Se evaluaron las predicciones mediante métricas adecuadas para modelos de regresión, como el error cuadrático medio (MSE) o el coeficiente de determinación (R^2).
