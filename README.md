# WeatherPy

## Overview of Project
PLANMYTRIP is a top travel technology company that specializes in internet-related services in the hotel and lodging industry.  I have been asked by the head of analysis for the user interface team to assist in collecting and presenting data for customers via the search page, which customers will then filter based on their preferred travel criteria in order to find an ideal hotel, anywhere in the world.  After providing analysis, visualizations and presentations for the initial search page project the head of analysis for the user interface team and their beta testers have given their sign of approval.  After doing so they next recommended that I add the weather description to the weather data to enhance the customer search and filter experience.

### Purpose
The purpose of this project is to add the weather description to the weather data and enhance the PlanMyTrip app.  Once completed the company beta testers will use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels.  The beta tester will choose four cities from the list of potential travel destinations to create a travel itinerary. After the four cities are selected I will use Google Maps Directions API to create a travel route between the four cities and a marker layer map.

## Results

### Ride-Share Results
There are three ride-share areas, urban, suburban and rural.  As would be expected number of rides and total fares are highest in the urban area as the population and ride-share demand is highest and the lowest number of rides and fares are in the rural area.  The suburban area falls in the middle.  A concern from a business standpoint is the disproportionate number of drivers in the urban area based on ride-share demand and compared to the other two areas.  This in turn results in a much lower average fare per driver in the urban area compared to the other two regions.  The results are as follows:

![Ride_Share_Summary](https://raw.githubusercontent.com/JBro-Birds/PyBer_Analysis/master/analysis/Ride_Share_Summary.png)

Total Fare by City Type Line Chart:

![Total_Fare_By_City_Type_Line_Chart](https://raw.githubusercontent.com/JBro-Birds/PyBer_Analysis/master/analysis/Total_Fare_By_City_Type_Line_Chart.png)

## Summary

### Recommendations
There are three business recommendations for addressing disparities among city types.
* Eliminate a number of urban drivers.  There are too many urban drivers based on demand which in turn is lowering the average fare per driver.  The lower average fare per driver is going to discourage urban drivers and create business issues in the future.  Eliminating a number of urban drivers will lower company costs.
* Create and implement a driver-by-area flexibility model based on periods of higher demand by area.  Based on driver home addresses have rural and suburban drivers 
swap areas when needed and likewise have suburban and urban drivers swap areas.  This type of flexibility will increase driver morale by increasing their average fare by driver and increase company efficiencies.
* Revise ride-share pricing structure with rates based on demand by area.  Since there is a much greater demand in the urban area compared to the rural area this will create less fare per ride disparity between urban and rural riders. 

