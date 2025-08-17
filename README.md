# 📡 Telecom X - Parte 2

## 📊 Descripción

En esta segunda etapa del proyecto **Telecom X**, se trabaja sobre el mismo DataFrame ya tratado en la parte 1 para diseñar modelos de **clasificación** que permitan predecir si un cliente cancelará o no el servicio, a esto se le conoce como (*churn*). El objetivo es identificar los factores que mas influyen en la cancelación y aportar valor mediante modelos que ayuden a mejorar la retención de clientes de la compañia.

Para ello, se aplicaron técnicas de **preprocesamiento**, **balanceo de clases** y **codificación de variables**, seguidas de la creación y evaluación de modelos supervisados. Luego se comparan los distintos algoritmos para identificar el que ofrece mejor rendimiento.

## 🧰 Tecnologías utilizadas

- **Python** como lenguaje principal de análisis.
- **Google Colab** como entorno de desarrollo colaborativo.
- **Pandas** y **NumPy** para manipulación y tratamiento de datos.
- **Matplotlib**, **Seaborn** y **Plotly** para visualización de resultados.
- **Scikit-learn** para:
  - Separación de datos (train/test)
  - Codificación (`OneHotEncoder`)
  - Estandarización (`StandardScaler`)
  - Balanceo con `RandomOverSampler`
  - Creación de modelos de clasificación
  - Evaluación de métricas (accuracy, precision, recall, f1-score, etc.)

## 🗂️ Estructura del proyecto y organización del flujo de trabajo
El proyecto está compuesto por distintas etapas bien diferenciadas:

1. Extracción del Archivo Tratado.
2. Eliminación de las Columnas Irrelevantes.
3. Verificación de la Proporción de Cancelación (Churn).
4. Análisis de Correlación.
5. Análisis Dirigido.
6. Separación de los Datos.
7. Encoding.
8. Balanceo de las Clases.
9. Normalización o Estandarización.
10. Creación y Evaluación de los Modelos.
11. Análisis de la Importancia de las Variables según los Modelos.
12. Conclusión Final.

## Ejemplos de gráficos e insights obtenidos.
- 📊 Matriz de confusión para analizar errores de clasificación.
- 📉 Comparación de métricas entre modelos.
- 🧮 Histogramas y gráficas de violín para entender la distribución de las variables.
- 🌐 Gráficos interactivos para explorar la relación entre variables y churn.

## 🚀 Instrucciones para ejecutar el notebook
1. Descarga el archivo `.ipynb` desde este repositorio.
2. Súbelo a tu [Google Drive](https://drive.google.com/)
3. Ábrelo con [Google Colab](https://colab.research.google.com/).
4. Ejecutá las celdas en orden, comenzando por la sección de importación de datos.
