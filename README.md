# Ride Share Analysis

## Overview of Project:
We are tasked with performing data analysis and visualization for the ride sharing-app company “Pyber”.

### Purpose:
Using Jupyter Notebook and matplotlib library, the CEO V. Isualize has asked us to analyze the rideshare data from January to early May of 2019, in order to provided charts and graphs that will help the company improve its ride share affordability and access. 

## Results:
Before any data analysis or visualization could begin, we needed to load, read, and merge the data files which were stored in .CSV format. See below image of jupyter notebook code used to perform this task.
![](https://github.com/Apollo619/PyBer_Analysis/blob/main/Resources/JN_Code_Read_Merge.PNG)

-	Once this was accomplished, we were able to perform calculations based on the criteria requested by V. Isualize.
	-	These criteria’s include *“Total Rides”*, *“Total Drivers”*, *“Total Fares”*, *“Average Fare per Ride and Driver”*, and *“Total Fare by City Type”*. See below image for scripted used to perform calculations. 
![](https://github.com/Apollo619/PyBer_Analysis/blob/main/Resources/JN_Code.PNG)

-	After calculations were performed the CEO asked us to generate a Summary DataFrame based on the mentioned criteria’s above. See below image for Summary DataFrame.
![](https://github.com/Apollo619/PyBer_Analysis/blob/main/Resources/JN_Code_Results.PNG)

-	Next, a line chart displaying the Summary DataFrame was created to visually aid in the presentation of the data. See below image of line chart
![](https://github.com/Apollo619/PyBer_Analysis/blob/main/Analysis/PyBer_Fare_summary.png) 

## Summary:
Upon initial results when looking at the Summary DataFrame line graph provided above. Pyber might think the company is wasting its time providing drivers in *Rural* areas as the number of rides and drivers are on average 3 to 6 times lower than *Urban* or *Suburban* areas. See box plots below. 
![](https://github.com/Apollo619/PyBer_Analysis/blob/main/Analysis/Fig2.png) ![](https://github.com/Apollo619/PyBer_Analysis/blob/main/Analysis/Fig4.png)

1.	Looking at the *”Average Fare per Ride”* column of the Summary DataFrame, you can see that *Rural* areas on average have larger fares per ride than the other two city types. See image below

![](https://github.com/Apollo619/PyBer_Analysis/blob/main/Resources/JN_Code_Results.PNG)

2.	The same came be said for drivers as the data from the Summary DataFrame (see above image) indicates an increase fare per driver value. 


3.	The *”Urban”* city type reveals an outliner for ride count data that might skew the data set (see below plot).
![](https://github.com/Apollo619/PyBer_Analysis/blob/main/Analysis/Fig3.png)

When looking that the overall data and plots it’s important for the company to keep these observations in mind when deciding how to improve affordability and access. 
