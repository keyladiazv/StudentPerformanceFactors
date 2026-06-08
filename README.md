# Student Performance Prediction

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar los factores que influyen en el rendimiento académico de los estudiantes y desarrollar un modelo predictivo capaz de estimar la puntuación obtenida en los exámenes a partir de variables académicas y de comportamiento.

A través de técnicas de Análisis Exploratorio de Datos (EDA), visualización y Machine Learning, se identificaron las variables con mayor impacto en el desempeño estudiantil y se construyó un modelo de regresión para predecir los resultados académicos.

---

## Objetivos

* Analizar la relación entre diferentes factores académicos y la puntuación final de los estudiantes.
* Identificar las variables con mayor influencia en el rendimiento académico.
* Construir un modelo predictivo utilizando Machine Learning.
* Evaluar la capacidad del modelo para estimar las puntuaciones de los exámenes.

---

## Tecnologías Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab

---

## Dataset

El proyecto utiliza el conjunto de datos **Student Performance Factors**, que contiene información relacionada con:

* Horas de estudio
* Asistencia
* Puntuaciones previas
* Nivel de motivación
* Sesiones de tutoría
* Factores académicos y personales
* Puntuación final del examen

---

## Metodología

### 1. Exploración de Datos (EDA)

* Análisis de estructura y tipos de datos.
* Identificación de valores nulos y duplicados.
* Estadísticas descriptivas.
* Visualización de distribuciones y relaciones entre variables.

### 2. Preprocesamiento

* Limpieza de datos.
* Selección de variables relevantes.
* Preparación de los datos para el modelado.

### 3. Visualización

* Matriz de correlación.
* Pairplot para analizar relaciones entre variables.
* Análisis gráfico de patrones y tendencias.

### 4. Modelado

Se implementó un modelo de **Regresión Lineal** para predecir la puntuación de los estudiantes.

---

## Principales Hallazgos

El análisis exploratorio permitió identificar que:

* **Hours Studied** y **Attendance** presentan la relación positiva más fuerte con la puntuación del examen.
* **Previous Scores** también muestra una correlación positiva significativa con el rendimiento académico.
* **Tutoring Sessions** contribuye al desempeño de los estudiantes, aunque con menor impacto.
* **Motivation Level** no evidencia una relación lineal fuerte dentro de este conjunto de datos.

---

## Resultados del Modelo

### Métricas de Evaluación

| Métrica                  | Valor   |
| ------------------------ | ------- |
| Mean Squared Error (MSE) | 0.00208 |
| R² Score                 | 0.6886  |

### Interpretación

El modelo logra explicar aproximadamente el **68.86% de la variabilidad** observada en las puntuaciones de los exámenes, obteniendo un desempeño aceptable para fines predictivos.

Las predicciones siguen adecuadamente la tendencia general de los datos, aunque existen algunos casos extremos que podrían beneficiarse de modelos más complejos.

---

## Posibles Mejoras

* Comparar el rendimiento con modelos como:

  * Random Forest Regressor
  * XGBoost Regressor
  * Gradient Boosting Regressor
* Realizar ingeniería de características más avanzada.
* Aplicar validación cruzada para mejorar la evaluación del modelo.
* Optimizar hiperparámetros.

---

## Visualizaciones

### Matriz de Correlación

[Ver Matriz de Correlación](https://drive.google.com/file/d/1PF5DxNZPJ5dLuYA0nmSXO4mxoigz8Kay/view?usp=sharing)


### Pairplot

[Ver Pairplot](https://drive.google.com/file/d/100JNEJCmf714iLG-hL3CQqKx_YBKaabg/view?usp=sharing)

### Predicciones vs Valores Reales

[Ver Predicciones vs Valores Reales](https://drive.google.com/file/d/1A5eheTRdC3hVyOiKnjGcI0X-9gzhdKLb/view?usp=sharing)

