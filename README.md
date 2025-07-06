# Challenge Telecom X: análisis de evasión de clientes para G8 - ONE de Alura Latam

## :brain: Objetivos del proyecto

- Comprender los factores que llevan a que la empresa "Telecom X" tenga una alta tasa de cancelaciones, lo que repercute en la pérdida de clientes
- Recopilar, procesar y analizar los datos, utilizando Python y sus principales bibliotecas 
- Extraer información detallada
- Realizar un análisis detallado para que el equipo de Data Science pueda avanzar en modelos predictivos y desarrollar estrategias para reducir la evasión

## :hammer_and_wrench: Desarrollo del proyecto

- Importar y manipular datos desde una API de manera eficiente
- Aplicar los conceptos de ETL (Extracción, Transformación y Carga) en la preparación de los datos
- Crear visualizaciones estratégicas para identificar patrones y tendencias
- Realizar un Análisis Exploratorio de Datos (EDA) y generar un informe con insights relevantes
  
## :memo: Extracción de datos

 - Para iniciar el análisis, necesitaremos importar los datos de la API de Telecom X. Estos datos están disponibles en formato JSON y contienen información esencial sobre los clientes, incluyendo datos          demográficos,   tipo de servicio contratado y estado de evasión
 - Cargar los datos directamente desde la API utilizando Python.
 - Convertir los datos a un DataFrame de Pandas para facilitar su manipulación
   
 ## :computer: Conjuntos y estructura de datos

 Para comprender la estructura del dataset y el significado de sus columnas, identificaremos qué variables son más relevantes para el análisis de evasión de clientes
 - Diccionario de datos con la descripción de cada columna
 - Explorar las columnas del dataset y verificar sus tipos de datos
 - Consultar el diccionario para comprender mejor el significado de las variables
 - Identificar las columnas más relevantes para el análisis de evasión
 
## :clipboard: Comprobación de incoherencias en los datos y manejo de inconsistencias

  - Verificación de problemas en los datos que puedan afectar el análisis
  - Atención a valores ausentes, duplicados, errores de formato e inconsistencias en las categorías
  - Identificación de inconsistencias y aplicación las correcciones necesarias.
  - Ajuste de datos para asegurar que estén completos y coherentes, preparándolos para las siguientes etapas del análisis

##  :bar_chart: Carga y análisis(L - Load & Analysis)

-  Análisis descriptivo de los datos, calculando métricas como media, mediana, desviación estándar y otras medidas que ayuden a comprender mejor la distribución y el comportamiento de los clientes
-  Comprender cómo está distribuida la variable "churn" (evasión) entre los clientes. Utilización de gráficos para visualizar la proporción de clientes que permanecieron y los que se dieron de baja
-  Explorar cómo se distribuye la evasión según variables categóricas, como género, tipo de contrato, método de pago, entre otras, revelando patrones interesantes, por ejemplo, si los clientes de ciertos perfiles tienen una mayor tendencia a cancelar el servicio, lo que ayudará a orientar acciones estratégicas
- Explorar cómo las variables numéricas, como "total gastado" o "tiempo de contrato", se distribuyen entre los clientes que cancelaron (evasión) y los que no cancelaron, para entender si ciertos valores numéricos están más asociados con la evasión, proporcionando insights sobre los factores que influyen en el comportamiento de los clientes

## :white_check_mark: Informe Final

- Introducción: Explica el objetivo del análisis y el problema de evasión de clientes (Churn)
- Limpieza y Tratamiento de Datos: Describe los pasos realizados para importar, limpiar y procesar los datos
- Análisis Exploratorio de Datos: Presenta los análisis realizados, incluyendo gráficos y visualizaciones para identificar patrones
- Conclusiones e Insights: Resume los principales hallazgos y cómo estos datos pueden ayudar a reducir la evasión



