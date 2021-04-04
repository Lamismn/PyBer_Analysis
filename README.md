# PyBer_Analysis
## Overview
This Analysis uses data from a python based ride sharing application database to create some visual charts, using Jupyter notebook, Pandas libraries & Matplotlib, to show the relations between number of drivers, city types, & fares.
### Background
The analysis uses two csv files from the ride sharing application, showing the city data (city type, number of drivers) & the ride data (fare, and date & time). The files are available on the following link:
https://github.com/Lamismn/PyBer_Analysis/tree/main/Resources
### Purpose
The purpose of this analysis is to help the application team understand trends and relations to be able to improve access to ride sharing services & determine affordability in under-served neighborhoods, to do this, we study the following:

1. The relation between the average Fare, the total number of rides per city & the total number of drivers
2. The measures of central tendencies for each city type
3. The ride count data & the percentages of total fares, total number of drivers, & total number of rides for each city type
4. Create a summary dataframe showing the Total Rides,	Total Drivers,	Total Fares	Average, Fare per Ride	Average, & Fare per Driver for each city type
5. Separate & analyze the data from a specific time frame of interest & show the relation between teh total fare & the date for each city type
## Results
After analyzing the data, the following was concluded:

1. The type of city has a direct and strong effect on the number of drivers available, number of rides & ultimately the average fare

![Fig1](https://user-images.githubusercontent.com/79733383/113519825-b5873900-955c-11eb-9dd9-0fa41d14bd13.png)

As shown in the above figure, we can see that cities that fall under the Urban category have the highest number of rides, highest number of drivers & a the lowest fare average, whereas the cities that fall in the Rural category haeve the lowest number of rides, lowest number of drivers & highest fare average, and cities that are Suburban lie in the middle.
2. We can see that the dataset provided has only one outlier, in the urban category, where West Angela city has 39 rides

![Fig2](https://user-images.githubusercontent.com/79733383/113519930-90df9100-955d-11eb-9f85-7d680da3072b.png)

![Fig3](https://user-images.githubusercontent.com/79733383/113520035-4f9bb100-955e-11eb-8c31-86bd5719826d.png)

![Fig4](https://user-images.githubusercontent.com/79733383/113520039-56c2bf00-955e-11eb-941a-d0b140b8e240.png)


we can also see from the above figures that the ride counts for Urban cities vary from 12 to 39 with a mean of 24.5 rides per city, and that this mean goes down to 17.3 rides per city for Suburban cities & to 6.9 rides per city for Rural cities.

The above figures also show that the mean fare for Urban city trips is around 24.5$, this number goes up to around 30$ for Suburban cities & 34$ for Rural cities. And that the average number of drivers for Urban cities is 37, and that this number goes down to 14 for Suburban cities & just 4 for Rural cities.
3. The analysis also determined the percentages of total fare, total number of drivers & total number of rides for each city type, those results can be shown in the following charts:

![Fig5](https://user-images.githubusercontent.com/79733383/113520499-7f988380-9561-11eb-9957-9b31fec62be6.png)
![Fig6](https://user-images.githubusercontent.com/79733383/113520502-86bf9180-9561-11eb-90d6-759aa5e08374.png)
![Fig7](https://user-images.githubusercontent.com/79733383/113520511-8d4e0900-9561-11eb-8ec6-68afca4484fd.png)

As seen in the above charts, Urban cities represent the highest percentages in all three categories.

4. After sparating a specific period of interest & studying it (from 1.1.2019 to 4.29.2019), the final analysis resulted the following chart:

![Total Fare by city type](https://user-images.githubusercontent.com/79733383/113520616-47de0b80-9562-11eb-9fe1-dc20f2b10306.png)

The above chart shows that the total fare for Urban cities for this period is almost four times that of Rural cities & twice that of Suburban cities. 

It also shows that the total fare in Urban cities was more in March & April than in January & February, the same relation can be seen in Suburban cities, but is not present in Rural cities. Rural cities total fares seem to be almost constant with only one small spike in the first month of April.
## Summary
Based on the Analysis and charts shown, we can conclude that there is a clear negative correlation between the number of drivers available in the city & the average fare, we can also see a negative correlation between the average fare and the total number of rides, whereas the relation between the number of rides correlates positively to the number of drivers available. We can also see that even though the average fare for Rural cities is the highest, the percentage of total fares is the lowest.

Even though it's expected for number of drivers & number of rides to be highest in the Urban areas lowest in the Rural, the significant difference in average fare shows that there is also a shortage in drivers there and that there is a need for more drivers, which means that it help if the application tried recruiting more drivers in Rural areas.

The very low count rides in rural cities mean that the low number of drivers & increased fare mean that people are not inclined to use the application, or that they do not know about it, a way to solve that would be advertising more in those areas and offering discounts for new users to encourage them to join.

Finally, another way to solve both the low driver count and low number of rides for Rural cities would be for the application to offer more incentives for drivers in those areas to join as well as decrease their targeted margin to allow for a decreased average fare.

