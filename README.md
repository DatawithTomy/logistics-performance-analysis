# Logistics Performance Analysis

A 4-page Power BI dashboard analyzing a logistics/trucking operation across revenue, driver performance, fleet efficiency, and route safety built from a 14-table relational dataset.

## Business Problem

A logistics company needs visibility into where revenue is coming from, which drivers and routes are underperforming, how fuel and maintenance costs are trending, and where safety incidents are concentrated. This dashboard consolidates that into four focused views for operations managers.

## Dataset

- Source: Logistic Operations Database (14 related tables covering trips, drivers, trucks, trailers, routes, fuel, maintenance, and incidents)
- [Link to dataset](https://drive.google.com/drive/folders/1Uk7U-DvssMWGyBxSaXHo-TqzanptUJZf)
- Tables were joined on drivers, trucks, trailers, and routes to build a unified model in Power BI

## Tools

- Power BI (data modeling, DAX, interactive dashboards)
- Excel (initial exploration and cleaning)

## Dashboard Walkthrough

### 1. Executive Overview
![Executive Overview](assets/01-executive-overview.jpeg)

Top-line KPIs — ₦262.5M total revenue, ₦95.6M fuel cost, ₦5.7M maintenance cost, 85K trips, 200 customers — plus revenue trend by month, top 5 customers by revenue, and revenue breakdowns by status, freight type, and load type.

**Key insight:** Automotive is the top freight type by revenue, and refrigerated loads make up just over half of total load revenue.

### 2. Driver & Delivery Performance
![Driver & Delivery Performance](assets/02-driver-delivery-performance.jpeg)

Tracks 124 active drivers across 85K trips and 120M miles, with average MPG and on-time delivery rate as headline metrics, plus top drivers by revenue, on-time rate, average MPG, and trip count.

**Key insight:** The average on-time delivery rate (44.6%) trails well behind the top individual drivers (up to ~49%), pointing to inconsistency worth investigating at the fleet level rather than a few outliers.

### 3. Fleet & Fuel Efficiency
![Fleet & Fuel Efficiency](assets/03-fleet-fuel-efficiency.jpeg)

Covers 120 trucks and 180 trailers, fuel cost trend over the year, maintenance cost by type, and fuel cost by truck maker and trailer type.

**Key insight:** Preventive maintenance is the single largest maintenance cost category — higher than repair — suggesting the fleet is being maintained proactively rather than reactively.

### 4. Route & Safety Performance
![Route & Safety Performance](assets/04-route-safety-performance.jpeg)

Breaks down 5 incident types across the network, claim amounts, and the highest-mileage, highest-revenue, and highest-fuel-cost routes and cities.

**Key insight:** DOT violations are the most frequent incident type, narrowly ahead of accidents and equipment damage — a compliance-focused intervention could address the largest single category.

## Skills Demonstrated

- Data modeling across a multi-table relational dataset
- DAX for KPI calculations and trend analysis
- Dashboard design for a non-technical operations audience
- Translating raw metrics into actionable business insights

## Contact

**Tomi (Ejitoye Oluwatomisin)** — Data Analyst
08147120274
📧 ejitoyeoluwatomisin@gmail.com
