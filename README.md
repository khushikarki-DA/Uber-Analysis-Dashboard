# Uber Trip Analysis – Power BI Dashboard

# Project Overview

This project focuses on analysing Uber trip data to understand booking behaviour, revenue trends, and trip efficiency. Using Power BI, interactive dashboards were created to explore key performance indicators such as total bookings, revenue generated, trip distance, and trip duration.

This dashboards helps in identifying peak demand periods, popular pickup and drop-off locations, and customer travel patterns. These insights can support better decision-making for pricing strategies, driver allocation, and service optimization.

# Business Problem

Ride-hailing companies like Uber generate large volumes of trip data daily. However, without proper analysis it is difficult to understand:
- When demand for rides is highest
- Which locations generate the most bookings
- Which vehicle types are most preferred
- How trip distance and duration impact revenue
- How booking trends vary across time
- This project solves these problems by bui

# Objectives

- Analyse booking trends and revenue performance.
- Understand trip behaviour in terms of distance and duration.
- Identify high-demand locations and preferred vehicle types.
- Explore booking patterns across different time intervals.
- Provide actionable insights through interactive visualizations.

# Tools & Technologies

- Power BI
- DAX (Data Analysis Expressions)
- Power Query
- Data Modeling

# Key KPIs

- The dashboard tracks the following metrics:
- Total Bookings – Total number of Uber trips
- Total Booking Value – Total revenue generated
- Average Booking Value – Revenue per trip
- Total Trip Distance – Distance covered by all trips
- Average Trip Distance – Average distance travelled per trip
- Average Trip Time – Average trip duration

# Dashboard 1: Overview Analysis

This dashboard provides a high-level view of booking trends and trip performance.
Key Features
- KPI cards for booking metrics
- Measure Selector using Disconnected Table
- Dynamic visuals based on selected measure
  
Analysis by:
Payment Type
Trip Type (Day/Night)
Vehicle Type performance grid
Daily booking trends
Dynamic titles and interactive slicers
Business Insights
Identify peak booking days
Understand payment preferences
Compare vehicle performance
Analyse booking value trends
Location Analysis
Location analysis helps in optimizing driver distribution and demand forecasting.

Key Analysis
- Most Frequent Pickup Location
- Most Frequent Drop-off Location
- Top 5 Locations by Bookings
- Most Preferred Vehicle by Pickup Location
- Farthest Trip Analysis
- Advanced DAX calculations were used to identify:
- Longest distance trip
- Drop-off location using lookup relationships
- Dynamic location-based measures

# Dashboard 2: Time Analysis

This dashboard focuses on ride demand patterns based on time.
Visualizations
- Area Chart → Bookings by 10-minute pickup intervals
- Line Chart → Bookings by Day of Week
- Heatmap → Bookings by Hour vs Day

Business Value
- Identify peak demand hours
- Analyse weekday vs weekend ride patterns
- Help optimize driver availability

# Dashboard 3: Trip Details (Drill-Through)

This dashboard provides granular trip data.
Features
- Detailed grid table with trip level data
- Drill-through from other visuals
- Bookmark to toggle between filtered and full dataset
- Advanced Power BI Features Used
- Disconnected Table for dynamic measure selection
- Dynamic titles using DAX
- Drill-through navigation
- Conditional formatting
- Bookmarks for user interaction
- Clear slicer button
- Interactive tooltips

# Business Impact
This dashboard helps stakeholders:
Optimize driver allocation during peak demand
Improve pricing strategies based on trip patterns
Identify high-demand pickup and drop-off areas
Understand customer booking behaviour

