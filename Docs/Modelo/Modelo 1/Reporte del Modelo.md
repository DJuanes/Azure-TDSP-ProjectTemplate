# Reporte del Modelo
_Un reporte para proporcionar detalles sobre un experimento específico (modelo), posiblemente uno de muchos_

Si corresponde, la utilidad Automated Modeling and Reporting desarrollada por el equipo de Microsoft TDSP se puede utilizar para generar reportes, que pueden proporcionar contenido para la mayoría de las secciones de este reporte del modelo.

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
* Conclusion
* Discussion on overfitting (if applicable)
* What other Features Can Be Generated from the Current Data
* What other Relevant Data Sources Are Available to Help the Modeling
