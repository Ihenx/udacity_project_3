#  Ford GoBike Ride Analysis For the Month of February

## Investigation Overview

In this project i analysed the fordgobike datasets and explored the information about the rides made by individuals made in the month february 2019.for this analysis , pandas DataFrame were used. The following questions were answered during this project:
* Which of the day of week were most of the trips made.
* the number of user type
* How was the gender distributed.
* Was there any round trip etc
## Dataset Overview

The datasets consists of information regarding about 183,412 rides made in the month of february.The datasets consists of about 16 features which includes the following:

* duration_sec : duration of trip made in seconds
* start_time : time trip started
* end_time : time trip ended.
* start_station_id: station id where trip started.
* end_station_id : station id where trip ended.
* start_station_latitude : the lattitude location of the station  where of the trip started
* end_station_latitude : latitude location of the station where the trip ended.
* end_station_longitude :longitude location of the station where the trip ended.
* start_station_latitude :longitude location of the station where the trip started.

* User_type : type of user(subscriber or customer)
* member_birth_year : Year which member were born
* member_gender : gender of member(male, female and other)
* bike_id : unique identifier of bike used for trips:
## Libraries used
For this project i made used pandas for Data wrangling while matplotlib and seaborn were used for visualizations.
## Summary and Finding
from the above analysis we arrive at the following conclusion:
* The male gender made the most trips in the month of february.
* Most of the trips made falls around 10 minutes.
* Majority of the trips made were not round trips.
* The age group of those who patronised ford Gobike were within the age range of 18 to 35 years hence the name young adults.
* Most of the trips made was were during the day time.
* Most of the trips were made on Thursday while there was low patronage during the weekend.
* Most of the trips started between 7 am and 9 am in the morning.


Keys Insights
For this presentation, i focused on the following:
* i focused on which of the day of the week that most of trips were made.
* How long does most of trips take and check if the results depends on member gender and user type
* From our presentation we could see that the other gender's ride last longer than both male and female.
