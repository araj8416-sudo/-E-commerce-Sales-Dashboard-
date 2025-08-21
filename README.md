# -E-commerce-Sales-Dashboard-

📊 E-Commerce Sales Dashboard (Power BI)

🔎 Project Overview

This project delivers an interactive Power BI dashboard to analyze E-commerce sales data.
It allows business users to track sales, profit, orders, and customer behavior across states, categories, and time periods.

📂 Dataset

Orders.csv → Transaction-level data (Order ID, Date of Sale, State, Amount, Profit, Quantity, Customer, Payment Mode)

Details.csv → Product metadata (Category, Sub-Category, etc.)

Date Dimension (created in Power BI using CALENDAR) → Provides Year, Quarter, Month fields

⚙️ Steps Performed

Data Preparation

1.Imported Orders & Details CSVs into Power BI

2.Built relationships between Orders and Details

3.Created a Date Table with Year, Month, Quarter

#DAX Measures

Total Sales   = SUM(Orders[Amount])
Total Profit  = SUM(Orders[Profit])
Quantity Sold = SUM(Orders[Quantity])
Order Count   = DISTINCTCOUNT(Orders[Order ID])
AOV           = DIVIDE([Total Sales], [Order Count])
Profit %      = DIVIDE([Total Profit], [Total Sales])


Dashboard Visuals

1.KPI Cards: Sales, Profit, Quantity, AOV

2.Bar Chart: Profit by Month

3.Horizontal Bar: Sales by State

4.Donut Charts: Quantity by Category, Payment Mode Distribution

5.Stacked Column: Sales by Customer

6.Horizontal Bar: Profit by Sub-Category

7.Quarter & Year Slicers

8.Styling & Interactivity

9.Added drill-downs (e.g., Category → Sub-Category)

10.Customized tooltips (showing Profit %, Quantity)

Validated slicers/filters to ensure dynamic updates

📈 Key Insights

1.Festive boost: Sales and profit peak in Q4 (Oct–Dec)

2.Top categories: Electronics lead revenue, Clothing lead margins

3.Regional leaders: Maharashtra, Delhi, Karnataka dominate sales

4.Payment mode: UPI is the most used method

5.Customer patterns: A few customers contribute disproportionately to revenue

🚀 How to Use

1.Clone this repo

2.Open Ecommerce_Sales_Dashboard.pbix in Power BI Desktop

3.Connect to provided CSVs if needed (Orders.csv, Details.csv)

4.Explore the dashboard with slicers & drill-downs

🛠️ Tools Used

1.Power BI Desktop – Dashboard creation

2.DAX – Calculations & measures

3.CSV (Orders & Details) – Data source

📈 Business Insights from E-Commerce Dashboard

Overall Performance

📊 Total Sales and Total Profit are healthy with consistent growth across the year.

🛒 Average Order Value (AOV) gives an idea of customer spending habits and helps optimize pricing/discount strategies.

Time Trends

⏳ Q4 (Oct–Dec) shows a sharp boost in sales and profit → linked to festive season demand (Diwali, year-end shopping).

📉 Certain months (e.g., Q2) show dips → could be used to plan targeted marketing campaigns.

Regional Performance

🌍 Maharashtra, Delhi, Karnataka emerge as top sales contributors.

📍 States with lower sales can be potential growth markets for regional campaigns.

Category Insights

📦 Electronics generate the highest revenue, but margins are thinner.

👕 Clothing shows better profit margins → focus on scaling.

📚 Books & Beauty categories contribute smaller shares but have stable demand.

Customer Behavior

👤 A small set of repeat customers drives a large share of sales (Pareto principle: 20% customers ≈ 80% sales).

🚀 Identifying & rewarding these loyal customers can further boost retention.

Payment Mode Trends

💳 UPI is the most preferred payment method → indicates shift toward digital payments.

📦 Cash on Delivery still present → shows need to manage logistics & risk.

Profitability by Sub-Category

🏆 Some sub-categories (e.g., Footwear, Kitchen Appliances) are highly profitable.

⚠️ A few categories show negative profit (returns/discounts) → require attention to pricing & cost structure.

✅ These insights can guide strategic business decisions:

#Focus on festive sales campaigns.

1.Invest in high-margin categories like Clothing.

2.Expand into underperforming states.

3.Strengthen digital payment offers.

4.Build loyalty programs for repeat customers.

#Screenshot/ demo :- https://github.com/araj8416-sudo/-E-commerce-Sales-Dashboard-/blob/main/snapshot%20of%20the%20Dasboard.PNG

👤 Author

Abhishek Kumar
Data Analyst | Power BI | SQL | Excel | Tableau
