# 📊 S&P 500 Stock Analysis (2014–2017) – Beginner Investor Dashboard

## 🧠 Project Summary
This project simulates the journey of a **beginner investor** exploring historical stock data to identify promising investment opportunities within the **S&P 500 index**. Using **Power BI**, I analyzed stock prices from **2014 to 2017** to understand trends, volatility, volume activity, and price behaviors across multiple companies.

---

## 🎯 Objective
To **visually explore** and understand stock performance and trends, and based on data-driven insights, make an informed hypothesis on which stocks would have been worth investing in.

---

## 📁 Data Source
- **Dataset**: S&P 500 Stock Prices 2014–2017  from [Maven Analytics](https://mavenanalytics.io/data-playground?accessType=open&order=date_added%2Cdesc&page=12&pageSize=5) and some **analytics** from [Yahoo Finance](https://finance.yahoo.com/markets/stocks/most-active/)
- **Fields included**: `date`, `symbol`, `open`, `high`, `low`, `close`, `volume`

---

## 📌 Key Dashboard Insights

### 🔹 Insight 1: Average Volume per Company for dates 2014-2017
This page examines the **average volume** across selected companies over time. A **pie chart** helps visualize how many transactions (share trading) happened in average. A threshold was inisialized to set the avg volume above 20,000,000 shares traded which correlates with how active stock market is.

![Pie chart: Average Volume per Company for dates 2014-2017](https://github.com/user-attachments/assets/7f48c811-f8d7-4abe-a8bf-a44b59fe40b1)

### 🔹 Insight 2: Average Volume per Company for dates 2014-2017 & measure
Here, it was analyzed a  **measure = average(highprice) - average(lowprice)** and added a threshold to be over 7,5. Using this approach to understand how much in average the stock is increased during these 3 years. This highlights that the higher the measure and the volume means lots of people traded and the differences of prices can benefit an investor.

![Scatter plot: Average Volume per Company for dates 2014-2017 with a measure](https://github.com/user-attachments/assets/1bfc6299-7047-486e-ad34-0797813f4f82)

### 🔹 Insight 3: Variance of high price per Company
This chart focuses on **the companies with higher than 750 measure of variance**. This means that the higher the variance there is more risk but also more chance for bigger gains too. This can indicate both risk and opportunity for short-term and of course for long-term investors.

![Variance of high price](https://github.com/user-attachments/assets/f2d2741c-8a0f-4794-a4d9-864e1fe1a499)

### 🔹 Insight 4: Variance of open price per Company per Month
These visuals here show each company's stock **historical variance for open prices**. These additionally with the previous one can help us understand which company can offer stability and safe options for invest and other more risky and with higher chances of gain.

![Variance of open price per Company per Month](https://github.com/user-attachments/assets/a208a94b-b6ea-4393-b0ec-15efe551ebad)
![Variance of open price per Company per Month2](https://github.com/user-attachments/assets/405402fd-a943-4d82-8b8b-c8d05b78356e)
![Variance of open price per Company per Month3](https://github.com/user-attachments/assets/4d876050-e823-4e54-974b-a87ec3265469)

---

## 🛠 Tools Used
- Power BI Desktop
- Excel from Microsoft Suite
- Power Query for Data Modeling  
- DAX Measures for Custom Aggregations

---

## 🚀 What I Learned
- How to clean and visualize time-series stock data  
- Using Power BI slicers and visuals to interactively filter trends  
- Comparing data across multiple companies  
- Making beginner-friendly insights using financial metrics

---

