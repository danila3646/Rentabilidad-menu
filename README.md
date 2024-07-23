# Rentabilidad del Menú

## Introducción

Este proyecto se enfoca en el análisis y optimización de la rentabilidad de los elementos del menú de un restaurante. Utilizando un conjunto de datos que proporciona información sobre las categorías de los elementos del menú, los ingredientes, los precios y los indicadores de rentabilidad, se busca identificar estrategias para maximizar la rentabilidad.

## Descripción del Conjunto de Datos

El conjunto de datos utilizado en este proyecto contiene la siguiente información:
- **RestaurantID**: Identificador del restaurante.
- **MenuCategory**: Categoría del elemento del menú (Aperitivos, Plato principal, Postres, Bebidas).
- **MenuItem**: Nombre del elemento del menú.
- **Ingredients**: Lista de ingredientes utilizados en el elemento del menú (datos confidenciales incluidos para las bebidas).
- **Price**: Precio del elemento del menú en dólares.
- **Profitability**: Variable objetivo que indica la rentabilidad del elemento del menú (alto/medio/bajo).

## Objetivos del Proyecto

El objetivo principal de este proyecto es analizar los factores que influyen en la rentabilidad de los elementos del menú y proponer estrategias para optimizar dicha rentabilidad. Para lograrlo, se llevarán a cabo las siguientes actividades:

### 1. Análisis de Rentabilidad
**Objetivo**: Identificar los factores que influyen en la rentabilidad de los elementos del menú. 

**Actividades**: 
- Análisis exploratorio de datos (EDA) para entender la distribución de la rentabilidad en diferentes categorías de menú.
- Distribución de rentabilidad por categoría de menu.
- Visualizaciones de la rentabilidad por categoría y precio.

### 2. Clasificación de Rentabilidad
**Objetivo**: Desarrollar un modelo de clasificación para predecir la rentabilidad de los nuevos elementos del menú.

**Actividades**:
- Preprocesamiento de datos, incluyendo la codificación de variables categóricas y manejo de datos confidenciales.
- Entrenamiento de modelos de clasificación (e.g., Random Forest, SVM) para predecir la rentabilidad.
- Evaluación de modelos y selección del mejor modelo basado en métricas de desempeño.
