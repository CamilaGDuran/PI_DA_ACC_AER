# Análisis de Accidentes Aéreos

## Introducción
Este informe presenta un análisis de datos relacionados con accidentes aéreos recopilados de la Organización de Aviación Civil Internacional (OACI). La OACI, un organismo de las Naciones Unidas, proporcionó un conjunto de datos que abarca accidentes aéreos desde principios del siglo XX. El objetivo de este análisis es profundizar en la comprensión de estos accidentes y extraer información relevante.

### Exploratory Data Analysis (EDA)
Para comenzar, se realizó un proceso de Análisis Exploratorio de Datos (EDA). Este paso fue esencial para comprender la calidad de los datos y la información contenida en ellos. Se llevaron a cabo las siguientes tareas:

#### Limpieza de Datos: Se identificaron y trataron los valores nulos o faltantes en los datos para garantizar la integridad del análisis.

#### Visualización de Datos: Se crearon gráficos para visualizar la distribución de datos en las columnas, tanto numéricas como categóricas, lo que permitió identificar patrones y repeticiones en los valores.

#### Análisis Bivariado: Se exploraron relaciones entre pares de variables para identificar posibles correlaciones y patrones significativos en los datos.

### KPIs (Indicadores Clave de Desempeño)
En respuesta a las solicitudes de la empresa, se definieron dos KPIs significativos:

1. #### Tasa de Fatalidad de la Tripulación
Se calculó la tasa de fatalidad de la tripulación en los últimos 10 años en comparación con la década anterior. Esta tasa se obtuvo dividiendo la suma total de fallecidos en el período de tiempo entre la suma total de accidentes en ese período. Esta métrica se utiliza para evaluar la seguridad de la tripulación.

##### Fórmula del KPI: Tasa de Fatalidad de la Tripulación = (Suma Total de Fallecidos / Suma Total de Accidentes) * 100

2. #### Índice de Seguridad Aérea por Década
Este KPI mide la seguridad aérea por década y se calcula utilizando la fórmula:

##### Índice de Seguridad Aérea = (Número de Pasajeros Fallecidos en Accidentes Aéreos / Total de Pasajeros a Bordo) * 100

Un índice más bajo indica un nivel de seguridad más alto en esa década, reflejando una menor proporción de pasajeros fallecidos en accidentes.

## Análisis de los Resultados
Después de calcular los KPIs y analizar los datos, se observaron algunas tendencias significativas:

La cantidad de accidentes aéreos se correlaciona con la elección de ciertos tipos de aviones. Se identificaron los cinco aviones más frecuentes en los datos y se analizó su relación con los accidentes. A medida que disminuyó el uso de estos aviones, se registraron menos accidentes aéreos.


## Conclusiones
El análisis de los datos de accidentes aéreos revela importantes implicaciones para mejorar la seguridad en la aviación. Las siguientes conclusiones se derivan de este análisis:

La elección de ciertos tipos de aviones influye significativamente en la incidencia de accidentes aéreos. Para mejorar la seguridad, se debería considerar la limitación o eliminación de la adquisición de estos aviones.

La seguridad de la tripulación es fundamental. A pesar de un alto índice de seguridad aérea, la tasa de fatalidad de la tripulación no disminuyó. Esto subraya la necesidad de una capacitación continua y un compromiso de las empresas a proporcionar los medios y las capacitaciones necesarias a sus tripulantes para garantizar su seguridad.
