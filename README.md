# (Analysis for San Francisco Bay GoBike service)
## by (Caleb Okon)


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. information collated in this dataset includes the following 'duration_sec', 'start_time', 'end_time', 'start_station_id','start_station_name','start_station_latitude','start_station_longitude','end_station_id','end_station_name','end_station_latitude','end_station_longitude','bike_id','user_type','member_birth_year','member_gender' and 'bike_share_for_all_trip'. 


## Summary of Findings

After the univariate exploration, i discovered that;
1. About 89.2% of thr riders are subscribers, with just 10.8% as customers.

2. Also, 'market St at 10th St' is the most popular start station and 'san francisco caltrain station 2 (Townsend St at 4th St)' is the most popular end station.

3. The '16th st depot' is the most rarely used start station and 'willow St at vine St' is the most rarely used end station.

4. most trip took between 7-15 minute, with wednesdays having most rides and they begin and end mostly between the hours of 6-9am and 4-8pm.

5.  All the rides in this dataset occured in february, which i didn't noticed earlier until during the univariate analysis.

After the Bivariate exploration, i discovered that:

1. most subscribers rode for 7-13 minutes and most customers rode for 10-15 minutes.
2. more customers rode for more than one hour as compared to subscribers.
3. since all data given in the dataset are only for february then we can see that the subscribers user_type tends to ride more bikes than its customer counterpart.
4. subscribers uses bike mostly on weekdays with tuesday and thursday having the most rides, but there is a major reduction during weekends. for the customer part thursday and sunday seems to be the days with most rides, and unlike the subscribers, customers tend to ride more during weekends.
5. the hour with in which most subscribers start riding is mostly by 8am and 5pm. but, most customers ride starts by 5pm followed by 4pm and 8am.

After the multivariate analysis, i discovered that:

1. subscribers seems to have a similar duration minute not above 20 minutes, unlike that of customers. 
2.customers seems to spend more time riding in each hour than subscribers.

## Key Insights for Presentation

#### Days of use

subscribers uses bike mostly on weekdays with tuesday and thursday having the most rides, but there is a major reduction during weekends. for the customer part thursday and sunday seems to be the days with most rides, and unlike the subscribers, customers tend to ride more during weekends.

#### Duration of use
Customers have are have more flexible and spend longer time using the service than subscibers and it is strange that the average duration at 2am and 3am is higher than other hours.