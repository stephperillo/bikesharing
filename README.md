# bikesharing

## Overview

This analysis examines bike trip data to help convince investors that a bike-sharing program in Des Moines is a solid business proposal. 

I used New York City Citi Bike data as a model so that one may have a better idea of the type of Des Moines users that a similar bike sharing program would interest.

To prepare the data, I used Pandas to convert the "tripduration" column to datetime format.

![converted_to_datetime.png](https://github.com/stephperillo/bikesharing/blob/main/Resources/converted_to_datetime.png)

## Results

Using Tableau, I created visualizations that show:

- How long bikes are checked out for all riders and genders.
- How many trips are taken by the hour for each day of the week, for all riders and genders.
- A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.

[Link to Tableau Story](https://public.tableau.com/views/dashboard_16559352930370/NYCCitiBikeStory?:language=en-US&:display_count=n&:origin=viz_share_link)

This graph shows the length of time that bikes are checked out for all riders:

![checkout_times.png](https://github.com/stephperillo/bikesharing/blob/main/Resources/checkout_times.png)

The majority of bike rental durations are less than an hour. This supports the fact that most users (over 80%) are Subscribers. 

![customers.png](https://github.com/stephperillo/bikesharing/blob/main/Resources/customers.png)

The most popular times for bike users to begin their rides are: 

Thursdays from 5 pm - 7 pm, 8 am - 9 am, and Mondays and Tuesdays from 5 pm - 7 pm in that order. Midday on Saturdays also tends to be a common time for NYC bikers to begin using Citi bikes.

![weekday_for_each_hour.png](https://github.com/stephperillo/bikesharing/blob/main/Resources/weekday_for_each_hour.png) 

The majority of users are males.

![checkout_times_by_gender.png](https://github.com/stephperillo/bikesharing/blob/main/Resources/checkout_times_by_gender.png)

People of all genders tend to rent bikes for no longer than an hour.

The following heatmap displays the number of bike trips by gender for each hour of each day of the week:

![gender_by_hour.png](https://github.com/stephperillo/bikesharing/blob/main/Resources/gender_by_hour.png)

I then created a heatmap that shows the number of bike trips broken down by gender for each day of the week by each user type:

![trips_by_gender.png](https://github.com/stephperillo/bikesharing/blob/main/Resources/trips_by_gender.png)

Male subsribers most often use NYC Citi Bikes on Thursdays and Fridays compared to other weekdays. Similarly, females tend to use bikes mainly during those same times.

![trips_by_gender_by_weekday.png](https://github.com/stephperillo/bikesharing/blob/main/Resources/trips_by_gender_by_weekday.png)

Younger riders tend to use bikes longer. There are a few outliers, such as riders born in 1891 (shown by the peak).

![avg_trip_duration_by_birthyear.png](https://github.com/stephperillo/bikesharing/blob/main/Resources/avg_trip_duration_by_birthyear.png)

## Summary

Two additional visualizations that I would perform with the given dataset would be:
1. To examine the starting and ending locations of the bikes that are used the most. 
2. To show the most common starting and ending locations specifically during the hours of highest volume bike utilization (i.e. Thursdays from 5 pm - 7 pm, 8 am - 9 am, and Mondays and Tuesdays from 5 pm - 7 pm, and midday on Saturdays). It may be helpful to see where most users are commuting.

Outside of this dataset, it would be beneficial to look at data for winter months to see if it would be worth it to start a bike sharing program in Des Moines, where the snow may affect bike utilization. In addition, one should compare the tourism data between Des Moines and New York City.
