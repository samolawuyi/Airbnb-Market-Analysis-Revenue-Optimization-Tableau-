# Airbnb-Market-Analysis-Revenue-Optimization-Tableau-
This project analyzes Airbnb listing data to identify pricing trends, seasonal demand, and geographic revenue hotspots. By visualizing the relationship between bedroom counts, pricing, and location, this dashboard serves as a decision-support tool for potential real estate investors or short-term rental hosts to optimize their listing strategy.

Data Architecture & Cleaning
​Source Integration: Processed a comprehensive dataset containing listing IDs, geographic coordinates, pricing, and property attributes.

​Data Transformation: Performed data type adjustments and cleaning within Tableau’s data source layer to ensure accurate map rendering and currency calculations.

​Field Organization: Structured data into logical dimensions (Location, Room Type) and measures (Price, Revenue) for seamless drill-down analysis.

​Key Visualizations & Market Insights
​Price Evolution by Year (Trend Analysis)
​Visualization Type: Dual-axis line and area chart.

​Insight: Tracks the average price per bedroom from 2016 through the end of the year.

​Technical Detail: Utilized AVG(Price) against Year(Week) to identify long-term market growth and pricing stability.

​Revenue vs. Property Size (Profitability Metrics)
​Visualization Type: Ranked Horizontal Bar Chart.
​Insight: Analyzes which property configurations (e.g., 1-bedroom vs. 4-bedroom) generate the highest total revenue.

​Business Value: Helps investors understand the "sweet spot" for property acquisition based on historical earnings.

​Geographic Distribution & Pricing Hotspots
​Visualization Type: Interactive Symbol Map.
​Insight: Maps individual listings across the city using Latitude and Longitude.

​Visual Encoding: Uses a color gradient to distinguish high-priced luxury listings from budget-friendly options, allowing for micro-market analysis at the neighborhood level.

​Bedroom-Count Pricing Matrix
​Visualization Type: Sorted Bar Chart.
​Objective: Compares the average price of listings based on the number of bedrooms.

​Logic: Calculated AVG(Price) for categories ranging from 1 to 6+ bedrooms to set competitive baseline pricing.

Technical Skills Demonstrated
​Geospatial Mapping: Plotting complex coordinate data for location-based intelligence.

​Time-Series Forecasting: Analyzing year-over-year pricing trends.

​Calculated Fields: Aggregating revenue and average pricing across different property segments.

​Dashboard Design: Creating a unified visual story that moves from high-level trends to specific property insights.
