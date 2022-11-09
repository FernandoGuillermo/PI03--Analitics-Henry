# PI03--Analitics-Henry

## **Contexto**
La **Organización de Aviación Civil Internacional (OACI)**, organismo de la Organización de las Naciones Unidas,
quiere investigar en profundidad los accidentes producidos desde inicios del siglo XX. Para ello,les solicita la elaboración de un informe y un
dashboard interactivo que recopile tal información.

La OACI únicamente cuenta con un dataset sobre datos de accidentes de aviones, pero insta a la consultora de datos -de la que forman parte- que intente 
cruzar esta información con otras fuentes de su interés. Esto con el objetivo de obtener mayor claridad y consistencia en los fundamentos del estudio.

## **Objetivos**
 

+ Realizar análisis exploratorio de datos en los datasets para luego relacionaros e ingestarlos al  motor de base de datos.
+ Extraer la información de la base de datos con alguna herramienta de visualización. 
+ Contar una historia a partir de los datos.

## **Stack tecnológico**

+ `Python`: EDA + transformaciones. 
+ `SQL`: base de datos.
+ `Power BI` -preferentemente- o `Streamlit`: dashboard.
+ `GitHub`: con un README.md donde se elabore el informe.


## **Diccionario**

A fin de simplificar la presentación se describen las variables que se van a utilizar en el análisis y se citan las fuentes para mayor investigación.

#### Dataset: Airplane Crashes Dataset Since 1908- Historia de los accidentes aéreos civiles y militares en todo el mundo.

+ Fecha: fecha del accidente
+ Cantidad de fallecidos: cantidad total de muertes incluyendo pasajeros y tripulación.

Fuente original: https://www.kaggle.com/datasets/landfallmotto/airplane-crashes-dataset-since-1908

#### Dataset: Australian Fatal Road Accident 1989-2021 -Un conjunto de datos de accidentes de tráfico en todo el país (1989-2021)

+ Crash ID: identificación de accidente
+ State: estado
+ Year: año
+ Month: mes
+ Dayweek: día de ocurrencia del accidente
+ Crash Type: accidente simple/múltiple
+ Age: edad de la persona fallecida
+ Day of week: semana/fin de semana
+ Time of day: día/noche

Fuente original: https://www.kaggle.com/datasets/deepcontractor/australian-fatal-car-accident-data-19892021?select=Crash_Data.csv

