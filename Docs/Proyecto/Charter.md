# Project Charter

## Conocimiento del negocio

* Quién es el cliente, en qué dominio del negocio se encuentra el cliente.
* ¿Qué problemas del negocio estamos tratando de abordar?

## Alcance
* ¿Qué soluciones de ciencia de datos estamos tratando de construir?
* ¿Que haremos?
* ¿Cómo lo va a consumir el cliente?

## Personal
* Quiénes están en este proyecto:
	* Equipo DS YPF:
		* Lider del Proyecto
		* PM
		* Científico(s) de datos
		* Gerente de cuentas
	* Cliente interno:
		* Administrador de datos
		* Contacto del negocio

## Métricas
* ¿Cuáles son los objetivos cualitativos? (por ejemplo, reducir la pérdida de usuarios)
* ¿Cuáles son las métricas cuantificables? (por ejemplo, reducir la fracción de usuarios con 4 semanas de inactividad)
* Cuantificar qué mejoras en los valores de las métricas son útiles para el escenario del cliente (por ejemplo, reducir la fracción de usuarios con 4 semanas de inactividad en un 20%)
* ¿Cuál es el valor de referencia (actual) de la métrica? (por ejemplo, fracción actual de usuarios con 4 semanas de inactividad = 60%)
* ¿Cómo mediremos la métrica? (por ejemplo, prueba A/B en un subconjunto específico durante un período específico; o comparación del desempeño después de la implementación con la línea de base)

## Plan
* Fases (hitos), cronograma, breve descripción de lo que haremos en cada fase.

## Arquitectura
* Datos
  * ¿Qué datos esperamos? Datos sin procesar en las fuentes de datos del cliente (por ejemplo, archivos on-premises, SQL, Hadoop, etc.)
* Movimiento de datos desde on-premises a Azure mediante ADF u otras herramientas de movimiento de datos (Azcopy, EventHub, etc.) para mover
  * todos los datos,
  * después de una agregación previa,
  * datos muestreados suficientes para modelar

* Qué herramientas y recursos de almacenamiento / análisis se utilizarán en la solución, por ejemplo,
  * ASA para agregación de streaming
  * HDI / Hive / R / Python para construcción, agregación y muestreo de features
  * AzureML para modelado y operacionalización de servicios web
* ¿Cómo se consumirá el puntaje o los servicios web operacionalizados (RRS y / o BES) en el flujo de trabajo del cliente? Si corresponde, escriba el pseudocódigo para las API de las llamadas al servicio web.
  * ¿Cómo utilizará el cliente los resultados del modelo para tomar decisiones?
  * Canalización de movimiento de datos en producción
  * Haga un diagrama de 1 diapositiva que muestre el flujo de datos de extremo a extremo y la arquitectura de decisiones
    * Si hay un cambio sustancial en el flujo de trabajo comercial del cliente, haga un diagrama de antes / después que muestre el flujo de datos.

## Comunicación
* ¿Cómo nos mantendremos en contacto? ¿Reuniones semanales?
* ¿Quiénes son las personas de contacto en ambos lados?
