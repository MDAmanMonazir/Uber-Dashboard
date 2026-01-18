# Uber-Dashboard


🚗 **Urban Mobility Insights: Uber Ride Analytics Dashboard**

A comprehensive, interactive data visualization tool designed to analyze Uber's ride-sharing operations, focusing on ride patterns, driver performance, revenue trends, and service efficiency across different urban areas.

### 2. Short Description / Purpose

The Urban Mobility Insights Dashboard is a powerful Power BI report created to provide deep insights into Uber's operational and financial performance. It helps stakeholders explore key metrics related to ride volume, fare structures, demand hotspots, and temporal patterns. This tool is intended for use by operations managers, financial analysts, data scientists, and marketing teams to make data-driven decisions that enhance service delivery and profitability.

### 3. Tech Stack

The dashboard was built using the following tools and technologies:<br>

*   📊 **Power BI Desktop** – Primary platform used for creating the interactive report and visualizations.<br>
*   📂 **Power Query** – Utilized for ETL (Extract, Transform, Load) processes, including data cleaning, merging, and preparation.<br>
*   🧠 **DAX (Data Analysis Expressions)** – Employed for creating complex calculations, custom measures, and key performance indicators (KPIs).<br>
*   📝 **Data Modeling** – A relational model was established between key data tables (e.g., Rides, Drivers, Locations, Payments) to enable robust filtering and analysis.<br>
*   📁 **File Format** – .pbix for the source file and .png for static previews.

### 4. Data Source

**Source:** Anonymized transactional data from Uber's internal ride-sharing database.

The dataset includes comprehensive information on hundreds of thousands of rides, detailing pickup/drop-off locations, timestamps, trip duration, distance, fare components (base fare, surge pricing), and service type (e.g., UberX, Uber Black, Uber Pool).

### 5. Features / Highlights

*   **Business Problem**

    In the highly competitive ride-sharing market, operational efficiency and customer satisfaction are paramount. Key business questions often arise, such as:
    *   Where and when does the highest demand occur?
    *   How does surge pricing impact ride volume and revenue?
    *   Which service types are the most profitable?
    *   What are the primary factors influencing trip duration and cost?

    Answering these requires a dynamic tool to sift through massive amounts of data and uncover actionable patterns.

*   **Goal of the Dashboard**

    To provide a centralized, interactive platform that:
    *   Visualizes key operational and financial metrics in an intuitive manner.
    *   Identifies demand hotspots and temporal trends to optimize driver allocation.
    *   Analyzes the effectiveness of pricing strategies and their impact on revenue.
    *   Empowers managers to monitor performance and drive strategic initiatives.

*   **Walkthrough of Key Visuals**

    -   **Key KPIs (Top Banner)**
        *   **Total Rides:** Overall count of completed trips.
        *   **Total Revenue:** Sum of all fares collected.
        *   **Average Fare:** The average cost per ride.
        *   **Active Drivers:** Number of unique drivers who completed at least one trip.
        *   **Average Trip Distance:** Mean distance covered per ride.

    -   **Demand Heatmap (Map Visual)**
        An interactive map displaying pickup and drop-off hotspots, allowing users to visually identify areas of high demand.

    -   **Rides by Hour of Day & Day of Week (Bar/Line Chart Combo)**
        A combination chart that illustrates ride volume fluctuations throughout the day and across the week, highlighting peak and off-peak hours.

    -   **Revenue vs. Distance by Service Type (Scatter Plot)**
        A scatter plot that shows the relationship between the fare charged and the distance of the trip, color-coded by the Uber service type (UberX, Black, etc.).

    -   **Revenue Trend Analysis (Area Chart)**
        An area chart displaying total revenue over time (e.g., daily, weekly, or monthly) to track financial performance and seasonality.

    -   **Fare Component Breakdown (Stacked Bar Chart)**
        A chart that breaks down the average fare into its core components: base fare, distance charge, time charge, and surge multiplier, helping to analyze the pricing structure.

*   **Business Impact & Insights**

    *   **Operational Efficiency:** By identifying demand hotspots, operations teams can implement strategies for dynamic driver positioning, reducing wait times and improving service reliability.
    *   **Dynamic Pricing Strategy:** Analyzing the impact of surge pricing helps in refining algorithms to maximize revenue without significantly deterring customers.
    *   **Marketing and Promotions:** Insights into low-demand periods or areas can inform targeted promotional campaigns to stimulate user activity.
    *   **Financial Planning:** Clear visibility into revenue trends and fare structures aids in financial forecasting and strategic planning for market expansion.

### 6. Screenshots / Demos

Show what the dashboard looks like.

*Example:* 
![Dashboard Preview](https://github.com/MDAmanMonazir/Uber-Dashboard/blob/main/Screenshot%20of%20Dashboard.png?raw=true)
