# Python API Weather Challenge
# Background
Two API providers (OpenWeatherMap and Geoapify) were used as relevant source directories for over 500 cities within specific coordinates to generate real time weather data analysis. Two specific files (WeatherPy.ipynb and VacationPy.ipynb) were used on the Jupyter platform as the foundation for codes used to implement gathering and scrutinizing the data presented. Scipy and linregress libraries helped with importing in statistical computation and generating a linear regression line for data points. Citipy helped generate an accurate list of cities with specific coordinates while hvplot was used as an interactive tool for data visualization. The geoviews python library helped import, explore and visualize all required data analysis geographically.

# Observations on WeatherPy
# Latitude vs. Temperature
![North_Hemi - Temp vs  LatLinear Regression](https://github.com/faceadversity/python-api-challenge/assets/137361966/78e7284f-c78c-4176-9944-b2c2ea14b35d)
There is a reasonably strong negative correlation between max temperature and latitude on the Northern Hemisphere with a correlation coefficient of roughly -0.83.
![South_Hemi - Temp vs  LatLinear Regression](https://github.com/faceadversity/python-api-challenge/assets/137361966/ac756768-355a-4761-b0c7-487390bb9be6)
There is a decently strong positive correlation between max temperature and latitude on the Southern Hemisphere with a correlation coefficient of roughly 0.67.

# Latitude vs. Humidity
![North_Hemi - Hum vs  LatLinear Regression](https://github.com/faceadversity/python-api-challenge/assets/137361966/bf048b73-f1d3-4388-9fe6-205ff4fb04a0)
There is a noticeably weak negative correlation between humidity and latitude on the Northern Hemisphere with a correlation coefficient of roughly -0.02.
![South_Hemi - Hum vs  LatLinear Regression](https://github.com/faceadversity/python-api-challenge/assets/137361966/d2232c51-45bb-4a15-9d29-7f861073288c)
There is a very slight positive correlation between humidity and latitude on the Southern Hemisphere with a correlation coefficient of roughly 0.14.

# Latitude vs. Cloudiness
![North_Hemi - Cloud vs  LatLinear Regression](https://github.com/faceadversity/python-api-challenge/assets/137361966/884ab6c8-a43e-4ad6-99ee-a8389a54b6e0)
There is an extremely slight positive correlation between cloudiness and latitude on the Northern Hemisphere with a correlation coefficient of roughly 0.07.
![South_Hemi - Cloud vs  LatLinear Regression](https://github.com/faceadversity/python-api-challenge/assets/137361966/19173cdb-0973-4f58-866b-f0a376f37923)
There is a noticeably weak negative correlation between cloudiness and latitude on the Southern Hemisphere with a correlation coefficient of roughly -0.01.

# Latitude vs. Wind Speed
![North_Hemi - WindSpeed vs  LatLinear Regression](https://github.com/faceadversity/python-api-challenge/assets/137361966/6a55e4fb-e97b-4083-ac90-f8a0c68d9930)
There is a very slight positive correlation between wind speed and latitude on the Northern Hemisphere with a correlation coefficient of roughly 0.26.
![South_Hemi - WindSpeed vs  LatLinear Regression](https://github.com/faceadversity/python-api-challenge/assets/137361966/19dcc997-4d75-4e00-b55c-c67b48c95f50)
There is a slight negative correlation between wind speed and latitude on the Southern Hemisphere with a correlation coefficient of roughly -0.28.

# Observations on VacationPy
A map was created that displayed a point for every city in the city_data_df DataFrame. The size of the point is tied into the humidity in each city. The map could not display as needed in the VacationPy.ipynb script so I have decided to document as needed below for analysis:
![city_humidity](https://github.com/faceadversity/python-api-challenge/assets/137361966/5d117b63-7adc-4a5f-8c50-3401975de525)

I was directed to add the hotel name and the country as additional information in the hover message for each city in the map. The map could not display as needed in the VacationPy.ipynb script so I have decided to document as needed below for analysis:
![hotel_hover](https://github.com/faceadversity/python-api-challenge/assets/137361966/04b07e4a-952f-42bc-abf6-026e74cbda5d)



