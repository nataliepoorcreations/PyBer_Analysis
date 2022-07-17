# PyBer_Analysis
Analysis of ride-sharing data by city type using pandas and matplotlib libraries.

## Background
* Using Python skills and knowledge of Pandas, create a summary DataFrame of the ride-sharing data by city type. 
* Use Pandas and Matplotlib to create a multiple-line graph that shows the total weekly fares for each city type.
* Submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

![summarytable](https://user-images.githubusercontent.com/106033535/179428624-27d09164-e05b-4365-a061-6ae22d7af835.png)

## Resources
* Data Source: Pyber_city_data.csv, Pyber_ride_data.csv
* Software: Python, Anaconda, Jupyter Notebook, Pandas

## Overview of the analysis:
The totaly drivers, total rides, total fares, and average fare per ride were calculated using the groupby function, in to addition using the sum, count and mean functions. To find the average fares per driver I divided the total fares per city type by the toal drivers per city type. 

* City data type

![citydatatype](https://user-images.githubusercontent.com/106033535/179428648-c9894c34-0eb9-46db-a8c4-ba7ab67e2628.png)

* Driver count

![drivercount](https://user-images.githubusercontent.com/106033535/179428679-c357053b-ea80-4901-bf64-d98433a14284.png)


* Ride data

![ridedata](https://user-images.githubusercontent.com/106033535/179428690-bd9d88bc-e430-4f27-88d3-a487dc3af0ee.png)

![Fig2](https://user-images.githubusercontent.com/106033535/179429125-43e8040c-9c8e-463f-a6eb-656d83e8c665.png)



## Results
The rural cities had the highest average fares per driver and ride. The urban cities had the lowest and the high fares seen in the rural cities were due to lower number of total rides and total drivers in those cities. 

![summarytable](https://user-images.githubusercontent.com/106033535/179428947-5eac714e-7e91-4139-a829-077ccf7ac4ce.png)

The urban cities had the highest total fare within the months of January to April 2019. The rural cities had the lowest fare during those months.  

![Fare_Summary](https://user-images.githubusercontent.com/106033535/179428960-53178fc1-490b-4286-91e9-396da14b2cc0.png)


## Summary
In summary he number of ride usage in the rural cities in January to April 2019 could be due to the low number of available rides and drivers in those cities.
* Allocating more rides and drivers to the rural cities can ruduce average fare per ride and driver. 
* More rides and drivers will boost ride affordability. 
* Urban cities can also benefit from addint more ride allocation during those months. 
* Making these changes will help meet demands for rides and increase revenue. 
