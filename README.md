# sales_dashboard
### Dashboard Link : 
## Problem Statement

This dashboard helps the sales understand their customers better. It helps the supersales know if their customers are satisfied with their services.A retail company wants to better understand its sales performance across different regions, products, and customer segments. Despite having large amounts of data, they are unable to make quick, data-driven decisions due to a lack of visual insights.
The goal of this project is to analyze retail sales data and create an interactive Power BI dashboard that provides insights into:

-Overall sales trends over time

-Top-performing products and categories

-Regional sales performance

-Customer behavior and segmentation

-Profitability analysis
This analysis will help stakeholders identify growth opportunities, underperforming areas, and make informed business decisions to boost revenue and efficien


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except column named "Arrival Delay".
- Step 5 : For calculating average delay time, null values were not taken into account as only less than 1% values are null in this column(i.e column named "Arrival Delay") 
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 8 : Visual filters (Slicers) were added for provide interactivity, allowing users to filter the dashboard by Order Date, Region, State, Segment, Category, and Sub-Category
 - Step 9 : Three card visuals were added to the canvas, one representing Total Revenu & other representing Total Profit and Total Quantity Using the Card" visualization.
- Step 10 : Created bar and column charts to show Sales and Profit trends by Year, Segment, and Category, helping identify performance patterns over time and Used a map visualization to analyze Sales by Region, enhancing the geographical insight of the business performance. 
- Step 11 : Designed a matrix or table view for detailed analysis of Sales, Profit, and Quantity at the City and Sub-Category level and Added tooltip and formatting enhancements to make the visuals more readable, such as labeling data points, setting proper legends, and adjusting color schemes
- Step 12 : In the report view, under the insert tab, two text boxes were added to the canvas, in one of them name of the airlines was mentioned & in the other one company's tagline was written.
- Step 13 : In the report view, under the insert tab, using shapes option from elements group a rectangle was inserted & similarly using image option company's logo was added to the report design area. 
- Step 14 : Calculated column was created in which, customers were grouped into various age groups.

for creating new column following DAX expression was written;

       Total Sales = SUM(Sales)

       Total Profit = SUM(Profit)

       Total Quantity = SUM(Quantity)

Time-based calculations using YEAR(), QUARTER(), CALCULATE()
###  Snapshot of Dashboard Sales Dashboard

![Image](https://github.com/user-attachments/assets/956df891-9e3c-4c44-ad6b-4eaf8104f2f6)

### Snapshot of Dashboard Region and state level Analysis

![Image](https://github.com/user-attachments/assets/7642eb82-610f-43a5-87d6-4708b89edecc)

 ### snapshot of dashboard Category and sub-category level analysis 
        
![Image](https://github.com/user-attachments/assets/e1f2b2f5-baac-4c36-b428-143feca20666)
 

 
 

 

