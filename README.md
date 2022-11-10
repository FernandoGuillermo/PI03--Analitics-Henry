# PI03--Analytics--Henry

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
+ `Power BI`: dashboard.



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

## **Desarrollo**

La pregunta es: cómo relacionamos las muertes por accidentes aéreos y muertes por accidentes de tránsito en este contexto de investigación?
Vamos a resaltar de forma simple en esta investigación, las causas por las cuales fueron disminuendo las muertes por accidente aéreo los últimos 30 años y las vamos a comparar en el mismo sentido con las muertes por accidente de tránsito en Australia.
Entonces, ¿cuáles son las causas de disminución de muertes en accidentes aéreos los últmos 30 años?. Se dice el avíon es uno de los transportes más seguros, ¿a qué se debe?:

“el año 2017 hasta 2021, de la Asociación de Transporte Aéreo Internacional (en inglés IATA), un accidente de avión se produce cada, aproximadamente, 2.27 millones de viajes, equivalente a 0.44 por ciento”
[¿Por qué el avión es el transporte más seguro?](https://listindiario.com/la-republica/2022/09/25/740351/por-que-el-avion-es-el-transporte-mas-seguro "¿Por qué el avión es el transporte más seguro?")

Entre las causas de disminución de accidentes aereos:
-avance tecnológico.
-cuidado y calidad de los aviones.
-sistemas avanzados de protección: radares, control de tráfico, sistemas de alerta.
-pilotos altamente calificados.


### Dato curioso 1:
“ El 27 de marzo de 1977 ocurrió el peor accidente aéreo de la historia.
Dos aviones Boeing 747, de Panam Airways y KLM, chocaron en la pista de despegue del aeropuerto Los Rodeos, en Tenerife,
Islas Canarias, España, y dejaron 583 muertos”

[583 muertos y dos Boeing 747 destruidos](https://www.bbc.com/mundo/noticias-39402012 "583 muertos y dos Boeing 747 destruidos")

[![Accidente en Tenerife](https://ichef.bbci.co.uk/news/800/cpsprodpb/0A02/production/_95326520_gettyimages-3259518.jpg.webp "Accidente en Tenerife")] 
"Accidente en Tenerife"

### Dato curioso 2:

“Así es Graham, el “superhumano mutante” creado por el gobierno de Australia para alertar sobre los accidentes de tránsito
La creación es un reflejo de cómo debería evolucionar el ser humano para tolerar en su cuerpo los impactos de un choque”
[“superhumano mutante](https://www.infobae.com/america/mundo/2022/02/16/asi-es-graham-el-superhumano-mutante-creado-por-el-gobierno-de-australia-para-alertar-sobre-los-accidentes-de-transito/ "“superhumano mutante")”

[![](https://www.infobae.com/new-resizer/am6G8HYjKjaJOCDoD6Hzk4ANbDc=/992x606/filters:format(webp):quality(85)/cloudfront-us-east-1.images.arcpublishing.com/infobae/MMVKHN4EV5BNJA6PHQNU5EUMQ4.jpeg)](https://www.infobae.com/new-resizer/am6G8HYjKjaJOCDoD6Hzk4ANbDc=/992x606/filters:format(webp):quality(85)/cloudfront-us-east-1.images.arcpublishing.com/infobae/MMVKHN4EV5BNJA6PHQNU5EUMQ4.jpeg)


## Conclusión
En principio, de forma intuitiva en dirección hacía una posible idea, se extrajeron los datos, se transformaron, y luego fueron ingestados utilizando el stack tecnológico. A continuación, se realizó un acercamiento a los datos ya transformados mediante una herramienta de visualización, generando relaciones con el objetivo de obtener  una idea simple y clara. Finalmente se contó una historia a partir de los datos.

















