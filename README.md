# World_Weather_Analysis

# Overview:

In this analysis, we generated 2000 random latitudes and longitudes. Then we retrieved nearest cities with API call. The purpose of this analysis is to determine weather patterns around the world to provide travellers insights to plan their vacation.


# Weather Database

In this analysis, we generated 2000 random latitudes and longitudes and retrieved all cities nearby. Then using Openweathermap and weather API key we found the following for each city: 

Latitude and longitude,
Maximum temperature,
Percent humidity,
Percent cloudiness,
Wind speed and 
Weather description (for example, clouds, fog, light rain, clear sky)


<img width="571" alt="DataFrame" src="https://user-images.githubusercontent.com/86980240/136595988-a1883f6a-e49a-4488-bd6f-19f8fa2cdb16.png">


# Vacation Search

In this analysis, we retrived our weather dataframe and filtered it with min temp as 75 F and max temp as 90 as preferred cities.

<img width="608" alt="Preferred_cities" src="https://user-images.githubusercontent.com/86980240/136667035-af791e87-bc69-42c7-875e-9f9d4970e9b9.png">


Then after finding cities, we serached for hotels by setting up parameters. Again using google maps API we retrieved all hotels according to our parameters.

<img width="449" alt="Empty_hotels" src="https://user-images.githubusercontent.com/86980240/136667049-de08a344-2f0f-4944-a1a7-02e3f7c132e0.png">

<img width="566" alt="Hotel_names" src="https://user-images.githubusercontent.com/86980240/136667053-fb5320ac-198a-4ad1-82a8-5c576096aa31.png">


Using "info_box_template", we added City, Country, Current Weather and Max Temp for cities. With Gmaps extension, we displayed map with adding heat layers and markers that shows template contents.

<img width="670" alt="WeatherPy_Vacation_Map_1" src="https://user-images.githubusercontent.com/86980240/136667062-d4c829ac-4a41-44e8-8004-e74f766e6a86.png">


<img width="832" alt="WeatherPy_Vacation_Map" src="https://user-images.githubusercontent.com/86980240/136667070-e9f1ac57-8e85-4a22-85d0-699292e4f1c5.png">


# Vacation Itinenary

In this analysis, we retrieved above WeatherPy Vacation CSV file that contains our preferred cities and hotels in those cities. From that dataframe, we selected 4 cities in a particular country with start to end points and a few stopovers in between, retrieved their lat and long details. Using gmaps, we displayed those 4 cities and their connecting routes as we set "Driving", "Bicycling" or "Walking" as travel modes along with weather details, temparatures, hotels etc. We created a dataframe of those 4 cities. 

<img width="624" alt="Vacation_itenary" src="https://user-images.githubusercontent.com/86980240/136667119-fb112183-c414-439e-aa1e-557c24b9a7a5.png">


Again, using "info_box_template", we added City, Country, Current Weather and Max Temp for cities. With Gmaps extension, we displayed map with adding heat layers and markers that shows template contents.

<img width="458" alt="WeatherPy_Travel_Map" src="https://user-images.githubusercontent.com/86980240/136667084-d51b4777-d5be-4bbf-8daa-47688835de31.png">

<img width="473" alt="WeatherPy_Travel_Map_Markers" src="https://user-images.githubusercontent.com/86980240/136667095-496be809-e2da-40b0-9978-33b284fd0af1.png">

