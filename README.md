# PowerBI_project_Air_Quality
Power BI Project: Air quality analysis

## **Problem statement**

The cities of Manizales and Pereira in Colombia have seen a rising number of cars in recent years, which has significantly impacted air quality. This decline in air quality, in turn, adversely affects the health and quality of life of residents. To tackle this issue, data analytics can be employed to identify the relationship between air quality and key factors, such as weather conditions. 

## **Objective**

The objective is to provide detailed information on air quality in Manizales and Pereira, enabling informed decisions and a comprehensive understanding of the relationship between various factors, utilizing Power BI. This effort will specifically examine the dependency of PM10 levels on spatial and temporal variables, including city location, day of the week, month, and year.

## **Tools and techniques utilized**

- DAX Formulas for Creating Sub-Tables
- filters and slicers 
- ‘key influencers’ tool
- charts: line chart, line and clustered column chart, ribbon chart, bar chart, etc.


## **Methodology**

The data was obtained from the webpage http://sisaire.ideam.gov.co/ideam-sisaire-web/consultas.xhtml and downloaded as an Excel file. After opening this file in Excel, several new columns were created, including Year, Month, and Day of the Week. The Excel table was then imported into Power BI (Power BI Desktop), where various charts and analyses were conducted. A slicer was implemented for each report page, allowing users to select between the cities of Manizales and Pereira.
Specifically, a line chart was created to show the relationship between PM10 levels and the months of the year, displaying separate lines for the years 2022, 2023, and 2024. To achieve this, three sub-tables were generated using DAX formulas, one for each of the years 2022, 2023, and 2024.


## **Visualizations and insights**

* Relationship Between PM10 Levels and Days of the Week. In Manizales, PM10 levels tend to be lower on Saturdays and Sundays, while they are higher on Wednesdays and Fridays. 
* Relationship between PM10 levels and the months of the year. In Manizales, PM10 values are higher in March and September.
* Relationship between PM10 levels and the air quality station. In Manizales, the PM10 levels at the 'Gobernacion' station are, on average, higher than those at 'UCM' and 'Palogrande'. 
* Relationship between PM10 Levels and the Year. In Manizales, the PM10 levels at the 'UCM' station have shown an increasing trend over the years, while the other two stations do not display a clear trend. 
* Ranking of air quality stations throughout the year, broken down by month. For Manizales, the ranking of the stations is overly fluctuating. However, the PM10 in ‘Gobernacion’ station is the highest during the period from March to June, thus occupying the first rank during this time.   
* ‘key influencers’ tool. In Manizales, the highest influence on elevated PM10 levels is the 'day of the week' variable. In Pereira, the variable with the most significant impact on PM10 is the month.  

## **Tools/techniques utilized and achievements**

* The Power BI analysis provided insights into the relationship between PM10 levels and various factors such as the day of the week, month of the year, year, and air quality station, specifically for Manizales and Pereira. 
* The ribbon chart allowed for the comparison of PM10 rankings at different air quality stations over time, specifically for Manizales and Pereira.
* The 'key influencers' tool helped identify the variable most influencing high PM10 values.
* The DAX formulas were crucial for generating the PM10 line chart over time, with separate lines representing the years 2022, 2023, and 2024.

## **Overall conclusions and project impact**
* The Power BI analysis provided insights into the relationship between PM10 levels and various factors, specifically for Manizales and Pereira. 
* This information helps make informed decisions to enhance residents' health and quality of life, such as transportation measures that reduce air pollution.

## **Recommendations**

* Protective measures for people must be taken on days and months with the highest air pollution, namely Wednesday and Friday, as well as in March and September, for Manizales. For instance, communication campaigns about health risks should be conducted during these periods, especially for individuals with respiratory issues.
* Transportation measures should be taken on days and months with the highest air pollution. For instance, fostering the use of public transportation and low-carbon-emission transport, as well as imposing license plate restrictions.


##  Interactive Power BI report:
https://app.powerbi.com/view?r=eyJrIjoiZjI2ZmU2YzEtZWQ5Yy00M2Q2LTllNTctMGU1YTljZjc1YmQ1IiwidCI6ImM3ZWNlM2Y5LTU4NjgtNDI3ZC1hNzdmLWU1MGJmMDY5MGEzNCIsImMiOjR9

https://app.powerbi.com/links/zl-65-prg9?ctid=c7ece3f9-5868-427d-a77f-e50bf0690a34&pbi_source=linkShare

