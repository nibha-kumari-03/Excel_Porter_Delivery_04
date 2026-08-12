# Porter – Optimizing Delivery for the Digital Diner

## Project  Link:-
https://docs.google.com/spreadsheets/d/16TFjS-BJbpU2LKm2d81SolEUr0p6J2u2/edit?usp=sharing&ouid=118214303763742802960&rtpof=true&sd=true

## Project Overview

This project focuses on analysing food delivery data for **Porter**, a digital delivery platform.

The main goal is to understand the factors that affect **delivery time, order volume, restaurant performance, and delivery partner availability**. The analysis is performed in **Microsoft Excel** using formulas, Pivot Tables, and charts.

The project helps identify delivery patterns and provides useful insights that can support better operational and business decisions.

---

## Problem Statement

- Analyse the distribution of orders across different markets.
- Compare average delivery time across restaurant categories.
- Understand how order volume changes by hour and day.
- Identify the busiest days and time periods.
- Study the relationship between order volume and total item sales.
- Analyse delivery performance and delays.
- Understand the impact of delivery partners on delivery time.
- Identify high-performing and low-performing stores.
- Compare delivery performance across different order protocols.
- Analyse customer ordering patterns and repeat customers.

---

## Dataset Columns

The dataset contains information related to food delivery orders.

- **market_id** – Identifier for the market.
- **created_at** – Date and time when the order was placed.
- **actual_delivery_time** – Actual date and time when the order was delivered.
- **store_primary_category** – Primary category of the restaurant.
- **order_protocol** – Method through which the order was placed.
- **total_items** – Total number of items in the order.
- **subtotal** – Final price/value of the order.
- **num_distinct_items** – Number of different items in the order.
- **min_item_price** – Lowest item price in the order.
- **max_item_price** – Highest item price in the order.
- **total_onshift_partners** – Number of delivery partners currently on shift.
- **total_busy_partners** – Number of delivery partners currently busy.
- **total_outstanding_orders** – Number of orders waiting to be fulfilled.

---

## Data Cleaning & Preparation

The following preparation steps were considered before analysis:

- Handling missing values appropriately.
- Converting date and time columns into proper Excel date/time formats.
- Checking duplicate or inconsistent records.
- Checking categorical columns for unusual or inconsistent values.
- Creating useful calculated fields such as **Delivery Time**, **Day of Week**, and **Hour of Day**.

### Delivery Time Calculation

Delivery time can be calculated using:

**Delivery Time = Actual Delivery Time – Created At**

The calculated delivery time is then used for further analysis.

---

## Tools & Excel Skills Used

- **Microsoft Excel**
- Data Cleaning
- Excel Formulas
- Calculated Columns
- Sorting & Filtering
- Pivot Tables
- Pivot Charts
- Conditional Formatting
- Correlation Analysis
- Date & Time Analysis
- Data Visualisation

---

## Key Business Insights

This project helps answer important business questions such as:

- Which markets generate the highest order volume?
- Which restaurant categories have longer delivery times?
- When are the busiest ordering periods?
- Which days require more delivery capacity?
- Does a higher number of items lead to higher order values?
- Do busy delivery partners affect delivery time?
- Which stores need improvement in delivery performance?
- Does delivery partner availability affect customer experience?
- Are repeat customers different from first-time customers in their ordering behaviour?

---

## Business Recommendations

Based on the analysis, Porter can use the findings to:

- Improve delivery partner allocation during peak hours.
- Plan staffing based on busy days and time periods.
- Identify stores with consistently high delivery times.
- Improve operational planning for high-demand markets.
- Monitor delivery partner workload.
- Use customer ordering patterns to improve retention strategies.
- Improve delivery efficiency and customer satisfaction.

---

## Project Structure

```text
Porter_Delivery_Analysis/
│
├──  Photos_Porter
│
├──  README.md
     |-- Project Link
---

## Conclusion

- Developed an Excel-based delivery performance analysis.
- Analysed order volume, delivery time, restaurant categories, and delivery partners.
- Identified important patterns in delivery operations.
- Used Excel to convert raw data into meaningful business insights.
- Practised real-world data analyst skills including data cleaning, Pivot Tables, formulas, and visualisation.

---

## Author

**Nibha Kumari**

Aspiring Data Analyst | Business Analyst

**Skills:** Excel | SQL | Power BI | Python | Data Analysis | Data Visualisation
