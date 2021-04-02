# PyBer_Analysis

## Overview 
This analysis looks at the ridesharing data by city type and combines the data to look at weekly fares from January to April 2019. A visualization of the data available for year 2019 is below: 

![](https://github.com/madihajaved/PyBer_Analysis/blob/main/analysis/Fig1.png)

## Resources 
The data sources are stored in the resources folder and include city_data.csv and ride_data.csv

## Results 
The results show a few key trends in the ride-sharing data among the different city types. These are:

* Total rides: Most of the rides are in the urban cities (1,625 out of the total rides) while rural had the least as 125. 

![](https://github.com/madihajaved/PyBer_Analysis/blob/main/analysis/Fig6.png)

* Total drivers: Not surprisingly, most of the drivers are in the urban cities vs suburban or rural cities as seen in the pie chart below. This should be due to higher population and the demand for rides in these cities. 

![](https://github.com/madihajaved/PyBer_Analysis/blob/main/analysis/Fig7.png)

* Total fares: The amount of fares collected from urban cities is the highest close to $40,000 compared to rural which is almost only 10% of the urban revenue at close to $4,000.
* Average fare per ride: Average fare per ride is an interesting data point. While the number of rides and total fare have been highest for urban cities, it is actually rides in the rural cities which have the highest average fare per ride. This might likely be due to longer distances travelled given in rural cities, places might be farther away. 
* Average fare per driver: A similar trend is seen for average fare per driver. From Pyber's perspective, a driver earns the most in rural areas while the revenue for a driver in urban area is the least at $16.57. 
* Total fare by city type: However, it is important to keep in context the total fare by city type. Despite the highest average fares in rural cities, the total fare in rural cities remain the lowest given lower scale (i.e. less number of overall rides). 

## Summary 
![](https://github.com/madihajaved/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

The above chart summarizes the weekly trends for fares from Jan to April 2019. It can be seen that: 
* In April, total fares are highest in rural cities. It might be worth exploring if this trend is the same over years and ensuring there are more drivers in rural cities during that time to earn more revenues. 
* In suburban cities, fares dip in Jan and mid-April, again if this trend is observed over various years it might be helpful to reallocate drivers. In Jan, rural cities fares are up which is where more drivers can be allocated. 
* Urban cities generate the highest amount of revenues but have the lowest revenue per ride. This needs to be balanced with opportunities in rural and suburban cities. One area where the company can conduct further analysis is whether the company makes more profit if it identifies a group of flexible drivers who can easily be moved around as and when needed by city type.  

