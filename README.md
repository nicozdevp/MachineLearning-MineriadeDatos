# Predicción de Precios de Viviendas con Machine Learning

---

## Descripción

Este proyecto desarrolla un análisis de datos sobre el mercado inmobiliario utilizando un dataset real de propiedades en Bangladesh. El objetivo es identificar los factores que influyen en el precio de las viviendas y preparar la información para la construcción de un modelo predictivo basado en Machine Learning.

---

## Fuente de datos

El dataset utilizado proviene de Kaggle:

https://www.kaggle.com/datasets/durjoychandrapaul/house-price-bangladesh

Este conjunto de datos contiene propiedades de distintas ciudades como Dhaka, Chattogram, Cumilla, Narayanganj y Gazipur, incluyendo variables como número de habitaciones, baños, superficie y precio. ([Kaggle][1])

---

## Variables principales

El dataset incluye las siguientes características relevantes:

* **Bedrooms**: número de habitaciones
* **Bathrooms**: número de baños
* **Floor_no**: número de piso
* **Floor_area**: superficie en pies cuadrados
* **City**: ciudad de la propiedad
* **Location**: ubicación específica
* **Occupancy_status**: estado de ocupación
* **Price_in_taka**: precio de la propiedad

Estas variables permiten analizar el comportamiento del mercado y construir modelos de predicción de precios. 

---

## Objetivo

Desarrollar un modelo de análisis que permita:

* Identificar los factores que afectan el precio de las viviendas
* Analizar la relación entre variables mediante correlación
* Preparar los datos para su uso en Machine Learning
* Predecir el valor de una propiedad según sus características

---

## Metodología

El proyecto sigue la metodología **CRISP-DM**:

1. **Business Understanding**
   Definición del problema: predicción de precios inmobiliarios.

2. **Data Understanding**
   Exploración del dataset y análisis de variables.

3. **Data Preparation**

   * Eliminación de variables irrelevantes (ej: `Title`)
   * Tratamiento de outliers
   * Estandarización de datos
   * Limpieza de valores

4. **Modeling (base)**
   Preparación del dataset para modelos predictivos.

5. **Evaluation (inicial)**
   Uso de matriz de correlación y heatmap para analizar relaciones.

---

## Análisis realizado

* Limpieza y depuración del dataset
* Eliminación de columnas no relevantes
* Detección y tratamiento de outliers
* Estandarización de variables numéricas
* Construcción de matriz de correlación
* Visualización de datos con heatmap

---

## Aplicaciones de Machine Learning

Por definir.


---

## 🛠️ Tecnologías utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

---

## Estructura del proyecto

```
MachineLearning-Miner-adeDatos/
├── MachineLearning_MineriadeDatos.ipynb
└── README.md
```

---


