# PyBer_Analysis

## Project Overview

Create a summary DataFrame of the ride-sharing data by city type. The city types are:
- Urban, 
- Suburban
- Rural

Then, using Pandas and Matplotlib, create a multiple-line graph that shows the total weekly fares for each city type.
Summarize how the data differs by city type and how those differences can be used by decision-makers at PyBer.


## Resources
- Data Source: city_data.csv, ride_data.csv


## Analysis and Results
### Analysis from Summary Dataframe
From the summary dataframe, we can infer that:
1. There is more ride-sharing that happens in cities in urban areas compared to Suburban and Rural
2. Similarly there are also most number of drivers in Urban areas, then in Suburban and least in Rural areas.
Which also displays disparity of total number of drivers between urban vs Suburban and Urban vs Rural, and Suburban vs Rural.

3. For a person using ride-sharing, it is least expensive in urban areas where avg fare per ride is $24.53 versus rural areas where it is $34.62.
4. With having more drivers in urban areas, the avg fare per driver is also only $0.67 versus in rural ($8.06) or 
suburban($2.26)
![Summary of Rides across different City Types](https://github.com/sag7221/PyBer_Analysis/blob/main/analysis/Summary_DataFrame.png?raw=true)


### Analysis from line graph
From the original data, i created a time series data for different city type with weekly fares and plotted a multiple line graph
Following are the observations from this graph:
1. On a weekly basis, Total fares for urban cities is always higher than Suburban and Rural
2. In the later part of February, total fares are high across all city types of Urban, Suburban and Rural.
3. Although you see highs and lows for both urban and suburban, rural areas, the total fares rural is more or less in the same range between (greater than 0 and <=500), more or less fares in rural areas seems consistent.
![Total Fare By City Type](https://github.com/sag7221/PyBer_Analysis/blob/main/analysis/Total_Fare_By_City_Type.png?raw=true)


## Recommendations
Based on the above observations i have the following recommendations:
1. Due to a huge disparity of total number of drivers between urban vs Suburban and Urban vs Rural, and Suburban vs Rural, one recommendation is to increase number of drivers in rural areas. This increases the total collection of fares, and also decreases the avg fare per driver attracting more people to use ride-sharing.
2. Similarly the number of drivers can be increased in Suburban areas too to bring down the avg. fare per driver.
3. Bring down the number of total drivers in Urban areas, this will increase the avg fare per ride which is currently only 67 cents but to see that the average fare per ride does not increase a lot.git 

