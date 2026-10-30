# Análisis del crecimiento empresarial — INC 5000 (2019)

## Introducción
Este proyecto analiza las empresas incluidas en el ranking INC 5000 de 2019 con el objetivo de identificar patrones asociados al crecimiento de sus ingresos.

## Pregunta de análisis
¿Qué características de las empresas incluidas en el ranking INC 5000 de 2019 se relacionan con su crecimiento de ingresos, considerando la industria, los ingresos, la cantidad de empleados, la antigüedad y la ubicación geográfica?

## Justificación del dataset
Se seleccionó el ranking INC 5000 de 2019 porque reúne información de empresas de distintos sectores y ubicaciones geográficas, e incluye variables relevantes para analizar su crecimiento, como ingresos, porcentaje de crecimiento, cantidad de empleados y antigüedad. Estas características permiten realizar comparaciones y explorar posibles relaciones entre las variables dentro del conjunto de empresas analizado.

## Objetivos
- Analizar el crecimiento de ingresos de las empresas.
- Comparar resultados según industria, ubicación geográfica y antigüedad.
- Explorar la relación entre ingresos, cantidad de empleados y crecimiento.
- Comunicar los principales hallazgos mediante visualizaciones y un dashboard interactivo.

## Dataset
El análisis utiliza el ranking INC 5000 de 2019. El conjunto de datos contiene 5.012 empresas y variables relacionadas con ingresos, crecimiento porcentual, industria, empleados, antigüedad y ubicación.

## Herramientas utilizadas
- Python
- Pandas y NumPy
- Matplotlib y Seaborn
- Power BI
- GitHub

## Metodología
1. Carga y exploración de los datos.
2. Limpieza y validación de la información.
3. Análisis exploratorio de datos (EDA).
4. Visualización e interpretación de resultados.
5. Desarrollo de un dashboard interactivo en Power BI.

## Principales hallazgos
El análisis muestra una distribución asimétrica del crecimiento de ingresos: el promedio es considerablemente superior a la mediana, debido a la presencia de empresas con tasas de crecimiento excepcionalmente altas.

También se observan diferencias en el crecimiento según la antigüedad y la industria. Estos resultados corresponden a las empresas incluidas en el ranking analizado y no deben generalizarse automáticamente a todas las empresas.

## Archivos del proyecto
- [Notebook de Python](notebooks/Análisis_del_crecimiento_empresarial_—_INC_5000_2019.ipynb): código, análisis exploratorio y visualizaciones.
- [Dashboard de Power BI](dashboard/INC5000_Analisis.pbix): dashboard interactivo.
- [Dataset limpio](data/raw/INC5000_limpio%20(1).csv): conjunto de datos utilizado en el análisis.

## Autor
Proyecto final realizado como parte de la formación en análisis de datos de UTN.
