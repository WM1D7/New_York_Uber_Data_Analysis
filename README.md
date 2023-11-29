# New_York_Uber_Data_Analysis


## " New York City Uber Insights "






 <img src="https://miro.medium.com/v2/resize:fit:747/1*YU7bBSY3j5CZqj6VqsqrAA.png" width="400" height="200">




## Project Description :

Explore the dynamic world of Uber pickups in the bustling streets of New York City with our project, **"NYC Uber Insights."**     
This data analysis endeavor aims to unravel the patterns, trends, and insights hidden within the New York Uber dataset.    
From data retrieval to preparation, and from hourly rush analysis to pinpointing locations of peak activity, our project delves into various aspects of Uber pickups to extract meaningful information.


## Tech Stack Used

 <img src="https://miro.medium.com/v2/resize:fit:1400/1*RzxZF0mmXAsMLrIzAWYDSg.png" width="250" height="150">

## Libraries Used

 <img src="https://cdn.sanity.io/images/1xvnv7n3/production/5056f47776a6b5811d4e1cdf3dd6587dbe6e75b4-1917x596.png?w=1917&h=596&q=75&fit=max&auto=format" width="600" height="200">

## 🛠 Skills Demonstrated :

-  Data Loading

-  Exploratory Data Analysis (EDA)

-  Data Pre-processing and Cleaning

-  Data Manipulation 

-  Data Grouping and Aggregation

-  Data Visualization

## Dataset : 

-  [My kaggle Dataset](https://www.kaggle.com/datasets/wm1deep7/new-york-uber-dataset)
 
  
##  Objectives :

- Data Retrieval and Preliminary Analysis:
  
1. Read and understand the Uber dataset for New York City.

- Data Pre-processing and Cleaning:

2. Perform thorough data pre-processing and cleaning to ensure the accuracy and reliability of subsequent analyses.

- Monthly Pickup Peaks:

3. Identify the month with the highest number of Uber pickups in New York City.

- Hourly Rush Analysis:

4. Analyze the hourly rush in New York City on all days, uncovering patterns and trends throughout the day.

- Active Vehicle Analysis:

5. Determine the base_number associated with the most significant number of active vehicles.

- Comprehensive Data Collection:

6. Collect and organize the entire dataset to facilitate in-depth data analysis.

- Location-Based Rush Analysis:

7. Investigate and visualize the locations in New York City where Uber pickups experience the highest demand.

- Hourly and Weekly Patterns:

8. Examine rush patterns on an hourly and weekday basis, performing pair-wise analysis to uncover correlations and insights.



## Approach :

**1. Data Retrieval and Preliminary Analysis:**

Used jupyter notebook to conduct a preliminary analysis to understand the structure of the dataset, the types of variables present, and any initial patterns or anomalies.      
Python  programming languages and Python libraries  (packages such as OS ) to read and load the dataset.     




**2. Data Pre-processing and Cleaning:**

Identify and handle missing or null values in the dataset.     
Standardize data formats and units for consistency.    
Remove duplicates and irrelevant columns.    
Convert date column to a suitable format for time-based analysis.    


**3. Monthly Pickup Peaks:**

Extract the month from the date data.    
Aggregate the data to find the total pickups for each month.    
Identify the month with the maximum number of pickups.     

**Deliverables 1:**

 <img src="https://github.com/WM1D7/New_York_Uber_Data_Analysis/blob/main/Uber%20Images/Month.png"  width="600" height="400">

**Conclusion:** 

Here we can see , June seems to have max Uber Pickups. 

**Deliverables 2 :**

<img src="https://github.com/WM1D7/New_York_Uber_Data_Analysis/blob/main/Uber%20Images/Weekdays.png"  width="1000" height="400">


**Conclusion:**

On Saturday & Friday, we are getting more Uber pickups in each month.        
It seems that New Yorkers used to go for  shopping , Malls , fun activities alot on these days.       


**4. Hourly Rush Analysis:**

Extract the hour from the timestamp data.     
Aggregate the data on an hourly basis to determine pickup trends throughout the day.     
Visualize the results using graphs or charts to highlight peak hours.      

**Deliverables :**
<img src="https://github.com/WM1D7/New_York_Uber_Data_Analysis/blob/main/Uber%20Images/Hour%20Rush.png"  width="1000" height="500">


**Conclusion:**

It's interesting to see that Saturday and Sunday exhibit similar demand throughout the late night/morning/afternoon, 
but it exhibits opposite trends during the evening.       
In the evening, Saturday pickups continue to increase throughout the evening,but Sunday pickups takes a downward turn after evening.       

We can see that there the weekdays that has the most demand during the late evening is Friday and Saturday,        
which is expected, but what strikes me is that Thursday nights also exhibits very similar trends as Friday and Saturday nights.        

It seems like New Yorkers are starting their 'weekends' on Thursday nights.       


**5. Active Vehicle Analysis:**

Group the data by base_number.     
Calculate the count of active vehicles associated with each base_number.     
Identify the base_number with the highest count of active vehicles.     

**Deliverables1:**  Boxplot to see 5-summary stats of the data. (  minimum, first quartile, median, third quartile, and maximum )

<img src="https://github.com/WM1D7/New_York_Uber_Data_Analysis/blob/main/Uber%20Images/Max%20Number%20Base.png"  width="700" height="400">

**Conclusion:**
Here we can see each base number  with active vehicles range and compare it.    
Base Number B02764 has most number of Active Vehicles.       

**Deliverables 2:**  Violinplot to see  distribution and 5-summary stats of the data.     

<img src="https://github.com/WM1D7/New_York_Uber_Data_Analysis/blob/main/Uber%20Images/distribution%20MNB.png"  width="700" height="400">

**6. Comprehensive Data Collection:**

Ensure that all relevant data is collected and organized for further analysis.    
Save the cleaned and processed dataset for future reference.    
remove unnecessary file.     


**7. Location-Based Rush Analysis:**

Utilize geospatial data to pinpoint pickup locations.  
Lat : The latitude of the Uber pickup  
Lon : The longitude of the Uber pickup   
Group the data by location to identify areas with the highest demand.    
Visualize the results on a map for better insights.
using Folium Python library that helps you create several types of  maps.

**Deliverables :**
Zoom Out View 

<img src="https://github.com/WM1D7/New_York_Uber_Data_Analysis/blob/main/Uber%20Images/Location%20Rush.png"  width="700" height="400">

Zoom In View 

<img src="https://github.com/WM1D7/New_York_Uber_Data_Analysis/blob/main/Uber%20Images/zoom%20in.png"  width="700" height="400">



**Conclusion:**
By Zoom In / Out we can see which locations of New York City we are getting rush.

**8. Hourly and Weekly Patterns:**

Further refine the dataset to include hourly and weekday information.     
Perform pair-wise analysis to explore relationships between hour, weekday, and pickup counts.    
Visualize the patterns to gain a deeper understanding of hourly and weekly trends.     

**Deliverables :**
<img src="https://github.com/WM1D7/New_York_Uber_Data_Analysis/blob/main/Uber%20Images/rush%20on%20Hour%20and%20Weekday.png"  width="1000" height="700">

**Conclusion:**
 Here we can easily Perform Pair wise Analysis and Examine  rush on Hour and Weekday by color gradient.

