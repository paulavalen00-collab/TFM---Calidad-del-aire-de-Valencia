# Valencia Verde 2030
## Análisis y predicción de indicadores ambientales urbanos con tecnologías Big Data

Trabajo Fin de Máster del Máster Universitario en Análisis y Visualización de Datos Masivos de la Universidad Internacional de La Rioja (UNIR).

## Objetivo del proyecto

Analizar la evolución de la calidad del aire en Valencia mediante tecnologías Big Data y modelos predictivos, con el fin de evaluar su evolución respecto a los objetivos europeos de calidad del aire establecidos para 2030.

Se estudian cuatro contaminantes: NO₂, PM₁₀, PM₂,₅ y O₃, junto con información complementaria de tráfico, meteorología y contaminación acústica.

## Tecnologías utilizadas
- Python y PySpark
- Google Cloud Storage
- Google Cloud Dataproc
- SQL
- Power BI


## Organización del repositorio

Los notebooks están organizados siguiendo los apartados del capítulo 6 de la memoria del TFM.

- **01_comprension_datos:** exploración y caracterización inicial de los conjuntos de datos, incluyendo su estructura, cobertura y calidad.

- **02_preparacion_datos:** limpieza, transformación y estandarización de los datos para su posterior análisis e integración.

- **03_integracion_gold:** construcción y carga de las tablas de hechos y dimensiones de la capa Gold mediante PySpark en Google Cloud.

- **04_analisis_comportamiento:** análisis de la evolución de la calidad del aire, su relación con el tráfico, la meteorología y el ruido, y sus patrones temporales y espaciales.

- **05_modelos:** desarrollo, validación y evaluación de modelos predictivos de calidad del aire y tráfico, incluyendo las estimaciones hasta 2030 y a 24 horas.

- **06_visualizacion_powerbi:** desarrollo del panel interactivo de Power BI para explorar los indicadores ambientales y visualizar los resultados predictivos.

    
