# Sales-Dashboard
##Basic PowerBi project with MySQL database

##Objective
The objective of this Sales Dashboard Project is to provide a dynamic, interactive, and user-friendly solution for analyzing sales performance data across multiple dimensions. The dashboard enables business users and decision-makers to:

- Monitor key sales metrics such as Total Sales, Number of Units Sold, and Number of Customers at a glance.
- Analyze sales trends over time (July to October) to identify seasonal patterns and performance improvements.
- Understand the contribution of different Product Categories and Top Products to total sales revenue.
- Explore geographic distribution of sales with the City-level Sales Map, enabling identification of high-performing regions.
- Segment and filter data by Gender, Product Category, Time Period, and Geography for targeted insights.
- Quickly access predefined views through interactive Buttons and Slicers for efficient data exploration.
- Support data-driven decision-making by providing actionable insights on sales performance and customer behavior.

This dashboard empowers stakeholders to analyze sales data interactively, detect trends, evaluate performance, and make informed strategic decisions in a visual and intuitive manner.

#QUESTIONS
- What is the total sales value and number of units sold during the observed period?

- Which category contributes the most to total sales in terms of quantity and revenue?

- How does sales performance vary by month from July to October?

- Identify the top five states contributing to sales and their percentage shares.

- Which products have the highest sales revenue and how much do they contribute individually?

- How is customer distribution segmented by gender, and how can it be filtered in the dashboard?

- What interactive features (e.g., slicers, filters, buttons) are available in the dashboard to customize the data view?

- Based on the map visualization, which cities have the highest total sales?

#PROCESS
- Navigate to the KPI Cards or Summary section in the dashboard.
- The cards titled TOTAL SALES and NO. OF UNITS SOLD display aggregated values automatically.
- Inspect the Pie Charts labeled "Sum of Quantity by Category" and "Sales by Category."
  
- Hover over each segment to view exact percentages or use the tooltip.
- Alternatively, apply a Category Slicer to filter visuals and confirm by observing the highest share.
  
- Analyze the "Sales by Month" area chart.
- The x-axis shows months (July to October), and the y-axis shows sales amount.
- Hover over each bar/point to view exact sales numbers per month.
- Optionally, use a Date Slicer to filter months and observe changes in other visuals.

- Look at the "Sales by Top 5 States" Pie Chart.
- Hover over each slice to see the state name and corresponding percentage share.
- To adjust or confirm the top 5 states, use a Top N Filter in Power BI.

- Use the "Sales by Product" Bar Chart.
- The length of each bar represents sales revenue per product.
- Hover over bars to see precise sales values (e.g., Laptop: 0.28M).
- Sort the visual descending by sales revenue to rank products.

- Find the Gender slicer/filter (shown as checkboxes: Female, Male)

- Slicers:
Allow selection by Gender, Date, Product Category, etc.
- Buttons:
Example: "Accessories", "Electronics", "Fashion", "Home Appliances" → Apply predefined filters/bookmarks.
- Date Buttons:
Buttons for July, August, September, October → Apply time-based filters.
- Cross-filtering:
Clicking any visual element (e.g., a bar in "Sales by Product") filters related visuals.

- Observe the "Total Sales by City" map visual.
- The size of the blue circles represents sales volume.
- Hover over each city bubble to see exact sales numbers.
- Cities with larger circles (e.g., New Delhi, Mumbai) indicate higher sales.

##DASHBOARD
<img width="879" height="491" alt="Screenshot (2)" src="https://github.com/user-attachments/assets/b596a44b-35c3-4216-bb6b-6d345934ee70" />
