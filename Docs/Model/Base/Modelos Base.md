# Reporte de Modelo Base

_El modelo base es el modelo que un científico de datos capacitaría y evaluaría rápidamente después de tener el primer conjunto de features (preliminar) listo para el modelado de aprendizaje automático. A través de la construcción del modelo base, el científico de datos puede tener una evaluación rápida de la viabilidad de la tarea de aprendizaje automático._

Cuando corresponde, la utilidad Automated Modeling and Reporting desarrollada por el equipo TDSP de Microsoft se emplea para construir los modelos base rápidamente. El reporte del modelo base se genera fácilmente a partir de esta utilidad.

> Si utiliza la herramienta Automated Modeling and Reporting, la mayoría de las secciones siguientes se generarán automáticamente a partir de esta herramienta. 

## Analytic Approach
* What is target definition
* What are inputs (description)
* What kind of model was built?

## Model Description

* Models and Parameters

	* Description or images of data flow graph
  		* if AzureML, link to:
    		* Training experiment
    		* Scoring workflow
	* What learner(s) were used?
	* Learner hyper-parameters


## Results (Model Performance)
* ROC/Lift charts, AUC, R^2, MAPE as appropriate
* Performance graphs for parameters sweeps if applicable

## Model Understanding

* Variable Importance (significance)

* Insight Derived from the Model



## Conclusion and Discussions for Next Steps

* Conclusion on Feasibility Assessment of the Machine Learning Task

* Discussion on Overfitting (If Applicable)

* What other Features Can Be Generated from the Current Data

* What other Relevant Data Sources Are Available to Help the Modeling
