# Financial-Consumer-Complaints-Tracker-Dashboard-in-Excel

Introduction:
A dynamic financial dashboard tracker is a functional and automated reporting tool which helps by transforming raw customer complaint data into visual insights. The process begins by creating pivot tables to track essential key performance indicators (KPIs), such as total complaint counts and resolution rates. To make the data interactive, I implemented slicers and timelines, which allowed me to filter information by specific dates or product categories across all charts simultaneously. For visualizations I used bar charts for subproduct rankings, line graphs for chronological trends, and a geographic map for location-based analysis. By linking text boxes and shapes to underlying data cells,it has been possible to maintain real-time updates within a professional layout.

Steps:
To create this interactive Excel dashboard, I followed these steps:

Prepared the KPI Pivot Tables: I started by creating several pivot tables from the raw data to track core metrics
. I calculated the total number of complaints, the percentage of those resolved with a timely response (which was 96.06%), and the number of complaints currently in progress
.
Analyzed Product and Subproduct Data: I created another pivot table to see the number of complaints by product and subproduct
. I sorted these by the count of complaints and filtered for the top 10
. To ensure "blank" entries didn't appear in my top 10 list, I adjusted the pivot table options to allow multiple filters
.
Analyzed Trends and Geography: I set up a pivot table to find trends over time by adding the "date received" and grouping it by years and months
. I also pulled in state information to prepare for a geographic visualization
.
Added Interactive Filters: To make the dashboard dynamic, I inserted a Timeline for the date received and a Slicer for the products
. I used Report Connections to link the timeline to every pivot table
. For the product slicer, I connected it to all tables except the specific "product" pivot table to avoid redundant filtering
.
Designed the KPI Cards: On a new dashboard tab, I built KPI cards using text boxes and shapes
. I made each shape equal to the corresponding cell in my pivot tables so the numbers update automatically as filters are applied
.
Created Visualizations:
I added a pie chart to show complaints by product
.
I inserted a bar chart for subproducts, setting the categories to "reverse order" so the largest values appeared at the top
.
I used a column chart to display the trend over time
.
Built the Map Visual: Because Excel does not allow you to create a map directly from a pivot table, I used a workaround
. I inserted a blank map, went to "Select Data," and manually assigned the state names as axis labels and the complaint counts as the series values
.
Tested the Functionality: Finally, I verified that the dashboard was fully dynamic
. I tested the timeline by selecting specific years and expanded the trend chart to ensure I could see data broken down by month
