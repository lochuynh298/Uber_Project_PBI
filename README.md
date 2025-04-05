# 📊 Project Title: Project Title: Uber Analysis 

🤵 Author: Lộc Huỳnh

📆 Date: Nov. 30, 2024

💻 Tools Used: Power BI

## 📑 Table of Contents

1.📌 Background & Overview

2.📂 Dataset Description & Data Structure

3.🧠 Design Thinking Process

4.📊 Key Insights & Visualizations

5.🔎 Final Conclusion & Recommendations

## 📌 Background & Overview

### Objective:

## 📖 What is this project about? 

- Business Perfomance : Analyse Uber trip data using Power BI to gain insights into booking trends, revenue, and trip efficiency, helping stakeholders make data-driven decisions.
- Opportunities and Challenges: The manager recognizes growth opportunities but is uncertain if the trend reflects the entire market or specific products. They aim to use data to analyze overall performance and avoid bias in evaluations.

👤 Who is this project for?

➡️ The Sales Manager can make data-driven decisions on expansion strategies.

❓Business Questions:
- How to identify trends in ride bookings and revenue generation.
- How to analyse trip efficiency in terms of distance and duration.
- How to compare booking values and trip patterns across different time periods.
  
👤 Who is this project for?
➡️ The  Manager can make data-driven decisions on expansion strategies.

📂 Dataset Description & Data Structure

📌 Data Source
Source: [https://drive.google.com/drive/folders/1ipbzuuJut2j9v1bqyEtZzeORHPyFzalq?usp=sharing]
Format: .xlsv


📊 Data Structure & Relationships

1️⃣ Tables Used:
There're:

1 fact table: Trip Details

1 dim table: Location

2️⃣ Table Schema & Data Snapshot
Table 1: Trip Details
Table 2: Location

3️⃣ Data Relationships:

![image](https://github.com/user-attachments/assets/d7571ebf-1fe0-4873-ac85-d5e4e7f555c3)


🧠 Design Thinking Process

1️⃣ Empathize

➡️ Applied 5W1H to define the problem

![image](https://github.com/user-attachments/assets/7fc18750-54d0-4555-bd48-1295b15d1b70)


➡️ Empathy Map for Stakeholders

![image](https://github.com/user-attachments/assets/22ae349e-5f1c-45e1-a0c2-2cdbb9fcdfd3)


2️⃣ Define point of view

➡️ Find the North star metric

![image](https://github.com/user-attachments/assets/129ba09b-ada2-417b-a581-a2333ae8ee2a)


➡️ Dimension Data Group
![image](https://github.com/user-attachments/assets/2d5855fe-174c-49d3-bc5c-6711305f27b3)


⚒️ Main Process
1️⃣ Apply CodeM to create Dim_Date table


| Column Name | Description                         |
|-------------|-------------------------------------|
| Date        | The specific date.                  |
| Date Name   | The name date of the given date.    |
| Date Number | The date number  of the given date. |


2️⃣ Apply DAX to calculate the metrics

| Column Name                 | Description                                                                     |
|-----------------------------|---------------------------------------------------------------------------------|
| Average Booking Amount      | The average monetary value of each booking.                                       |
| Average Trip Distance       | The average distance traveled for each trip (e.g., in miles or kilometers).      |
| Average Trip Time           | The average duration of each trip (e.g., in minutes or hours).                  |
| Most Frequent Drop-off Point | The most commonly occurring destination or drop-off location.                        |
| Total Booking Amount        | The sum of the monetary values of all bookings.                                 |
| Total Bookings              | The total number of bookings made.                                              |
| Total Trip Distance         | The sum of the distances traveled for all trips (e.g., in miles or kilometers). |

⚒️ Main Process

3️⃣ Power BI Visualization (applicable for PBI Projects)

📊 Dashboard 1: Overview

![image](https://github.com/user-attachments/assets/a48327c7-52f9-4cf5-a9a8-af1d4d9322d0)

## Key Insight Values to Improve Business:

## Demand Management and Driver Allocation:

- Insight: "Total Bookings By Day" highlights fluctuations in demand. "Most Frequent Value" (Penn Station/Madison Sq West) and "Most Frequent Dropoff Point" (Upper East Side North) identify high-demand locations.
- Value: Optimize driver allocation by increasing availability during peak hours and in high-demand areas. Implement dynamic pricing during peak times to balance supply and demand.
Pricing Strategy:

- Insight: "Average Booking Amount" ($15.0) and "Average Trip Distance" (3 Miles) provide insights into average trip costs.
Value: Analyze pricing strategies based on trip distance, time, and location. Consider implementing surge pricing during peak hours or in high-demand areas.
Marketing and Promotions:

- Insight: "Most Preferred Vehicle" (UberX, Uber Co, etc.) indicates customer preferences.
Value: Tailor marketing campaigns and promotions based on preferred vehicle types. Offer discounts or promotions for less popular vehicle types to increase utilization.
Payment and Trip Type Optimization:

- Insight: "Total Bookings by Location" shows the distribution of bookings across different areas.
Value: Identify high-growth areas and invest in infrastructure or partnerships to support increased demand. Address areas with lower bookings to improve market penetration.
Vehicle Performance Analysis:

- Insight: "Vehicle Type Analysis" provides a comprehensive view of vehicle performance metrics.
Value: Optimize vehicle fleet management based on performance data. Identify high-performing vehicle types and consider expanding their availability.
Operational Efficiency:

Insight: "Average Trip Time" (16 Min) and "Total Trip Distance" (349K Miles) provide insights into operational efficiency.
Value: Analyze trip times and distances to identify areas for improvement. Implement strategies to reduce trip times and improve efficiency.

📊 Dashboard 2: Time Analysis

![image](https://github.com/user-attachments/assets/bd63cc4d-0b61-4452-91c4-ef1beafe5d26)
## Key Insight Values to Improve Business:

## Peak Hour Identification and Driver Allocation:

- Insight: The "Total Booking Pick Up Time" chart clearly shows peak hours during the day.
Value: Uber can optimize driver scheduling and availability to match peak demand. This minimizes wait times for customers and ensures drivers are utilized efficiently. Implementing surge pricing during peak hours can help manage demand and increase revenue.
Day-of-Week Demand Patterns:

- Insight: The "Total Booking Pick Up Day" chart reveals variations in demand across different days of the week.
Value: Uber can tailor marketing campaigns and promotions to specific days of the week. For example, if weekends show higher demand, they can run weekend-specific promotions. They can also adjust driver incentives based on day-specific demand.
Detailed Hourly and Daily Demand Analysis:

- Insight: The "Total Booking Pick Up Hour" heatmap provides a granular view of booking patterns, showing the busiest times across each day of the week.
Value: This allows for very precise driver scheduling and resource allocation. Uber can identify specific hours and days with high demand and ensure sufficient driver availability. It also helps to pinpoint the quietest hours for maintenance or driver breaks.
Operational Efficiency and Resource Planning:

- Insight: By understanding when demand is low, Uber can optimize resource allocation and reduce operational costs.
Value: Uber can schedule maintenance or downtime during off-peak hours. They can also offer driver incentives to work during traditionally slow periods to ensure consistent service availability.
Targeted Marketing and Promotions:

- Insight: The dashboard data can inform targeted marketing campaigns.
Value: Uber can run promotions or discounts during specific hours or days with lower demand to incentivize ridership.
Customer Behavior Understanding:

- Insight: The patterns in the charts reveal customer behavior regarding ride requests.
Value: Uber can use this to understand customer habits and tailor services to meet their needs. For example, if there's a surge in late-night bookings on weekends, they might focus on providing safer and more reliable late-night services.

📊 Dashboard 3: Details
![image](https://github.com/user-attachments/assets/30d02a38-7a4e-490a-826c-25564bc4c301)
Key Data Points for Each Trip:

- Trip ID: A unique identifier for each trip.
- Pick up Date: The date the trip started (all trips shown are on June 1, 2024).
- Pick up time: The time the trip started.
- Vehicle: The type of vehicle used (e.g., UberX, Uber Black, Uber Comfort, Uber Green, UberXL).
- Payment_type: The method of payment (e.g., Cash, Uber Pay).
- Total Trip Distan Measure: The distance of the trip.
- Total Booking Amount: The fare charged for the trip.
- Location: The destination of the trip.
- Total Bookings: The number of bookings associated with this trip (likely always 1, indicating each row represents a single trip).

## 🔎 Final Conclusion & Recommendations

# This dashboard provides a basic overview of Uber trip data, focusing on:

Overall Good Performance: Total bookings, total booking amount, and trip distance indicate that the business is performing quite well.
Stable Average Values: The average booking amount and average trip distance are relatively stable, indicating a consistent pricing and distance model.
Preferred Vehicle Type: UberX is the most preferred vehicle type, indicating that it is your main market segment.
Frequent Pick-up/Drop-off Locations: Penn Station/Madison Sq West and Upper East Side North are important locations, indicating high demand areas.
Day of Week Variation: Bookings increase sharply on Fridays and Saturdays, with the lowest bookings on Wednesdays.

# Improvement Recommendations:

# 1. Optimize Pricing Based on Time:
-Use peak hour and day data to implement a more effective dynamic pricing (surge pricing) strategy.
-Consider offering promotions or discounts during off-peak hours and days to stimulate demand.
# 2. Efficient Resource Management:
-Allocate more drivers to high-demand areas (Penn Station/Madison Sq West and Upper East Side North) and during peak hours.
-Ensure sufficient UberX vehicles to meet high demand.
-Base on day of week data, increase driver counts on Fridays and Saturdays, and reduce drivers on Wednesdays.
Focus on Preferred Vehicle Type:
-Invest in increasing the number of UberX vehicles and ensure good service quality.
-Consider implementing loyalty programs for UberX users.
-Improve Customer Experience:
-Monitor and improve wait times at frequent pick-up locations.
-Ensure consistent service quality across all vehicle types.
In-depth Research on Payment Methods and Trip Types:
-More research is needed on the rates of usage of different payment methods and different trip types to create appropriate strategies, which could be promotions or forms of cooperation with payment partners.
Marketing by Day of the Week:
Focus marketing campaigns on high-booking days, while finding promotions for lower-booking days.

























