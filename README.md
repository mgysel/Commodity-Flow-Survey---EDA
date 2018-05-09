# 2012 Commodity Flow Survey -- Exploratory Data Analysis

## Summary of 2012 Commodity Flow Survey
The 2012 Commodity Flow Survey (CFS) is a joint effort by the Bureau of 
Transportation Statistics and the U.S. Census Bureau, U.S. Department of 
Commerce. The survey is the primary source of national and state-level data on 
domestic freight shipments by establishments in mining, manufacturing, whole 
sale auxiliaries, and selected retail and services trade industries, located in 
the 50 states and the District of Columbia. The survey produces estimates on 
the type, origin and destination, value, weight, modes of transportation, 
distance shipped, and ton-miles of commodities shipped. 

2012 Commodity Flow Survey data and additional information can be found at: 
https://catalog.data.gov/dataset/commodity-flow-survey

## Conclusions

The main conclusions drawn from the exploration of the Commodity Flow Survey
dataset are:

* The shipments with the most weight and value tend to be in the agriculture, 
transportation, and energy industries.
* The heaviest shipments are transported mainly by rail, while the average 
shipments are transported mainly by road.
* Air, water, and rail are the modes of transit used for the longest shipment 
distances.
* For-hire and Private Truck have the highest percentages of 
shipments up to about 1,000 miles. Parcel, USPS, or courier has the highest 
percentage of shipments greater than 1,000 miles.
* Parcel, USPS, or Courier has the highest percentage of 
shipments up to about 70 pounds, and then falls precipitously to practically 
none of the shipments. For-Hire Truck and Private Truck have the highest 
percentage of shipments that weigh greater than 70 pounds. 

## R Libraries: The code in this repository assumes the following R libraries are installed:
* ggplot2
* GGally
* dplyr
