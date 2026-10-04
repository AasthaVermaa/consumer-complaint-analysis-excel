# Consumer Complaint Analysis – Excel

## About the Project

This project analyzes consumer complaint data to understand complaint volume, company performance, response timeliness, resolution time, and recurring complaint patterns.

The analysis transforms raw complaint data into a cleaned dataset, company-level performance analysis, complaint trend reports, and an interactive Excel dashboard designed to provide a clear view of service performance and areas requiring attention.

## Business Objective

The analysis focuses on answering key business questions:

* Which companies receive the highest number of complaints?
* Which companies have a higher proportion of complaints without a timely response?
* How long do companies take to resolve complaints?
* Which products and issues generate the most complaints?
* How has complaint volume changed over time?
* Which complaint areas should receive greater operational attention?

## Data Preparation

The raw complaint data was prepared for analysis using Excel.

Key data preparation steps included:

* Mapping state codes to state names using `XLOOKUP`
* Identifying missing and unmapped state information
* Converting date fields into usable Excel date values
* Calculating complaint resolution time in days
* Extracting year and quarter from complaint dates
* Checking data quality and consistency before analysis

## Analysis Performed

### Company Performance

Company-level analysis was used to evaluate:

* Total complaint volume
* Complaints without a timely response
* Percentage of complaints without a timely response
* Consumer dispute rate
* Average resolution time

### Complaint Trends & Concentration

The analysis also examined:

* Top companies by complaint volume
* Top complaint issues
* Monthly complaint trends
* Complaint distribution across products
* Complaint distribution across submission channels

## Interactive Dashboard

The project includes an interactive Excel dashboard combining KPIs, charts, and slicers.

The dashboard provides:

* Total complaints
* Year-over-year complaint change
* Timely response rate
* Average resolution time
* Monthly complaint trends
* Complaints by product
* Complaints by submission channel
* Priority issues by complaint volume
* Interactive filtering by year, quarter, product, company, state, submission channel, timely response, and consumer dispute status

### Dashboard Preview

![Consumer Complaint Analysis Dashboard](Screenshots/dashboard.png)

## Key Findings

* Complaint volume peaked in 2015 at **4,373 complaints** before declining by **16.35% in 2016**.
* **98.31% of 2016 complaints received a timely response**.
* Average resolution time was approximately **1.6 days in 2016**.
* Complaint volume is concentrated across a smaller group of recurring products and issues, highlighting areas where service teams can prioritize investigation and process improvement.

## Excel Skills Demonstrated

* Data cleaning and preparation
* `XLOOKUP`
* Date and time calculations
* PivotTables
* PivotCharts
* Slicers
* Conditional analysis
* Company performance analysis
* Trend analysis
* Data segmentation
* Interactive dashboard design

## Project Structure

```text
Consumer-Complaint-Analysis-Excel/
│
├── Consumer_Complaint_Analysis.xlsx
├── README.md
└── Screenshots/
    └── dashboard.png
```

## Tools Used

**Microsoft Excel**

The project demonstrates the use of Excel for data preparation, business analysis, reporting, visualization, and interactive dashboard development.
