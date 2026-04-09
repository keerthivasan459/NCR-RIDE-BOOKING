# NCR-RIDE-BOOKING

Introduction

The NCR Ride Bookings Dataset provides detailed information on ride-hailing activity within the National Capital Region (NCR). This dataset captures operational, customer, and financial aspects of ride bookings, offering a comprehensive view of the ride-sharing ecosystem in a busy metropolitan area.

The purpose of this analysis is to explore patterns in ride bookings, understand customer preferences, identify operational bottlenecks, and uncover business insights that can guide decision-making for ride allocation, pricing, and improving overall customer satisfaction.

1. Project Overview

This project analyzes a ride-booking dataset for the NCR region to uncover operational patterns, customer preferences, and business insights.
The main goal is to improve decision-making for ride allocation, pricing, and customer satisfaction.

2. Dataset Description
Source: Ride-booking company data (NCR)
Columns Include:
Date, Time
Vehicle Type
Pickup & Drop Locations
Booking Status
Booking Value
Payment Method
Avg VTAT (Vehicle Arrival Time)
Avg CTAT (Customer Arrival Time)
Customer Rating
Ride Distance

3. EDA (Exploratory Data Analysis)
Steps Performed:
Data Understanding – Check dataset shape, column names, and data types
Data Cleaning – Handle missing values, remove duplicates, fix data types
Univariate Analysis – Booking status, vehicle type, payment methods, ride distance, booking value
Bivariate / Multivariate Analysis – Booking value vs vehicle type, ratings vs wait time, cancellations by vehicle type, revenue by location
Statistical Analysis – T-Test, ANOVA for significant differences
Time-Based Analysis – Peak booking hours, busiest days, monthly trends
Advanced KPIs – Cancellation rate, ride completion rate, average revenue per ride, revenue per KM, average wait time
Customer Experience Analysis – Ratings vs wait time, best/worst rated vehicle types, ratings by location
Geographic Insights – Top pickup/drop locations, high revenue locations, high cancellation locations

4. Key Insights
Booking Completion Performance: Most bookings are successfully completed, indicating operational stability.
Vehicle Type Demand: Customer demand varies across vehicle types.
Payment Preference: Digital payments are widely preferred.
Revenue Hotspots: Revenue is concentrated in key pickup locations.
Wait Time Impact: Higher wait times negatively affect customer satisfaction.

5. Recommendation

Implement data-driven driver allocation and operational optimization by increasing driver availability in high-demand locations and peak hours, reducing wait times and cancellations to improve customer satisfaction and maximize revenue.

6. Visualizations
   
Bar charts: Vehicle type bookings, revenue by location
Pie charts: Payment methods distribution
Line charts: Monthly booking trends, peak hours
Scatter plots: Ratings vs wait time, booking value vs distance
Heatmaps: Correlation between numerical features

7. Tools & Libraries
   
Python Libraries: pandas, numpy, matplotlib, seaborn, plotly, scipy
Notebook: Jupyter Notebook (.ipynb)
Data Analysis Techniques: EDA, descriptive statistics, hypothesis testing (T-Test, ANOVA), KPI calculations

8.Conclusion

The analysis of the NCR ride bookings dataset provides valuable insights into operational efficiency, customer behavior, and revenue generation. Key findings include strong ride completion rates, varying demand across vehicle types, a preference for digital payments, and revenue concentration in specific locations.

Higher wait times were found to negatively impact customer satisfaction, highlighting the importance of timely ride allocation. Implementing data-driven strategies, such as optimizing driver availability during peak hours and at high-demand locations, can reduce cancellations, improve customer experience, and maximize revenue.

Overall, this project demonstrates how data analysis can guide strategic decisions in ride-sharing operations and enhance both business performance and customer satisfaction.
