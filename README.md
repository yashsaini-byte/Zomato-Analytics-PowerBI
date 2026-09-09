# Zomato-Analytics-PowerBI

🍽️ Zomato Analytics – Power BI Dashboard
An interactive Power BI dashboard built to analyze Zomato restaurant data and generate actionable insights around restaurant distribution, openings, ratings, pricing, cuisines, cities, and countries.

📊 Project Overview
This project demonstrates how raw restaurant data can be transformed into an interactive business intelligence dashboard using Microsoft Power BI.

The dashboard focuses on answering questions such as:

Where are restaurants concentrated by country and city?

How do restaurant openings vary over time?

How are restaurants distributed across rating buckets?

How are restaurants distributed across different price buckets?

Which cuisines have the highest number of restaurants?

Which restaurants/cities/countries contribute most to the overall restaurant landscape?

🛠️ Tools & Technologies
Microsoft Power BI

Power Query – Data cleaning and transformation

DAX – Calculated logic and analytical measures

Data Modeling – Relationships between fact and supporting tables

Interactive Visualizations – Tables, bar charts, column charts, filters and slicers

🗂️ Data Model
The Power BI model contains the following key tables:

Zomato
Main restaurant dataset containing fields such as:

Restaurant ID

Restaurant Name

Country

Country Name

City

Cuisines

Rating

Rating Bucket

Price / Price Bucket

Year

Restaurant-related attributes

Calendar
A dedicated calendar table used for time-based analysis, including:

Year

Month

Year-Month

Weekday information

Country Codes
A supporting lookup table used for country-related analysis and geographic reporting.

📈 Dashboard Analysis
1. Restaurants by City & Country
A detailed table showing restaurant counts by:

Country

City

Number of Restaurants

This helps identify locations with a higher concentration of restaurants.

2. Restaurant Openings Over Time
A column chart analyzes restaurant openings by year, allowing users to identify growth patterns and changes in restaurant activity over time.

3. Rating Analysis
Restaurants are grouped into rating buckets and compared based on restaurant count.

This makes it easier to understand the overall distribution of restaurant ratings.

4. Price Bucket Analysis
Restaurants are categorized into price buckets to understand the distribution of restaurants across different pricing levels.

5. Cuisine Analysis
A bar chart compares cuisines based on the number of restaurants, helping identify cuisines with stronger representation in the dataset.

🎯 Key Business Questions
The dashboard was designed around practical business-analysis questions:

Which countries and cities have the highest number of restaurants?

How has the number of restaurant openings changed over time?

What rating ranges contain the largest number of restaurants?

How are restaurants distributed by price category?

Which cuisines are most widely represented?

How can geographic and pricing information support restaurant-market analysis?

🔄 Data Preparation Process
The analysis follows a typical BI workflow:

Raw Zomato Data
      ↓
Data Cleaning & Transformation
      ↓
Power Query
      ↓
Data Modeling
      ↓
Calendar & Lookup Tables
      ↓
DAX / Calculated Logic
      ↓
Interactive Power BI Dashboard
      ↓
Business Insights
📁 Repository Structure
Zomato-PowerBI-Analytics/
│
├── Zomato Analytics Power BI Dashboard.pbix
├── README.md
└── screenshots/
    └── dashboard.png
Note: The .pbix file requires Microsoft Power BI Desktop to open and interact with the dashboard.

💡 Skills Demonstrated
This project demonstrates practical experience in:

Business Intelligence

Data Cleaning

Data Transformation

Data Modeling

Power Query

DAX

Time-Series Analysis

KPI & Metric Development

Data Visualization

Dashboard Design

Business Insight Generation

📌 Resume Description
Zomato Restaurant Analytics Dashboard | Power BI

Developed an interactive Power BI dashboard to analyze Zomato restaurant data across countries, cities, ratings, pricing, cuisines, and restaurant openings; performed data transformation, calendar modeling, DAX-based analysis, and interactive visualization to generate actionable business insights.

👨‍💻 Author
Yash Saini

Business Analytics | Power BI | SQL | Excel | Data Visualization

⭐ If you find this project useful, feel free to explore the dashboard and analysis.
