# Weather-Prediction

This project is to deal with a weather forecast problem. It is a binary classification problem to predict whether or not a location will get rain the next day.  We will use Kmeans, Hierarchical Agglomerative Clustering and Decision Trees.

Information about the dataset (Weather Forecast Training.csv):
- <b>Location:</b> The location name of the weather station
- <b>MinTemp:</b> The minimum temperature in degrees celsius
- <b>MaxTemp:</b> The maximum temperature in degrees celsius
- <b>Rainfall:</b> The amount of rainfall recorded for the day in mm
- <b>Evaporation:</b> The so-called Class A pan evaporation (mm) in the 24 hours to 9am
- <b>Sunshine: </b>The number of hours of bright sunshine in the day.
- <b>WindGustDir:</b> The direction of the strongest wind gust in the 24 hours to midnight
- <b>WindGustSpeed:</b> The speed (km/h) of the strongest wind gust in the 24 hours to midnight
- <b>WindDir:</b> Direction of the wind
- <b>WindSpeed:</b> Wind speed (km/hr) averaged over 10 minutes
- <b>Humidity:</b> Humidity (percent)
- <b>Pressure:</b> Atmospheric pressure (hpa) reduced to mean sea level
- <b>Cloud:</b> Fraction of sky obscured by cloud This is measured in “oktas”, which are a unit of eigths. It records how many eigths of the sky are obscured by cloud. A 0 measure indicates completely clear sky whilst an 8 indicates that it is completely overcast.
- <b>Temp:</b> Temperature (degrees C)
- <b>RainTodayBoolean:</b> 1 if precipitation (mm) in the 24 hours to 9am exceeds 1mm, otherwise 0
- <b>RainTomorrow:</b> The target variable. Did it rain tomorrow?
