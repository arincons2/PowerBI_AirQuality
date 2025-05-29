# PowerBI_project_Air_Quality
Power BI Project: Air quality analysis

## **Problem statement**

The cities of Manizales and Pereira in Colombia have seen a rising number of cars in recent years, which has significantly impacted air quality. This decline in air quality, in turn, adversely affects the health and quality of life of residents. To tackle this issue, data analytics can be employed to identify the relationship between air quality and key factors, such as weather conditions. 

## **Objective**

The objective is to provide detailed information on air quality in Manizales and Pereira, enabling informed decisions and a comprehensive understanding of the relationship between various factors, utilizing Power BI. This effort will specifically examine the dependency of PM10 levels on spatial and temporal variables, including city location, day of the week, month, and year.


## **Methodology**

Power BI is used for unveiling the relationship between PM10 levels and various factors such as the day of the week, month of the year, year, and air quality station, specifically for Manizales and Pereira. The data was obtained from the webpage http://sisaire.ideam.gov.co/ideam-sisaire-web/consultas.xhtml and downloaded as an Excel file. After opening this file in Excel, several new columns were created, including Year, Month, and Day of the Week. The Excel table was then imported into Power BI (Power BI Desktop), where various charts and analyses were conducted. A slicer was implemented for each report page, allowing users to select between the cities of Manizales and Pereira.
Specifically, a line chart was created to show the relationship between PM10 levels and the months of the year, displaying separate lines for the years 2022, 2023, and 2024. To achieve this, three sub-tables were generated using DAX formulas, one for each of the years 2022, 2023, and 2024.

### **Tools and techniques utilized:**

- charts: line chart, ribbon chart, bar chart, etc.
- Map
- filters and slicers
- error bands
- ‘key influencers’ tool
- DAX Formulas for Creating Sub-Tables. The DAX formulas were an alternative way for generating the PM10 line chart over time, with separate lines representing the years 2022, 2023, and 2024.
- Data information was updated by means of 'Transform Data'. 

## **Insights**

* Relationship between PM10 levels and the air quality station. The ranking of air quality stations of Manizales, in descending PM10 order is: Milan, Liceo, and Gobernación. This was mainly supported by the bar chart.
* Ranking of air quality stations according to the variation of PM10 along time in months. The ranking of air quality stations of Manizales, in descending PM10 order is: Milan, Liceo, and Gobernación. This was mainly supported by the ribbon chart.
* Relationship between PM10 Levels and the Year. In Manizales, the PM10 levels at the 'Milan' and 'Liceo' stations exhibit an increasing shape with plateau, while the shape of the curve of the 'Gobernacion' is  unclear.
* Relationship between PM10 levels and the 12 months of the year. In Manizales, PM10 values exhibit a peak in first semester and a peak in second semester. The exact month for these peaks depend on the air quality station. For Milan station, the peaks occur on February and September. 
* Relationship Between PM10 Levels and Days of the Week. In Manizales, PM10 levels are lower on Sundays, while they are higher on Fridays. 
* Variable with highest influence on air quality. In Manizales, the variable with the highest influence on high PM10 values is the station name, according to the ‘Key influencers’ tool.

## **Overall conclusions and project impact**
* The Power BI analysis provided insights into the relationship between PM10 levels and various factors, specifically for Manizales and Pereira. 
* This information helps make informed decisions to enhance residents' health and quality of life, such as transportation measures that reduce air pollution.

## **Recommendations**

* Protective measures for people must be taken for the station with the highest air pollution (Milan station), in the day with highest pollution (Friday) and the Months with highest pollution (April and September), for Manizales. Indeed, communication campaigns about health risks should be conducted during these time moments, especially for individuals with respiratory issues.
* Transportation measures should be taken on days and months with the highest air pollution, mainly for the stations with the highest air pollution (Miland and Liceo). For instance, fostering the use of public transportation and low-carbon-emission transport, as well as imposing license plate restrictions.


##  Interactive Power BI report:

https://app.powerbi.com/view?r=eyJrIjoiZWQxZjhiZjUtOGQ3Ny00Y2I4LTljOTktNDZlM2UzNjliYjkwIiwidCI6ImM3ZWNlM2Y5LTU4NjgtNDI3ZC1hNzdmLWU1MGJmMDY5MGEzNCIsImMiOjR9

<iframe title="PM10_MilanIcatGob" width="600" height="373.5" src="https://app.powerbi.com/view?r=eyJrIjoiZWQxZjhiZjUtOGQ3Ny00Y2I4LTljOTktNDZlM2UzNjliYjkwIiwidCI6ImM3ZWNlM2Y5LTU4NjgtNDI3ZC1hNzdmLWU1MGJmMDY5MGEzNCIsImMiOjR9" frameborder="0" allowFullScreen="true"></iframe>

### Sample of the Power BI report:
https://github.com/arincons2/PowerBI_AirQuality/blob/9bf39f77653e4f1ecb2f1d07ccb0ab1bc7e65b55/Pres1_PowerBI.pdf
