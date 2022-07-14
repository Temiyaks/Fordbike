
Communicate Data Findings Project

Fordgobike Dataset Exploration and Visualization 

Dataset 

Ford GoBike System Dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

The dataset orginally consists of 183,412 row (records) and 16 columns, and most variables are numeric and concerns three major things as follow:

- Trip (duration_sec, start_time, end_time)
- station (start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude, end_station_longitude)
- User (bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip)

After adjustment and cleaning process new columns were created to help in analyzing and expolring the data so, our dataset consists of 174,952 rows and  20 columns now and the new columns as follow:

- Trip (duration_min,Trip_day of the week, Trip_hour of the day)
- User (member_age)

Summary of Findings:

- Most bikers are between the age 25 and 35. There is a steadly decline in usage from age 35.
- Most users are actually subscribers than actual customers who represents only 9.6% of total users.
- The service is most used on Thursday. The usage decreases significantly on the weekends.
- Subscribers mostly rode bikes for (8-12) minutes, while customers mostly rode them for (10-20) minutes.
- Customers rides were more likely to last more than one hour compared to subscribers.
- It appears that customers hire bikes for amusement and enjoyment since they keep them longer than subscribers do,                 especially on weekends (Saturday and Sunday).
- Subscribers tends to rent bikes for shorter duration while Customers tends to rent bikes for longer duration.


Key Insights for Presentation Below are the insights for the presentation:

- The distribution of biking durations is skewed. After log transformation and outliner removing, we may visualize and interpret     data better.
- Subscribers rent bikes more efficiently as they have a shorter trip duration overall than customers.
- Both of Users type have a longer trip duration on weekend in relative to their trips during other week days.


