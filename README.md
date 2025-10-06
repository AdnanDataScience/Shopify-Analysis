# 🛍️ Shopify Sales Analysis Dashboard
This project focuses on analyzing Shopify sales performance across multiple countries using **Power BI**. It highlights key business insights such as revenue trends, top-performing products, customer distribution, and regional sales performance.


## 📊 Project Overview
The **Shopify Sales Analysis Dashboard** was designed to help business stakeholders track and understand sales performance, identify growth opportunities, and make data-driven decisions.  
This dashboard provides visual insights into:
- Country-wise and category-wise revenue
- Sales and profit trends over time
- Top-performing products and customers
- Discount impact on sales
- Seasonal trends and performance indicators


## 🧩 Data Model
The project uses a **star schema** model with one fact table and multiple dimension tables:
- **Fact Tables:**
  - Sales Data
- **Dimension Tables:**
  - Customer
  - Product
  - Product Category
  - Product Subcategory
  - Territory
  - Calendar

All tables are connected through appropriate keys to ensure clean relationships and optimized model performance.


## ⚙️ Tools & Technologies
- **Power BI Desktop (DAX, Modeling, Visualization)**
- **Microsoft Excel**
- **SQL Server (for data storage and transformation)**
- **Power Query (for data cleaning and transformation)**


## 🧮 DAX Measures
Key DAX calculations used:
- `Total Sales = SUM(Sales[Sales Amount])`
- `Total Profit = SUM(Sales[Profit])`
- `Profit Margin = DIVIDE([Total Profit], [Total Sales])`
- `YoY Growth = (This Year Sales - Last Year Sales) / Last Year Sales`


## 💡 Key Insights
- The **United States** and **United Kingdom** lead in overall revenue.
- **Accessories** and **Clothing** categories have the highest sales contribution.
- A strong **seasonal sales pattern** was observed in Q4 across multiple regions.
- Discounts show a positive correlation with sales volume but slightly reduce profit margins.



## 📈 Visuals & Dashboards
The Power BI report includes:
- Revenue and profit trend charts
- Sales by product and region heatmaps
- Top 10 products and customers
- KPI cards and slicers for interactivity
- Monthly and yearly comparison visuals


## 🚀 How to Use
1. Open the `.pbix` file in **Power BI Desktop**.
2. Connect your data sources or refresh the existing ones.
3. Explore the dashboard visuals to analyze performance metrics.


## 📬 Contact
**Adnan Haider**  
📧 adnanhaider9410@gmail.com 
💼[ LinkedIn Profile or Portfolio Link  ](https://www.linkedin.com/in/adnan-haider-data-analyst/)
🌍 [GitHub Profile – AdnanDataScience](https://github.com/AdnanDataScience)

---

⭐ *If you found this project helpful, please star the repository!*
