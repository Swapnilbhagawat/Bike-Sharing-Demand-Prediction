# Bike-Sharing-Demand-Prediction
**Problem Statement:**
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

**Aim Of Project:**
The goal of the company Seoul Bike is providing the city with a stable supply of rental bikes. It becomes a major concern to keep users satisfied. The crucial part is the prediction of bike count rents at each hour for a stable supply of rental bikes. We can suppose that this study could be reported to the company 'Seoul Bikes'. We think it could help them knowing if yes or not they have to supply bike stations in the city, in order to keep the customers.

**Attribute Information:**

● Date : The day of the day, during 365 days, type : str

● Rented Bike Count : Number of rented bikes per hour which is the target, type : int

● Hour: The hour of the day, type : int

● Temperature(°C): Temperature per hour, type : Float

● Humidity(%): Humidity in the air in %, type : int

● Wind speed (m/s) : Speed of the wind in m/s, type : Float

● Visibility (10m): Visibility in m, type : int

● Dew point temperature(°C): Temperature at the beginning of the day, type : Float

● Solar Radiation (MJ/m2): Sun contribution, type : Float

● Rainfall(mm): Amount of rain in mm, type : Float

● Snowfall (cm): Amount of snow in cm, type : Float

● Seasons: Season of the year, type : str

● Holiday: If it is holiday period, type: str

● Functioning Day: If it is a Functioning Day, type : str

For this project, we will be analyzing SeoulBikeData data. The contents of the data came 
from a city called Seoul. A bike-sharing system is a service in which bikes are made available for 
shared use to individuals on a short-term basis for a price or free. 

We first decided to analyze and transform data for data analysis. We
did EDA on dataset and then we decided perform experiment on ML algorithms and gate results from it,
then we decided which model is best for dataset from 
results.

# Conclusion:

● Hour of the day holds most importance among all the features for prediction of dataset
● It is observed that highest number bike rentals count in Summer and Autumn Seasons and the 
lowest in Spring season.
● We observed that the highest number of bike rentals on a clear day and the lowest on a snowy 
or rainy day 
● The top 5 important features of our dataset are: Season_winter, Temperature, Hour, 
Season_autumn, Humidity 
● Peoples don’t use rented bikes in no functioning day 
● People tend to rent bikes when the temperature is between -5 to 25 degrees 
● People tend to rent bikes when the visibility is between 300 to 1700 
● For all the above experiments we can conclude that gradient boosting and random forest 
regressor with using hyperparameters we got the best results.
