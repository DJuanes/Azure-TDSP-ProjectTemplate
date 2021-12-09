# Reporte de Modelo Base

_El modelo base es el modelo que un científico de datos capacitaría y evaluaría rápidamente después de tener el primer conjunto de features (preliminar) listo para el modelado de aprendizaje automático. A través de la construcción del modelo base, el científico de datos puede tener una evaluación rápida de la viabilidad de la tarea de aprendizaje automático._

Cuando corresponde, la utilidad Automated Modeling and Reporting desarrollada por el equipo TDSP de Microsoft se emplea para construir los modelos base rápidamente. El reporte del modelo base se genera fácilmente a partir de esta utilidad.

> Si utiliza la herramienta Automated Modeling and Reporting, la mayoría de las secciones siguientes se generarán automáticamente a partir de esta herramienta. 

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
* Conclusión sobre la evaluación de viabilidad de la tarea de aprendizaje automático
* Discusión sobre sobreajuste (si corresponde)
* ¿Qué otros features se pueden generar a partir de los datos actuales?
* ¿Qué otras fuentes de datos relevantes están disponibles para ayudar al modelado? 
