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

ANALYSIS


The goal of these reports is to predict power consumption every 10 Min/hour. Power consumption is a very important factor in Today’s life especially the Tourist Cities as governments have to create Pre-planned for the energy crisis. The production and consumption power is the first step of this system. Using the following equation we’re going to predict and forecast our Model :   production−(consumption+ELT)=v 
ELT stated ‘Energy Lost’ and v represents real consumption energy. In this analysis, we have to create a model where v should be positive and near 0, which means it should be created equally and used equally.
In figure 1, all the variables have been stated with respect to basic EDA.


Figure: 1
  

We can see that In figure 2, depicts the number of rows as 52415 and also we can see the basic analysis of the dataset and infer that there are no null values in the columns of the dataset.We can see that the type of the dataset is float and the DateTime column is an object. 

 
                                                             Figure:2


In figure 3, we can see that there are no null values present in the columns. Now, we check for the missing values and null values. Also, there were no null values present.

 Figure :3
As data is recorded Every 10 Minutes, we expand the data using hours, months, years, etc as we can see in the below figure 4.


                                                       Figure 4

In figure 5, We're trying to find the co-relation with each matrix as we can infer humidity, quarter, and month are negatively correlated with each other.

     Figure 5





In figure 6, we have displayed the pivot tables for the temperature , humidity, wind speed and general diffuse flows. 


           Figure 6
 
        



















EDA: Exploratory Data Analysis

We plotted histograms to understand the data. There were a total of 1 year of data has been captured. The medium of temperature is 25 degrees around.  It predicts that the humidity level is inclined ( 40-95) which is not good. Zone 1 power consumption usage is a lot rather than in zone 2 and zone 3.General diffuse flows stated how much production of energy has happened. Diffuse flow stated how much energy has been used.




                 Figure 7




We can infer that there are no missing and null values in the dataset and so we move ahead and start visualizing the dataset by creating charts so that we can infer more about the dataset and answer the business questions that we intend to.


In figure 8, we have displayed the barchart of the zone 1 power consumption  and we can infer that the power consumption was uneven and it decreased eventually.

 Figure 8

Figure 9 show’s the correlation trend  between Temperature and Humidity as Temperature and Humidity are inversely proportional to each other. It show’s from the figure as Temperature decreases humidity increases and vice versa.

 Figure 9

Figure 10, show’s the power consumption of zone 1, zone2, and zone 3. As seen from the following figure, zone 1 power consumption is skyrocketing which is around 35,000 Voltages per watt.

Figure 10

In figure 11, we have checked for the correlation of the columns of the dataset. We can infer humidity, quarter, and month are negatively correlated with each other.



