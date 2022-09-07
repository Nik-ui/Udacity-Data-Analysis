# (Bike - Trip Dataset)
## by (Adeniya Adenike)


## Dataset

**The original dataset had 18341 entries & 16 columns. After the data was cleaned with
the removal of na, the dataset reduced to 174952 entries and 16 colums.**

**The last two columns are discrete features and the first one is a continuos feature.**


**The dataset after cleaning contains 174952 trips with 15 features. The features are:**
1. duration_sec : duration for the trip in second
2. start_station_name : the trip start station name
3. end_station_name : the trip end station name
4. start_station_latitude : start station latitude location
5. end_station_latitude : end station latitude location
6. user_type : Members divided to Subscriber (subscribe to the service) or Customer (normal customer)
7. start_date : the date at which the trip start
8. end_date : the date at which the trip end
9. start_station_longitude : start station longitude location
10. end_station_longitude : end station longitude location
11. start_week : the day of the week at which the trip start (Saturday, Sunday, Monday, Tuesday, Wednesday, Thursday and Friday)
12. end_week : the day of the week at which the trip end (Saturday, Sunday, Monday, Tuesday, Wednesday, Thursday and Friday)
13. start_day : start day of the month (1-31)
14. end_day : end day of the month (1-31)
15. bike_share_for_all_trip : bike share for all trips
16. member_birth_year: birth year for users
17. member_gender: users gender (Male, Female)


## Summary of Findings

- The majority of long-distance trips are taken by people in their mid-twenties, regardless of gender.
- The age range of subscribers is marginally higher than that of customers.
- More than other user kinds, subscribers use the three primary locations..
- Males were more evenly distributed across the three major clusters than females.
- When compared to users who utilize bikes from both right locations, users who started their journey from the left cluster are more likely to share a bike during the entire trip.


## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.

Distribution for trips over (Duration / Sec , Age, User Type, Member Gender, Bike Share, Start and End Stations).
Station Locations (latitude and longitude)
Days of Month and Day of Week
The correlation between the numerical features.
The relation between the main features which are (Duration, Age and Gender).