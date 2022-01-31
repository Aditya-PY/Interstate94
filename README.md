# Exploratory analysis of heavy traffic indicators on the I-94 interstate highway using data visualisation techniques.

Interstate 94 (I-94) is an east–west Interstate Highway connecting the Great Lakes and northern Great Plains regions of the United States.

This project aims to analyse the westbound traffic on the Interstate highway. Our primary goal is to determine a few indicators of heavy traffic on the highway through visualisation techniques using pandas and matplotlib.

Information about the coloumns are below:

|Column Name| Type|Description|
|-----------|-----------|----------|
|holiday| Categorical |US National holidays plus regional holiday, Minnesota State Fair|
|temp| Numeric |Average temp in kelvin|
|rain_1h| Numeric |Amount in mm of rain that occurred in the hour|
|snow_1h| Numeric |Amount in mm of snow that occurred in the hour|
|clouds_all| Numeric |Percentage of cloud cover|
|weather_main| Categorical |Short textual description of the current weather|
|weather_description| Categorical |Longer textual description of the current weather|
|date_time| DateTime |Hour of the data collected in local CST time|
|traffic_volume| Numeric |Hourly I-94 ATR 301 reported westbound traffic volume|

The original dataset was downloaded from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Metro+Interstate+Traffic+Volume). 
