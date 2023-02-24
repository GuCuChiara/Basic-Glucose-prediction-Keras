# Basic-Glucose-prediction-Keras
Modelo básico de predicción del valor de glucemia en mg/dl usando Keras

Entrenamos un modelo con el archivo gluc_conversion.csv que contiene 57 registros con las siguientes variables:

**variable x** = valores de glucemia en "mmol_L"

**variable y** = valores de glucemia a predecir en "mg_dl"

* Red neuronal 3 capas ocultas, 1 capa de salida
* Función de activación: ReLu
* Optimizador: Adam
* Learning_rate: 0.01
* epochs: 500

Graficamos con matplotlib, comparamos la predicción, con los valores de entrada.

Guardamos el modelo (gluc_conversion.h5) en nuestro colab luego lo importamos para hacer nuevas predicciones de los valores de glucemia en mg/dl.
