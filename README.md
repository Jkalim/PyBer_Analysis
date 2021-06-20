# PyBer_Analysis
Analysis of a rideshare company


## Overview of PyBer analysis
The purpose of this analysis is to present to V. Isualize the following:
- a summary DataFrame of the ride-sharing data by city type
- a multiple-line graph that shows the total weekly fares for each city type
- the differences in data by city type and how those differences can be used by decision-makers at PyBer.




## Resources
-Data Source: scity_data csv and ride_data cscv 
-Sofware: Python 3.6.1, VS jupyter notebook

## Results
The PyBer analysis shows the differences in ride share between rural, urban and suburban city type. 

-The rural city type has 125 total rides, 78 total drivers, and a total fare of $4,327.93 which yields
  an average fare of $34.62 per ride and $55.49 per driver. 

-The suburban city type has 625 total rides, 490 total drivers, and a total fare of $19,356.33 which yields
  an average fare of $30.97 per ride and $39.50 per driver.

-The urban city type has 1,625 total rides, 2,405 total drivers, and a total fare of $39,854.36 which yields
  an average fare of $24.53 per ride and $16.57 per driver. 

-In general, the urban city type has the highest total weekly fare, followed by the surburban city type, then 
  the rural city type; however, the rural city type has the highest avearage fare per ride and driver followed 
  by surburban then urban type. 
 
-The following figure show how consistently these fares are higher than others every week:
  plt.savefig("/Users/jkstuff/Desktop/Data Analytics/PyBer_Analysis/Resources/PyBer_fare_summary.png")  
  
  ## Challenge Summary
  The following recommendations are advised in order to address the disparities between the city types:
  
  - Decrease the the fare amount in order to invite more people from the rural community to use the Pyber service more.
    More request will most likely lead to more drivers in the rural type.
    
  - Increase the number of drivers in the surburban community in order to compete with the urban type

  - Increase the fare amount in the urban community as it generates more request to improve the average fare per ride and driver. 
  
