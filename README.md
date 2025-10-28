# BikeShare Exploration for San Francisco Greater Bay Area, New York City and Washington DC Metro Area
## by Princewill Okechukwu


## Dataset
We'll work with 3 datasets, 1 for each city. The dataset contains infomation on: where Bikeshare riders go, when they ride, how far they go, which stations are most popular, what days of the week are most rides taken on,Gender and Age of ride Bikesharers. 

The df_sf containing Bikeshare data for San Franciso Greater Bay Area contains 183412 observations with 16 variables, this is the primary dataset, the other datasets like the New York City dataset which contains 943744 observations and 15 variables and the Washington DC Metro area dataset which contains 158130 observations and 9 variables will be compared alone side when necessary. 



## Summary of Findings
The variable of interest is the Trip duration in minutes, (duration_min). The analysis wwere carried out in 3 stages: Univariate, Bivariate and Multivariate:
For Univariate: 
- Here we saw that the distribution of duration_min was fairly unimodal for the 3 Cities.
- Age Distribution is Unimodal for San Franciso and Bimodal for New York.
-For Gender distribution between San Franciso and New York, while the Male percentages were almost the same (74.6% and 74.7% respectively) , we saw that the Female proportion recorded for San Franciso (23.3%) was higher than that recorded for New York (21.6%). The unknown gender category for New York was 3.85% higher than that of San Franciso (2.1%).
-Distribution of UserType across the 3 cities, NYC recorded the highest subscriber to customer ratio, followed by DC and then SF.
- For Day and Period Traffic, we saw that Thursday was the busiest day of the week of the 3 cities, also early evening (bewteen 5pm - 8pm) was the busiest period of the day.

For Bivariate:
-For Trip duration versus age, No much information was observed from the scatter plot.
-For Tripduration versus period of day, it can be observed that Early afternoon(between 12pm - 3pm) has the largest interquartile range and max value, than the rest of the day for the three Cities, This means that the duration at this time varies more than other periods. While late evenings(Between 8pm- 12 midnight) duration having lowest median for the three cities.
-For Trip Duration versus day of the week, it can be seen that Weekends(Saturday and Sunday) have the largest interquartile range for Trip duration, this means that duration varies more on weekends than on weekdays across the 3 cities.
- Usertype proportion for Gender- It can be seen that the ratio of customers to subscribers for both male and female groups in San Francisco is higher than that for New York.

For Multivariate:
Comparing Gender and Usertype in the Scatter plot for Trip duration versus Age, it can be seen that age varies more at higher trip duration for San Francisco than for New York.This is a more visible visualization than the bivariate plot of just Trip duration versus Age. 
Nevertheless, it is recommended that more statistical tests are carried out know if the difference is statically significant across both cities. 



## Key Insights for Presentation
The histogram of Trip duration(minutes) for the three cities shows a unimodal distribution.

Trip Duration versus the Period of the day, a box plot was chosen, it was observed that early afternoon(between 12pm - 3pm) has the largest interquartile range and max value, than the rest of the day for the three Cities, This means that the duration at this time varies more than other periods. While late evenings(Between 8pm- 12 midnight) duration having lowest median for the three cities.

Trip Duration versus Day of week For All Cities
From the Box plots, it can be seen that Weekends(Saturday and Sunday) have the largest interquartile range for Trip duration, this means that duration varies more on weekends than on weekdays across the 3 cities (more spread out).

User-Type proportion in Gender For San Francisco and New York
From the Clustered Bar Chart It can be observed that the ratio of customers to subscribers for both male and female groups in San Francisco is higher than that for New York.



