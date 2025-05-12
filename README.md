# 🏨 Hotel Booking Cancellation Analysis Using Python

## 📌 Project Overview
This project analyses hotel booking data from 2015 to 2017 to uncover the key factors contributing to reservation cancellations. Using Python libraries such as Pandas, Matplotlib, and Seaborn, the analysis focuses on identifying patterns in customer behaviour, lead time, pricing, and booking sources. The goal is to provide actionable insights to help hotels reduce cancellation rates and improve revenue efficiency.

---

## 📁 Dataset
- **Source:** (Link - https://drive.google.com/file/d/1-QwWigkene6K-EXRQTXEEEghq9SMiirb/view)
- **Time Frame:** 2015–2017
- **Hotels Included:** City Hotel and Resort Hotel
- **Features:** Booking date, lead time, ADR (average daily rate), cancellation status, customer type, market segment, etc.

---

## 🛠 Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Features
- Data cleaning and preprocessing
- Outlier handling (ADR > 5000 removed)
- Exploratory data analysis (EDA) with visualisations
- Hypothesis testing using T-tests:
  - Do higher prices lead to more cancellations?
  - Does longer lead time increase cancellation likelihood?
  - Are cancellations more frequent from certain booking channels?
- Insight generation to assist hotel decision-making

---

## 📊 Key Results
- Cancellations are more likely when the ADR (price) is higher.
- Bookings made far in advance (high lead time) tend to cancel more.
- Most cancellations come from **Online Travel Agents**, not offline ones.
- City hotels show a higher cancellation rate than resort hotels.
