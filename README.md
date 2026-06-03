# Machine Learning and Data Science Portfolio

This repository contains several practical data science and machine learning projects developed in Python. 
The goal is to demonstrate my ability to approach analytical problems end-to-end: problem understanding, exploratory data analysis, data preparation, modeling, evaluation, and interpretation of results.

The notebooks cover different types of real-world analytics problems:

- Unsupervised learning: customer/patient segmentation using clustering.
- Supervised classification: fetal health prediction.
- Supervised regression: vehicle price estimation.
- Time series forecasting: daily flight prediction in the United Kingdom.

---

## Included Projects

### 1. Patient Clustering

**Notebook:** `Agrupamiento_Clustering.ipynb`

Patient segmentation project based on demographic, medical, and billing-related variables. The objective was to identify groups of patients with similar characteristics in order to support profile analysis and potential healthcare strategies.

**Techniques applied:**

- Exploratory data analysis.
- Missing value treatment.
- Removal of redundant and high-cardinality variables.
- Feature scaling using `MinMaxScaler`.
- Categorical encoding using `OneHotEncoder`.
- Clustering models:
  - K-Means
  - Hierarchical Clustering
  - DBSCAN
  - Gaussian Mixture Models
- Model evaluation using Silhouette Score.
- Cluster interpretation through centroid analysis.

**Key result:**

K-Means was selected as the main model because it provided a good balance between interpretability and a practical number of clusters. Although DBSCAN achieved a higher Silhouette Score, it generated too many clusters, making it less useful for practical segmentation.

---

### 2. Fetal Health Classification

**Notebook:** `Classification.ipynb`

Multiclass classification project using fetal cardiotocography records. The goal was to predict whether fetal health was normal, suspicious, or pathological, supporting early detection of potential medical risks.

**Techniques applied:**

- Business problem understanding.
- Exploratory data analysis.
- Missing value validation.
- Feature distribution analysis.
- Class imbalance review.
- Data preprocessing.
- Training and comparison of multiple models:
  - Logistic Regression
  - K-Nearest Neighbors
  - Support Vector Machine
  - Decision Tree
  - Extra Trees
  - Random Forest
  - AdaBoost
  - Gradient Boosting
  - Artificial Neural Network
- Hyperparameter optimization with `GridSearchCV` and `RandomizedSearchCV`.
- Evaluation using accuracy, precision, recall, F1-score, and confusion matrix.

**Key result:**

The best-performing models achieved around 99% accuracy on validation data. Random Forest and Gradient Boosting stood out as strong models for this multiclass classification problem.

---

### 3. Vehicle Price Regression

**Notebook:** `regresion_Trabajo(1).ipynb`

Regression project focused on estimating vehicle prices in the United States based on features such as brand, model, year, color, mileage, and location.

**Techniques applied:**

- Problem understanding.
- Exploratory data analysis.
- Target variable distribution analysis.
- Numerical and categorical feature preprocessing.
- Scaling and encoding.
- Train-validation split.
- Training of multiple regression models:
  - Linear Regression
  - KNN Regressor
  - Support Vector Regressor
  - Decision Tree Regressor
  - Random Forest Regressor
  - Extra Trees Regressor
  - AdaBoost Regressor
  - Gradient Boosting Regressor
  - Neural Network
  - LARS
- Evaluation using R², MAE, RMSE, and MAPE.

**Key result:**

This project compares several regression approaches and evaluates their performance using business-relevant error metrics, especially MAPE, which helps interpret the average percentage error in price estimation.

---

### 4. UK Daily Flights Time Series Forecasting

**Notebook:** `SeriesDeTiempo_TimeSeries.ipynb`

Time series forecasting project focused on predicting the daily number of flights in the United Kingdom using data from 2019 to 2022. The analysis includes the impact of the COVID-19 pandemic and the recovery period as exogenous variables.

**Techniques applied:**

- Time series visualization.
- Weekly data aggregation.
- Time series decomposition into trend, seasonality, and residuals.
- Dickey-Fuller stationarity test.
- Series differencing.
- Creation of exogenous variables:
  - Pandemic period
  - Recovery period
- Time-based train-validation split.
- Models used:
  - SARIMAX
  - Linear Regression with lag features
  - Decision Tree
  - Random Forest
  - LSTM
  - GRU
- Evaluation using MAE and MAPE.

**Key result:**

Recurrent neural network models achieved the best performance. GRU reached approximately 11.26% MAPE and LSTM approximately 11.8% MAPE, outperforming SARIMAX and traditional machine learning models in this case.

---

## Technologies Used

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

## Skills Demonstrated

This repository demonstrates practical experience in:

- Exploratory data analysis.
- Data cleaning and preparation.
- Feature engineering.
- Categorical variable encoding.
- Numerical feature scaling.
- Supervised and unsupervised machine learning.
- Hyperparameter tuning.
- Model evaluation with appropriate metrics.
- Business-oriented interpretation of results.
- Time series forecasting.
- Comparison between statistical models, traditional machine learning models, and neural networks.

---

## Repository Purpose

This repository is part of my professional portfolio and aims to showcase my progress and capabilities in data science, machine learning, and applied analytics.

Although some projects were developed in an academic context, they are structured following a workflow similar to real-world analytical projects: problem definition, exploration, preparation, modeling, evaluation, and interpretation.

---

## Author

**Tomás Posada**  
Systems Engineering Student  
Machine Learning / Data Science / Backend Development  
