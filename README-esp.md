# Portafolio de Machine Learning y Ciencia de Datos

Este repositorio reúne varios proyectos prácticos de ciencia de datos y machine learning desarrollados en Python. 
El objetivo es demostrar mi capacidad para abordar problemas analíticos de extremo a extremo: entendimiento del problema, 
exploración de datos, preparación, modelado, evaluación e interpretación de resultados.

Los notebooks cubren diferentes tipos de problemas reales de analítica:

- Aprendizaje no supervisado: segmentación mediante clustering.
- Clasificación supervisada: predicción de estado de salud fetal.
- Regresión supervisada: estimación del precio de vehículos.
- Series de tiempo: predicción de vuelos diarios en Reino Unido.

---

## Proyectos incluidos

### 1. Clustering de pacientes

**Notebook:** `Agrupamiento_Clustering.ipynb`

Proyecto de segmentación de pacientes a partir de variables demográficas, médicas y de facturación. 
El objetivo fue encontrar grupos con características similares para facilitar análisis de perfiles y posibles estrategias de atención.

**Técnicas aplicadas:**

- Análisis exploratorio de datos.
- Tratamiento de valores nulos.
- Eliminación de variables redundantes o de alta cardinalidad.
- Escalamiento con `MinMaxScaler`.
- Codificación de variables categóricas con `OneHotEncoder`.
- Modelos de clustering:
  - K-Means
  - Clustering jerárquico
  - DBSCAN
  - Gaussian Mixture Models
- Evaluación con Silhouette Score.
- Interpretación de centroides para explicar los grupos obtenidos.

**Resultado destacado:**

Se seleccionó K-Means como modelo principal por ofrecer un equilibrio entre interpretabilidad y cantidad adecuada de grupos. Aunque DBSCAN obtuvo un Silhouette Score más alto, generó demasiados clusters, lo que lo hacía menos útil para una segmentación práctica.

---

### 2. Clasificación de salud fetal

**Notebook:** `Classification.ipynb`

Proyecto de clasificación multiclase usando registros de cardiotocografía fetal. El objetivo fue predecir si el estado de salud del feto era normal, sospechoso o patológico, apoyando la detección temprana de posibles riesgos médicos.

**Técnicas aplicadas:**

- Entendimiento del problema de negocio.
- Análisis exploratorio de datos.
- Validación de valores nulos.
- Análisis de distribución de variables.
- Revisión de desbalance de clases.
- Preprocesamiento de variables.
- Entrenamiento y comparación de múltiples modelos:
  - Regresión logística
  - KNN
  - Support Vector Machine
  - Árbol de decisión
  - Extra Trees
  - Random Forest
  - AdaBoost
  - Gradient Boosting
  - Red neuronal artificial
- Optimización de hiperparámetros con `GridSearchCV` y `RandomizedSearchCV`.
- Evaluación con accuracy, precision, recall, F1-score y matriz de confusión.

**Resultado destacado:**

Los mejores modelos alcanzaron un desempeño cercano al 99% de accuracy en validación, destacando Random Forest y Gradient Boosting como modelos de alto rendimiento para este problema de clasificación multiclase.

---

### 3. Regresión para estimación de precios de vehículos

**Notebook:** `regresion_Trabajo(1).ipynb`

Proyecto de regresión enfocado en estimar el precio de vehículos en Estados Unidos a partir de características como marca, modelo, año, color, kilometraje y ubicación.

**Técnicas aplicadas:**

- Entendimiento del problema.
- Análisis exploratorio de datos.
- Análisis de distribución de la variable objetivo.
- Tratamiento de variables categóricas y numéricas.
- Escalamiento y codificación.
- Separación entre entrenamiento y validación.
- Entrenamiento de múltiples modelos:
  - Regresión lineal
  - KNN Regressor
  - Support Vector Regressor
  - Decision Tree Regressor
  - Random Forest Regressor
  - Extra Trees Regressor
  - AdaBoost Regressor
  - Gradient Boosting Regressor
  - Red neuronal
  - LARS
- Evaluación con R², MAE, RMSE y MAPE.

**Resultado destacado:**

El proyecto permitió comparar diferentes enfoques de regresión y medir su desempeño usando métricas de error relevantes para negocio, especialmente MAPE, que facilita interpretar el error porcentual en la estimación del precio.

---

### 4. Predicción de vuelos diarios en Reino Unido

**Notebook:** `SeriesDeTiempo_TimeSeries.ipynb`

Proyecto de series de tiempo para predecir la cantidad diaria de vuelos en Reino Unido usando datos entre 2019 y 2022. El análisis considera el impacto de la pandemia y la recuperación posterior como variables exógenas.

**Técnicas aplicadas:**

- Visualización de la serie temporal.
- Agregación semanal de datos.
- Descomposición de la serie en tendencia, estacionalidad y residuales.
- Prueba de estacionariedad Dickey-Fuller.
- Diferenciación de la serie.
- Creación de variables exógenas:
  - Pandemia
  - Recuperación
- Separación temporal entre entrenamiento y validación.
- Modelos utilizados:
  - SARIMAX
  - Regresión lineal con lags
  - Árbol de decisión
  - Random Forest
  - LSTM
  - GRU
- Evaluación con MAE y MAPE.

**Resultado destacado:**

Los modelos basados en redes recurrentes obtuvieron el mejor desempeño. GRU logró aproximadamente 11.26% de MAPE y LSTM aproximadamente 11.8%, superando a SARIMAX y a los modelos tradicionales de machine learning en este caso.

---

## Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
- Skforecast
- TensorFlow / Keras
- Jupyter Notebook

---

## Habilidades demostradas

Este repositorio demuestra experiencia práctica en:

- Análisis exploratorio de datos.
- Limpieza y preparación de datos.
- Feature engineering.
- Codificación de variables categóricas.
- Escalamiento de variables numéricas.
- Modelado supervisado y no supervisado.
- Optimización de hiperparámetros.
- Evaluación de modelos con métricas adecuadas.
- Interpretación de resultados para contextos de negocio.
- Modelado de series de tiempo.
- Comparación entre modelos estadísticos, modelos clásicos de machine learning y redes neuronales.

---

## Objetivo del repositorio

Este repositorio forma parte de mi portafolio profesional y busca mostrar mi progreso y capacidades en ciencia de datos, machine learning y analítica aplicada.

Aunque algunos proyectos fueron desarrollados en un contexto académico, están estructurados siguiendo un flujo de trabajo similar al usado en proyectos reales: definición del problema, exploración, preparación, modelado, evaluación e interpretación.

---

## Autor

**Tomás Posada**  
Systems Engineering Student  
Machine Learning / Data Science / Backend Development  
