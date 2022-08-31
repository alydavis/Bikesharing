# Bikesharing Analysis with CitiBike

## Overview
Citi Bike is the nation's largest bike share program, with 25,000 bikes and over 1,500 stations across Manhattan, Brooklyn, Queens, the Bronx, Jersey City and Hoboken. In this analysis, I analyzed Citi Bike trip history data from August 2019. I used Pandas to clean the "tripduration" column from an integer to a datetime data type. Then created a set of visualizations in a Tableau story to summarize my analysis.

## Process
First I cleaned the data in a Jupyter Notebook with the Pandas library. First I imported the .csv file and converted to a DataFrame. Using the df.dtypes function I learned the trip duration was measured in seconds, displayed as an integer. For a stronger analysis, I converted the datatype to a datetime format to get the time in hours and minutes. Rather than replace the original data, I added this new format to a new column in the data. I then exported the data as a .csv again for visualizations in Tableau. You can see the full process in this [Jupyter Notebook file](NYC_CitiBike_Challenge.ipynb).
I created visualizations in [Tableau Public](https://public.tableau.com/app/discover).

## Results

Results:

The final Tableau Story can be viewed [here](https://public.tableau.com/app/profile/alyssa.davis/viz/BikesharingChallenge_16618926814050/BikesharingChallenge).


Visualization 1: Customer Insights
![Customer_Insights](Images/01_Customer_Data.png)

Analysis
This first story is a combination of several worksheets in a dashboard showcasing the number of rides in August, the customer type breakdown, and customer gender demographics.


Visualization 2
Analysis

Visualization 3
Analysis

Visualization 4
Analysis

Visualization 5
Analysis

Visualization 6
Analysis

Visualization 7
Analysis

Visualization 8
Analysis

Visualization 9
Analysis

Visualization 10
Analysis

## Summary
- a high-level summary of the results 
- two additional visualizations are suggested for future analysis
- -- Looking at the CitiBike website - there's an option for a single "day pass" - would be interesting to track that in addition to customers and subscribers.

### Resources
Citibike [Data](https://ride.citibikenyc.com/system-data) - August 2019
Python version
Pandas version
Jupyter Notebook version
