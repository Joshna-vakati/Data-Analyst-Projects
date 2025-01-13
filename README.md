# Provide Insights to the Revenue Team in the Hospitality Domain

### dashboard link : https://app.powerbi.com/groups/5633cdb8-4796-4a1e-991a-62a85d826cc1/reports/5abd4be1-92d4-4ff5-b12c-626bb6039484/ReportSectionce2063a216d8e001051e?experience=power-bi

## problem statement

AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. 
Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Grands are losing its market share and revenue in the luxury/business hotels category. 
As a strategic move, the managing director of AtliQ Grands wanted to incorporate “Business and Data Intelligence” to regain their market share and revenue. 
However, they do not have an in-house data analytics team to provide them with these insights. Their revenue management team had decided to hire a 3rd party service provider to provide them with insights from their historical data.

## Task 
Create the metrics according to the metric list.
Create a dashboard according to the mock-up provided by stakeholders.

## Steps Followed

1. Load data into Power BI Desktop using folder, dataset is a CSV files.
2. Transform the data using power Query editor, create all the tables
3. Do all neessary data cleaning like checking data types, rename files, close and apply the data
4. In the table view, u can view the tables
5. Open the model view and created the star schema using manage relationsships.
6. Created the dax formulas for rhe dim date table, as friday and satuerday are the weeknds 
7.created some of the measiures like

Revenue = SUM(fact_bookings[revenue_realized])
Total Succesful Bookings = SUM(fact_aggregated_bookings[successful_bookings])
Total Bookings = COUNT(fact_bookings[booking_id])
Occupancy % = DIVIDE([Total Succesful Bookings],[Total Capacity],0)

8. Visual filters (Slicers) were added for four fields named City, Status, Week, Month.



