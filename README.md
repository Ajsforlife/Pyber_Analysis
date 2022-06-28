# Pyber Analysis

## Overview

### Purpose

The sole purpose of the analysis was to create ride=sharing data that was filtered by city type. Upon having the data we were to process the data and create a multiple line chart which compared the total fares for each city type. We were to find the sum of the total rides by city type, sum of the total drivers by ity type, sum of the total fares by city type, the average fare per ride in that city type and the aveage fare per driver per that city type. In finding all of these statsitics we then used ther pivot() function to create a pivot chart and the resample() function also to create yet another new data set which we then used to create a multiple line graph showing the final data set from the resample() function.
   
## Results
The first and foremost chart that we created had the sums of total ride, total drivers, total fares, and the average fare per rider and average fare per driver. the picture is below. 
![image1](https://github.com/Ajsforlife/Pyber_Analysis/blob/main/challenge_pictures/Screenshot%202022-06-27%20180931.png)

The next major part that is somewhat hidden is to remove the time stamp from the dates which changes what some of the future data looks like because it will sum all the fares for those dates, but here is the original code which I had help with from a fellow coder, whom I mentioned.
![image2](https://github.com/Ajsforlife/Pyber_Analysis/blob/main/challenge_pictures/Screenshot%202022-06-27%20181647.png)

Next we have 2 charts one with the sums of everyday in the dataframe and one with the sums of the specific dates between 29-01-01 and 2019-04-28 which reduced the rows in the data frame by 10. first one is before and second one is after filtering by date.
![image3](https://github.com/Ajsforlife/Pyber_Analysis/blob/main/challenge_pictures/before%20date%20modification.png)
![image4](https://github.com/Ajsforlife/Pyber_Analysis/blob/main/challenge_pictures/modifid%20by%20date.png)

Upon filtering by data we can then get the final sum of the data on a weekly basis which follows
![image5](https://github.com/Ajsforlife/Pyber_Analysis/blob/main/challenge_pictures/Screenshot%202022-06-27%20181855.png)

And lastly the line chart which shows this weekly data comparison in a clean fashion.
![image6](https://github.com/Ajsforlife/Pyber_Analysis/blob/main/challenge_pictures/Screenshot%202022-06-27%20181840.png)

As you can learn from the data the urban city type seems to of had the most total rides, total drivers, and total fares, however the city type with the least drivers aka rural is the one with the highest average fare per ride and the average fare per driver. Suburban is steady in between both Rural and Urban city types.
        
## Summary
At the end of this analysis it seems the CEO us definitely capitilizing the most on the Rural city type, however there is a much higher demand in larger cities (Urban areas). The rides in the rural areas seem to be longer and more profitable for the driver and the company but the sheer volume of rides provided in the city shows that it is the cash cow of this analysis. Everyone wants a ride in the city and doesn't want to drive so the more drivers there are the less distance they have to go and the more rides they can provide traffic depending. It does seem that all of the city types spike in rides provided at the end of February so maybe its in the CEO's best interest to add some drivers in the middle of febrary to keep the supply available.

