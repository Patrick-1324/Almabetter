Business Context

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

Data Description:

**Name: Date**
  Datatype: Object
  Description: Represents the date when bike-sharing data was recorded.
  Example: '30/11/2018'
  Potential Insights: Understanding temporal patterns and trends in bike-sharing demand over different days,       
  months, and seasons.

**Name: Rented Bike Count**
  Datatype: Int64
  Description: Indicates the count of rented bikes at a specific hour.
  Example: 150
  Potential Insights: Analyzing peak hours and low-activity periods for bike rentals.

**Name: Hour**
  Datatype: Int64
  Description: Denotes the hour of the day when the bike-sharing data was recorded.
  Example: 14
  Potential Insights: Identifying patterns in bike rental demand based on specific hours of the day.

**Name: Temperature(°C)**
  Datatype: Float64
  Description: Measures the temperature in degrees Celsius at the time of recording.
  Example: 22.5
  Potential Insights: Exploring the correlation between temperature and bike rental patterns.

**Name: Humidity(%)**
  Datatype: Int64
  Description: Represents the percentage of humidity at the time of recording.
  Example: 65
  Potential Insights: Investigating how humidity levels impact bike-sharing preferences.
  
**Name: Wind speed (m/s)**
  Datatype: Float64
  Description: Measures the wind speed in meters per second at the time of recording.
  Example: 3.2
  Potential Insights: Assessing the influence of wind speed on bike-sharing activity.

**Name: Visibility (10m)**
  Datatype: Int64
  Description: Represents the visibility in meters at the time of recording.
  Example: 1000
  Potential Insights: Understanding how visibility conditions relate to bike rental demand.

**Name: Dew point temperature(°C)**
  Datatype: Float64
  Description: Represents the dew point temperature in degrees Celsius at the time of recording.
  Example: 18.7
  Potential Insights: Exploring the impact of dew point temperature on bike-sharing behavior.

**Name: Solar Radiation (MJ/m2)**
  Datatype: Float64
  Description: Measures the solar radiation in megajoules per square meter at the time of recording.
  Example: 4.5
  Potential Insights: Investigating the relationship between solar radiation and bike rental patterns.

**Name: Rainfall(mm)**
  Datatype: Float64
  Description: Represents the amount of rainfall in millimeters at the time of recording.
  Example: 0.8
  Potential Insights: Analyzing how rainfall affects bike-sharing demand.
  
**Name: Snowfall (cm)**
  Datatype: Float64
  Description: Represents the amount of snowfall in centimeters at the time of recording.
  Example: 0.0
  Potential Insights: Understanding the impact of snowfall on bike rental activity.
  
**Name: Seasons**
  Datatype: Object
  Description: Represents the season during which the bike-sharing data was recorded.
  Example: 'Spring'
  Potential Insights: Analyzing seasonal variations in bike-sharing demand.
  
**Name: Holiday**
  Datatype: Object
  Description: Indicates whether the day is a holiday or not.
  Example: 'Yes'
  Potential Insights: Exploring the impact of holidays on bike rental behavior.

**Name: Functioning Day**
  Datatype: Object
  Description: Indicates whether the bike-sharing system is functioning on the recorded day.
  Example: 'Yes'
  Potential Insights: Assessing the overall functioning and operational status of the bike-sharing system.
  

**Main Libraries to be Used:**

Pandas for data manipulation, aggregation
Matplotlib and Seaborn for visualisation and behaviour with respect to the target variable
NumPy for computationally efficient operations
Scikit Learn for model training, model optimization, and metrics calculation
