# World-Weather-Analysis-Python-APIs

This project focuses on the usage of Google API and OpenWeather API to acquire data. After the data retreival process it is filtered by user based critera.

1. Firstly, the [Weather_Database.ipynb](./Weather_Database/Weather_Database.ipynb) jupyter notebook generated [WeatherPy_Database.csv](./Weather_Database/Weather_Database.csv) by using OpenWeather API. This outputs weather in cities close to 2000 number of random latitudes and longitudes generated across the globe.
2. Secondly, the [Vacation_Search.ipynb](./Vacation_Search/Vacation_Search.ipynb) jupyter notebook generated [WeatherPy_vacation.csv](./Vacation_Search/WeatherPy_vacation.csv) by using Pandas to filter the user criteria that the user might be likely to visit based off temperature ranges. Applying this filter to our Pandas dataframe, we use Google API to help us generate a list of hotels based on the user's temperature ranges.
3. Finally, based on the previous filteration of the data, we can now allow the user to select upto `four` cities to create a [Vacation_Itinerary.ipynb](./Vacation_Itinerary/Vacation_Itinerary.ipynb).

Here is an example of the above:

<p align="center">
<img src="https://github.com/mubeenkh4u/RBC-Module-6-WeatherPy-with-Python-APIs/blob/main/Vacation_Search/WeatherPy_vacation_map.png"/>
<img src="https://github.com/mubeenkh4u/RBC-Module-6-WeatherPy-with-Python-APIs/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png"/>
<img src="https://github.com/mubeenkh4u/RBC-Module-6-WeatherPy-with-Python-APIs/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png"/>
</p>

## Additional Resources:

During the course of the project, whilst using the Google API and OpenWeather API and the generated [cities.csv](./weather_data/cities.csv), heat maps were also generated based off:

1. [City Latitude vs. Max Temeprature](./weather_data/Fig1.png)
2. [City Latitude vs. Humidity](./weather_data/Fig2.png)
3. [City Latitude vs. Cloudiness](./weather_data/Fig3.png)
4. [City Latitude vs. Windspeed](./weather_data/Fig4.png)
