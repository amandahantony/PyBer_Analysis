# PyBer_Analysis
Performing an analysis on ride-sharing data by city type. 

## Overview of Project 
### Purpose
In this new analysis, we compared the three city types(urban, suburban and rural) based on the total rides, total drivers and total fares in 2019. A more specified analysis was done on the total fares in each city type by date. Using Python plotting, a multi-line graph was created to show the total weekly fares for each city type between the months of January to April. This graph provides meaningful information that can be used to draw conclusions on city type trends, and weekly performance.

## Results 
1) A dataframe was created to compare the total rides, total drivers, total fares, average fare per ride and average fare per driver in each city type during the year of 2019 (shown below). The dataframe shows that the urban city type had the most total rides, total drivers and total revenue from fares in comparison to suburban and rural city types. The average fare per ride and average fare per driver were the lowest in the urban areas in comparison to the other two. Rural city type, on the other hand, had the lowest total rides, total drivers and total revenue from fares. The average fare per ride and average fare per driver was the highest in rural city type in comparison to urban and suburban city types.

![Summary Dataframe](Images/pyber_summary_df.png)

2) A more specified analysis was conducted on the total weekly fares in the three city types between January and April. First, a dataframe was created to gather the total fare amount from each date in each city type, using the groupby() function. The dataframe was then converted to a pivot table, using the pivot() function, to show the total fare for the date and time of each ride in the city types. The loc function further narrowed the analysis to the rides between January 1st to April 29th (shown below). 

![PyBer Pivot Table](Images/pyber_pivot_table.png)

3) A new dataframe was created using the resample() function to gather the total weekly fares from January to April in each city type (shown below).
![PyBer Resample](Images/resample_df.png)

![PyBer Fare Summary](analysis/PyBer_fare_summary.png)


