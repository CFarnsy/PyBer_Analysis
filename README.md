# PyBer Analysis

## Overview of the Analysis:

The purpose of the analysis is to create a summary dataframe showing the ride-sharing data by city type (Urban, Suburban, and Rural).  We will use the groupby() function and apply the count() and sum() methods to find the number of rides, drivers, and fares per city type.  Then we will calculate the average fare per ride and driver, as well as the total rides, drivers, and fares by city type.  

Finally, we will create a new dataframe and reformat the columns to show the total weekly fares by city type from January through April of 2019. 


## Results: 

There is a description of the differences in ride-sharing data among the different city types.  Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. 

-	Urban cities have the largest number of rides, drivers, and fares.

-	Rural cities have the least number of rides, drivers, and fares.
  
-	There are approximately 3x the number of rides, 5x the number of drivers, and about 2x the total fares in urban cities vs. suburban cities.

-	There are about 5x the number of rides, 6x the number of drivers,
and almost 4.5x the total fares in suburban cities vs. rural cities.

-	Rural cities have the highest average fare per ride and driver. 

-	Urban cities have the lowest average fare per ride and driver. 

This graph provides additional information related to the types of cities:
![city_type_details](https://user-images.githubusercontent.com/99366022/160998000-3e86a34c-fceb-49d3-9671-ab10349d19a1.png)

This graph shows the total fares per city type from January through April of 2019:
![PyBer_fare_summary](https://user-images.githubusercontent.com/99366022/160998014-7ec21b7f-7322-4480-8012-501d92242c4a.png)

## Summary:

There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types

After reviewing the data, the significant difference between the urban and rural totals makes sense if rural customers are using the service less often due to a higher cost related to a longer trip distance.  It also makes sense why the number of drivers is higher but the average fare per ride and driver are lower in urban cities.  Customers are using the service more often but have shorter trip distances.  I would like to propose the following recommendations:
1.	Expand the timeframe of the data being analyzed to a two-to-five-year period.  This will help better identify trends and see a more complete picture.
2.	Add demographic information specific to the cities, population, and the customers.  This can help better identify the target audience as well as any adjustments that should be made. 
3.	Build in a minimum cost per trip for urban cities.  This could help off-set some of the expense of short trips and could result in gains based on the frequency of the trips. 

I believe implementing these three recommendations will provide additional information that can be used for strategic planning and business growth.

 
