
# Blinkit Sales Dashboard

### Dashboard Link :https://app.powerbi.com/groups/me/reports/1b11dcc4-368a-46bf-bfa8-688c32f80921/7397ab5c7631dc5441c2?experience=power-bi

## Problem Statement

This dashboard is designed to help Blinkit—India's Last Minute App—analyze sales performance across various outlets. By providing insights into total sales, average sales, item types, ratings, and number of items sold, Blinkit can enhance its business strategies by focusing on key areas like outlet size, location, item types, and outlet establishment history.

The dashboard reveals that Total Sales reached $4.79K, with an Average Sales of $133 per item. Moreover, 36 items are listed, with an Average Rating of 3.6. Sales are categorized based on Fat Content, Outlet Size, Outlet Location, and Outlet Type, allowing Blinkit to identify top-performing outlets and adjust inventory or promotional strategies accordingly.


### Steps followed 

Step 1: Loaded the dataset into Power BI Desktop (CSV format).

Step 2: Opened Power Query Editor, checked data distribution and quality using "Column Distribution", "Column Quality", and "Column Profile" options.

Step 3: Applied Column Profiling based on the entire dataset to get an overview of missing values and errors. For the "Fat Content" and "Item Type" columns, no errors or missing values were found.

Step 4: Created slicers for Outlet Location, Outlet Size, and Item Type to allow dynamic filtering of the data.

Step 5: Visualized Total Sales ($4.79K) using a Card Visual and created additional cards for Average Sales ($133), Number of Items (36), and Average Rating (3.6).

Step 6: Added a Line Chart to represent the Outlet Establishment Timeline, showing sales trends from 2016 to 2020. The highest sales in a single year were $1,439.30 in 2018.

Step 7: Included a Pie Chart to visualize Fat Content (Regular vs. Low Fat), showing total sales distribution between these two categories, with Regular accounting for $2.43K and Low Fat for $2.36K.

Step 8: Used a Donut Chart to depict sales based on Outlet Size. Here, the focus is on Small outlets, accounting for the entire $4.79K in sales.

Step 9: Added a Bar Chart to highlight the Item Type (Breakfast), which contributes $4.8K in sales. This visual also segments the sales based on Fat Content and Outlet Location.

Step 10: Incorporated a Table Visual to show a breakdown of Outlet Type (Grocery Store vs. Supermarket Type 1), including total sales, number of items, average sales, average ratings, and item visibility for each type. For example:

        Grocery Store: $1.28K total sales, 10 items, 4.0 average rating, and 0.15 item visibility.
        Supermarket Type 1: $3.51K total sales, 26 items, 4.0 average rating, and 0.08 item visibility.

Step 11: Added Text Boxes for branding, including the Blinkit logo, tagline "India's Last Minute App", and a reset button for easy filter clearing.

# Snapshot of Dashboard (Power BI Service)

![dashboard_snapo]![Screenshot 2024-10-15 201544](https://github.com/user-attachments/assets/695e46e8-d4cb-4377-a4d9-a7e3034f9d92)



 


# Insights

### [1] Total Sales and Average Sales

Total Sales: $4.79K, spread across various items and outlets.

Average Sales: $133 per item sold.

           
### [2] Outlet Location and Size
Tier 1 outlets contributed $2.48K, while Tier 2 contributed $2.31K.

Sales are concentrated in Small outlets, as indicated by the pie chart, which shows 100% of sales coming from this category.
  

  
  ### [3] Item Types and Ratings
  
Item Type (Breakfast): Major contributor to sales, totaling $4.8K.

Fat Content: Sales are split almost equally between Regular ($2.43K) and Low Fat ($2.36K) categories.

 ### [4] Outlet Type and Customer Preferences
Supermarket Type 1 dominates with $3.51K in sales compared to $1.28K for Grocery Stores.

Supermarket Type 1 also has more items listed (26) compared to Grocery Stores (10), though both have the same average rating (4.0).
         
### [5] Sales Over Time
From 2016 to 2020, sales grew significantly, peaking in 2018 with $1,439.30 and showing a slight decline afterward.


## Recommendations
Blinkit should focus on improving the Item Visibility for Grocery Stores (currently 0.15) to increase sales.

Further marketing efforts can be directed at Breakfast items and Tier 1 outlets, which show the highest sales performance.
# Publishing
The report was successfully published to Power BI Service, making it accessible for real-time updates and insights.
