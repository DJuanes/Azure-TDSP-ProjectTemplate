# Definiciones de features y datos

Este documento proporciona un hub para las fuentes de datos sin procesar, los datos procesados/transformados y los conjuntos de features. Se proporcionan más detalles de cada dataset en el reporte de resumen de datos.

Para cada dato, se proporciona un reporte individual que describe el esquema de datos, el significado de cada campo y cualquier otra información que sea útil para comprender los datos. Si el dataset es la salida de datasets existentes de procesamiento/transformación/features, también se proporcionan los nombres de los datasets de entrada y los links a los scripts que se utilizan para realizar la operación.

Cuando corresponde, la utilidad Interactive Data Exploration, Analysis, and Reporting (IDEAR) desarrollada por Microsoft se aplica para explorar y visualizar los datos y generar el reporte de datos. Las instrucciones sobre cómo utilizar IDEAR se pueden encontrar [aquí]().

When applicable, the Interactive Data Exploration, Analysis, and Reporting (IDEAR) utility developed by Microsoft is applied to explore and visualize the data, and generate the data report. Instructions of how to use IDEAR can be found [here](). 

For each dataset, the links to the sample datasets in the _**Data**_ directory are also provided. 

_**For ease of modifying this report, placeholder links are included in this page, for example a link to dataset 1, but they are just placeholders pointing to a non-existent page. These should be modified to point to the actual location.**_


## Raw Data Sources


| Dataset Name | Original Location   | Destination Location  | Data Movement Tools / Scripts | Link to Report |
| ---:| ---: | ---: | ---: | -----: |
| Dataset 1 | Brief description of its orignal location | Brief description of its destination location | [script1.py](link/to/python/script/file/in/Code) | [Dataset 1 Report](link/to/report1)|
| Dataset 2 | Brief description of its orignal location | Brief description of its destination location | [script2.R](link/to/R/script/file/in/Code) | [Dataset 2 Report](link/to/report2)|


* Dataset1 summary. <Provide brief summary of the data, such as how to access the data. More detailed information should be in the Dataset1 Report.>
* Dataset2 summary. <Provide brief summary of the data, such as how to access the data. More detailed information should be in the Dataset2 Report.> 

## Processed Data
| Processed Dataset Name | Input Dataset(s)   | Data Processing Tools/Scripts | Link to Report |
| ---:| ---: | ---: | ---: | 
| Processed Dataset 1 | [Dataset1](link/to/dataset1/report), [Dataset2](link/to/dataset2/report) | [Python_Script1.py](link/to/python/script/file/in/Code) | [Processed Dataset 1 Report](link/to/report1)|
| Processed Dataset 2 | [Dataset2](link/to/dataset2/report) |[script2.R](link/to/R/script/file/in/Code) | [Processed Dataset 2 Report](link/to/report2)|

* Processed Data1 summary. <Provide brief summary of the processed data, such as why you want to process data in this way. More detailed information about the processed data should be in the Processed Data1 Report.>
* Processed Data2 summary. <Provide brief summary of the processed data, such as why you want to process data in this way. More detailed information about the processed data should be in the Processed Data2 Report.> 

## Feature Sets

| Feature Set Name | Input Dataset(s)   | Feature Engineering Tools/Scripts | Link to Report |
| ---:| ---: | ---: | ---: | 
| Feature Set 1 | [Dataset1](link/to/dataset1/report), [Processed Dataset2](link/to/dataset2/report) | [R_Script2.R](link/to/R/script/file/in/Code) | [Feature Set1 Report](link/to/report1)|
| Feature Set 2 | [Processed Dataset2](link/to/dataset2/report) |[SQL_Script2.sql](link/to/sql/script/file/in/Code) | [Feature Set2 Report](link/to/report2)|

* Feature Set1 summary. <Provide detailed description of the feature set, such as the meaning of each feature. More detailed information about the feature set should be in the Feature Set1 Report.>
* Feature Set2 summary. <Provide detailed description of the feature set, such as the meaning of each feature. More detailed information about the feature set should be in the Feature Set2 Report.> 
