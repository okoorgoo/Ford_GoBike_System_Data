# Ford GoBike Data Visualization
## by (Olga Kurguzova)


## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. This project analyzes the data collected from users of the GoBike program for February 2019.

The dataset includes:

- an ID number for each bicycle
- how long it was rented for, in seconds
- the start and end time
- the beginning and end staton ID, latitude, longitude and station name
- user's year of birth
- the gender of the user
- whether the user has a subscription to the service or not

There are 174,278 rows and 14 columns.

Some cleaning was needed in the dataset:

- Deleting the rows with NaN values in gender or birth year;
- Deliting unnecessary columns;
- Only use ages that are reasonable. Check for abnormally old or young values and remove them;
- Change data types, including times to datetimes, and user_type and member_gender to categories;
- Extract time of day and days of the week from start_time;

## Summary of Findings

1. Most of users Ford GoBike service are subscribers (91%);
2. The majority of users are men both among subscribers and customers;
3. The majority of users are people between the ages of 25 and 35, both among subscribers and customers;
4.Subscribers mostly use the service during the working week, especially in the evening, while customers use the service throughout the week, especially around noon on weekends. Perhaps subscribers used the service to travel to work or at work, and customers for entertainment. It is worth noting that the trips of customers on average lasted much longer.


## Key Insights for Presentation

In this project, I focused on the difference in usage of Ford GoBike service for customers and subscribers in terms of: when they use the service, how long their trips lasted and the influence of gender and age    