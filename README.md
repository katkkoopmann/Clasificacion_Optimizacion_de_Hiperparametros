# **Classification and Hyperparameter Optimization**  

This repository contains a notebook that performs **exploratory data analysis (EDA)** and prepares a **medical cost dataset** for classification and machine learning model optimization. The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance).  

## **Notebook Content**  

### **1. Environment Setup**  
- Loading compressed files and reading the dataset in CSV format.  

### **2. Data Exploration**  
- Inspecting dataset structure using `info()` and `describe()`.  
- Analyzing categorical and numerical variables.  
- Checking for missing values.  

### **3. Outlier Detection**  
- Using the **interquartile range (IQR)** method to detect outliers in numerical variables.  
- Summarizing outliers per column.  

### **4. Visual Analysis**  
- Scatter plot of `age` vs. `charges` to identify patterns and anomalies.  

### **5. Modeling and Optimization**  
- Training classification models, including **Random Forest and Gradient Boosting**.  
- Hyperparameter tuning using **GridSearchCV and RandomizedSearchCV**.  
- Evaluating model performance with **accuracy and F1-score**.  

## **Requirements**  

- Python **3.7+**  
- Libraries:  
  - `pandas`  
  - `numpy`  
  - `matplotlib`  
  - `scikit-learn`  

## **Usage**  

1. Clone the repository:  
   ```bash
   git clone <REPOSITORY_URL>
   ```  
2. Open the notebook in **Jupyter Notebook** or **Google Colab**.  
3. Run the cells sequentially to load and process the dataset.  

## **Dataset**  

The dataset contains information on **medical costs** and associated factors:  
- **age**: Patient's age.  
- **sex**: Patient's gender.  
- **bmi**: Body mass index.  
- **children**: Number of dependents.  
- **smoker**: Whether the patient is a smoker.  
- **region**: Geographical region.  
- **charges**: Medical costs (target variable).  

**Size:** 1,338 rows × 7 columns.  

##Spanish Version

# Clasificación y Optimización de Hiperparámetros

Este repositorio contiene un notebook que realiza un análisis exploratorio y prepara un conjunto de datos de costos médicos para clasificación y optimización de modelos de machine learning. El dataset utilizado proviene de [Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance).

## Contenido del Notebook

### 1. Preparación del Entorno
- Carga de archivos comprimidos y lectura del dataset en formato CSV.

### 2. Exploración de Datos
- Visualización de la estructura de los datos con `info()` y `describe()`.
- Análisis de las variables categóricas y numéricas.
- Inspección de valores nulos.

### 3. Identificación de Outliers
- Cálculo del rango intercuartílico (IQR) para detectar outliers en las variables numéricas.
- Resumen de los outliers por columna.

### 4. Análisis Visual
- Gráfico de dispersión entre las variables `age` y `charges` para identificar patrones y valores atípicos.

### 5. Modelado y Optimización
- Entrenamiento de modelos de clasificación, incluyendo Random Forest y Gradient Boosting.
- Optimización de hiperparámetros utilizando GridSearchCV y RandomizedSearchCV.
- Evaluación del desempeño de los modelos utilizando métricas como precisión y F1-score.

## Requisitos

- Python 3.7+
- Librerías:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `scikit-learn`

## Uso

1. Clonar el repositorio:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   ```

2. Abrir el notebook en Jupyter o Google Colab.

3. Ejecutar las celdas en orden para cargar y procesar el dataset.

## Dataset

El dataset contiene información sobre costos médicos y factores asociados:
- **age**: Edad del paciente.
- **sex**: Género del paciente.
- **bmi**: Índice de masa corporal.
- **children**: Número de hijos a cargo.
- **smoker**: Indicador de si el paciente es fumador.
- **region**: Región geográfica.
- **charges**: Costos médicos (variable objetivo).

Tamaño: 1,338 filas y 7 columnas.
