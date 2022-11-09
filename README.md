# PyBer Analysis

## Overview
The purpose of this analysis is to compare the distribution of PyBer drivers, rides, and fares among the different city types encapsulated by this study: Urban, Suburban, and Rural. The analysis calculates and considers the count of drivers, rides, and fares in each city type and the proportion of fares-per-ride and fares-per-driver that have been collected in each city type. This data is visualized by a data frame summarizing all of the data and a line chart displaying total fares by city type. 

## Results
### Comparing data by city type
##### The below data frame summarizes all relevant data by city type

<img width="602" alt="PyBer_Summary_df" src="https://user-images.githubusercontent.com/114126935/200733098-f6b576ac-35ab-45c3-a52b-ad279d665a47.png">

#### Total Rides
The most rides are in urban cities, followed by suburban cities, and then by rural cities. Five hundred more rides were given in suburban cities than in rural cities, and double that jump, one thousand, more rides were given in urban cities than in suburban cities. 

#### Total drivers
As seen in the above data frame, there are only 78 drivers in rural cities. Approximately 400 more drivers work in suburban cities (490 total). The jump in total drivers in urban cities is massive, with nearly 2,000 more drivers than in suburban cities. This is important because urban cities are the only group that has more drivers than rides, suggesting that some drivers are totally inactive. 

#### Total fares
As may be expected, fares are distributed as total drivers and total rides are. Urban cities have collected the most fares, followed by suburban cities, with rural cities collecting the least total fares.

The below line chart samples total fares collected in urban (yellow), suburban (red), and rural (blue) cities for the first four months of 2019. It demonstrates that the distribution in fare collection is roughly consistent. Although the lines converge and diverge, they never cross. Urban cities always collect more fares than do suburban cities, which always collect more fares than rural cities (for January - April 2019). Also worth noting, is a simultaneous spike in all city types during third week of February.

![Pyber_fare_summary](https://user-images.githubusercontent.com/114126935/200733165-9817c58c-f700-4412-8b7f-c4444bc0a11a.png)

#### Average Fare per Ride
Rural rides collect the highest fare per ride. They are followed by suburban and then by urban cities. This may be attributable to distances. Urban areas being most densely populated and rural areas being least densely populated, one may reasonably surmise that rural passengers have farther to travel than do their suburban and urban counterparts, thereby incurring higher fares per ride.  

#### Average Fare per Driver
These follow the same pattern as average fares per ride. On average, rural drivers collect the most fares per driver. Urban drivers have the lowest fare-to-driver proportion, and suburban drivers are in the middle. This makes sense because as the driver count increases, the proportion of fares per driver should decrease. High volumes of drivers reduce the per-driver share of total fares. 

## Summary 
1. Drivers should be diverted from urban cities to rural cities. Urban cities have many more drivers than rides that were actually given. As mentioned above, this suggests the presence of completely inactive drivers and wasted resources. These drivers could be serving possibly underserved rural areas, where higher per-ride fares can be collected. 

2. Conduct a study to determine demand in rural cities. We must determine where inactive urban drivers are most needed and understand how to deploy advertising funds to ensure that people are aware of the new PyBer drivers available in their areas. 

3. Despite the low Average Fare per Ride and Average Fare per Driver values in urban cities, the amount of fares collected from urban cities accounts for nearly two thirds of all fares collected from all the cities. This makes urban cities the most important to PyBer’s business and earnings. As a result, commensurate resources should be spent understanding and serving issues and customers in urban cities to ensure that PyBer can maintain its chief fare-producing regions. 
