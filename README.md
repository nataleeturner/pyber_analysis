# pyber_analysis

## Overview
The purpose of this exercise is to analyze the differences in PyBer ride share data for 3 different city types – Urban, Suburban, and Rural. With these analyses, I will make some recommendations to the CEO.

## Results

### Summary Data Frame
Referencing the Data Frame below, the first notable difference between the three city types is the volume of rides and drivers in Urban cities. There was ~62% more rides taken in Urban cities than in Suburban cities, and ~92% more rides taken in Urban cities vs Rural cities. This is to be expected, since Urban cities have a higher population than Suburban cities and Suburban cities have a higher population than Rural cities. Subsequently, the total fares in Urban cities are higher than in Suburban cities and Rural cities.

Another notable difference between the three city types is that the average fare per ride is fairly close between the three, while the average fare per driver is quite different. This is because the total drivers to total rides ratio is much higher in Urban cities than in the other two (1.48 drivers per ride in Urban cities compared to 0.78 and 0.62 drivers per ride in Suburban and Rural cities). 

<img width="599" alt="pyber_summary" src="https://user-images.githubusercontent.com/88349443/134783888-f572a0d6-54b3-4b51-982e-d36075e617e7.png">

### Total Fare by City Type Line Chart
The summary chart below shows the total fare per city type over the course of the first 5 months of 2019. Urban and Suburban cities start off the year on the low end and increase over the first month. In Urban cities the fare continues to increase in February and then fluctuates between $2,000 and $2,500 per week through May. Suburban city fares decrease in early February and then spike just before March starts. Over the next couple of months, the fares go back down and then end May with an increase. Rural city fares have minor fluctuations between 0-$500 per week throughout the first 5 months.

Overall, the total fare per week in Urban cities are the highest, Suburban second, and Rural the lowest. Interestingly, they all have a spike in the week before March, so it would be good to look into the reasoning behind this.

![PyBer_fare_summary](https://user-images.githubusercontent.com/88349443/134783894-bd6bdd2e-ecc5-48b9-b105-c8032d0c4018.png)

## Summary
First, I would recommend that the CEO reduce the total number of drivers in Urban cities to closer match the demand of rides. Ideally, there would be a 1:1 ratio of total rides to total drivers. This would make it so that each driver would earn more for each ride. Similarly, I would recommend that the number of drivers be increased in Rural and Suburban cities to make the total rides to total drivers ratio closer to 1. While this change may not be as well received by the drivers in these city types, since at first it would lower the average fare per driver, it would likely make customers happier by not having to pay as much and having more ride options. Making these two changes would cause the average fare per driver between the city types to eventually even out.

Additionally, I would recommend that the rate be adjusted between the city types to even out the average fare per ride. Before doing this, I would recommend that the CEO do a study to determine the optimal rate that would allow PyBer to charge as much as they can while keeping customers happy and not overcharging. It may be that Rural rates will need to be lowered or that Urban rates will need to be increased, but this would help reduce the discrepancies between the three city types.

Lastly, I would recommend that the CEO create more charts similar to the 2019 fare chart, but with multiple years of data for one city type on each chart. This would allow for the identifications of patterns throughout the year. When there are major increases or decreases at certain times of the year, different things can be done to optimize revenue during these times. Some ideas would be to incentivize low times of the year to increase rides or to charge more during busy times, since the demand will outpace the supply of drivers if they are kept constant.
