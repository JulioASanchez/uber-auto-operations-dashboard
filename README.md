# Uber Operations Analysis – Power BI

**Role:** Business Analyst / Project Manager  
**Tools:** Power BI, DAX, Power Query  

## 🎯 Business Context
The Uber Auto operations team lacked a single, unified view of core operational KPIs such as ride completion, cancellations, customer behavior, and revenue. Metrics were not consistently analyzed by vehicle type, payment method, or time period, making it difficult to monitor service quality, identify lost bookings, and prioritize operational improvements.

**Objective:**  
Design and deliver a centralized analytics solution to support operational decision-making, issue diagnosis, and prioritization of improvement initiatives.

---

## 📊 Data & Tools
**Dataset:**  
Uber Auto booking data including ride status, distance, vehicle type, customer ID, pickup/drop locations, payment method, and customer ratings.

**Tooling:**  
- Power BI Desktop  
- DAX for KPI definitions  
- Power Query for data transformation  

**Deliverable:**  
A multi-page interactive Power BI dashboard with slicers and bookmarks, designed for operational and management stakeholders.

---

## 🧹 Data Preparation & Modeling
- Loaded raw CSV data and validated data quality by removing unused and duplicate fields.
- Standardized numeric measures (distance, revenue) and enforced consistent data types for dates and categorical dimensions.
- Designed a relational data model to support scalable analysis across vehicles, customers, and time.
- Implemented DAX-based KPIs aligned with business definitions to ensure metric consistency.

---

## 🧭 Dashboard Pages & Decision Logic

### Overview – Operational Health
Provides a high-level snapshot of operational performance:
- KPI cards for completed vs lost bookings, total and average distance, and total revenue
- Monthly and quarterly trend analysis for rides and revenue
- Revenue breakdown by vehicle type and payment method

**Business value:** Enables leaders to quickly assess overall performance trends and detect anomalies requiring investigation.

---

### Vehicles – Product & Capacity Performance
Analyzes vehicle types by:
- Customer count
- Revenue and completed bookings
- Contribution percentage
- Monthly performance trends

**Business value:** Supports prioritization of vehicle categories for driver onboarding, pricing, promotions, and capacity planning.

---

### Customers – Demand & Retention
Focuses on rider behavior through:
- Segmentation of first-time, return, and regular riders
- Customer volume trends over time
- Identification of high-value customers
- Cancellation analysis by reason

**Business value:** Informs retention strategies, loyalty programs, and operational fixes targeting key churn drivers.

---

### Distance & Time Behavior – Demand Patterns
Explores temporal and spatial behavior using:
- Total distance KPIs
- Weekday × time-slot heatmaps
- Vehicle and payment method performance by time window

**Business value:** Enables smarter staffing, incentive planning, and monitoring during peak demand periods.

---

## 📌 Key Insights & Recommended Actions

- **Vehicle mix:** Auto and Bike generate the highest revenue and distance and should be prioritized for driver onboarding and marketing. Uber XL underperforms and may require targeted promotions or pricing adjustments.
- **Customer mix:** Regular riders drive most demand, while first-time riders remain significant. Referral and onboarding incentives could increase conversion to repeat riders.
- **Lost bookings:** High lost bookings during specific periods suggest capacity or matching issues. Zone-based incentives or dynamic pricing can be tested.
- **Payments:** UPI dominates transaction value, making it a critical dependency requiring close monitoring and contingency planning.

---

