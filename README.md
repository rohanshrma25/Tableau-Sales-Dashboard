# Superstore Sales Overview Dashboard

Link to dashboard : https://public.tableau.com/app/profile/rohan.sharma1268/viz/SuperstoreSalesDashboard_17156077177330/Dashboard

## Overview
The Superstore Sales dashboard provides a detailed analysis of sales data from the Superstore dataset. It aims to help users understand sales trends, profitability, and product performance. This dashboard offers valuable insights via KPI cards and visuals.

## Features

* KPI's:  
  Key performers such as Sales, Profit, Avg Order Value, Avg Profit Margin, Avg Shipping Cost at the top.
  
* Market bifurcation based on chosen metric(Profit/Sales):    
A bar graph showcasing profit/sales distribution across global markets (e.g., APAC, EU).  
Helps identify which markets contribute significantly to overall profit/sales.  
  
* Category distribution:  
A pie chart breaking down profits/sales by product category.  
Useful for understanding which categories drive the most profit/sale.  
  
* Profit/Sales over Months:  
A colorful line chart depicting monthly profit/sales trends over a year.  
Observe seasonal patterns and identify peak months.    
  
* Profit/Sales by Country:  
A world map shaded according to profit/sales levels in different countries.  
Quickly spot high-profit/sales regions and potential growth areas.

* Sub Category profits/sales:  
A bar graph highlighting profits/sales from top sub-categories.  
Useful for focusing on specific product segments.  
  
* Avg Shipping Cost wrt Order Priority:  
Shows shipping costs associated with different order priorities across markets.  
Helps optimize shipping strategies.  
Used LOD (Level of Detail) to find avg shipping cost of each market irrespective of other parameters.
 
<img src="https://github.com/rohanshrma25/Tableau-Sales-Dashboard/assets/143126097/b90d2461-b94f-4bfa-89c4-00bb6f022a4a" width="400" height="200">  
  
* Best Selling Products:  
Lists top-selling products along with their respective total sales.  
Useful for inventory management and marketing decisions.  

## Dashboard Interactivity  
The dashboard offers couple of interactive features to empower user in exploring and analyzing the data:  

* Filtering Options:
User can filter the whole data using the year filter provided at top right. Also, metric filter provided with first container lets the user to filter dashboard based on 'profit' or 'sales'. This allows for a customized view of the metrics according to specific year.  
Created a parameter and its dedicated calculated field which lets the user to select metric 
<img src="https://github.com/rohanshrma25/Tableau-Sales-Dashboard/assets/143126097/deef3d3d-5988-444d-a57d-650dc3cb8e27" width="500" height="550">  
  
<img src="https://github.com/rohanshrma25/Tableau-Sales-Dashboard/assets/143126097/8a04dc1e-6228-4819-8fa9-f2499fe05cfa" width="400" height="200">  

* Hover Interactions:
Hovering over data points or visual elements provides users with additional information, such as exact values, percentage breakdowns, or tooltips explaining trends and patterns.  

## Installation & Usage
Install Tableau Desktop if you want to explore the dashboard interactively.  
Clone this repository:  https://github.com/rohanshrma25/Tableau-Sales-Dashboard  
Open the .twb file in Tableau Desktop to view the dashboard.  
