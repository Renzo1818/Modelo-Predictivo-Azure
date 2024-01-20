## DISEÑO DE UN MODELO PREDICTIVO: APROBACIÓN DE PRÉSTAMOS MONETARIOS
El presente proyecto tiene como objetivo diseñar un modelo predictivo para hallar si ciertos clientes de una entidad financiera son aptos para recibir un préstamo monetario. Se realizó bajo la arquitectura de aprendiza automático de Azure.

#### AZURE DATA FACTORY: INGESTA Y ORQUESTADOR DE PROCESOS

<p align="center">
  <img src="https://learn.microsoft.com/es-es/azure/architecture/example-scenario/ai/media/deploy-real-time-machine-learning-model-application-ui.png">
</p>


## IMPLEMENTACION DE SERVICIOS AZURE
#### AZURE DATA FACTORY: INGESTA Y ORQUESTADOR DE PROCESOS

![DATA FACTORY PRESTAMOS](https://github.com/Renzo1818/Modelo-Predictivo-Azure/assets/93232895/614d87df-20ce-4474-bf13-1ac392bc247b)

Creación de conjuntos de datos a partir de fuentes de datos On-Premises, extracción de estos mismos, invocación de notebooks de Databricks para la transformaciones necesarias y por último el diseño de un modelo predictivo en Azure Machine Learning.

#### AZURE DATA LAKE STORAGE

![DATA LAKE PRESTAMOS](https://github.com/Renzo1818/Modelo-Predictivo-Azure/assets/93232895/3e64cb73-31c8-4776-b0f6-6219ade1c694)

Diseño de un Data Lakehouse para almacenar los conjuntos de datos en su formato en bruto, datos semiprocesados y procesados para en consumo de otros servicios de Azure. Aplicación de la arquitectura de medallas: bronze, Silver y Gold para almacenar los datos por capa de calidad.

#### AZURE DATABRICKS
- ETL PRESTAMOS:

![DATABRICKS PRESTAMOS](https://github.com/Renzo1818/Modelo-Predictivo-Azure/assets/93232895/fc004f4e-5cd4-42f1-9088-49c7f3793e66)

#### AZURE MACHINE LEARNING
Diseño de un modelo predictivo para hallar si ciertos clientes de una entidad financiera son aptos para recibir un préstamo monetario utilizando el algoritmo "Árbol de decisiones" para el entrenamiento del modelo.

- Modelo entrenado: Árbol de decision - Prestamos

![DISEÑO ARBOL DE DECISIONES PRESTAMOS](https://github.com/Renzo1818/Modelo-Predictivo-Azure/assets/93232895/7b863c56-0ec1-413e-a1ca-25c2a627db7c)

- Porcentajes de confianza:

![PORCENTAJE DE CONFIANZA PRESTAMOS](https://github.com/Renzo1818/Modelo-Predictivo-Azure/assets/93232895/a3e9a141-ae5b-4b12-9dc1-26db9f386825)

- Matriz de Confusión:

![MATRIZ DE CONFUSION PRESTAMOS](https://github.com/Renzo1818/Modelo-Predictivo-Azure/assets/93232895/21ca0cad-d2ef-4225-8dbb-863c4e733de8)
