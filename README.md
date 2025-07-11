OLA Data Analysis and Visualization Project
This repository showcases a comprehensive data analysis and visualization project based on OLA ride-booking data. The project explores booking patterns, revenue trends, customer and driver behaviors, and cancellation insights using SQL, Power BI, and Excel. It is designed for recruiters, collaborators, and learners interested in data analytics workflows and dashboards.

Project Objective
To analyze ride-booking data from OLA, identify patterns, and create interactive dashboards to present actionable insights into:

Booking trends over time.
Customer and driver ratings.
Revenue and cancellation analysis.
Repository Structure
This repository contains the following files and folders:

1. OLA-Data-Analyst-Project.pdf
Blueprint of the project, detailing:
SQL queries.
Power BI dashboards.
Segregation of insights and visualizations.
2. Bookings-100000-Rows.xlsx
Dataset containing 100,000+ rows with the following columns:
Date, Time, Booking_ID, Booking_Status.
Customer_ID, Vehicle_Type, Pickup_Location, Drop_Location.
V_TAT, C_TAT, Booking_Value, Payment_Method.
Ride_Distance, Driver_Ratings, Customer_Ratings.
Cancellation details and reasons.
Source for SQL queries and Power BI visualizations.
3. Ola Data Analysis.sql
SQL script with 10 structured queries to derive key insights, including the creation of reusable views:
Retrieve all successful bookings.
Calculate the average ride distance for each vehicle type.
Count the total number of rides canceled by customers.
Identify the top 5 customers by total bookings.
Analyze the number of rides canceled by drivers due to personal or car-related issues.
Find the maximum and minimum driver ratings for Prime Sedan bookings.
Retrieve all rides where payment was made using UPI.
Calculate the average customer rating per vehicle type.
Compute the total booking value of successful rides.
List all incomplete rides along with their reasons.
4. Ola Data Visualization.pbix
Power BI file with interactive dashboards, divided into 5 main sections:
Overall Trends: Ride volume over time and booking status breakdown.
Vehicle Insights: Top vehicle types by distance and ratings.
Revenue Analysis: Payment method breakdown and top spenders.
Cancellations: Reasons for cancellations by customers and drivers.
Ratings Analysis: Distribution and comparison of customer vs. driver ratings.
5. Ola-Slides
Folder containing 5 PNG images used as canvas backgrounds for the Power BI dashboards.
Slide1.png
Slide2.png
Slide3.png
Slide4.png
Slide5.png
6. Portfolio Dashboard
The complete dashboard is designed for showcasing in your portfolio, emphasizing interactive storytelling and professional design.
Dashboard Preview
Below is a snapshot of the PowerBI dashboard:

Dashboard Screenshot Dashboard Screenshot Dashboard Screenshot Dashboard Screenshot Dashboard Screenshot

Key Insights and Analysis
SQL Analysis
Successful Bookings: Identified all completed rides.
Average Ride Distance: Calculated for each vehicle type to understand efficiency.
Cancellation Insights:
Total canceled rides (customer and driver).
Reasons for driver cancellations (personal, car issues, etc.).
Top Customers: Ranked by number of bookings and total spending.
Revenue Trends: Summarized booking values for successful rides.
Ratings Distribution: Analyzed by vehicle type for customer and driver performance.
Power BI Dashboards
Ride Volume Over Time: Trends in ride bookings across days and weeks.
Booking Status Breakdown: Pie charts illustrating success, cancellations, and incomplete rides.
Revenue Breakdown: Bar charts by payment method and customer value.
Cancellation Reasons: Segmented by customers and drivers for actionable insights.
Rating Comparisons: Driver and customer ratings are compared across various vehicle types using card visuals.
How to Use the Repository
Clone or Download:

Clone this repository using Git or download it as a ZIP file.
SQL Queries:

Load the Bookings-100000-Rows.xlsx dataset into your database (e.g., MySQL, PostgreSQL).
Run the queries in Ola_Data_Analysis.sql to generate insights.
Power BI Dashboard:

Open Ola_Data_Visualization.pbix in Power BI Desktop.
Explore the dashboards and interact with filters for detailed insights.
Portfolio Showcase:

Include the Power BI file to demonstrate interactive dashboarding skills.
Tools and Technologies Used
SQL: For querying and extracting insights from the dataset.
Excel: To handle large datasets and initial data exploration.
Power BI: For creating interactive dashboards and visual storytelling.
Future Enhancements
Integrate Python for predictive analytics and ride-demand forecasting.
Expand dashboards with additional drill-through and tooltips for enhanced interactivity.
Automate data pipelines for real-time dashboard updates.
