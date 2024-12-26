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

### 5. Modelado (pendiente o en desarrollo)
- Se espera que el notebook incluya clasificación y optimización de hiperparámetros en futuras iteraciones.

## Requisitos

- Python 3.7+
- Librerías:
  - `pandas`
  - `numpy`
  - `matplotlib`

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

## Autor

Este proyecto fue desarrollado como parte de un ejercicio práctico para el análisis de datos y preparación de modelos predictivos.
