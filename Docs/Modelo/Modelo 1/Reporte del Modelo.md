# Reporte del Modelo
_Un reporte para proporcionar detalles sobre un experimento específico (modelo), posiblemente uno de muchos_

Si corresponde, la utilidad Automated Modeling and Reporting desarrollada por el equipo de Microsoft TDSP se puede utilizar para generar reportes, que pueden proporcionar contenido para la mayoría de las secciones de este reporte del modelo.

## Enfoque analítico
* ¿Cual es la definición del target?
* ¿Cuales son las entradas? (descripción)
* ¿Qué tipo de modelo se construyó?

## Descripción del modelo
* Modelos y parámetros
	* Descripción o imágenes del gráfico de flujo de datos
	  * si es AzureML, link a:
	    * Experimento de entrenamiento
	    * Flujo de trabajo de puntuación
	* ¿Qué aprendizajes se utilizaron?
	* Hiperparámetros del aprendizaje

## Resultados (rendimiento del modelo)
* Gráficos ROC/Lift, AUC, R^2, MAPE según corresponda
* Gráficos de rendimiento para barridos de parámetros, si corresponde 

## Comprensión del modelo
* Importancia variable (significación)
* Conocimiento derivado del modelo

## Conclusión y discusiones para los próximos pasos
* Conclusión
* Discusión sobre sobreajuste (si corresponde)
* ¿Qué otros features se pueden generar a partir de los datos actuales?
* ¿Qué otras fuentes de datos relevantes están disponibles para ayudar al modelado? 
