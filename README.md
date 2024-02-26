# Power-Bi---UK-Country-Specific-Foreign-Aid-Spending
This Power Bi project aims to show how foreign aid is spent on countries around the world for 2022. This project encompasses data collection, cleaning, manipulation and visualisation in a clean interactive dashboard. Extensive Analysis Expressions (DAX) was used to make the user interface function properly and with the correct figures.

# Viewing the dashboard
(1) Download the 'Friday Power Bi' file

(2) Run Power Bi and open the file

# The Source of the Data
Two data sources were used with one being table C7 from [the total country specific aid allocation](https://www.gov.uk/government/statistics/statistics-on-international-development-final-uk-aid-spend-2022) from the government website and the other is [country information](https://www.kaggle.com/datasets/nelgiriyewithana/countries-of-the-world-2023/data) from Kaggle.

The total country specific aid allocation contains 128 rows each representing a country or a region with the amount of aid allocated to each. 

The country information dataset has 195 rows each representing a country and 35 columns which represent a statistic about the country like population, unemployment rate and CO2 emissions for example.

# Cleaning the Data
Both datasets were cleaned in the Power Query Editor, removing junk data on the top and bottom of the data to fix formatting, renaming columns and changing data types to name a few.

A new table was created using a query where a left join was performed to the total country specific aid allocation with the country information. 

This table was called ‘Foreign Aid Data with Country Factsheet’ and each country that received aid also had statistics for it as well.

Only 12 of the 35 columns were kept from the country information for the new table

# The Dashboard

Screenshot below shows the dashboard. On the lefthand column, you can see the total aid dispersed, the number of countries and regions and the list of countries you can pick and sort by the amount of aid recieved.

On the middle column, you can see the amount of money recieved in 2022 and the map below it shows the country or region. You can also use it to search as well.

On the left column, the pie chart shows the share of total aid for the selected country with the total amount of aid dispersed and below it is the statistics for the country.

![image](https://github.com/sr781/Power-Bi---UK-Country-Specific-Foreign-Aid-Spending/assets/96390217/ceb39728-378d-47e1-85ad-9ab1611fb217)



