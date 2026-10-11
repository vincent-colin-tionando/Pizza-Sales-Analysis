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
### Monthly Performances
<img width="476" height="248" alt="Screenshot 2026-10-12 040629" src="https://github.com/user-attachments/assets/d2fe5e5f-c648-495b-b12c-5d8feda0b54a" />
1. **July** was the best-performing month, generating **$72.6K in revenue, 1.9K orders, and 4.4K pizzas sold.**
2. **October** was the lowest-performing month, with **$64K in revenue, 1.6K orders, and 3.9K pizzas sold,** despite a relatively high **AOV of $38.9.**
3. **Q4** recorded the highest AOV, averaging around **$38 per order**, potentially driven by holiday spending.
4. **June** had the highest **revenue per pizza at $16.61**, generating **$68.2K in revenue from 1.8K orders and 4.1K pizzas sold**, despite lower overall sales than July.

### Daily Performances
<img width="475" height="249" alt="Screenshot 2026-10-12 040645" src="https://github.com/user-attachments/assets/6d9f7561-909f-41b1-a757-9df84a1b5ac9" />
1. **Friday** was the best-performing day, generating **$136.1K in revenue, 3.5K orders, and 8.2K pizzas sold.**
2. **Sunday** was the lowest-performing day, with **$99.2K in revenue, 2.6K orders, and 6K pizzas sold.**
3. **AOV and Revenue per Pizza** remained stable, averaging **$38 per order and $16.50 per pizza**, indicating sales differences were driven mainly by order volume.

### Hourly Performances
<img width="476" height="250" alt="Screenshot 2026-10-12 040656" src="https://github.com/user-attachments/assets/f1d332df-f98f-49ef-a894-247029294674" />
1. **12 PM** was the strongest sales hour, generating $111.9K in revenue, 2.5K orders, and 6.8K pizzas sold.
2. **6 PM** marked a secondary sales peak, generating $89.3K in revenue, 2.4K orders, and 5.4K pizzas sold.
3. **AOV and Revenue per Pizza** remained stable during operating hours at $37–$40 per order and around $16.50 per pizza, with higher early-morning averages driven by low sales volume.

### Top 5 Pizza Performances
<img width="476" height="250" alt="Screenshot 2026-10-12 040708" src="https://github.com/user-attachments/assets/475b6a78-1634-4562-a4c1-00ccabb95835" />
1. **Thai Chicken Pizza** led revenue, generating **$43.4K from 2.2K orders and 2.4K pizzas sold, at $18.32 per pizza.**
2. **Classic Deluxe Pizza** led sales volume, with **2.3K orders, 2.5K pizzas sold, and $38.2K in revenue.**
3. **Barbecue Chicken Pizza** ranked second in revenue, generating **$42.8K from 2.3K orders and 2.4K pizzas sold.**
4. **Brie Carré Pizza** had the highest revenue per pizza at **$23.65**, despite the **lowest revenue ($11.6K) and only 480 orders.**
5. **Chicken and meat pizzas** dominated performance, accounting for most of the menu’s top-performing products.

### Bottom 5 Pizza Performances
<img width="476" height="248" alt="Screenshot 2026-10-12 040727" src="https://github.com/user-attachments/assets/60076a3b-29c5-4fb0-b60b-8a295441d2f7" />
1.** Vegetable-based pizzas **dominated the bottom 5, indicating lower demand than meat-based options.
2. **Brie Carré** had the lowest total revenue at **$11.6K from 480 orders**, despite the highest **revenue per pizza ($23.65).**
3. **Spinach Supreme and Mediterranean pizzas** consistently underperformed in revenue, orders, and quantities sold.
4. **Green Garden Pizza** ranked second-lowest in revenue, generating **$14K at $14 per pizza.**
5. **Pepperoni and Hawaiian pizzas** had low **revenue per pizza at $12.47 and $13.33**, respectively, despite high order volumes.


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
   
   Focus inventory, staffing, promotions, and menu placement on **Chicken/Meat pizzas, Friday, 12 PM**, and **6 PM,** where demand is strongest.
   
2. **Increase order volume during weaker periods**
   
   Target **October, Sundays, and off-peak hours **with **specific promotions, bundles, and traffic-driving campaigns** rather than relying mainly on price increases or upselling.
   
3. **Maximize high-value sales opportunities**
   
   Leverage **Q4 holiday promotions, premium bundles, and Brie Carré’s premium positioning**, while testing modest price increases or premium variants for high-volume products like Pepperoni and Hawaiian.
   
4. **Replicate proven performance**
   
   Use **July’s sales** patterns and **June’s product/pricing mix** as benchmarks, applying successful products, pricing, promotions, and timing to improve weaker months
   
5. **Optimize the menu portfolio using multiple performance metrics**
    
   Maintain and expand high-volume/high-revenue products such as **Thai Chicken, Barbecue Chicken, **and **Classic Deluxe**, while reviewing vegetable-based and consistently weak pizzas, reducing inventory or promotional investment where appropriate, while testing repositioning, bundling, or selective removal before making final menu decisions.









