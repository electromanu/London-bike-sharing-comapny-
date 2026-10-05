LONDON BIKE SHARING COMPANY 



This is an interactive dashboard where it is helps in the analyzing the problem the bike sharing company to get the key insights that how the company is doing and what measure they can take to grow even more higher.
Business Problem 
The company has collected two years of bike-sharing data. However, they don't clearly understand their customers' rental behaviour.
The company want to increase their bike rentals and understand what factors influence customer demand.
So The Main Goal Of The This Project Is To  Clean The Dataset And Derive The Business Problem The Company Is Facing 
Objective 
•	KPI – Total Bike Rentals: Measure the overall rental volume during the period. 
•	KPI – Average Rentals: Understand the typical rental demand per hour. 
•	Monthly Trend: Identify how bike rental demand changes across months and years. 
•	Yearly Growth: Measure the change in rental demand between years. 
•	Season Analysis: Determine which seasons generate the highest and lowest rental demand. 
•	Weather Analysis: Understand how different weather conditions are associated with rental demand. 
•	Holiday Analysis: Compare rental demand on holidays versus non-holidays
•	Weekend Analysis: Compare rental demand on weekdays versus weekends.

Dataset
Column 	Description 
timestamp	Date and time of rental
new_bike_shares	Number of bikes rented
t1	Actual temperature
t2	Feels-like temperature
hum	Humidity
wind_speed	Wind speed
weather_code	Weather condition
is_holiday	1 = Holiday
is_weekend	1 = Weekend
season	Season of the year
 







Data cleaning 
•	Checked for the null values.
•	Added a new column Month based on the time stamp.
•	Added the new column called weather based on the weather_code column. 
•	Added a new column called season based on the season_code column.
•	Checked for the inconsistent data in all columns.
 

Data analysis 
Business questions
How can London Bike Sharing improve bike availability and operations by understanding rental demand trends and the impact of time, seasons, weather, holidays, and weekends?
KPIs (key performance indicators)
•	Average_bike_shares
•	Total_bike_shares 

Dashboard 
KPI cards
•	Average_bike_shares
•	Total_bike_shares 
Visualization 
•	Sum of new_bike_shares by Month and Year
•	Sum of new_bike_shares by season
•	Average of new_bike_shares by is_holiday Average of new_bike_shares by is_holiday
•	Average_bike_shares by is_weekend
•	Average of new_bike_shares by weather

Filters 
•	Is_weekend
•	Is_holiday
•	Year 
 <img width="975" height="544" alt="image" src="https://github.com/user-attachments/assets/9fd0a56e-6b19-4d7a-8190-1dc518637152" />


Insights
•	Overall Rentals:
The business recorded around 20 million bike rentals, showing strong overall demand. 
•	Yearly Growth:
Bike rentals increased by 4% from 2015 to 2016, indicating modest business growth. 
•	Monthly Trend:
Rental demand follows a similar seasonal pattern each year, with some months consistently having higher demand. 
•	Season:
Summer has the highest rental demand, while winter has the lowest. 
•	Weather:
Clear weather is associated with higher bike rental demand, while poorer weather conditions show lower demand. 
•	Weekday vs Weekend:
Weekday rentals are higher than weekend rentals, suggesting stronger demand during weekdays. 
•	Holiday:
Non-holiday days have much higher total rentals than holidays, although this is partly because there are many more non-holiday days. 
•	2017:
2017 data is incomplete, so it should not be used for a full-year comparison with 2015 and 2016.

Tools 
SQL -> for cleaning the data 
Power bi -> creating visualization and getting meaning full insights 

Conclusion 
•	Increase bike availability during high-demand months. 
•	Keep more bikes available during the summer season. 
•	Expect lower demand during poor weather conditions. 
•	Maintain higher availability on weekdays. 
•	Reduce excess bike availability during winter. 
•	Use rental trends to plan bike distribution and improve operations. 
•	Focus resources on periods with consistently high demand
