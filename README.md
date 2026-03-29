
🏨 AtliQ Hospitality Dashboard — Power BI
A comprehensive hospitality analytics dashboard built in Power BI to analyze the revenue, occupancy, and booking performance of AtliQ Hotels — a fictional hotel chain operating 25 properties across 4 major Indian cities (Bangalore, Delhi, Hyderabad, Mumbai) over a 3-month period (May–July 2022)
📊 Project Highlights

Total Revenue Analyzed: ₹1,708.8 Million
Total Bookings: 134,600+
Occupancy Rate: 57.9%
Cancellation Rate: 24.8%
Average Guest Rating: 3.6 / 5

🗂️ Data Model (Star Schema)
dim_date Dimension
dim_hotels Dimension
dim_rooms Dimension
fact_bookings Fact
fact_aggregated_bookings Fact

📁 Dashboard Pages

Main Dashboard — KPI cards, property-level performance table, filters by city, room type & week
Revenue by Week & Category — Luxury vs. Business revenue trends across 14 weeks
Revenue by Booking Type — Platform-wise booking volume and revenue (OTA vs. Direct)
Bookings by Week — Weekly booking trends broken down by room type

🛠️ Tech Stack

Power BI Desktop — Dashboard & Visuals
Power Query — Data Transformation
DAX — KPI Calculations (RevPAR, ADR, DSRN, DBRN, DURN, Realization%)
Star Schema — Data Modelling

📌 Key Metrics Tracked
Revenue RevPAR ADR Occupancy% DSRN DBRN DURN Realization% Cancellation% Avg Rating
