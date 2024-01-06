# Análisis de la relación entre la edad y los costos del seguro médico

Este proyecto analiza cómo la edad de los asegurados afecta los costos del seguro médico. Utilizamos un conjunto de datos inspirado en el libro "Machine Learning with R" de Brett Lantz, el cual contiene información médica y los costos facturados por las compañías de seguros de salud.

## Problema de Negocio: Predicción del Costo del Seguro en función de la Edad

**Descripción del Problema**
El objetivo de este análisis es entender cómo la edad influye en los costos del seguro médico. Se parte de la hipótesis de que, a medida que las personas envejecen, es probable que los costos asociados al seguro médico aumenten, debido a un incremento en los riesgos de salud.

## Datos

El conjunto de datos contiene las siguientes columnas:

| Variable  | Descripción                        |
|-----------|------------------------------------|
| age       | Edad del asegurado                 |
| sex       | Sexo del asegurado                 |
| bmi       | Índice de masa corporal            |
| children  | Número de hijos/dependientes       |
| smoker    | Si el asegurado es fumador         |
| region    | Región de residencia del asegurado |
| charges   | Costos del seguro médico           |

## Metodología

Para realizar este análisis se llevó a cabo los siguientes pasos:

1. **Carga y Exploración de Datos**: Se cargaron los datos y se realizó una exploración inicial para comprender la estructura y naturaleza de los datos disponibles.

2. **Preparación de Datos**: Se segmentó el conjunto de datos en características ('features') y variable objetivo ('target'), donde la edad fue la característica y los costos del seguro la variable objetivo.

3. **División en Conjuntos de Entrenamiento y Prueba**: Se dividió el conjunto de datos en un subconjunto para entrenamiento y otro para prueba, con el fin de poder evaluar la eficacia del modelo.

4. **Modelado**: Se construyó un modelo de regresión lineal simple utilizando la biblioteca `scikit-learn` de Python para predecir los costos del seguro en función de la edad.

5. **Evaluación del Modelo**: Se evaluó el modelo utilizando métricas estándar como el Error Cuadrático Medio (MSE) y el coeficiente de determinación (R^2).

## Resultados y Conclusión

Los resultados del modelo indicaron que la edad tiene una relación lineal con el aumento de los costos del seguro. Sin embargo, el coeficiente de determinación (R^2) sugiere que otros factores no incluidos en el modelo también juegan un papel significativo en la predicción de los costos. Se recomienda la inclusión de más variables para mejorar la precisión del modelo.

## Bibliotecas Utilizadas

- Pandas: Para la manipulación y análisis de datos.
- Scikit-learn: Para la creación y evaluación de modelos de machine learning.
- Matplotlib: Para la visualización de datos.

## Cómo Ejecutar el Código

El análisis se realizó en un entorno de Jupyter Notebook. Para ejecutar este análisis, se requiere tener instalado Python y las bibliotecas mencionadas. El código fuente está disponible en este repositorio y se puede ejecutar célula por célula en Jupyter Notebook para reproducir el análisis.

## Licencia

Este proyecto está licenciado bajo los términos de la licencia MIT.
