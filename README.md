# PyBer Analysis

## Overview of Project

The purpose of this data project is to analyze various factors impacting performance of PyBer ride sharing service.  In an initial round of analysis, we looked at a variety of factors to gain a baseline understanding of what influences revenue and volume.  In a further analysis, the data were analyzed to understand how the city type (urban, suburban, or rural) impacts capacity and revenue.  Data were examined from the period of January 1, 2019 through April 29, 2019.

With greater insight into differences between the city types, decision makers will be able to make more well-informed future plans that align with the vision of PyBer.

## City Type Results

Several of the key metrics analyzed differ greatly between the various city types.

There are 120 total cities that were analyzed.  Of these, 66 (55%) were urban, while 36 (30%) were suburban, and 18 (15%) were rural.  

![Summary_DataFrame](https://user-images.githubusercontent.com/82730954/120115633-307a6380-c14a-11eb-908b-b701efc9bd98.PNG)

With this in mind, as expected, there were many more urban rides in the data.  However, the magnitude of the discrepancy cannot be explained simply by being in more urban cities.  Nearly 70% of the rides were in urban cities, while suburban accounted for 26%, and rural for 5%.

In the urban cities, it’s important to note that there are more drivers than rides, so during this period, the average urban driver had 0.67 rides.  This metric was not much higher for suburban (1.3) or rural (1.6).  It appears that the there is a significant imbalance between the number of rides and the number of drivers.

When looking at total fare dollars during this period, 63% of the total fare dollars was in urban cities, while 30% was in suburban areas, and 7% was in rural cities.

![Overall_Revenue_Pie_Chart](https://user-images.githubusercontent.com/82730954/120115641-3c662580-c14a-11eb-9e75-70e2e193b6d0.PNG)

As expected, the average fare per ride was highest in rural areas and lowest in urban areas.

Accordingly, the overall average fare per driver was highest in rural areas and lowest in urban areas.  When analyzed on a monthly basis, this value was $13.87 (rural), $9.88 (suburban), and $4.14 (urban).

![PyBer_fare_summary](https://user-images.githubusercontent.com/82730954/120115653-48ea7e00-c14a-11eb-9297-4874cdbc444c.png)

The week over week data show that, while there were some variances throughout the year, revenue generally remained fairly steady within each city type.  It does not appear that our business, during this period at least, was growing substantially.  The graph more clearly demonstrates that the majority of the revenue currently flows through the urban markets.  

## Summary

Based upon the data analyzed, there are a number of recommendations to improve the disparity between the various types of cities and enhance overall success.

- First, it is recommended that there be a better balance between the number of drivers and rides.  Across all cities, the average driver had 0.8 rides over a nearly four-month period.  Ideally, it is recommended that the number of rides be increased in deliberate ways while ensuring that driver capacity remains at an acceptable level.  This has the potential of greatly increasing company revenue and average fare for each driver which would be a win-win for the company, our drivers, and our customers.  This focus should be strongest on urban markets.

- Secondly, and in using a cautious approach based upon the success of the first recommendation, it is suggested that the number of drivers be reduced.  This should be done in conjunction with a data project examining driver quality.  This can help us ensure that we retain the highest quality drivers while reducing those drivers who provide lower quality experiences for our customers.  Again, the strongest focus here should be on the urban markets.

- Finally, it is recommended that we launch an in-depth data project to examine the potential of greatly expanding our focus on rural markets.  The data show the highest average fare and driver fares are in the rural markets.  It is possible that there’s a large opportunity for growth in these potentially untapped markets.  Launching a larger data project to understand the various factors could help us have a more meaningful conversation regarding the potential rewards and risks of highlighting these markets.  It might be worth discussing if this project should also include suburban markets in its scope.
