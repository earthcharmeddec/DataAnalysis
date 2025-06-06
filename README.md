# DataAnalysis
My different Data Analysis projects

![image](https://github.com/user-attachments/assets/7b63127c-1ec3-42e1-a901-0163029a7718)

The data was downloaded as a csv file with a semicolon delineator from this site: https://www.statistik-bw.de/BevoelkGebiet/Alter/010352xx.tab?R=GS212000

Data Transformation:
1. Extra rows from the top and bottom was removed and the Columns in BI were manually added

2. The graph looked stranged and only some data was in the 1000s of range. Realized that the German data uses a decimal point to separate thousands and a comma for decimal points.
Shown in the picture below is the setting that was changed - the locale for the decimal number. The columns could have been set as a whole number with Germany locale as well.

![image](https://github.com/user-attachments/assets/31c0a987-24d5-4fff-ba18-09ea8524dabb)
This setting however didn't change much in the report or the table.

This was not enough and I had to change the regional setting for the numbers to show correctly.

3. Next problems was the graph was not displaying the ages in chronological age order.

     For this, I had to click on the three dots on the visual itself to sort the x axis by the Column that I wanted (Age)

The conclusion I obtain from this data is that there are more citizen in Karlsruhe comparedd to foreigners. I need to Transform the data further in order to obtain any further use of the data. 
It would be interesting to compare this data to those from cities such as Frankfurt, Munich, and Berlin.


