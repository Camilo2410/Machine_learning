# Predicción de Precios de Bienes Raíces con Regresión Lineal Múltiple

Este proyecto se enfoca en predecir los precios de bienes raíces utilizando un modelo de regresión lineal múltiple. El conjunto de datos incluye características como la edad de la casa, la ubicación, la distancia a la estación MRT más cercana, entre otras, para predecir el precio de la vivienda por unidad de área.

## Problema de Negocio: Predicción del Precio de la Vivienda

**Descripción del Problema**
El objetivo de este análisis es desarrollar un modelo predictivo que pueda estimar el precio de los bienes raíces en función de diversas características de la propiedad. Este tipo de modelos son útiles para inversores inmobiliarios, agentes y compradores potenciales para entender mejor el mercado y tomar decisiones informadas.

## Datos

El conjunto de datos contiene las siguientes columnas:

| Variable                                  | Descripción                                      |
|-------------------------------------------|--------------------------------------------------|
| X1 transaction date                       | Fecha de la transacción                          |
| X2 house age                              | Edad de la casa                                  |
| X3 distance to the nearest MRT station    | Distancia a la estación MRT más cercana          |
| X4 number of convenience stores           | Número de tiendas de conveniencia cercanas       |
| X5 latitude                               | Latitud                                          |
| X6 longitude                              | Longitud                                         |
| Y house price of unit area                | Precio de la casa por unidad de área             |

## Metodología

Pasos realizados en el análisis:

1. **Carga y Exploración de Datos**: Se cargaron y exploraron los datos para comprender su estructura y naturaleza.

2. **Preparación de Datos**: Se dividió el conjunto de datos en variables independientes y dependientes para el análisis.

3. **División en Conjuntos de Entrenamiento y Prueba**: Se separó el conjunto de datos en subconjuntos para entrenamiento y prueba.

4. **Modelado con Regresión Lineal Múltiple**: Se construyó y entrenó un modelo de regresión lineal múltiple.

5. **Evaluación del Modelo y Eliminación hacia Atrás**: Se evaluó el modelo utilizando MSE y R², y se aplicó la técnica de eliminación hacia atrás para optimizar la selección de variables.

## Resultados y Conclusión

Los resultados muestran cómo cada característica contribuye al precio de los bienes raíces. La técnica de eliminación hacia atrás confirmó la significancia de todas las variables en este caso, indicando su relevancia en el modelo de predicción.

## Bibliotecas Utilizadas

- Pandas: Para manipulación y análisis de datos.
- Scikit-learn: Para creación y evaluación de modelos de machine learning.
- Statsmodels: Para realizar la eliminación hacia atrás y análisis estadístico.
- Matplotlib y Seaborn: Para visualización de datos.

## Cómo Ejecutar el Código

El análisis se llevó a cabo en Jupyter Notebook. Para reproducir este análisis, es necesario tener Python instalado junto con las bibliotecas mencionadas.

## Licencia

Este proyecto está licenciado bajo los términos de la licencia MIT.

