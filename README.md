# Pizza Sales Dashboard

## Overview

This dashboard project analyzes the sales performance of a pizza restaurant. It highlights customer behavior, product performance, peak operating hours, revenue trends, and provides insights to improve operational and marketing strategies.

Built using Power BI and Excel, the dashboard enables users to interact with key metrics and drill down into areas like top-performing products, daily and hourly sales trends, and sitting efficiency.

This project is powered by four interrelated CSV files that simulate the daily operations of a pizza restaurant. The dataset is organized as follows:


### Dataset Descriptions

| File | Description |
|------|-------------|
| **orders.csv** | One row per order with `order_id`, `order_date`, and `time`. Used for daily, weekly, and hourly sales analysis. |
| **order_details.csv** | Breaks down each order into individual pizzas. Contains `order_id`, `pizza_id`, `quantity`, `price`, and `line_total`. |
| **pizzas.csv** | Links each `pizza_id` to its size and base price. Useful for size filtering and pricing calculations. |
| **pizza_types.csv** | Descriptive information for each pizza including `name`, `category`, and `ingredients`. Enables category-level insights. |
| **data_dictionary.csv** | A helper file defining all fields across the datasets. Useful for quick schema reference. |

### Data Relationships


orders.order_id         →  order_details.order_id

order_details.pizza_id  →  pizzas.pizza_id

pizzas.pizza_type_id    →  pizza_types.pizza_type_id 

## Key Visuals in the Dashboard

- KPI Cards for quick business overview  
- Bar Charts showing daily product performance  
- Donut Chart visualizing category sales distribution  
- Line Graph tracking monthly revenue trends  
- Heatmap displaying hourly and daily order patterns  
- Horizontal Bars for top/least performing products

## Insights and Recommendations

- Focus marketing and inventory efforts around high-demand days and times (Fridays, 6–9 PM)  
- Promote underperforming days (e.g., Sunday) with discounts or campaigns  
- Expand promotions for best-selling items and bundle underperformers  
- Improve dine-in experience to increase seat utilization  

## Tools and Skills Used

- Data Cleaning and Preparation  
- Power BI and Excel  
- Dashboard Design and UX Principles  
- Business Insight Generation  
- Exploratory Data Analysis (EDA)

![image](https://github.com/user-attachments/assets/bb649690-f070-4e9d-a2ef-76a87f408adf)



## How to Use

1. Clone this repository  
2. Open the dashboard file in Power BI / Excel / Tableau  
3. Use the slicers and visuals to explore the data  
4. Analyze trends and extract insights

## License

This project is for educational and portfolio demonstration purposes only.

## Author
[Mary Obutwe Duodu][www.linkedin.com/in/mary-duodu-052792163]
