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

<img width="717" height="513" alt="image" src="https://github.com/user-attachments/assets/7a941570-65d7-484b-9477-5a77279cfc85" />

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

## KPI Metrics
<img width="509" height="168" alt="KPI Metrics" src="https://github.com/user-attachments/assets/3899c504-6c9a-462f-80a0-2d769489cd59" />

### Key Findings
1. **Revenue Performance:** 21.4K orders generated $817.9K in annual revenue.
2. **Order Behavior:** 49.6K pizzas across 21.4K orders, averaging roughly 2 pizzas per order.
3. **Monthly Performance:** July recorded the highest revenue and order volume.
4. **Peak Demand:** Friday was the strongest sales day, with a pronounced peak during lunch hours.







