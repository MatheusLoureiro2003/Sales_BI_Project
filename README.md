# Sales_BI_Project
This case study is based on a computer hardware company operating in a highly competitive and dynamically changing market. Due to increasing market complexity and fluctuating demand, the Sales Director decided to invest in a data analytics project to gain real-time insights into sales performance and support strategic decision-making.
🎯 Problem Statement

The company faced the following challenges:

Lack of centralized sales information

Difficulty in tracking sales performance across regions and products

Limited visibility into revenue trends and key performance indicators (KPIs)

Slow, manual reporting processes

The goal of this project was to build an interactive Power BI dashboard capable of delivering clear, reliable, and actionable sales insights.

🛠️ Tools & Technologies

MySQL – Data storage and initial data import

Power BI Desktop – Data modeling, ETL, DAX, and visualization

SQL – Data querying and validation

DAX – Measures and business logic

🔄 Data Pipeline (ETL Process)

Data Import

Raw sales data was imported into a MySQL database.

The database served as the single source of truth.

Data Connection

Power BI was connected directly to MySQL using the MySQL Connector.

Data Cleaning & Transformation (ETL)

Data cleaning and transformations were performed inside Power BI (Power Query).

Handling missing values and inconsistencies

Data type standardization

Creation of calculated columns

Data Modeling

Relationships between tables were defined following best practices.

A clean and efficient data model was built to support analysis.

📐 Metrics & Analysis

The following analyses were developed:

Total Revenue

Sales Quantity

Revenue by Region

Revenue by Product

Monthly and yearly sales trends

KPI comparison and performance tracking

Descriptive statistics for sales performance evaluation

All business metrics were implemented using DAX measures.

📊 Dashboard Overview

The final Power BI dashboard provides:

Interactive filters (region, product, time)

KPI cards for quick performance assessment

Bar and line charts for trend analysis

Clear visual storytelling for decision-makers

📷 Screenshots of the dashboard are available in the /images folder.

🚀 Key Insights

Identification of top-performing regions and products

Detection of declining sales trends in specific markets

Improved visibility into revenue concentration

Faster and more reliable reporting for management

📁 Repository Content

/dashboard – Power BI (.pbix) file

/data – Raw data and SQL scripts

/images – Dashboard screenshots

/docs – Data model and documentation

📌 How to Use

Clone the repository

Open the .pbix file using Power BI Desktop

Update database credentials if needed

Refresh the data to explore the dashboard

👤 Author

Matheus Loureiro
Data Analysis & Business Intelligence Enthusiast
