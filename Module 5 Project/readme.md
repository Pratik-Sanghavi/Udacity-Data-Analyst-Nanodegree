# Ford Go Bike Trip Data
## by Pratik Ravikumar Sanghavi


## Dataset

The Ford Go Bike trip data from the month of February 2019 is being considered here. It includes data about the trips made by different bikes and captures features such as duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude, end_station_longitude, bike_id, user_type, member_birth_year, member_gender and bike_share_for_all_trip. We can draw several interesting conclusion just from these features as is shown in the subsequent slides


## Summary of Findings

The one crucial question we seek to answer here is for what exactly does our user base utilise our services. For this the following is proposed:-

1. The Subscriber group comprises of working individuals that are likely to use our services for work
2. The Customer group comprises of a mixed set of users - although they are more poised to use the service for leisure activities on the weekend than the Subscriber group
3. There are certainly nodes where the bike concentration either increases or decreases over the course of the month.
4. There are no destination changes between weekend 'leisure' trips and weekday 'routine' trips
5. The age of some of our users has not been correctly recorded
6. The gender representation in our dataset is pretty skewed


## Key Insights for Presentation

1. Representation of different genders is very skewed in our dataset. Is this because females and others don't use our services or because we've not recorded these trips? If its the former then we should investigate the reason for their aversion and if its the latter well just randomly shuffle and provide the dataset.

2. We might consider trying to create some sort of equilibrium faster in order to ensure a healthy supply of bikes at the stations. This could be achieved by offering heavy discounts on less frequented routes to our users in hope that they might consider travelling on those routes during their leisure rides.
