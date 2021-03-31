# PyBer Analysis

## Project Overview

Pyber a ride sharing company requested an analysis that showcased the differences betweeen the three types of of cities (Rural,Urban & Suburban) where the company operates. The main areas of focus here were the number and percentages of drivers, riders, and averafe fares by type of city using python's pandas, numpy, and matplotlib libraries. This was used to help determine affordability for under served neighborhoods. 

## Resources
Data Sources: 
- city_data.csv
- ride_data.csv


## Results

### Rides per City Type

Average rides per city type

![Ride Count Box and Whisker Plot](analysis/Fig2.png)

Total rides per city type

![Total Rides Pie Chart](analysis/Fig6.png)

### Fares per City Type

Average fares per city type 

![Ride Fare Box and Whisker Plot](analysis/Fig3.png)

Total fares per city type

![Total Fares Pie Chart](analysis/Fig5.png)

Monthly totals per city type

![Total Fare Multiple Line Graph](analysis/PyBer_fare_summary.png)

### Drivers per City Type

Average driver count per city type

![Driver Count Box and Whisker Plot](analysis/Fig4.png)

Total driver count per city type

![Total Drivers Pie Chart](analysis/Fig7.png)



Based on the results lsited above we can conclude the following: 

  - Rural cities has the least amount of drivers, rides and total fares.
  - Urban cities have the most amount of drivers, rides and total fares.
  - Suburban cities are in the middle having the 2nd most drivers, rides and total fares.
  - Rural cities have the highest average fare per ride and per driver.
  - Urban cities have the lowest average fare per ride and per driver.

## Summary

### Summary of Previous Analysis

The analysis indicates the following key points: 

1) Rural cities represent 5.0% of total rides and 6.8% of fares, with only 2.6% of drivers. Incentitives should be made to attract more drivers to underrepresented areas by showing them that on average they can make more per ride compared to other city types. 
2) In contrast, we should increase riders in rural areas by showing them that on average they spend less per ride compared to other city types. 

### Multiple-line Graph   

The graph indicates consistent trend across the different city types so we can effectively use this to determine average fare on a weekly basis dependent on the type of city.

### Implications 

Given the high number of drivers in urban areas, it is recommended to increase the fees per mile as drivers do not make the same amount of money for number of trips.
Adjust the fees to match number of riders and drivers during certain months.
