# Swiggy--PowerBI---Project
Swiggy Data Analysis and Power BI Dashboard Project
# 🍔 Swiggy Power BI Dashboard Project
-------------------------------------------------------------

This project focuses on analyzing and visualizing Swiggy food delivery data using Power BI. The project includes data cleaning, transformation, modeling, KPI generation, and interactive dashboard creation to uncover meaningful business insights.

The main objective of this project is to transform raw Swiggy data into an interactive business intelligence dashboard for better decision-making and performance analysis.

---

# 🔗 Power BI Report

- [View the Power BI Report Here](https://app.powerbi.com/view?r=eyJrIjoiMzZiNzhkODUtNWZjZi00N2NjLWIwYjEtOWI4Yzk5NzlhYjVlIiwidCI6ImZmYzMxNjU1LTI0NTMtNGMzNy1iNmM3LWI4MzQ2ODM4MTc3NiJ9)

---

# 📊 Dashboard KPIs

- ✅ Total Orders
- ✅ Total Revenue
- ✅ Average Rating
- ✅ Total Restaurants
- ✅ Total Quantity Sold
- ✅ Average Price
- ✅ Top Performing Restaurant
- ✅ Most Ordered Food Category

---

# 📂 Dataset Information

The dataset contains Swiggy-related restaurant and order information including:

- Restaurant Details
- Menu Information
- Order Data
- Customer Information
- Food Categories
- Ratings & Reviews
- City-wise Sales Data
- Order Types

---

# 📋 Tables and Column Names

## 🍲 Food Table
- `f_id`
- `item`
- `veg_or_non_veg`

## 📋 Menu Table
- `menu_id`
- `r_id`
- `f_id`
- `Cuisine`
- `price`

## 📝 Orders Table
- `order_date`
- `sales_qty`
- `sales_amount`
- `currency`
- `user_id`
- `r_id`

## 🛍️ Orders Type Table
- `order_id`
- `type`

## 🍴 Restaurant Table
- `id`
- `name`
- `country`
- `city`
- `rating`
- `rating_count`
- `cuisine`
- `link`
- `address`

## 👥 Users Table
- `user_id`
- `name`
- `age`
- `gender`
- `marital_status`
- `occupation`

---

# 🧹 Data Cleaning Process

The following data cleaning operations were performed:

- Removed null values
- Removed duplicate records
- Renamed columns properly
- Corrected data types
- Handled missing values
- Standardized category names
- Removed unnecessary columns
- Removed unwanted tables
- Created calculated columns
- Created DAX measures

---

# 🛠️ Data Transformation

Power Query Editor was used for:

- Merging tables
- Splitting columns
- Extracting date components
- Filtering unwanted rows
- Creating conditional columns
- Formatting data

---

# 🔗 Data Modeling

Relationships were created between tables using:

- Primary Keys
- Foreign Keys

Example:
- Restaurant ID
- User ID
- Food ID

---

# 📊 Dashboard Visualizations

The dashboard includes multiple interactive visuals such as:

## 📌 KPI Cards
Used for displaying:
- Total Revenue
- Total Orders
- Average Ratings
- Total Quantity

## 📊 Bar Charts
Used for:
- Restaurant Performance
- Category Sales
- City-wise Analysis

## 🥧 Pie Charts
Used for:
- Food Category Distribution
- Veg vs Non-Veg Analysis

## 📈 Line Charts
Used for:
- Sales Trends
- Order Trends
- Revenue Growth

## 📋 Tables & Matrix
Used for detailed business analysis.

## 🎛️ Slicers
Interactive filters added for:
- City
- Restaurant
- Category
- Ratings
- Order Type

---

# 📐 DAX Measures Used

```DAX
Total Revenue = SUM(Orders[sales_amount])
Average Rating = AVERAGE(Restaurant[rating])
Total Quantity = SUM(Orders[sales_qty])
Total Orders = COUNT(Orders[user_id])
🔍 Business Insights

Some important insights identified from the dashboard:

🥗 Vegetarian food generated 122M sales, which is 7.2% higher than Non-Vegetarian sales.
👥 Top 10% of customers contributed nearly 80% of total sales.
🏙️ Tirupati city recorded the highest order amount at 43M.
⭐ Highly rated restaurants generated maximum revenue.
🍔 Certain food categories showed consistently higher demand.
📈 Revenue increased significantly during peak ordering hours.
🚀 Power BI Workflow
Step 1️⃣: Data Collection

Collected Swiggy dataset from available sources.

Step 2️⃣: Data Cleaning

Performed cleaning using Power Query Editor.

Step 3️⃣: Data Transformation

Created calculated columns and DAX measures.

Step 4️⃣: Data Modeling

Established relationships between tables.

Step 5️⃣: Dashboard Development

Designed interactive Power BI dashboard.

Step 6️⃣: Insight Generation

Generated meaningful business insights.

🎯 Project Objectives
Analyze restaurant performance
Understand customer behavior
Track sales performance
Monitor food category trends
Improve business decision-making
Create interactive visual reports
💡 Tools & Technologies Used
Power BI Desktop
Power Query
DAX
Data Modeling
Data Cleaning
Business Intelligence Techniques
📁 Recommended GitHub Repository Structure
Swiggy-PowerBI-Dashboard/
│
├── Dataset/
├── Dashboard Screenshots/
├── Swiggy Dashboard.pbix
├── README.md
└── Documentation.docx
📷 Dashboard Features
Interactive dashboard
Dynamic filtering
Business KPI tracking
User-friendly visuals
Real-time analytical experience
🔮 Future Improvements

Future enhancements can include:

Real-time API integration
Predictive analytics
Customer segmentation
Delivery performance tracking
AI-powered forecasting
Mobile dashboard optimization
📌 Conclusion

This Swiggy Power BI Dashboard project demonstrates how raw food delivery data can be transformed into meaningful business insights using Power BI.

The dashboard helps businesses analyze performance, monitor customer behavior, and make data-driven decisions effectively.

👨‍💻 Author

Created By: Jyothi

⭐ License

This project is created for educational and portfolio purposes.
