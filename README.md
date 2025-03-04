# PowerBI_AirQuality
Proyecto Power BI: análisis de calidad del aire (PM10) en Manizales y Pereira

## **Planteamiento del problema**

La ciudad de Manizales (Caldas, Colombia) ha venido presentando un aumento en la cantidad de vehículos, lo cual afecta significativamente la calidad del aire. Esto tiene impacto en la salud y calidad de vida de las personas. Se desconoce la dependencia de la calidad del aire (PM10) con respecto a variables espacio-temporales como: zona de la ciudad, día de la semana, mes del año, y año. 

## **Objetivo**

Generar información sobre la dependencia de la calidad del aire (PM10) de Manizales y Pereira con respecto a variables espacio-temporales, que permita tomar decisiones informadas y entender la relación entre las variables, mediante el uso de herramientas gráficas generadas a partir de datos originales. 

## **Herramientas usadas (habilidades)**

Herramientas usadas:
-fórmulas DAX (para creación de subtablas)
-filtros: filters, slicers 
-herramienta ‘key influencers’
-gráficas: line chart, line and clustered column chart, ribbon chart, bar chart.

## **Metodología**

Los datos fueron obtenidos de la página http://sisaire.ideam.gov.co/ideam-sisaire-web/consultas.xhtml, descargados en formato xls. Este archivo fue abierto en Excel, en donde se crearon nuevas columnas (Año, Mes de 1 a 12, día de la semana, etc). Se importó la tabla del archivo Excel hacia Power BI (Power BI desktop), y se realizaron las distintas gráficas. Con el fin de realizar una gráfica de línea con líneas de PM10 a lo largo del tiempo en meses, usando una línea distinta para cada uno de los años (2022, 2023, 2024), se crearon tres nuevas sub-tablas, una para cada línea. Para estas sub-tablas se usaron formulas DAX. Se usó un slicer en cada una de las páginas del reporte, y estos slicers permiten filtrar por ciudad (Manizales o Pereira).      

## **Visualizaciones y análisis (Conclusiones)**

* Dependencia de PM10 con respecto a los 7 días de la semana. Para Manizales, el día domingo y sábado hay menores valores de PM10, mientras el miércoles y viernes hay mayores valores.
* Dependencia de PM10 con respecto a los 12 meses del año. En Manizales, los meses marzo y septiembre son los meses con mayores valores de PM10.
* Dependencia de PM10 con respecto a la estación de calidad del aire. Para Manizales, en promedio, el PM10 es mayor en la Gobernación que en la universidad UCM y que en Palogrande. 
* Dependencia de PM10 con respecto a los años. Para Manizales, el PM10 en la estación UCM tiene una tendencia creciente a lo largo de los años, mientras que en las otras dos estaciones no hay una tendencia clara. 
* Ranking de las estaciones, con respecto a los 12 meses del año. Para Manizales, el ranking que ocupan las tres estaciones es muy cambiante. Sin embargo, de los meses marzo a junio, en la estación de la Gobernación se presentan mayores valores de PM10 (ocupa el primer lugar).  
*  Variable con mayor influencia en PM10. Para Manizales, la variable que tiene mayor influencia en valores altos de PM10 es día de la semana. Para Pereira, la variable con mayor influencia es el tiempo en meses. Esto se obtuvo usando la herramienta ‘key influencers’.

