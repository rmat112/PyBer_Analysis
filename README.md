# PyBer_Analysis
## Overview of the Analysis
PyBer is a ride sharing app company. All the rideshare data from January to early May of 2019 is available for analysis, which includes the 'city data' and the 'ride data'. The city data provides information like city names, driver counts and type of cities (Urban, Suburban, or Rural). The ride data has information about each ride like, the city of a particular ride, the date of ride, the fare, and the ride ID. 

The purpose of this analysis is to create a summary dataframe of the ride sharing data by city type by using Python. Then, using Pandas and matplotlib, to create a multiple-line graph that shows the total weekly fares for each city type. And finally, prepare a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

Here is a link to the Jupyer notebook with my analysis: [PyBer Challenge](https://github.com/rmat112/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb)

## Results

####    PyBer Summary DataFrame
![pyber_summary](https://github.com/rmat112/PyBer_Analysis/blob/main/analysis/pyber_summary.png)

* As seen in the summary screenshot above, the total number of rides taken in urban cities are 13 times more than in rural cities and in suburban cities 5 times more than the rural cities.
* Similarly, total drivers in urban cities are 30 times that in rural cities and in suburban cities it is 6 times that of rural cities. 
* Moreover, the total fare in urban cities is 9 times that of rural cities and in suburban cities it is 4 times that of rural cities. 
* A glaring fact that this summary points to is that the total number of rides in urban cities is less than the total number of drivers. This means that there are some drivers who did not get a single ride from January to May of 2019.
* When comparing average fare pre ride, the rural cities are 1.5 times that of urban cities and 1.1 times more than suburban cities as well. 
* Average fare per driver is the highest in rural cities as well @ 3.5 times that of urban cities and 1.3 times that of suburban cities.
* As illustrated in the plot below, urban cities have the total highest fares and rural cities have the lowest.
#### Pyber Summary Multi-Line Plot
![Pyber_fare_summary](https://github.com/rmat112/PyBer_Analysis/blob/main/analysis/Pyber_fare_summary.png)

## Summary

Based on this analysis it is evident that there is significant disparity in urban, suburban, and rural areas. I would recommend the following to PyBer:

* The average fare per ride is quite high in rural areas, Which could mean that either each trip in rural cities is much longer compared to urban areas, or that demand is actually high and drivers are less.
* Total number of rides and total number of drivers in rural and suburban areas are sgnificantly lower than that in urban areas.
* Increasing the number of drivers in rural and suburban areas will help in fulfilling the demand in these areas.
* There are too many drivers in urban cities and if reassigning them to rural or urban areas is a possibility, this would increase the overall revenue for the company.
