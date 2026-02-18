# Data-Analysis-Customer-Behavior-Shopping-

Customer Shopping Behavior Analysis

Data Analytics Project


---

📌 Project Overview

This project focuses on analyzing customer shopping behavior using a structured data analytics workflow. The goal is to extract meaningful insights from transactional data by combining Python, SQL, and Power BI.

The analysis helps understand customer demographics, purchasing patterns, spending behavior, and engagement factors to support data-driven decision making.


---

📊 Dataset

Records: 3,900

Features: 18


Key Data Categories

Customer Demographics: Age, Gender, Location, Subscription Status

Purchase Details: Item Purchased, Category, Purchase Amount, Season

Behavioral Indicators: Discount Applied, Promo Code Used, Previous Purchases

Customer Feedback: Review Rating

Logistics: Shipping Type



---

🛠 Tools & Technologies Used

Python → Data loading, EDA, and data cleaning

MySQL → Querying and analysis using SQL

Power BI → Interactive dashboard & visualization

Gamma → Report and presentation creation



---

⚙️ Project Workflow

1️⃣ Data Loading (Python)

Imported dataset using pandas

Examined structure using df.info() and df.describe()


2️⃣ Exploratory Data Analysis (EDA)

Analyzed distributions and trends

Identified missing values and anomalies


3️⃣ Data Cleaning

Handled missing values

Ensured consistency and data quality


4️⃣ SQL Analysis (MySQL)

Ran queries for revenue analysis

Performed customer segmentation

Compared purchase behavior across categories


5️⃣ Dashboard Creation (Power BI)

Built interactive visualizations

Highlighted key KPIs and trends


6️⃣ Reporting & Presentation (Gamma)

Created analytical report

Designed presentation slides



---

📈 Key Outcomes

✔ Identified customer spending patterns
✔ Analyzed impact of discounts & promo codes
✔ Evaluated purchase frequency behavior
✔ Compared revenue across customer segments
✔ Developed decision-support dashboard


---

🚀 How to Run the Project

Python Analysis

1. Install required libraries:



pip install pandas sqlalchemy pymysql

2. Load dataset:



import pandas as pd
df = pd.read_csv("dataset.csv")


---

MySQL Queries

1. Import dataset into MySQL


2. Run SQL queries for analysis



Example:

SELECT Gender, SUM(Purchase_Amount)
FROM mytable
GROUP BY Gender;


---

Power BI Dashboard

1. Connect Power BI to MySQL / dataset


2. Load cleaned data


3. Build visualizations




---

🎯 Project Objective

This project demonstrates a complete end-to-end data analytics workflow, covering:

Data preparation

Data exploration

Data cleaning

SQL-based analysis

Business intelligence visualization

Reporting & presentation



---

👤 Author

Sumit Sen
BBA (Hons) – Marketing
Data Analytics Enthusiast
