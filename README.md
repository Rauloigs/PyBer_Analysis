# PyBer_Analysis

## 1. Overview of the analysis

After been done with the first data V Isualize needed which was the following...

1.  Determine the mean, median, and mode for the following:
- The total number of rides for each city type.
- The average fares for each city type.
- The total number of drivers for each city type.

*All of the data above was intended to plot the following **bubble chart**:

<img width="447" alt="Bubble_Chart" src="https://user-images.githubusercontent.com/84519822/151428624-af848be1-2bb6-4d8a-aa9d-d9567b5e538e.png">


2. Create box-and-whisker plots that visualize each of the following to determine if there are any outliers:
- The number of rides for each city type.
- The fares for each city type.
- The number of drivers for each city type.

3. Create a pie chart that visualizes each of the following data for each city type:
- The percent of total fares.
- The percent of total rides.
- The percent of total drivers.

... V. Isualize gave the task to create a **Summary DataFrame of the ride-sharing data by city type** & a **Multiple-line graph that shows the total weekly fares for each city type**. So, in the next point we will review the Results of:

1. Ride-sharing summary DataFrame by city type
2. A multiple-line chart of total fares for each city type

## 2. Results

**Important Note:** *I over checked the snippet to obtain the values for **total drivers**, because they didn´t match with the number of drivers shown in the Challenge Description: 78, 490, 2,405 for Rural, Suburban and Urban respectively. My conclusion is that I wrote the code right, and got the right values but I might be wrong. Hope not, fingers crossed.*

In the follwing image you can see the **Ride Sharing Summary DataFrame by city type**:

<img width="565" alt="Pyber_Summary_DF" src="https://user-images.githubusercontent.com/84519822/151425686-a515b3cd-52ce-4988-8427-79f7bd51e3b3.png">

For each variable *Total Rides*, *Total Drivers* and *Total Fares we can see that, the "less urbanized" a city is the less rides, drivers and fares, which is a behavior that we all naturally might expect. 

Nevertheless, if we observed the average fares per *ride* and *driver* columns (last two columns from left to right), we realized we have the opposite effect. The most urbanized the city type, the less fare per ride and driver. For example the total fares for Urban City are 25 times larger than the number of rides, meanwhile the total fare for Rural Cities is 35 times greater than the number of rides which implies there is a higher price/ ride in rural cities than in urban cities. This could be obviously explained with the supply and demand law, BUT! it could be also attributed to longer distance rides (more expensive).

We could say suburban cities have a more balanced average fare per ride and driver, and we can detect that the average fare per driver in Urban cities is a red light flag. V. Isualize could expose this topic to her experts in the business and talk about why is it like this. 

For the first third of 2019 year this are the fares per city:

![Pyber_fare_summary](https://user-images.githubusercontent.com/84519822/151425845-ed9c1b7d-e7f5-4f75-aec1-a1ee05f68f15.png)

Same as in the summary we can observe the fares distribution among the cities as "normal". There are some picks in the plot, but I wouldn´t say they are remarkably important enough to put special attention to them. 

## 3. Summary:

As a conclusion it is relevant to (1) dig a bit in how is Pyber determining the prices for the rides, because this might be the reason of an incredibly low performance in average fares per drivers. Also, for me one of the most important aspects is to (2) evaluate the number of drivers per total rides, because apparently there could be more drivers than needed. (3) Look over where are the locations (roads) where dirvers drive, specially in rural and suburban, because there might be a greater opportunity for rides and no need to fire drivers. 

Rauls Pyber Challenge Analysis: https://github.com/Rauloigs/PyBer_Analysis  
