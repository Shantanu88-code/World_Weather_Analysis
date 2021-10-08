# World_Weather_Analysis

# Overview:

In this analysis, we generated 2000 random latitudes and longitudes. Then we retrieved nearest cities with API call. The purpose of this analysis is to determine weather patterns around the world to provide travellers insights to plan their vacation.


# Weather Database

In this analysis, we generated 2000 random latitudes and longitudes and retrieved all cities nearby. Then using Openweathermap and weather API key we found the following for each city: 

Latitude and longitude
Maximum temperature
Percent humidity
Percent cloudiness
Wind speed
Weather description (for example, clouds, fog, light rain, clear sky)


<img width="571" alt="DataFrame" src="https://user-images.githubusercontent.com/86980240/136595988-a1883f6a-e49a-4488-bd6f-19f8fa2cdb16.png">


# Vacation Search

In this analysis, we retrived our weather dataframe and filtered it with min temp as 75 F and max temp as 90 as preferred cities.

<img width="601" alt="Filtered_df" src="https://user-images.githubusercontent.com/86980240/136596248-59735847-d67b-4666-abd2-8d9e272b868c.png">


Then after finding cities, we serached for hotels by setting up parameters. Again using google maps API we retrieved all hotels according to our parameters.

<img width="559" alt="Hotel_names" src="https://user-images.githubusercontent.com/86980240/136596782-aad5fd1d-5599-4773-801b-ec060972d0aa.png">


Using "info_box_template", we added City, Country, Current Weather and Max Temp for cities. With Gmaps extension, we displayed map with adding heat layers and markers that shows template contents.

<img width="720" alt="WeatherPy_Vacation_Map" src="https://user-images.githubusercontent.com/86980240/136596898-6756affd-b250-4dae-837c-4a376cfbfdc4.png">


<img width="723" alt="WeatherPy_Vacation_Map_1" src="https://user-images.githubusercontent.com/86980240/136596929-93e1190c-b25c-49f4-8c15-a8135b5d0c31.png">


# Vacation Itenary

In this analysis, we retrieved above WeatherPy Vacation CSV file that contains our preferred cities and hotels in those cities. From that dataframe, we selected 4 cities in a particular country with start to end points and a few stopovers in between, retrieved their lat and long details. Using gmaps, we displayed those 4 cities and their connecting routes as we set "Driving", "Bicycling" or "Walking" as travel modes. We created a dataframe of those 4 cities. 

<img width="536" alt="4_cities" src="https://user-images.githubusercontent.com/86980240/136597983-b0f2b593-08d3-438e-b262-a434178fa3d4.png">


Again, using "info_box_template", we added City, Country, Current Weather and Max Temp for cities. With Gmaps extension, we displayed map with adding heat layers and markers that shows template contents.

<img width="727" alt="WeatherPy_Travel_Map" src="https://user-images.githubusercontent.com/86980240/136598030-f5fb2e2b-6d37-4e60-9421-59444eb9bb4d.png">

<img width="376" alt="WeatherPy_Travel_Map_Markers" src="https://user-images.githubusercontent.com/86980240/136598053-a173023d-dfee-4b02-969c-54f59706b073.png">

