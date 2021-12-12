# Surfs_Up
## Analyzing Weather Data using SQL Lite &amp; Flask

## Overview of the statistical analysis

The purpose of this project is to analyze temperuature data for the months of June and December in Oahu within the past few years. This will help us determine if a surf and ice cream business is a viable investment and sustainable enough to operate year round. In this analysis, we've highlighted a few components within our exploratory climate analysis - the weather by date, the precipitation by date, and even gathered the minimum, average, and maximum tempartures within a range of dates. Finally, we displayed our data in a webpage by using Flask. Users can review our findings if provided with a link created with Flask.

## Results

### June
By pulling weather data for the months of June and December, we were able to create a DataFrame from the list of temperatures for both months. For June, we captured the following in Oahu:

- Unique Dates/Temps - **1700**
- Average Temperature - **74.95° F**
- Maxiumum temperature - **85.00° F**
- Miinimum Temperature - **64.00° F**

**List of Temperatures for June in Oahu**          

![image](https://user-images.githubusercontent.com/89496798/145729642-8c69c61d-e8a6-4966-a233-867a6730244a.png)

**Statistcal Analysis for the Temperature in June**         

![image](https://user-images.githubusercontent.com/89496798/145729523-f45ca655-421e-4a4b-9668-53f86eca39ab.png)

### December
For December, we captured the following in Oahu:

- Unique Dates/Temps - **1517**
- Average Temperature - **71.04° F**
- Maxiumum temperature - **83.00° F**
- Miinimum Temperature - **56.00° F**

**List of Temperatures for December in Oahu**               

![image](https://user-images.githubusercontent.com/89496798/145729659-b292c023-03e5-42f0-92c9-df27b01f5cd1.png)

**Statistical Analysis for the Temperature in December**                  

![image](https://user-images.githubusercontent.com/89496798/145729622-6acb4214-db76-461d-b135-2cff87e0e319.png)

## Summary
With maximum temperatures below 90 and minimum temperatures consistently above 55 degrees, our data analysis may suggest the highest performing months for a surf and ice cream business could possibly be in the summer time. One thing we should definitely take into account is the amount of precipitation in these months as well. We can simply do so by refactoring our code to pull precipitation data rather than temperature data for these same dates. In doing so, we can highlight the average precipitation along with the maximum precipitation for these months:

### June Precipitation

![image](https://user-images.githubusercontent.com/89496798/145730132-627ca25f-48d1-4704-b8ee-fa77d32c9bdb.png)

### December Precipitation

![image](https://user-images.githubusercontent.com/89496798/145730143-40188d25-9c06-45ad-b55d-c8cf0073217c.png)

With relatively low rainfall and and consistently warm temperature in Oahu, an investor can have confidence a surf and ice cream shop will perform well year round. If an investor would like to take a closer look at precipitation data for specific dates, they may do so if we provide them with the following link:

![image](https://user-images.githubusercontent.com/89496798/145730781-54735c02-14eb-4607-b568-f5597c831d30.png)

The data will display as follows:

![image](https://user-images.githubusercontent.com/89496798/145730790-7b0430d6-ef34-468c-97a6-36d421fe29a6.png)

