# Definiciones de features y datos

Este documento proporciona un hub para las fuentes de datos sin procesar, los datos procesados/transformados y los conjuntos de features. Se proporcionan más detalles de cada dataset en el reporte de resumen de datos.

Para cada dato, se proporciona un reporte individual que describe el esquema de datos, el significado de cada campo y cualquier otra información que sea útil para comprender los datos. Si el dataset es la salida de datasets existentes de procesamiento/transformación/features, también se proporcionan los nombres de los datasets de entrada y los links a los scripts que se utilizan para realizar la operación.

Cuando corresponde, la utilidad Interactive Data Exploration, Analysis, and Reporting (IDEAR) desarrollada por Microsoft se aplica para explorar y visualizar los datos y generar el reporte de datos.

Para cada dataset, también se proporcionan los links a los datasets de muestra en el directorio _**Datos**_.


_**Para facilitar la modificación de este reporte, los links de marcador de posición se incluyen en esta página, por ejemplo, un enlace al dataset 1, pero son solo marcadores de posición que apuntan a una página que no existe. Deben modificarse para que apunten a la ubicación real.**_


## Fuentes de datos sin procesar

| Nombre del Dataset | Ubicación Origen   | Ubicación Destino  | Herramienta de movimiento de datos / Scripts | Link al Reporte |
| ---:| ---: | ---: | ---: | -----: |
| Dataset 1 | Breve descripción de su ubicación de origen | Breve descripción de su ubicación de destino | [script1.py](link/to/python/script/file/in/Code) | [Reporte Dataset 1](link/to/report1)|
| Dataset 2 | Breve descripción de su ubicación de origen | Breve descripción de su ubicación de destino | [script2.R](link/to/R/script/file/in/Code) | [Reporte Dataset 2](link/to/report2)|

* Resúmen del Dataset1. <Proporcione un breve resumen de los datos, por ejemplo, cómo acceder a los datos. Debe haber información más detallada en el Reporte Dataset1.>
* Resúmen del Dataset2. <Proporcione un breve resumen de los datos, por ejemplo, cómo acceder a los datos. Debe haber información más detallada en el Reporte Dataset2.> 

## Fuentes de datos procesadas

| Nombre del Dataset | Dataset(s) origen   | Herramienta de Procesamiento/Scripts | Link al Reporte |
| ---:| ---: | ---: | ---: | 
| Dataset 1 Procesado | [Dataset1](link/to/dataset1/report), [Dataset2](link/to/dataset2/report) | [Python_Script1.py](link/to/python/script/file/in/Code) | [Reporte Dataset 1 Procesado](link/to/report1)|
| Dataset 2 Procesado | [Dataset2](link/to/dataset2/report) |[script2.R](link/to/R/script/file/in/Code) | [Reporte Dataset 2 Procesado](link/to/report2)|

* Resúmen del Dataset1 Procesado. <Proporcione un breve resumen de los datos procesados, como por qué desea procesar los datos de esta manera. La información más detallada sobre los datos procesados debe estar en el Reporte Dataset1 Procesado.>
* Resúmen del Dataset2 Procesado. <Proporcione un breve resumen de los datos procesados, como por qué desea procesar los datos de esta manera. La información más detallada sobre los datos procesados debe estar en el Reporte Dataset2 Procesado.> 

## Conjuntos de Features

| Nombre del conjunto de features | Dataset(s) origen  | Herramienta de ingeniería de Feature/Scripts | Link al Reporte |
| ---:| ---: | ---: | ---: | 
| Feature Set 1 | [Dataset1](link/to/dataset1/report), [Dataset2 Procesado](link/to/dataset2/report) | [R_Script2.R](link/to/R/script/file/in/Code) | [Reporte Feature Set1](link/to/report1)|
| Feature Set 2 | [Dataset2 Procesado](link/to/dataset2/report) |[SQL_Script2.sql](link/to/sql/script/file/in/Code) | [Reporte Feature Set2](link/to/report2)|

* Resúmen de Feature Set1. <Proporcione una descripción detallada del conjunto de features, como el significado de cada feature. La información más detallada sobre el conjunto de features debe estar en el Reporte Feature Set1.>
* Resúmen de Feature Set2. <Proporcione una descripción detallada del conjunto de features, como el significado de cada feature. La información más detallada sobre el conjunto de features debe estar en el Reporte Feature Set2.>
