# PyBer_Analysis
# Overview
The example company, PyBer, wants to generate some ride sharing data analysis and visualizations to display relationships between drivers, riders, and the type of city they are in. Specifically, PyBer is interested in the percentage of total fares, drivers, and riders all by city type. 
## Purpose
The purpose of this project is to combine all of the ride sharing data found previously into a summary dataframe for Pyber to review. The data will be organized by city type. Then, PyBer wants to review all of the different cities' total fares over the past few months. All of these objectives will be analyzed and visualized. These visualizations will be used to evaluate ride sharing in the different city types and also the trends of each city type so PyBer will know what kinds of cities are most profitable for the company.

# Results
## Ride Sharing Data
Some of the analysis was done during the module, meaning that the dataframes with the ride data and city data were merged into a single dataframe. From this single dataframe, the total number of rides, total number of drivers, total amount of fares for each city type were able to be calculated. Then, the average fare per rider and per driver for each city type was calculated. A larger summary dataframe was created to organize all of this data: ![Ride_Share_Data.png](https://github.com/allysakarr/PyBer_Analysis/blob/master/Resources/Ride_Share_Data.png?raw=true)

According to the analysis done on the ride sharing data, there were substantially more rides, more drivers, and higher fares in the urban cities. In terms of rides, there were 1,000 more in the urban cities vs. suburban and also over 4x more total drivers in the urban cities vs. suburban. The total fare was $20,000 greater in urban cities vs. suburban - so the urban cities show a lot of usage and revenue from the app. 

However, in terms of average fare per ride and average fare per driver, the rural areas actually showed to be the most profitable. Rural cities had $10 more average fare per ride than the urban cities and $38 more average per driver than the urban cities. From an individual transaction perspective, the rural cities showed a greater revenue per transaction than urban cities did.

## Total Fare by City Type
PyBer also wanted to view the total fares of all 3 kinds of cities over a few months timespan. In order to do this, the "fare" variable was separated through the indexes of time and date in order to localize a specific timespan. This data was then reorganized to get rid of null values and also condense the data to just display the months of January through April. This timespan was further broken down into weeks in order for the data to visualize accurately for PyBer to view the progression of the total fare by city type over January through April. The data was compiled into a mutliple line chart, as seen below: ![Total_Fare_by_City_Type.png](https://github.com/allysakarr/PyBer_Analysis/blob/master/Resources/Total_Fare_by_City_Type.png?raw=true)

# Summary

From overlooking the multiple line chart and also understanding the ride sharing data, it can be seen that the urban cities generally provide more total fare, riders, drivers and revenue than the rural and suburban cities. The only exception to this is that the average fares for both the rides and the drivers are higher in the rural areas. 

One of the possible reasons for this outcome could be that the the distance the drivers cover is longer and translates to a higher revenue per ride. There are also fewer riders meaning each driver might have to drive further just to pick up a customer, meaning that they pick up less customers overall meaning. Due to these reasons, each rural/suburban driver is somewhat "rarer" than an urban driver, meaning they can charge more per ride. They also have to drive further, and more effort on the driver end could lead to higher costs. 

To address these disparities, PyBer could develop an initiative program to recruit additional drivers in rural and suburban areas. This would increase the drivers, which would then increase the number of rides and improve revenue for the rural and suburban cities. Increasing advertisements as an additional form of work in these areas could also help recruit more drivers. PyBer could also introduce ride-sharing with other customers, meaning that one driver could have different customers all in the same car. This way, the driver could make additional revenue while they are completing another ride, increasing the overall revenue for the rural and suburban cities. 

