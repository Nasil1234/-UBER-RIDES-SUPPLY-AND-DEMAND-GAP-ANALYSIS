# -UBER-RIDES-SUPPLY-AND-DEMAND-GAP-ANALYSIS
![image](https://github.com/Nasil1234/-UBER-RIDES-SUPPLY-AND-DEMAND-GAP-ANALYSIS/assets/122611712/ac68bb79-9369-4d46-8e3c-70010d82dff7)
Aim:

The Uber Supply and Demand Gap Analysis involve creating a dashboard that provides a comprehensive overview of supply and demand trends across the entire Uber network. This dataset include data on the number of drivers, pickup points, trip status, request and drop time. The dataset downloaded from Kaggle. The objective is to identify and analyse the problems in Supply-Demand of Uber trips from City to Airport and vice-versa across various hours of the day and find out possible solutions to address the problem.

Introduction:

Uber is a ride-hailing technology platform that has become a popular and convenient way to get around in many cities all over the world. With its prevalence, Uber has created a unique opportunity to analyse the supply and demand of the platform. This analysis can be used to identify potential gaps in the market and develop strategies to improve the efficiency of Uber’s services.

Uber provides its services through mobile application. The current dataset taken has the details for five days in the month of July of 2016. We will use dataset from the Uber to create visualizations and analyse the data which is given for five days in the month of July of 2016. The main objective of this project is to analyse the dataset and give recommendations based on our findings.

Problem Statement:

In this project, we find out the performance of the Uber, how many request id is placed from the pickup point of the Airport and city, how many Drivers are present, how many trips are completed, and how many trips are cancelled also find out the availability/unavailability of the cab.

Methodology:

The dataset contains information for the period 11/July/2016 to 15/July/2016.

Data Exploration:

Data exploration is the first step of data analysis and it is used to explore and visualized data to take any necessary actions. Based on our understanding of the data we can go with the appropriate data cleaning.

Data Importing:

To Import the data into Power BI, Let’s start with the Get Data option under the home tab. As this is a CSV file, select the Text/CSV option from the drop-down list and the select the file named. After selecting the file, data will be displayed Click on Load and save data.

Data Cleaning:

After importing there are 6745 rows and 6 columns. We need to clean the data with the help of Power Query Editor.

To open the Power Query Editor by clicking on Transform Data under the Home tab and go to Power Query Editor.

In Power Query Editor, go to the View tab, enable Column Distribution, Column Quality and Column Profile. It will help you to find out missing values, any data errors, any data type mismatch, any outliers.

Data Visualization:

I have used Power BI tool to visualize the data available to gain meaningful insights and better understand the dataset. I have used different visualizations like bar graphs, pie chart, donut chart which are available in the tool.

Analysis:

The dataset contains the following columns

Request id: A unique identifier of the request
Time of request: The date and time at which the customer made the trip request
Drop-off time: The drop-off date and time, in case the trip was completed
Pick-up point: The point from which the request was made either airport or city
Driver id: The unique identification number of the driver
Status of the request: The final status of the trip, that can be either completed, cancelled by the driver or no cars available
There are total of 6745 ride requests are come from the customers from the uber request data.


From the above graph we can get the idea about the total number of requests and their status. In there is no car available from airport to city. Most of the cancellation was happened in the city. Also comparatively trips completion is little higher in the city.

We have made slots like:

00 to 12.00 — Morning
12 to 16.00 — Evening
16 to 24.00 — Night

Which will give the idea about the demand and supply in the uber request. From the Demand (Trip Completed) is lower than the supply (Except Trip Completed in the status).

Insights:

We observed that in the Peak Morning Slot where the demand for City to Airport trips are high, there are maximum number of trip cancellations leading to great Gap in the Demand & Supply.
Out of the Demand or Total Requests of 2103, the Supply or Trips Completed were only 854, with high Gap of 1249.
This is because the trip to Airport from the City usually takes a longer time. Once the driver is in the Airport, he will have a longer idle time depending on the on the flight’s patterns. In the mornings, a lot of flights usually leave the city and less flights arrive. Also, it doesn’t make any economic sense to come back empty from the Airport to the City.
All these factors lead to high cancellation rate for trips from City to Airport.
We observed that in the Peak Evening Slot where the demand for Airport to City trips are high, there are maximum number of “No Cars Available” leading to great Gap in the Demand & Supply.
Out of the Demand or Total Requests of 2342, the Supply or Trips Completed were only 784, with high Gap of 1558.
This is because by the night, a lot of flights including the international ones start arriving at the airport. This creates a high demand for the cars. Also, the Uber driver partners start retiring for the day as the dawn proceeds leading to a high non availability of the cars.
These factors lead to high “No Cars Available” issue for trips from Airport to City.

Recommendations:

By increasing the count of the cabs can resolve this gap
By given rewards to the customer takes the trip on the peak time can avoid the cancellations of the trip.
Incentivize to the drivers who takes trip from Airport to City in the night so that more drivers from the city reach the Airport thus increasing the availability of the cars.

Conclusion:

The Uber supply and demand gap is an ongoing problem that needs to be addressed in order to ensure that the company continues to be successful. Uber has already taken steps to increase the number of drivers in certain areas, as well as to better incentivize drivers with higher fares. However, the gap is unlikely to be closed completely, and Uber will need to continue to develop strategies to bridge the gap between supply and demand. Additionally, Uber will need to continue to monitor and adjust its pricing model to ensure that riders and drivers both receive fair and equitable compensation. Finally, Uber should also focus on improving the overall user experience in order to ensure that riders will continue to choose them as their preferred ride-sharing service.
