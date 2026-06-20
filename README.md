# restaurant-business-performance-report
Power BI Restaurant Analytics Dashboard | Business Intelligence | Customer Behavior | Revenue &amp; Operational Insights | Interactive Visualizations

# 🍽️ Restaurant Business Performance Analytics | Power BI

## 📖 Project Overview

This project is an end-to-end Power BI dashboard developed to analyze the performance of a restaurant business using customer, restaurant, and order data. The objective was to transform raw transactional data into an interactive reporting solution that provides meaningful insights into sales performance, customer behavior, restaurant operations, and delivery efficiency.

By combining data from multiple related tables into a well-structured data model, the dashboard enables users to explore business performance through interactive visuals and KPIs, making it easier to identify trends, monitor operations, and support data-driven decision-making.



## 🎯 Business Problem

Restaurant businesses generate a large volume of daily transactional data, but without a centralized reporting system it becomes difficult to answer important business questions. Management needs quick access to information such as revenue trends, customer retention, restaurant performance, and delivery efficiency to make timely business decisions.

This dashboard addresses that challenge by bringing together multiple data sources into a single, easy-to-use reporting solution.



## 🏗️ Data Model

The report was built using a **Star Schema** to improve report performance and simplify DAX calculations.

**Fact Table**

* Orders

**Dimension Tables**

* Customers
* Restaurants
* Date
* KPI (Disconnected table for dynamic KPI selection)



## 📊 Dashboard Overview

The report is organized into six interactive pages:

* **Executive Overview** – Business KPIs, revenue trends, order trends, and top-performing restaurants.
* **Customer Analytics** – Customer growth, repeat customers, signup trends, and customer segmentation.
* **Restaurant Performance** – Revenue by restaurant, cuisine analysis, ratings, and cost category performance.
* **Delivery & Operations** – Delivery time analysis, late deliveries, cancellations, and operational performance across cities.
* **Advanced Insights** – Dynamic KPI selection with interactive filtering and trend analysis.
* **Restaurant Details** – Detailed performance analysis for individual restaurants.



## ⚙️ Technical Implementation

* Designed a relational **Star Schema** data model.
* Developed DAX measures for business KPIs, customer metrics, and operational analysis.
* Implemented **Time Intelligence** calculations including YTD metrics, previous month revenue, and revenue growth.
* Used Power Query for data preparation and transformation.
* Added interactive features including slicers, drill-down analysis, and dynamic KPI selection using a disconnected table.



## 💡 Business Insights

The dashboard helps management answer key business questions, including:

* Which restaurants contribute the highest revenue?
* Which customer segments are driving repeat business?
* Which cuisines are most popular across restaurants?
* Which cities experience the highest delivery delays or cancellations?
* How are revenue and order volumes changing over time?
* Which restaurants may require operational improvements based on ratings and performance?

These insights help identify growth opportunities, monitor customer behavior, and improve operational efficiency.



## 🚀 Business Impact

This dashboard transforms raw business data into actionable insights that support faster and more informed decision-making. Instead of analyzing multiple spreadsheets or transaction records, stakeholders can monitor key business metrics from a single interactive dashboard.

The solution helps management:

* Monitor overall business performance through real-time KPIs.
* Identify top-performing restaurants and high-value customers.
* Improve customer retention by tracking repeat customer trends.
* Detect delivery bottlenecks and reduce operational inefficiencies.
* Support strategic decisions using data-driven insights rather than manual reporting.



## ⚙️ Tech Stack

* Power BI Desktop
* Power Query
* DAX
* Star Schema Data Modeling
* Interactive Data Visualization
