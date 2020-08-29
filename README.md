# PyBer_Analysis
Python Visualization exercise using MatPlotLib (Module 5 UT Data Visualization Bootcamp)
<!---
There is a title, and there are multiple sections. (2 pt)
Each section has a heading and subheading. (2 pt)
Links to images are working and displayed correctly. (2 pt)
--->

<!---
Overview:  The purpose of the new analysis is well defined. (3 pt)
--->
## Overview
For this challenge, task was to utilize MatPlotLib with Python to explore various charting & formatting options available to perform intrisic data visualization.

Specific dataset used was a simulation of ride sharing data:
-- Ride data (2376 rows)
-- City data (121 rows)

Using the visualizations within the module & challenge assignment, goal is to determine what relationships (specifically by city type) can be discerned within the datasets.

<!---
Results:  There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. (7 pt)
--->
## Results

Key charts from module & challenge assignment to determine pattern by city types: 
-- Rural
-- Suburban
-- Urban

*( Total Fare By City Type )*
![PyBer_fare_summary](/analysis/PyBer_fare_summary.png)

*( Average Fare versus Total Number of Rides Per City Type )*
![Fig1](/analysis/Fig1.png)

*( Percentage of Total Drivers by City Type )*
![Fig7](/analysis/Fig7.png)

<!---
Summary:  There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. (4 pt)
--->
## Summary

Based on Total Fare by City Type, highest fare revenue consistently month over month consistently comes from city types:
1. Urban
2. Suburban
3. Rural 

Urban city types achieves this through sheer volume.  Average Fare versus Total Number of Rides Per City Type shows a descending relationship.  
The higher number of rides within Urban environment leads to lower average fare cost---likely due to increased competition among drivers.

Percentage of TOtal Drivers by City Type helps to confirm this hypthosis.  Number of available drivers from highest to lowest is:
-- Urban
-- Suburban
-- Rural

To address this disparity, the following is recommended:
1.  Increasing the number of available drivers in rural & suburban cities may help to reduce average fare price.
2.  Late February shows peak alignment in total fare revenue among city types.  It is recommended to take advantage of this by increasing fare pricing.
3.  Early January alignment as well, but for lowest fare revenue.  This may be due to holiday season.  To confirm, it is recommended to extend analysis to include December 2018.
