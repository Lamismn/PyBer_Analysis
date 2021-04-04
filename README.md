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

4. 


