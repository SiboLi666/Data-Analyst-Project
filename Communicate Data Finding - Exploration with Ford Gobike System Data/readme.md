# Communicate Data Finding - Exploration with Ford Gobike System Data
## by Sibo Li


## Dataset

> This document explores a dataset containing the Ford Gobike system data obtained from https://www.lyft.com/bikes/bay-wheels/system-data. The dataset includes information about individual rides made in a bike-sharing system convering the greater San Francisco Bay Area. To explore the a full year's coverage, multiple data files will need to be joined together. The feature included in the dataset: Trip Duration (seconds), Start Time and Date, End Time and Date, Start Station ID, Start Station Name, Start Station Latitude, Start Station Longitude, End Station ID, End Station Name, End Station Latitude, End Station Longitude, Bike ID, User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual), Member Year of Birth, Member Gender.


## Summary of Findings

> I firstly find that the distribution is right skewed. There's a long tail in the distribution. There are a lot of people use bike for a short trip, few for a longer trip. When plotted in log-scale, the trip duration distribution is nearly unimodal. We can see that the average trip duration is around 600s. Most people use bike for a short trip. Also, the trip duration in summer is highest. Different season does have different trip duration, however, the difference is limited. It might becuase that the weather in San Francisco does not change that much.


## Key Insights for Presentation
* The trip duration distribution.
* The effect of season on the trip duration.
* The effect of user type on the trip duration.
* The combination effect of season and user type on the trip duration.
* The combination effect of season and bike share purpose on the trip duration.


