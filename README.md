# FUTURE_DS_03
Power BI dashboard analyzing marketing funnel performance and conversion rates.
# Marketing Funnel & Conversion Performance Dashboard

## Project Overview
This project presents a Power BI dashboard that analyzes the performance of a marketing campaign using a marketing funnel approach.

The dashboard helps understand how many customers were contacted, how many converted into subscribers, and identifies trends in conversion rates.

The goal of this project is to help marketing teams evaluate campaign performance and identify opportunities to improve customer conversions.

---

## Dashboard Preview
Add your dashboard screenshot here.
<img width="727" height="486" alt="dashboard_preview" src="https://github.com/user-attachments/assets/87d36085-a165-486e-8abd-3545ac48262e" />

---

## Key Metrics

• Total Contacts: 45K  
• Total Conversions: 5K  
• Conversion Rate: 11.7%

These KPIs provide a quick summary of the campaign performance.

---

## Dashboard Features

The dashboard includes several visualizations designed to analyze marketing performance.

### 1. Marketing Funnel
Shows the stages from contacted customers to successful conversions.

### 2. KPI Cards
Displays:
- Total Contacts
- Total Conversions
- Overall Conversion Rate

### 3. Conversion Rate by Job
Analyzes which job categories convert more frequently.

### 4. Monthly Conversion Trend
Shows how conversion rates change across months, helping identify seasonal patterns.

### 5. Interactive Filters
Users can filter the dashboard using:
- Job
- Education
- Month

This allows deeper exploration of customer segments.
---

## Key Insights

• The overall conversion rate is around 10–12%, indicating moderate marketing effectiveness.

• A significant drop occurs between total contacts and successful conversions, which highlights potential opportunities to improve targeting.

• Some job categories have higher conversion rates, suggesting more responsive customer segments.

• Monthly trends show fluctuations in conversion performance, which may indicate seasonal marketing effects.

---

## Dataset

The dataset used in this project is based on a Bank Marketing Campaign dataset commonly used for data analytics practice.

The dataset includes information such as:

- Customer demographics
- Job category
- Education level
- Month of contact
- Marketing campaign outcome

---

## Data Processing Steps

The following steps were performed during data preparation:

1. Imported dataset into Power BI
2. Cleaned and transformed data using Power Query
3. Created calculated columns and measures
4. Built relationships between fields where required
5. Designed interactive visualizations

## DAX Measures Used

### Total Contacts

Total Contacts = COUNT(Bank[Customer_ID])


### Total Conversions

Total Conversions =
CALCULATE(
COUNT(Bank[Customer_ID]),
Bank[Subscription] = "Yes"
)


### Conversion Rate

Conversion Rate =
DIVIDE([Total Conversions], [Total Contacts])


These measures power the main KPIs displayed in the dashboard.

---

## Tools & Technologies

• Power BI  
• Power Query  
• DAX (Data Analysis Expressions)  
• Data Visualization Techniques

---

## Business Value

This dashboard helps marketing teams:

• Monitor campaign performance  
• Identify high‑converting customer segments  
• Analyze monthly performance trends  
• Improve marketing strategy based on data insights

---

## What I Learned

Through this project, I learned:

• Designing professional Power BI dashboards  
• Creating KPI metrics using DAX  
• Implementing marketing funnel analysis  
• Applying effective data visualization practices

---

## Project Files

marketing-funnel-powerbi-dashboard

│

├── Marketing_Funnel_Dashboard.pbix

├── dashboard_preview.png

├── bank_marketing_dataset.csv

└── README.md

---

## Author

**KOTHANAGANNA GARI HEMALATHA**

Aspiring Data Analyst passionate about data visualization, business intelligence, and analytics.
---
**
