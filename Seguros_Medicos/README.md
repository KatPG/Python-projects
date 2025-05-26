## Predicción de Costos de Seguros Médicos en EE. UU.
### Dataset
El proyecto utiliza el conjunto de datos Medical Cost Personal Dataset, que contiene información de 1,338 asegurados en EE. UU., incluyendo variables como edad, sexo, índice de masa corporal (IMC), número de hijos, hábito de fumar, región y el costo del seguro médico.
Fuente: Kaggle - Medical Cost Personal Dataset

### Técnicas utilizadas
Análisis exploratorio de datos (EDA)
Transformación de variables categóricas (one-hot encoding)
Estratificación por grupos de edad e IMC
Modelos de regresión supervisada: `Regresión Lineal`, `Árbol de Decisión` y `Bosque Aleatorio (Random Forest)`.
Validación cruzada
Evaluación con R² y RMSE
Análisis de importancia de características

### Hallazgos clave
- El modelo con mejor desempeño fue el regresor de bosque aleatorio, con un R² de 0.879 y un RMSE de 4378.8 USD en el conjunto de prueba.
- Las variables más influyentes en la predicción del costo médico son: la condición de fumador, edad y el índice de masa corporal (IMC).
- No se observaron diferencias significativas en el costo promedio entre hombres y mujeres, pero los hombres mostraron mayor variabilidad en los costos, especialmente entre fumadores y personas con obesidad.
- El análisis evidencia que la combinación de factores de riesgo (mayor edad, condición de fumador y sobrepeso) incrementa notablemente el costo del seguro.

