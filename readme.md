# Ford GoBike System 02/19: Data Exploration 
## by Jan W.


## Dataset

The Ford GoBike System data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area in February 2019. The original data contains 183412 entries and 16 columns with a variaty of information regarding durations, start and end times, start and end stations, bike ids, user types, members birth years, member genders and bike share options. After cleaning due to missing data, tidiness and quality issues the dataset contains 166598 entries and 9 columns for further analysis:

Usage information:

- start_date: start date of trip
- end_date: end date of trip
- start_hour: start hour of trip
- start_day: start day of trip
- duration_minute: duration of trip in minutes

Member information:

- bike_id: id of bike
- user_type: customer or subscriber
- member_gender: male or female
- member_age: the age of the members in years
- bike_share_for_all_trip: members enrolled in the bike share for all program for low-income residents

The main feature of interest lies in analyzing the riding behavior of members and customers. Do the two target groups make different use of the service and, if so, for what reasons?

## Summary of Findings

Univariate Exploration

The data suggest that the service is predominantly paid by young and middle-aged men and regularly used for shorter trips during the week at the beginning and end of work hours. The service appears to be used less as a casual activity and more as a way to commute to work each day in february.

Bivariate Exploration

Interestingly, the user behavior of subscribers and customers is very similar in terms of usage times, trip length, and age distribution. Customers also seem to use the service primarily for commuting to work in feburary. However, the use of the service by customers does not decrease as much on weekends as it does among subscribers. Customers also take longer trips.

Multivariate Exploration

Customers and subscribers seem to use the service for the same purpose during the week: commuting to work. At the weekend, however, the usage behavior of the two target groups differs. While usage by subscribers is declining, younger customers in particular use the service at the weekend for medium distances during the day.

## Key Insights for Presentation

This presentation outlines similarities and differences in subscriber and customer usage patterns in February 2019 to provide interesting insights into the daily customer behavior of Ford GoBike system users. 

First, based on the visualization "Ride Distribution by Weekday in February 2019," the question is raised as to why usage numbers drop by nearly half on weekends. 

Second, using the visualization "Ride Distribution by Hour for Subscribers and Customers in February 2019", both groups appear to use the service primarily for their daily commute to work. 

Third, the visualization "Usage by Hour during Weekdays for Subscribers and Customers in February 2019" shows that subscribers and customers use the service to get to work. However, customers also use the service on weekends to travel medium distances during the day. But since the service is predominantly used by subscribers, user numbers decline on weekends. 

The same visualizations are used as in the explanatory analysis, but all diagrams have been given an appropriate title with labeled axes and legends, as well as appropriate coding and transformations.

## List of resources

https://seaborn.pydata.org/
https://matplotlib.org/stable/contents.html
https://pandas.pydata.org/docs/user_guide/index.html#user-guide