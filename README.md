# tetuon

INTRODUCTION
Dataset link:  https://archive.ics.uci.edu/ml/datasets/Power+consumption+of+Tetouan+city 
We selected this dataset because we are going to examine the energy consumption of three different distribution networks at this tourist destination. There are 52417 rows and 9 columns in the dataset. The dataset's primary characteristics are multivariate and time series. Integer and real numbers make up the columns. The attributes that are present in the dataset are:
1. Date Time: Data has been taken using an Hourly base.
2. Temperature: Centigrade Degrees (°C)
3. Humidity: The range of Humidity is 0-90.
.4 Wind Speed: The range of wind is 0-6.5 range.
5. General Diffuse Flows: The maximum range of  General Diffuse Flows is 0 to 500 and the minimum range is 0.0005 to 0.0110 ( Lowest and highest fluid)
6. Diffuse Flows
7. Zone 1 Power Consumption: Zone 1 Energy Usage Trend
8. Zone 2 Power Consumption: Zone 2 Energy Usage Trend
9. Zone 3 Power Consumption: Zone 3 Energy Usage Trend


The goal of these reports is to predict power consumption every 10 Min/hour. Power consumption is a very important factor in Today’s life especially the Tourist Cities as governments have to create Pre-planned for the energy crisis. The production and consumption power is the first step of this system. Using the following equation we’re going to predict and forecast our Model : 
production−(consumption+ELT)=v 
ELT stated ‘Energy Lost’ and v represents real consumption energy. In this analysis, we have to create a model where v should be positive and near 0, which means it should be created equally and used equally.


