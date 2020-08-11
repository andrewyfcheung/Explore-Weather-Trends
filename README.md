# Explore-Weather-Trends
Udacity Data Analyst Degree - Project I

## Overview
Outline
1. To extract city list data with SQL query statement “SELECT * FROM city_list”
2. Shenzhen is the closest big city to where I live
3. To extract Shenzhen’s city level data with SQL statement “SELECT * FROM city_data WHERE city='Shenzhen'” and export the extracted results to CSV
4. To extract global data with SQL statement “SELECT * FROM global_data” and export the extracted results to CSV
5. For average temperature data in both CSV files, create a new column to calculate moving average temperature to make it easier to observe the trends when it be shown in Charts

## What Software Do I need?
To complete this project, I required the following softwares:
- SQL
- Excel

## Extracting Data
To start I wrote an SQL query to retrieve all the temperature data from:
- Local Database (Shenzhen)
- Global Database

Upon retrieving the data, it was extracted on a CSV file for further evaluation.

## Data Selection & Manipulation
Once the data has been extracted on CSV, it was possible to further evaluate the data on Excel. To provide a more accurate and useful dataset for comparison a range of the common years only was chosen.

Moreover, due to fluctuations in yearly averages, the data was evaluated considering moving averages (7-years) to provide smoother results during data visualization. 

## Data Visualization
Once the dataset was ready, it was time to plug n play. The first chart shows a comparison between the global and local temperature set across the years.<br>

![capture](https://user-images.githubusercontent.com/43564654/46089107-dd90c700-c1be-11e8-9ecd-429f31039f3c.PNG)<br>

The second plot shows the global average temperature range across all the years to view a trend for the entire dataset.<br>

![capture2](https://user-images.githubusercontent.com/43564654/46089105-dcf83080-c1be-11e8-829d-e2f34ae21327.PNG)<br>

## Observations
- Shenzhen's weather has been warmer than the global average in the past couple hunder years.
- A significant rise in the yearly average temperature can be observed in Abu Dhabi in the past couple of decades.
- The yearly average temperature seems to be increasing abnormally on a global scale in the last 3-4 decades. 
