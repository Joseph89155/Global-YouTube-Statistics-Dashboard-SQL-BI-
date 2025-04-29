# 🌐 Global YouTube Statistics Dashboard

## 📋 Project Description

This project explores global YouTube statistics using SQL, Excel, and Power BI to uncover regional performance across various metrics such as uploads, views, earnings, and subscriptions. The dataset contains continent-, country-, and channel-type-specific YouTube data, enabling us to analyze how different parts of the world perform on the platform and what content types drive the most engagement.

The final deliverables include:
- Data cleaning and validation in Excel.
- Aggregation and analysis using SQL.
- Visual insights and storytelling via an interactive Power BI dashboard.

---

## 🎯 Project Objective

Analyze global YouTube data to:

- Identify the leading continents and countries in uploads, views, earnings, and subscribers.
- Measure percentage contribution to YouTube earnings by continent and country.
- Determine which content types dominate in terms of views.
- Provide insights that help creators, marketers, and digital strategists understand global YouTube trends.

---

## Dataset
<a href="https://github.com/Joseph89155/Global-YouTube-Statistics-Dashboard-SQL-BI-/blob/main/Global%20YouTube%20Statistics%20Dataset.csv">Dataset</a>

---

## ❓ Questions (KPIs)

1. Which continent leads in uploads, views, earnings, and subscribers?
2. What is the percentage of total earnings per continent?
3. Which top 8 countries contribute the highest percentage of YouTube earnings?
4. Which top 8 channel types generate the most views?

---

## 🛠️ Process

### 1. Data Collection
- Source file: `Global YouTube Statistics Dataset.csv`
- Key columns analyzed: `continent`, `country`, `channel_type`, `total_views`, `total_subscribers`, `total_uploads`, `total_earnings`, `pct_earnings`

### 2. Data Cleaning (SQL + Excel)
- Cleaned raw data for null values and outliers.
- Standardized column formats and validated key metrics.
- Joined, grouped, and aggregated data using SQL queries.

### 3. Excel Processing
- Cross-verified SQL results using Excel pivot tables.
- Exported key summaries for Power BI visualization.
- Prepared summary sheets for integration into the dashboard.

### 4. Dashboard Creation (Power BI)
- Developed an interactive dashboard with slicers and drill-downs.
- Visualizations include:
  - Bar Charts: Total subscribers and uploads by continent
  - Donut Chart: Earnings percentage by continent
  - Treemap: Top 8 countries by earnings share
  - Bar Chart: Top 8 channel types by views

---

## 🖼️ Dashboard Preview

![Dashboard Screenshot](Global%20Youtube%20Statistics%20Power%20BI%20shot.PNG)

---

## 🔍 Project Insights

- **North America** and **Asia** dominate in subscriber count and total views.
- **Asia** has the highest upload volume, indicating active creator participation.
- **North America** generates the highest earnings overall.
- **United States** and **India** are the biggest earners by country.
- **Entertainment** and **Music** are the top-performing content types by views globally.

---

## 🏁 Final Conclusion

This project reveals strong regional disparities in YouTube performance. While Asia drives a large portion of uploads, North America leads in monetization, implying high-value content and advertiser interest. Entertainment and music continue to be the dominant genres, making them key targets for marketers and content strategists.

These insights serve as valuable inputs for businesses, digital marketers, and creators aiming to optimize content reach and monetization strategies across global YouTube markets.

---

## 📂 Project Files

- `Global YouTube Statistics Dataset.csv` – Raw dataset  
- `youtube_stats SQL.sql` – All SQL queries used for analysis  
- `Youtube Statistics Dashboard.xlsx` – Processed Excel summary  
- `Global Youtube Statistics Power BI.pbix` – Power BI project file  
- `Global Youtube Statistics Power BI shot.PNG` – Final dashboard image  

---

## 🧰 Tools Used

- **SQL** – For querying and aggregating raw data  
- **Excel** – For cleaning and pre-visualization  
- **Power BI** – For building interactive dashboards  


