# 🚗 Uber Data Analysis 

## 📌 Project Overview

This project analyzes Uber ride data to uncover meaningful insights into **customer booking behavior, trip purposes, time trends, and travel distances**.
The analysis is designed from the perspective of a **Data Analyst working at Uber**, answering key business questions that help the company improve operations, demand planning, and customer experience.

---

## 🎯 Business Problem Statement

**Suppose you work in data analysis at Uber.**
You are required to analyze ride data and provide clear, data-driven answers to the following business questions:

1. **In which category do people book the most Uber rides?**
2. **For which purpose do people book Uber rides the most?**
3. **At what time do people book cabs the most from Uber?**
4. **In which months do people book Uber rides less frequently?**
5. **On which days of the week do people book Uber rides the most?**
6. **How many miles do people usually book a cab for through Uber?**
7. **Which locations have the highest pickups?**
8.  **How does Uber usage vary across months?**

This project answers all the above questions using **data preprocessing, exploratory data analysis (EDA), and visualization techniques**.

---

## 📊 Dataset Description

The dataset contains **1,156 Uber ride records** with the following attributes:

* `START_DATE`, `END_DATE` – Trip start and end timestamps
* `CATEGORY` – Business or Personal rides
* `START`, `STOP` – Pickup and drop locations
* `MILES` – Distance traveled
* `PURPOSE` – Reason for the trip

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas** – Data manipulation and cleaning
* **NumPy** – Numerical analysis
* **Matplotlib & Seaborn** – Data visualization

---

## 🔄 Data Preprocessing

* Handled missing values in the `PURPOSE` column
* Converted date columns to `datetime` format
* Extracted new features: **hour, day, month, weekday**
* Created a **day/night time category**
* Removed incomplete and invalid records

---

## 📈 Exploratory Data Analysis & Visualizations

* Category-wise ride count analysis
* Purpose-wise booking trends
* Hourly booking behavior
* Monthly ride frequency trends
* Weekday booking patterns
* Distance distribution and outlier detection

Each question is answered using **graphs such as bar plots, line plots, box plots, and distribution plots**.

---

## 🔍 Key Insights

* Business category has the highest number of bookings
* Work-related purposes dominate ride usage
* Peak booking hours occur during daytime
* Certain months show reduced ride demand
* Weekdays have higher booking frequency than weekends
* Most Uber trips are **short-distance rides**, with few long-distance outliers

---

## ✅ Conclusion
This project analyzes Uber ride data using Python to uncover booking patterns across categories, purposes, time, and distance.
The insights highlight peak usage periods, dominant trip types, and common travel distances, demonstrating the value of data-driven decision-making for Uber’s operations.
