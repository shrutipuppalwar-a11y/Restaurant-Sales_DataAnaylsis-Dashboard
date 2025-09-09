# 📈 Restaurant Sales Analysis Dashboard

## 📌 Project Overview
This project features an interactive dashboard created to analyze restaurant sales and consumer behavior across three states in Mexico: San Luis Potosi, Morelos, and Tamaulipas. The dashboard provides a comprehensive view of consumer demographics, dining habits, and restaurant performance.

The primary goal of this project is to transform raw data into a clear, visual, and actionable analysis tool that can be used to understand customer preferences, market trends, and restaurant-specific attributes.

---

## 🚀 Features
- **Total Metrics** – High-level summary of total restaurants, cuisines, and consumers.
- **Consumer Demographics** – Analysis of consumer age, marital status, occupation, and city.
- **Dining Habits** – Insights into preferred cuisines, price ranges, alcohol service, and transportation methods.
- **Restaurant Attributes** – Detailed breakdown of restaurant locations, smoking policies, and parking availability.
- **Performance & Ratings** – Visualizations of overall, food, and service ratings, including top-rated restaurants.
- **Filters** – Dynamic filtering by **State**, **City**, and other key variables for focused analysis.

---

## 🛠️ Tools & Technologies
- **Power BI** – Used for data modeling, dashboard creation, and interactive visualizations.
- **Excel/CSV Dataset** – The source data for all analyses.
- **Power Query** – Utilized for data cleaning, transformation, and shaping to prepare the data for reporting.

---

## 📊 Dataset Information
The analysis is built on a dataset structured across five sheets, each providing a different dimension of the data.

| Sheet Name | Key Columns | Description |
|---|---|---|
| **Sheet 1** | `Consumer_ID`, `Preferred_Cuisine` | Maps consumers to their favorite cuisine. |
| **Sheet 2** | `Consumer_ID`, `City`, `State`, `Age`, `Occupation`, `Budget` | Detailed consumer demographics and behavioral data. |
| **Sheet 3** | `Consumer_ID`, `Restaurant_ID`, `Overall_Rating`, `Food_Rating`, `Service_Rating` | Records consumer ratings for restaurants. |
| **Sheet 4** | `Restaurant_ID`, `Cuisine` | Links restaurants to the cuisine they serve. |
| **Sheet 5** | `Restaurant_ID`, `Name`, `City`, `State`, `Alcohol_Service`, `Smoking_Allowed`, `Price`, `Parking` | Provides restaurant-specific attributes and services. |

---

## 📈 Key Insights
- **Geographic distribution of consumers** and restaurants across the three Mexican states.
- **Correlation between parking availability and restaurant pricing**.
- **Breakdown of consumer habits** such as drinking levels and transportation methods.
- **Performance overview** showing ratings for food, service, and the overall dining experience.
- **Detailed analysis of restaurant policies**, including the prevalence of smoking sections.

---

## 📂 Repository Structure
│-- 📄 README.md
│-- 📊 Restaurant_Analysis.pbix   # Power BI dashboard file
│-- 📑 Restaurant_Data.xlsx      # Dataset (if shareable)
│-- Dashboard_Screenshot1.png
│-- Dashboard_Screenshot2.png
│-- Dashboard_Screenshot.......

---

## ⚡ How to Use
1. **Clone or Download** this repository.
2. Open the `Restaurant_Analysis.pbix` file in **Power BI Desktop**.
3. If the dataset (`Restaurant_Data.xlsx`) is in the same folder, the dashboard will automatically load the data. If not, you may need to update the data source settings.
4. Use the dynamic filters and interactive visuals to explore the data.

---

## 📷 Dashboard Preview
![Dashboard Preview](Dashboard_Screenshot1.png)
![Dashboard Preview](Dashboard_Screenshot2.png)
... (Add more screenshots if desired)

---

## 🎯 Conclusion
This dashboard serves as a powerful tool for a business owner or a data analyst to gain a deep understanding of the restaurant market dynamics and consumer preferences. By leveraging these insights, one can make data-driven decisions to optimize business strategy, improve customer satisfaction, and identify new opportunities.

