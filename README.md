# Análisis de Banderas para Predecir Religión, Continente e Idioma de Países

Este proyecto tiene como objetivo explorar si las características visuales de las banderas de diferentes países pueden ayudarnos a predecir tres atributos: la religión predominante, el continente y el idioma hablado en cada país. Utilizando un conjunto de datos de Kaggle con características de las banderas de 193 países, se emplean modelos de machine learning para realizar las predicciones.

## Archivos del Proyecto

1. **`flags.csv`**: Contiene información sobre las características de las banderas y datos geográficos de los países, como el nombre, continente, superficie, población, religión y los elementos gráficos de las banderas (colores, símbolos, cruces, etc.).
2. **`notebook.ipynb`**: El Jupyter Notebook que contiene todo el análisis, preprocesamiento de los datos, construcción de modelos y evaluación de resultados.
3. **`presentacion_canvas.pptx`**: Presentación que resume los resultados y la interpretación del análisis.

## Descripción del Proyecto

Este trabajo tiene como objetivo explorar cómo las características visuales de las banderas pueden ayudar a predecir tres atributos importantes de los países:

1. **Religión predominante**: A partir de los elementos visuales en la bandera, como los colores y los símbolos, intentamos identificar la religión que podría ser predominante en un país.
2. **Continente**: Basado en el diseño y los colores de la bandera, se predice en qué continente se encuentra el país.
3. **Idioma hablado**: Se trata de identificar el idioma más probable basado en las características visuales de la bandera.

### Objetivos Específicos:
- Limpiar y preprocesar los datos para su análisis.
- Analizar las banderas utilizando atributos como colores, símbolos, y patrones.
- Construir modelos de clasificación (como Random Forest, Support Vector Machines y K-Nearest Neighbors) para predecir la religión, continente e idioma de un país basándonos en las características de su bandera.
- Evaluar el rendimiento de los modelos usando métricas como precisión, recall y F1-score.

## Requisitos

Este proyecto requiere los siguientes paquetes de Python:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn`

