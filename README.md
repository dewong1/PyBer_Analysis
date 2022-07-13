# PyBer_Analysis
Performing analysis on ride-sharing and total weekly fares by city type 


## Overview of Project
PyBer is a ride-sharing app company valued at $2.3 billion. Using Python graphing and plotting library *Matplotlib*, we analyze all the rideshare data from January to early May of 2019 and create a compelling visualization to help improve access to ride-sharing services and determine affordability for underserved neighborhoods. The purpose of this project is to use *Python* to create a summary DataFrame of the ride-sharing data by city type, and then using *Pandas* and *Matplotlib* to create a multiple-line graph that shows the total weekly fares for each city type (urban, suburban, rural).


## Results

Below is a screenshot of the Summary DataFrame:

<img width="609" alt="Summary DataFrame" src="https://user-images.githubusercontent.com/107021231/178688039-213e6ca3-fefb-4571-898c-4bbed3fc9ac1.png">


### Differences in ride-sharing data among different city types

According to the ride-sharing data gathered (*Total Rides*, *Total Drivers*, *Total Fares*, *Average Fare per Ride*, and *Average Fare per Driver*) by city type (*Rural*, *Suburban*, and *Urban*), Urban cities have most *Total Rides*, *Total Drivers*, highest *Total Fares*, but the lowest *Average Fare per Ride*, and *Average Fare per Driver*. And quite the opposite, Rural (city type) have the least *Total Rides*, *Total Drivers*, lowest *Total Fares*, but the highest *Average Fare per Ride*, and *Average Fare per Driver*. This may be the result of the relationship between supply and demand. In rural places, the population is less compared to urban cities, and therefore, the supply is probably low resulting in higher prices. Suburban city results were in between Urban and Rural (not the highest or the lowest but in the middle). 

![PyBer_fare_summary](https://user-images.githubusercontent.com/107021231/178688053-b8e6bf6f-eff0-4764-8431-d050ecdd077d.png)

For the total weekly fares for each city type, all cities (rural, suburban, urban) share a peak/rise sometime around late February, and then a dip/drop as March approaches. From the month of March to April, Urban cities' total fare amount drastically fluctuates; Suburban cities' total fare amount has a steady rise till mid-March and then a steady drop as April approaches; and Rural area's total fare amount fluctuates as well (but not as drastic as urban's)

## Summary

### Three recommendations for addressing any disparities among city types 

During the month of April, unlike Rural and Urban cities, Suburban cities' total fare significantly increases after a small dip. The company can conduct some research to find the reason(s) behind the significant increases, especially because the total fare decreases for the other city types. From the results of their research findings, they can plan accordingly. 

Based off the data, we also see the correlation between *Avergae Fare per Ride* and *Average Fare per Driver* is higher when there are less drivers (rural). The company can influence the ride-share prices by changing (e.g. decreasing or increasing) the number of drivers during a certain time. 

In addition, the *Average Fare per Driver* is significantly higher in rural areas ($55.49) than urban cities ($16.57). This may indiciate that the number of drivers in rural areas are much lower. The company may want to allocate more drivers to rural areas.   

