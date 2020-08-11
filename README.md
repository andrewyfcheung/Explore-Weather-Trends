# Explore-Weather-Trends
Udacity Data Analyst Degree - Project I

## Outline
1. To extract city list data with SQL query statement “SELECT * FROM city_list”
2. Shenzhen is the closest big city to where I live
3. To extract Shenzhen’s city level data with SQL statement “SELECT * FROM city_data WHERE city='Shenzhen'” and export the extracted results to CSV
4. To extract global data with SQL statement “SELECT * FROM global_data” and export the extracted results to CSV
5. For average temperature data in both CSV files, create a new column to calculate moving average temperature to make it easier to observe the trends when it be shown in Charts

![capture](https://github.com/andrewyfcheung/Explore-Weather-Trends/blob/master/Shenzhen%20data%20screenshot.PNG)<br>

![capture](https://github.com/andrewyfcheung/Explore-Weather-Trends/blob/master/Global%20data%20screenshot.PNG)<br>

6. Visualize the data using Excel

![capture](https://github.com/andrewyfcheung/Explore-Weather-Trends/blob/master/Global%20vs%20Shenzhen%207-year%20moving%20average%20temperature%20line%20graph.PNG)<br>

## Observations
1. Average global temperature is increasing over time, and so is Shenzhen’s temperature. Average global temperature increases from 7.96 in 1846 to 9.57 in 2013, whereas average Shenzhen temperature increases from 21.30 in 1846 to 22.02 in 2013.
2. In terms of level of increment, average global temperature increases at a faster rate over time as compared with Shenzhen. Based on 1), average global temperature is increasing at 20.2% from 1846 to 2013, whereas average Shenzhen temperature is increasing at 3.3% from 1846 to 2013.
3. Average global temperature is increasing steadily from 1846 to 2013, which could be partially explained by the industrial revolution of the western countries back in the 19th century. Average Shenzhen temperature remained stable from 1846 to 1940 and is increasing steadily since then. This could be partially explained by the recovery of China post WWII since the CCP’s reign.
4. Below formula is used to measure how strong a relationship between two variables:

![capture](https://github.com/andrewyfcheung/Explore-Weather-Trends/blob/master/Formula.PNG)<br>
X Values (Global temperature) 
Σ = 1483.3 Mean = 8.525 
Σ(X - Mx)2 = SSx = 38.183 

Y Values (Shenzhen temperature)
Σ = 3728.97 Mean = 21.431 
Σ(Y - My)2 = SSy = 45.486 

X and Y Combined 
N = 174 
Σ(X - Mx)(Y - My) = 28.346 

R Calculation 
r = Σ((X - My)(Y - Mx)) / √((SSx)(SSy)) 
r = 28.346 / √((38.183)(45.486)) = 0.6802
The correlation coefficient between global and Shenzhen temperature trends is 0.6802 which indicates strong positive relationship among them.

In conclusion, we can depict that the global temperature is increasing steadily from 1846 to 2013 and Shenzhen temperature is also demonstrating similar pattern but at a slower rate during the same period.
