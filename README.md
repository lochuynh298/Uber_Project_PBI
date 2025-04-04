#  Project Title: Uber Analysis 

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

2️⃣ Define point of view

➡️ Find the North star metric

➡️ Dimension Data Group


3️⃣ Ideate

4️⃣ Prototype and review

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


📊 Dashboard 2: Market Analysis


📊 Dashboard 3: Product Analysis


📊 Key Insights & Visualizations


🔍 Dashboard Preview

























