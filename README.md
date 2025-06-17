# Proyecto Fin de Máster: Solución Integral de Data Science para Retail (DSMarket)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=Jupyter&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-0066B2?style=for-the-badge&logo=xgboost&logoColor=white)

## 🏢 Resumen del Proyecto

Este repositorio contiene el Trabajo de Fin de Máster (TFM) para el Máster en Data Science & IA. El proyecto simula una consultoría de datos completa para **DSMarket**, una empresa ficticia del sector retail. A través de un enfoque integral, se abordan diferentes áreas del negocio utilizando técnicas de análisis de datos, Business Intelligence, Machine Learning y forecasting.

El trabajo fue desarrollado en equipo, aplicando metodologías ágiles para gestionar las diferentes fases del proyecto.

## 🎯 Objetivos Clave

El proyecto se estructuró en torno a cuatro objetivos principales para proporcionar valor accionable a DSMarket:

1.  **Análisis Exploratorio de Datos (EDA):** Unificar, limpiar y analizar fuentes de datos complejas para obtener una comprensión profunda del negocio.
2.  **Visualización y Business Intelligence:** Desarrollar un dashboard interactivo en Power BI para monitorizar KPIs clave y facilitar la toma de decisiones estratégicas.
3.  **Segmentación de Productos (Clustering):** Agrupar productos en clústeres homogéneos para optimizar estrategias de marketing, pricing y gestión de stock.
4.  **Predicción de la Demanda (Time Series):** Construir y evaluar un modelo de series temporales para predecir ventas futuras y mejorar la planificación de la demanda.

## 📂 Estructura del Repositorio y Notebooks

El análisis se ha dividido en varios notebooks, cada uno centrado en una fase específica del proyecto:

* **`FinalVersion_EDA_y_Join.ipynb`**: Contiene el proceso de carga, unificación de las distintas fuentes de datos (ventas, calendario, precios) y el análisis exploratorio inicial.
* **`FinalVersion_Análisis_prePowerBI.ipynb`**: Se centra en la limpieza final y la transformación de los datos para dejarlos listos para su consumo en una herramienta de BI como Power BI.
* **`Clustering.ipynb`**: Desarrolla el pipeline completo de clustering de productos, incluyendo preprocesamiento, reducción de dimensionalidad con PCA y aplicación de algoritmos como K-Means.
* **`Time series.ipynb`**: Implementa un modelo de forecasting usando XGBoost para predecir la demanda de productos, incluyendo la creación de features específicas para series temporales.

## 🔧 Metodología y Técnicas Aplicadas

* **Análisis Exploratorio:** Visualización de datos con `Seaborn` y `Matplotlib` para entender distribuciones y correlaciones.
* **Clustering:** Reducción de dimensionalidad con **PCA** y segmentación con **K-Means**. Evaluación de clústeres mediante el **coeficiente de silueta**.
* **Time Series Forecasting:** Feature engineering sobre variables de tiempo (lags, medias móviles, componentes estacionales) y modelado con **XGBoost**.
* **Business Intelligence:** Creación de un dashboard interactivo para la visualización de KPIs.
  

## 💻 Tecnologías Utilizadas

* **Lenguaje:** Python 3.x
* **Librerías Principales:**
    * **Análisis de Datos:** Pandas, NumPy
    * **Visualización:** Matplotlib, Seaborn
    * **Machine Learning:** Scikit-learn, XGBoost
* **Entorno de Desarrollo:** Jupyter Notebooks, Google Colab
* **Business Intelligence:** Power BI

## 👥 Autores

Este proyecto fue realizado por:
* José Luengo
* Nicolás Gaveglio
* Marina Sallent

---
