##  Análisis Exploratorio y Predictivo de Calidad del Agua
Este proyecto analiza un conjunto de datos de calidad del agua proveniente de Kaggle con el objetivo de determinar la potabilidad de cuerpos de agua a partir de parámetros físicos y químicos.
###  Objetivo
Explorar, visualizar y modelar datos de calidad del agua para predecir si un cuerpo de agua es apto para el consumo humano, usando técnicas de machine learning.
###  Dataset
- Fuente: Kaggle – [Water Potability Dataset](https://www.kaggle.com/datasets/adityakadiwal/water-potability)
- Variables: pH, dureza, TDS, cloro, sulfato, conductividad, carbono orgánico, trihalometanos, turbidez, potabilidad.
###  Técnicas utilizadas
- Análisis exploratorio (EDA) con `pandas`, `matplotlib`, `seaborn`
- Imputación de valores nulos
- Modelos ML: `Decision Tree`, `KNN`, `Logistic Regression`, `SVC`
- Métricas: precision, recall, F1-score
- Curva Precision-Recall y Average Precision Score
###  Hallazgos clave
- Dataset altamente desbalanceado: solo el 7.6% de los cuerpos de agua es potable.
- El modelo Árbol de Decisión logró el mejor desempeño (98% recall para clase positiva).
- Las variables más influyentes en la evaluación de la potabiidad de los cuerpos de agua fueron: **conductividad, sólidos disueltos, dureza y trihalometanos**.
- El modelo de ML logró identificar bien los cuerpos de agua potables a pesar del desabalance de clases, se obtuvo un puntaje de precisión promedio (AP score) de 0.96.
