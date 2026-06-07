# 📈 Optimización de Ventas Retail: Predicción y Análisis de Comportamiento del Cliente

Este proyecto aplica técnicas avanzadas de Machine Learning para analizar el comportamiento de compra en un dataset de Retail Online. El objetivo es predecir patrones clave y proporcionar insights accionables mediante modelos de gradiente boosting y técnicas de explicabilidad (XAI).

## 🚀 Resumen del Proyecto
El análisis abarca desde la limpieza de datos transaccionales hasta la implementación de un modelo **CatBoost** optimizado con **Optuna**. Además, se utiliza **DALEX** para romper la "caja negra" del modelo y entender qué variables impulsan realmente las decisiones de compra.

## 🛠️ Stack Tecnológico
*   **Lenguaje:** Python 3.10+
*   **Manipulación de Datos:** Pandas, NumPy
*   **Visualización:** Seaborn, Matplotlib, Plotly
*   **Machine Learning:** CatBoost, Scikit-Learn
*   **Optimización de Hiperparámetros:** Optuna
*   **Explicabilidad (XAI):** DALEX

## 📊 Metodología
1.  **EDA (Análisis Exploratorio de Datos):** Identificación de valores atípicos, tendencias estacionales y análisis de productos más vendidos.
2.  **Feature Engineering:** Creación de variables derivadas (RFM - Recency, Frequency, Monetary) para segmentar el comportamiento del cliente.
3.  **Modelado:** Entrenamiento de un regresor/clasificador basado en CatBoost por su excelente manejo de variables categóricas.
4.  **Optimización:** Búsqueda bayesiana de parámetros para maximizar la precisión del modelo.
5.  **Interpretación:** Análisis de importancia de variables y perfiles de respuesta mediante DALEX.

## 📁 Estructura del Repositorio
*   `online_retail_II_EDA-basic.ipynb`: Notebook principal con el flujo completo de análisis y modelado.
*   `requirements.txt`: Lista de dependencias para replicar el entorno.
*   `resultado_modelos.pkl`: Pesos del modelo entrenado y métricas finales.

## ⚙️ Instalación y Uso
1. Clona el repositorio:
```bash
   git clone [https://github.com/tu-usuario/tu-repositorio.git](https://github.com/tu-usuario/tu-repositorio.git)