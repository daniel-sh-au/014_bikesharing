# Module 14: NY Citibike with Tableau

## Overview of the Analysis

### Summary
A bike trip analysis for New York City was completed to convince investors to invest in a bike-sharing program in Des Moines, Iowa. For this analysis, the 'tripduration' column in the dataset was first converted into the correct datatype (datetime). Then, a total of five additional visualizations were created to analyze the bike checkout times, the bike trips for each hour of each day, and the bike trips for each user type. Finally, these visualizations were assembled into a Tableau story for presenting. 

### Resources
* Jupyter Notebook, Tableau Public
* CitiBike Data: [201908-citibike-tripdata.csv.zip](https://s3.amazonaws.com/tripdata/index.html)
* Challenge Code: [NYC_CitiBike_Challenge.ipynb](https://github.com/daniel-sh-au/UofT_DataBC_Module14_bikesharing/blob/main/NYC_CitiBike_Challenge.ipynb)
* Tableau Dashboard: [NYC CitiBike Analysis](https://public.tableau.com/app/profile/daniel6815/viz/Module14_Challenge_16598008703440/NYCCitiBikeAnalysis?publish=yes)

## Results

### Summary Chart
![summary.png](https://github.com/daniel-sh-au/UofT_DataBC_Module14_bikesharing/blob/main/Resources/summary.png)

For the month of August in 2019, there were a total of **2,344,224** rides. A large majority of these rides occurred in the midtown and lower areas of Manhattan. More than **80%** of the users were annual subscribers while less than **20%** were short-term customers. Of all the riders, approximately **65%** were male, **25%** were female, and the rest unknown. These statistics demonstrate that more NYC residents are using CitiBike to travel in the mid-to-lower Manhattan region than short-term travelers.
Since most businesses are in that region, workers are likely using CitiBike to travel short distances rather than taking the subway. Recognizing that the majority of rides are located in the mid-to-lower Manhattan area also identifies the region that would require the most maintenance in the future. 

### Checkout Times for Users and Gender
![checkout_times.png](https://github.com/daniel-sh-au/UofT_DataBC_Module14_bikesharing/blob/main/Resources/checkout_times.png)

The checkout times represent the duration of each trip. The left chart represents the checkout times for all users and the right chart is separated by gender. From the left chart, we can see that the majority of all users are riding for 0-60 minutes and that most users are riding between 4-7 minutes. We can see similar trends on the right graph for each gender. These charts indicate that most users are only riding for a few blocks and pick-up/drop-up stations should be located at a maximum of 5-10 minutes apart at popular areas. 

### Trips by Weekday per Hour (and Gender)
![trips_weekday_per_hour.png](https://github.com/daniel-sh-au/UofT_DataBC_Module14_bikesharing/blob/main/Resources/trips_weekday_per_hour.png)

Trips by Weekday per Hour displays the most popular time to ride a CitiBike throughout the week. Both charts convey the same information, but the right chart is separated by gender. From the left chart, we can see that the most popular times to ride are 7-9am and 5-6pm for weekdays. During the weekend, the most popular times are 11am-4pm for Saturdays and 1pm-4pm for Sundays. The same trends can be observed for the right chart except that the majority of riders are male. During a weekday, it can be assumed that most riders are using CitiBike to travel to and from work. For weekends, ridership occurs mainly in the afternoon, possibly just for leisure. 

### User Trips by Gender by Weekday
![trips_usertype.png](https://github.com/daniel-sh-au/UofT_DataBC_Module14_bikesharing/blob/main/Resources/trips_usertype.png)

This final chart shows the number of trips for each gender at each day of the week. This data further supports the previous observations. It can be observed that ridership is higher for men than women. Additionally, ridership for subscribers is higher during a weekday especially on Thursdays and Fridays. It can be noted that ridership for short-term customers is higher during the weekend. 

## Summary
In conclusion, all these findings can be applied to successfully implement a bike sharing program in Des Moines, Iowa. The program will receive the most users during a weekday between 7-9am and 5-6pm as the population is commuting to and from work. Most rides will occur in the downtown region, which will require the most maintenance in the future. This maintenance should be performed during low usage times, around 1-3am. 

For future analysis, it may be beneficial to locate the most popular start and stop station names. This information can pinpoint the exact stations that need additional bikes and would require more maintenance to account for higher demand. Another visualization could compare trip duration and user type. We know that most rides are between 4-7 minutes but separating between user type could determine if short-term customers are riding for longer periods. 