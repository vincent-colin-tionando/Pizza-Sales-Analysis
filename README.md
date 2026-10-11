# Pizza-Sales-Analysis
Understanding what drives pizza sales performance through Revenue, Orders, Quantity, and AOV in 2017

## Table of Contents
- [Business Problem](#business-problem)
- [Data Profile](#data-profile)
- [Business Objectives](#business-objectives)
- [KPI Metrics](#kpi-metrics)
- [Analysis](#analysis)
- [Dashboard](#dashboard)
- [Business Recommendations](#business-recommendations)
---

## Business Problem
The lack of structured sales performance analysis makes it difficult to identify sales trends, customer ordering patterns, and opportunities to improve pizza sales performance. 

The business also needs to evaluate which pizza products should be retained, improved, or potentially removed based on their sales performance.

## Data Profile
A year's worth of sales from a fictitious pizza place, including the date and time of each order and the pizzas served, with additional details on the type, size, quantity, price, and ingredients.

Source:
https://mavenanalytics.io/data-playground/pizza-place-sales

The dataset consists of three tables with **48,620 records** covering a full year of pizza sales transactions.

| Table | Description |
|-------|-------------|
| `order_details` | Line-item details per order (`order_details_id`, `order_id`, `pizza_id`, `quantity`) |
| `orders` | Order-level data (`order_id`, `date`, `time`, `Day Name`) |
| `pizzas` | Pizza details data (`pizza_id`, `pizza_type_id`, `name`, `size`, `category`, `ingredients`, `price`) |
---

## Business Objectives
- Analyze Revenue, Orders, Quantity, and AOV performance.
- Identify sales trends and ordering patterns. 
- Evaluate the performance of individual pizza products. 
- Identify high-performing and underperforming products. 
- Provide recommendations for menu portfolio optimization. 
<img width="802" height="252" alt="image" src="https://github.com/user-attachments/assets/0d80d227-7353-4beb-8bfe-f46556ecd421" />


