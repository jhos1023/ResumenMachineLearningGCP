# Introduction
BigQuery is a fully managed data warehouse.
Un warehouse es un gran depósito, que contiene terabytes y petabytes de datos recogidos de una amplia gama de fuentes dentro de una organización, y que se utiliza para orientar las decisiones de gestión.

la principal diferencia entre un data warehouse y un data lake radica en la estructura y el enfoque de almacenamiento de datos. Los data warehouses son ideales para el análisis de negocios y generación de informes, mientras que los data lakes son más adecuados para almacenar grandes volúmenes de datos no procesados y permitir análisis avanzados y exploratorios. En muchos casos, ambas soluciones pueden complementarse en una arquitectura de datos más amplia y eficiente.

## Características de BigQuery
BigQuery brinda 2 servicios en uno: Storage y Analytics 
También es serverless solution, significa que no necesita preocuparse por recursos.
Los datos de BigQuery ya se encuentran encriptados por default.
El input de data puede ser real-time o batch data. Si es batch data será subida al Cloud Storage.
Si es Real-time va a PUB/SUB, luego ambos pipelines van a DataFLow a procesar la data.
Ahí realiza el ETL. Luego entra Big Query que envia a 2 buckets

![sub](Images/1.JPG)
