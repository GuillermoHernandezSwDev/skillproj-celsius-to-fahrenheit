# Celsius to Fahrenheit - LinearRegression
[PROYECTO DE SKILL] Ejercicio de práctica de una regresión lineal sencilla con scikik-learn. El modelo aprende a convertir grados Celsius a Fahrenheit por su cuenta, sin usar fórmulas matemáticas.

## Descripción del Proyecto

En lugar de utilizar reglas predefinidas, este proyecto emplea técnicas de Aprendizaje Supervisado. Se alimenta al algoritmo con un conjunto de datos simple para que este deduzca la relación lineal existente entre las dos escalas de temperatura.

## Flujo de Trabajo

El notebook `primer_modelo_linreg.ipynb` documenta los siguientes pasos técnicos:

1.  **Carga de Datos:** Importación del dataset `celsius-fahrenheit.csv` utilizando la librería Pandas para su manipulación.
2.  **Visualización:** Análisis gráfico de los datos mediante Seaborn para confirmar la linealidad entre las variables.
3.  **Preprocesamiento:** Adaptación de las dimensiones de los datos (reshape) para su correcta ingestión por el modelo.
4.  **Entrenamiento:** Implementación y ajuste de un modelo de Regresión Lineal (`LinearRegression`) utilizando Scikit-Learn.
5.  **Validación:** Prueba del modelo con datos nuevos. Se realizó una predicción para 400°C, obteniendo el resultado correcto de 752°F, con un coeficiente de determinación (R²) de 1.0.

## Tecnologías Utilizadas

* **Python**: Lenguaje de programación principal.
* **Pandas**: Para la estructura y análisis de datos.
* **Seaborn**: Para la visualización estadística.
* **Scikit-Learn**: Para la implementación de algoritmos de Machine Learning.

## Requisitos

Para reproducir este entorno, se requieren las siguientes librerías:

* pandas
* seaborn
* scikit-learn
