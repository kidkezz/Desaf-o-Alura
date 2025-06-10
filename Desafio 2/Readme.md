Análisis de Cancelación de Clientes - Telecom X
📌 Descripción del Proyecto
Telecom X, una empresa de servicios de internet y telefonía, enfrenta una alta tasa de cancelación de clientes. Este proyecto tiene como objetivo analizar los datos de sus clientes para identificar patrones y factores que influyen en el abandono del servicio (churn), utilizando Python y sus bibliotecas de análisis de datos.

🎯 Objetivo
Analizar el comportamiento de los clientes para detectar las causas de cancelación.

Aplicar técnicas de limpieza, visualización y modelado de datos.

Proponer recomendaciones accionables para mejorar la retención de clientes.

🧾 Diccionario de Datos
El dataset contiene 7267 registros y 21 columnas. Algunos de los campos clave son:

customerID: Identificación del cliente.

Churn: Si el cliente canceló o no el servicio.

gender: Género del cliente.

SeniorCitizen: Si el cliente es mayor de 65 años.

Partner, Dependents: Situación familiar.

tenure: Meses con la compañía.

InternetService, OnlineSecurity, StreamingTV, etc.: Servicios contratados.

Contract, PaymentMethod: Tipo de contrato y método de pago.

Charges.Monthly, Charges.Total: Cargos mensuales y totales.

🛠️ Herramientas y Tecnologías
Lenguaje: Python

Librerías:

pandas, numpy: Manipulación y análisis de datos

matplotlib, seaborn: Visualización de datos

📊 Análisis Realizado
Carga y Exploración Inicial del Dataset

Revisión de tipos de datos y valores faltantes.

Conversión de columnas a tipos adecuados (por ejemplo, valores numéricos).

Limpieza de Datos

Detección y eliminación de duplicados (no se encontraron).

Corrección de tipos de datos y valores inconsistentes.

Análisis Exploratorio

Distribuciones de variables relevantes.

Análisis de correlación entre características y churn.

Visualizaciones comparativas entre clientes que se quedaron vs. los que se fueron.
