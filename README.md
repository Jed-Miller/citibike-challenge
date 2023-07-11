# citibike-challenge

<p align="center">
  <img src="./Images/citi_bike_image.png"/>
</p>

## Overview

Congratulations on your new job! As the new lead analyst for the New York Citi BikeLinks to an external site. You are now responsible for overseeing the largest bike-sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the Citi Bike DataLinks to an external site.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so your first task on the job is to build a set of data reports to provide the answers.

## Data Collection

In a jupyter notebook, I pulled the different citibike csv files into dataframes and then concatenated them to each other. All of my files realte to Jersey City and not New York City.

![concatenation](./Images/concatenation.png "concatentaion of datasets")

![dat_info](./Images/dataset_info.png "Dataset info")

Next, I added a column to the dataset to get the distance traveled for each bike ride.

![distance_column](./Images/distance_column.png "diatnce column")

After creating this final column, I read the dataframe into a csv to use in Tableau.

## Data Visualization

### Ride Totals for Members vs. Casual

![total_rides](./Images/ride_numbers.png)

The first dashobard illustrates how Citibike largely services a membership-based clientele. with members using the bikes 3x the amount that casual clients use the bikes. Not surprisingly, the highest usage of bikes occur during commute times.

### Top 25 Start and End Stations

![start_end](./Images/start_end.png)

Analyzing the most popular start and end stations for both classic and e-bikes, Citibike would be wise to make sure that the most popular stations have the resources they need because there is direct overlap between the most popular starting stations and ending stations, regardless of the type of bike used.

### Days and Times

![start_end](./Images/start_end.png)








