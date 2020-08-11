# Communicate Data Findings
### by Arwa Alhumaidi
Udacity Data Analyst Nanodegree - Project 5

## Ford GoBike System Dataset
This dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The original dataset collected from January 2018 to December 2018 and it contains approximately 1863721 bike rides with 14 of features. The features divide into some main sections:
1. Trip duration: duration_sec, start_time and end_time. 
2. Station info: start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id and end_station_name. 
3. Membership info: bike_id, user_type and bike_share_for_all_trip.

I added the following columns into df_clean in cleaning data section: start_month, start_weekday, start_hour and duration_min

## Main Findings Summary of Findings
There are two of user types
- Customers: They are just 15% of user types. They usually take bike trips most of the time on weekend and in summer vacation from 10am to 4pm. However, there are some bike trips for costumers on weekdays at 7-9 am and 4-6 pm. The customer's bike trips take a long time because they are usually using bikes to take trips around the area and for tourism. This also explain most costumers are tourists.
- Subscribers: They are 85% of user types. They usually take bike trips most of the time on weekdays and in summer and fall seasons at 7-9 am and 4-6 pm. the subscriber's bike trips take a short time, this is due to subscribers are usually using bikes for go to work or school. This also explain most subscribers are residents.

## Key Insights for Presentation
### 1. Customers
- Most costumers are tourists
- They are just 15% of user types. 
- They usually take bike trips most of the time on weekend and in summer vacation from 10am to 4pm.
### 2. Subscribers 
- Most subscribers are residents. 
- They are 85% of user types. 
- They usually take bike trips most of the time on weekdays and in summer and fall seasons at 7-9 am and 4-6 pm.

## References
- https://stackoverflow.com/questions/20906474/import-multiple-csv-files-into-pandas-and-concatenate-into-one-dataframe/21232849#21232849
