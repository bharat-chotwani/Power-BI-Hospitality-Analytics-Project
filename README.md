# AtliQ Grands Hospitality Analysis

# Project Overview

AtliQ Grands, a luxury/business hotel chain, has been in the hospitality industry for over 20 years. However, due to **ineffective decision-making and increasing competition,** they’ve been losing **market share and revenue.**

To address this challenge, the **Managing Director** decided to incorporate **Business and Data Intelligence** to make data-driven decisions and regain their market position.

- **Power BI Dashboard Breakdown:**

✅ **Home Page** – A landing page for seamless navigation.

✅ **Overview View** – A high-level summary of all key metrics.

✅ **Revenue Contributors View** – Insights into revenue and occupancy trends.

✅ **Booking View** – Breakdown of bookings and customer ratings.

This project enables **data-driven decision-making** and helps AtliQ Grands to track their **progress** and **stay competitive** in the market.

### [Live Dashboard Link]()

## Company Summary: AtliQ Hardware
This project aims to boost Atliq Grands' market share and revenue within the luxury business hotel sector. The company aims to surpass competitors and enhance management decision-making by applying data-driven strategies and business intelligence.

In the properties we have AtliQ Bay, AtliQ Blu, AtliQ City, AtliQ Exotica, AtliQ Grands, AtliQ Palace, and AtliQ Seasons.
There are two categories that we are offering in the Hotel.
- Luxury,
- Business.

Those properties are in Delhi, Mumbai, Hyderabad, and Bangalore.



## Data Model

The datasets contain Two types of tables -->

Dimension table: Static data like customer and product details.

Fact table: Transaction data.

- dim_date
- dim_hotels
- dim_rooms
- fact_aggregated_bookings
- fact_bookings

### What is Data Modeling?
- The process of organizing and structuring data to define relationships between tables.
- Helps in creating accurate reports and performing complex calculations.
- Ensures smooth data integration for better business intelligence and decision-making.

### Why is Data Modeling Important?
- Acts as the foundation of the report—every visual is built on the data model.
- Poor modeling can negatively impact report performance and accuracy.
- Following best practices is essential for efficient data analysis.

### Data Modeling Approach in This Project
- Uses **Star and Snowflake Schema** techniques for structuring data.
- Maintains a **one-to-many relationship** between tables.
- Implements the **Snowflake modeling method** for better data organization.

By following ***best practices in data modeling***, this project ensures a **reliable and high-performance** Power BI report.

## Tech Stacks
- Power BI Desktop
- Power BI Service
- DAX
- Excel

## Technical Skills and Learning
- Understanding **data sources**, required transformations, and business needs.
- Ensuring proper **data validation techniques** before analysis.
- Performing **ETL processes** to clean and transform raw data.
- Extracting **Week Number** from given data.
- Establishing **one-to-many relationships** between tables using **Star & Snowflake Schema**.
- Creating **calculated columns** and **measures** using DAX.
- Using the **DIVIDE function** to prevent zero-division errors.
- Utilizing **KPI indicators** to track performance metrics.
- Using **Bookmarks** to switch between visuals dynamically.
- Implementing **Page navigation with buttons** for better user experience.
- Applying **conditional formatting** using icons and background colors.
- Publishing reports to **Power BI Service**.

**Key Learnings from This Project:**

1. **Business Intelligence & Power BI Techniques:**

✔ **Data Cleaning & Star Schema Modeling**

✔ **Page Navigation, Conditional Formatting**

✔ Tooltips and Tooltips on particular measures
✔ U**sers personalize visuals in a report**

✔ **Interactive Dashboard Design for Decision-Making**

1. **Soft Skills Developed:**

✔ **Hospitality Domain Knowledge & Revenue Strategies**

## Key Hospitality Metrics:

✔ **ADR (Average Daily Rate):** Revenue earned per room sold.

✔ **DBRN (Daily Booked Room Nights):** Average number of rooms booked per day.

✔ **DSRN (Daily Sellable Room Nights):** Average number of rooms available for sale per day.

✔ **DURN (Daily Utilized Room Nights):** Average number of rooms successfully utilized per day.

✔ **RevPAR (Revenue Per Available Room):** Revenue generated per available room, occupied or not.✔ **Realization %:** Percentage of successfully checked-out bookings.

✔ **Occupancy %:** Ratio of successful bookings to total available rooms.


##  AtliQ Grands Hospitality Project Overview

The **Home view** provides access to all available view buttons, allowing users to seamlessly navigate to a specific view page with a single click.

1. Overview
2. Revenue
3. Booking

### Home View
A source page providing easy page navigation access to all views, with dedicated support pane and information manual.

### 1. Overview View
Here you will find an overview of all the metrics.

### 2. Revenue View
This page tells you about the revenue and it's breakdown.

### 3. Booking View
This page tells you about the Bookings.
