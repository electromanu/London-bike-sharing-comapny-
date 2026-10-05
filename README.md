# 🚲 London Bike Sharing Analysis

## 📌 Project Overview

This project analyzes London bike-sharing data to understand how the company is performing and what factors influence bike rental demand.

The dashboard helps the company identify rental patterns based on time, season, weather, holidays, and weekends, so that better decisions can be made about bike availability and operations.

## 🎯 Business Problem

The company has collected bike-sharing data but does not clearly understand its customers' rental behavior.

The main goal of this project is to clean the dataset, analyze rental patterns, and identify the factors that influence bike rental demand.

## ❓ Business Question

**How can London Bike Sharing improve bike availability and operations by understanding rental demand trends and the impact of time, seasons, weather, holidays, and weekends?**

## 🎯 Objectives

- Measure the total number of bike rentals.
- Understand the average rental demand.
- Analyze rental trends across months and years.
- Measure yearly growth.
- Identify the seasons with the highest and lowest demand.
- Understand the impact of weather conditions on rentals.
- Compare rentals on holidays and non-holidays.
- Compare rentals on weekdays and weekends.

## 📊 Dataset

| Column | Description |
|---|---|
| `timestamp` | Date and time of rental |
| `new_bike_shares` | Number of bikes rented |
| `t1` | Actual temperature |
| `t2` | Feels-like temperature |
| `hum` | Humidity |
| `wind_speed` | Wind speed |
| `weather_code` | Weather condition |
| `is_holiday` | 1 = Holiday, 0 = Non-holiday |
| `is_weekend` | 1 = Weekend, 0 = Weekday |
| `season` | Season of the year |

## 🧹 Data Cleaning

- Checked for NULL values.
- Checked for inconsistent data.
- Created a `Month` column from the timestamp.
- Created a `Weather` column using the weather code.
- Created a `Season` column using the season code.

## 📈 KPIs

- **Total Bike Shares**
- **Average Bike Shares**
- **Yearly Growth**

## 📊 Dashboard

### Visualizations

- Bike shares by Month and Year
- Bike shares by Season
- Average bike shares by Holiday
- Average bike shares by Weekend
- Average bike shares by Weather

### Filters

- Year
- Is Weekend
- Is Holiday

  <img width="975" height="544" alt="image" src="https://github.com/user-attachments/assets/2fd8f1a4-9776-4bca-be17-46293ba7dbd7" />


## 💡 Key Insights

- The company recorded around **20 million bike rentals**, showing strong overall demand.
- Bike rentals increased by **4% from 2015 to 2016**, indicating modest business growth.
- Rental demand follows a **similar seasonal pattern across years**.
- **Summer** has the highest rental demand, while **winter** has the lowest.
- **Clear weather** is associated with higher bike rental demand.
- **Weekday rentals are higher than weekend rentals**, suggesting stronger weekday demand.
- **Non-holiday days have higher rental demand** than holidays.
- The **2017 data is incomplete**, so it should not be used for a full-year comparison.

## 🏁 Conclusion

- Increase bike availability during **high-demand months**.
- Keep more bikes available during the **summer season**.
- Maintain higher bike availability on **weekdays**.
- Reduce excess bike availability during **winter**.
- Consider **weather conditions** when planning bike distribution.
- Use rental trends to improve **bike availability and operational planning**.
- Focus resources on periods with **consistently high demand**.

## 🛠️ Tools Used

- **SQL** → Data cleaning and preparation
- **Power BI** → Data visualization and dashboard creation
- **Excel** → Initial data exploration

## 📌 Project Outcome

This project demonstrates how **SQL and Power BI** can be used together to clean raw data, analyze rental patterns, generate meaningful business insights, and support better operational decisions.
