## Project Title: To predict the sales of weather sensitive products of Walmart during major weather events

## Project No: 52

Walmart has provided us with a dataset which contains sales data for 111 products whose sales may get affected by the weather. These 111 products are sold in stores at 45 different locations which are covered by 20 weather stations. Considering data is provided on a daily basis and our main objective is to predict sales of stores in a day factorizing the weather on that particular day.

Dataset : https://www.kaggle.com/c/walmart-recruiting-sales-in-stormy-weather/data

The data description of all the attributes in our dataset is described as follows:
<li>Key.CSV : store_nbr, station_nbr</li>
Weather.CSV: station_nbr, date, tmax, tmin, tavg, depart, dewpoint, Wetbulb-heat, heat, cool, sunrise, sunset, codesum, snowfall, preciptotal, stnpressure, sealevel, resultspeed, resultdir, avgspeed
‘noaa_weather_qclcd_documentation.pdf’ used for the definition of the weather data column.
Train.CSV: date, station_nbr, item_nbr, units
Test.CSV: date, station_nbr, item_nbr, units
sampleSubmission.CSV: id, units


