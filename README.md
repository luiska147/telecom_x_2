# 📉 Predicción y Prevención de Churn en Telecomunicaciones



## 🎯 Objetivo del Proyecto
El objetivo principal de este proyecto es identificar proactivamente a los clientes con alta probabilidad de cancelar sus servicios de telecomunicaciones (**Churn**). Al predecir qué clientes están en riesgo, la empresa puede focalizar sus estrategias de retención, optimizar su presupuesto de marketing y reducir la tasa de abandono.

---

## 🛠️ Tecnologías y Herramientas Utilizadas
* **Lenguaje:** Python
* **Manipulación de Datos:** Pandas, NumPy
* **Visualización:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Random Forest, Logistic Regression, GridSearchCV)
* **Métricas de Evaluación:** F1-Score, ROC-AUC, Recall, Matriz de Confusión

---

## 📊 Metodología
1. **Análisis Exploratorio y Limpieza:** Tratamiento de valores nulos y análisis de correlación.
2. **Selección de Variables (Feature Selection):** Uso de la prueba Chi-cuadrado ($\chi^2$) para descartar variables con bajo impacto predictivo (ej. Género).
3. **Preprocesamiento:** Aplicación de *One-Hot Encoding* para variables categóricas y estandarización para variables numéricas.
4. **Modelado y Optimización:** Entrenamiento de modelos base y búsqueda de los mejores hiperparámetros usando `GridSearchCV`.

---

## 🏆 Resultados Clave
El modelo final seleccionado es una **Regresión Logística con penalización L1 (Lasso)**, optimizada para maximizar el área bajo la curva (ROC-AUC). 

* **Recall del Modelo:** **80.45%**. El algoritmo es capaz de identificar a 8 de cada 10 clientes que realmente van a abandonar el servicio.
* **Insights del Negocio:** Los factores que más impulsan el abandono son los **contratos mes a mes** y los **servicios de fibra óptica**. Por otro lado, los contratos a dos años son el mayor factor de retención.

---

## 🚀 Cómo ejecutar este proyecto
1. Clona este repositorio: `git clone https://github.com/luiska147/telecom_x_2.git`
2. Instala las dependencias requeridas: `pip install -r requirements.txt`
3. Ejecuta el notebook principal: `jupyter notebook Desafio_Telecom_X_2.ipynb`

---

## 👨‍💻 Autor
**Luis Carlos Leguizamon Rojas**

# 📉 Telecom Customer Churn Prediction & Prevention



## 🎯 Project Objective
The main goal of this project is to proactively identify customers with a high probability of canceling their telecommunications services (**Churn**). By predicting which customers are at risk, the company can focus its retention strategies, optimize its marketing budget, and reduce the overall churn rate.

---

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Random Forest, Logistic Regression, GridSearchCV)
* **Evaluation Metrics:** F1-Score, ROC-AUC, Recall, Confusion Matrix

---

## 📊 Methodology
1. **Exploratory Data Analysis (EDA) & Cleaning:** Handling missing values and correlation analysis.
2. **Feature Selection:** Utilizing the Chi-square ($\chi^2$) test to discard variables with low predictive impact (e.g., Gender).
3. **Preprocessing:** Applying *One-Hot Encoding* for categorical variables and standardization for numerical ones.
4. **Modeling & Optimization:** Training baseline models and hyperparameter tuning using `GridSearchCV`.

---

## 🏆 Key Results
The final selected model is a **Logistic Regression with L1 penalty (Lasso)**, optimized to maximize the Area Under the Curve (ROC-AUC).

* **Model Recall:** **80.45%**. The algorithm successfully identifies 8 out of 10 customers who are actually going to leave the service.
* **Business Insights:** The strongest drivers for customer churn are **month-to-month contracts** and **fiber optic services**. Conversely, two-year contracts act as the strongest retention factor.

---

## 🚀 How to Run the Project
1. Clone this repository: `git clone https://github.com/luiska147/telecom_x_2.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Run the main notebook: `jupyter notebook Desafio_Telecom_X_2.ipynb`

---

## 👨‍💻 Author
**Luis Carlos Leguizamon Rojas**
