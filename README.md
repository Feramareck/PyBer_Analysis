# PyBer_Analysis


# Overview of the analysis
The purpose of this project is to analyze all ridesharing data from January to early May 2019 and create a compelling visualization for the CEO.

# Results

The first step of this analysis was to merge the data provided into two csv files to create a single dataframe with all available rideshare information, generating the dataframe shown in the figure below:  

![PyBer_DataFrame](https://user-images.githubusercontent.com/111664141/192163609-4cfe83bf-846d-455b-9e7b-52b5dd13a854.png)
  
After the merge, we analyzed some totals based on city types.  
From the table below we can see that, despite the sum of the number of rides, driver and fares 
being much higher in urban cities, the average per ride and per driver of fares in rural cities are higher than the other types, reaching the average fare per driver to be almost 4 times bigger than urban.    

![PyBer_Summary](https://user-images.githubusercontent.com/111664141/192163723-64e24db9-ad59-4878-8bfe-544317c61697.png)

  
Performing the analysis of the data in relation to the rates generated weekly between the period from 01-01-2019 to 04-28-2018, we can draw the following conclusions: 
- Total urban fares are the highest among the 3 types, with their peaks occurring in the third week of February and the second week 
of March.  
- The suburban and rural types also had high fare peaks in the third week of February.  
- Rural cities had their highest rates in the fourth week of March.  
- For both urban and suburban, the lowest fare accumulated was for the first week of January, while for the rural, this occurred in the second week of January.  
- In general, we can verify that for the three types that the period where the total fare had the lowest accumulated was in the first fifteen days of January, and the best in the third week of February.  

Below is the graph showing our findings.  

![PyBer_fare_summary](https://user-images.githubusercontent.com/111664141/192163705-0ab9f65c-0ac3-41ef-9e4a-9842162d6ddd.png)

# Summary  
As a recommendation for possible analyzes among the city types, it would be interesting to analyze:  
- The total fare per day to check which day of the week is the most profitable.  
- As the date field has the hour of the ride, an analysis could be performed by shift (morning, afternoon, night) to verify where the largest number of rides and their fares are.  
- Its general comparatives (rides, drives, fares) in percentage terms for a better comparative exemplification.

In the PyBer_challege file we have the code with all the commented steps of the analysis.
