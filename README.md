# Pizza-Sales-Analysis
Understanding what drives pizza sales performance through Revenue, Orders, Quantity, and AOV in 2017

## Table of Contents
- [Business Problem](#business-problem)
- [Data Profile](#data-profile)
- [Business Objectives](#business-objectives)
- [KPI Metrics](#kpi-metrics)
- [Analysis](#analysis)
- [Dashboards](#dashboards)
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

## Analysis

## Dashboards
<img width="721" height="299" alt="Revenue Dashboard" src="https://github.com/user-attachments/assets/204b01a7-a60b-429e-a484-10047a7cd551" />

<img width="722" height="298" alt="Orders Dashboard" src="https://github.com/user-attachments/assets/76e2a289-bd04-4b38-99c5-6488f3d79287" />

<img width="723" height="298" alt="Quantities Dashboard" src="https://github.com/user-attachments/assets/417175fa-c62f-4fa2-b568-19d01cdb401a" />

<img width="722" height="301" alt="AOV Dashboard" src="https://github.com/user-attachments/assets/6839f67e-5741-4da6-8d69-cd6df7643c3d" />
---

### Dashboard Features
1. Interactive Buttons for 4 dashboards
2. KPI Dashboards (Revenue, Order Volumes, Total Pizza Sold, Average Prices per Pizza, Pizzas per Order, Pizza Varieties, Revenue per Pizza)
3. Category and Size Slicers
4. Peak Month, Peak Day, Peak Hour, Pizza Categories, Top 5 Pizzas, and Bottom 5 Pizzas
7. Interactive PivotCharts

## Business Recommendations
1. **Prioritize high-demand products and peak periods**
   Focus inventory, staffing, promotions, and menu placement on Chicken/Meat pizzas, Friday, 12 PM, and 6 PM, where demand is strongest.
2. **Increase order volume during weaker periods**
   Target October, Sundays, and off-peak hours with specific promotions, bundles, and traffic-driving campaigns rather than relying mainly on price increases or upselling.
3. **Maximize high-value sales opportunities**
   Leverage Q4 holiday promotions, premium bundles, and Brie Carré’s premium positioning, while testing modest price increases or premium variants for high-volume products like Pepperoni and Hawaiian.
4. **Replicate proven performance**
   Use July’s sales patterns and June’s product/pricing mix as benchmarks, applying successful products, pricing, promotions, and timing to improve weaker months
5. **Optimize the menu portfolio using multiple performance metrics**
   Maintain and expand high-volume/high-revenue products such as Thai Chicken, Barbecue Chicken, and Classic Deluxe, while reviewing vegetable-based and consistently weak pizzas, reducing inventory or promotional investment where appropriate, while testing repositioning, bundling, or selective removal before making final menu decisions.









