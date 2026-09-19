Proyecto de Regresión Lineal
Propósito
Este proyecto desarrolla un modelo de Regresión Lineal para predecir el precio de viviendas a partir de algunas de sus características físicas.

El conjunto de datos corresponde a ventas de viviendas de King County, Washington, durante 2014 y 2015.

Variables utilizadas
price: precio de la vivienda (variable objetivo).
bedrooms: número de habitaciones.
bathrooms: número de baños.
sqft_living: área habitable.
sqft_lot: área del terreno.
floors: número de pisos.
Librerías utilizadas
pandas
numpy
scikit-learn
matplotlib
Ejecución
Instalar Python 3.10 o superior.
Instalar las librerías necesarias:
pip install -r requirements.txt
Abrir el notebook:
notebooks/regresion_lineal.ipynb
Ejecutar las celdas del notebook en orden.
Modelo
Se utiliza un modelo de Regresión Lineal de scikit-learn, utilizando una división de los datos en entrenamiento y prueba con una semilla aleatoria fija (random_state=42).

Evaluación
El modelo se evalúa mediante:

MAE MSE RMSE R²

También se incluyen gráficos de precios reales frente a precios predichos y de residuos frente a valores predichos.
