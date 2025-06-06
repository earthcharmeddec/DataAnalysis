# DataAnalysis of the 2022 Karlsruhe Consensus

Chart to show the different percentage of the population by age (V.1)
![image](https://github.com/user-attachments/assets/7b63127c-1ec3-42e1-a901-0163029a7718)

Comparing the Population by age and finding the ration of foreigners to citizens is similiar for Male and Female population (V.2)
![image](https://github.com/user-attachments/assets/1b46f78b-638c-447b-b7ea-1a9f01b8ad37)

The data was downloaded as a csv file with a semicolon delineator from this site: https://www.statistik-bw.de/BevoelkGebiet/Alter/010352xx.tab?R=GS212000

**Data Transformation:**

1. Extra rows from the top and bottom was removed and the Columns in BI were manually added

2. The graph looked stranged and only some data was in the 1000s of range. Realized that the German data uses a decimal point to separate thousands and a comma for decimal points.
Shown in the picture below is the setting that was changed - the locale for the decimal number. The columns could have been set as a whole number with Germany locale as well.

     ![image](https://github.com/user-attachments/assets/31c0a987-24d5-4fff-ba18-09ea8524dabb)

This setting however didn't change much in the report or the table and the regional setting of the porject needed to be changed.

     ![image](https://github.com/user-attachments/assets/3347fb7d-8452-499b-a88c-db28412eb420)

3. Next problems was the graph was not displaying the ages in chronological age order.

     For this, I had to click on the three dots on the visual itself to sort the x axis by the Column that I wanted (Age)
4. The data was also manually filtered to remove the total population row from display.
**Conclusion:**

The conclusion I obtain from this data is that there are more citizen in Karlsruhe comparedd to foreigners. I need to Transform the data further in order to obtain any further use of the data. 
It would be interesting to compare this data to those from cities such as Frankfurt, Munich, and Berlin. I created the V.2 visual to help me find out if the same ratio of  males and females in Karlsruhe are foreigners. Even though it seems the foreigner males and females are in the same ratio, the visual needs further configuration to be able to confirm this hypothesis. 
