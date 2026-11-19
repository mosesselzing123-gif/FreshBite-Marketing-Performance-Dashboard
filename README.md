FreshBite Restaurant – Marketing Performance Analysis and Dashboard

1. Project Overview

This project analyses the marketing performance of FreshBite Restaurant, a Nigerian restaurant based in Lekki, Lagos.

The project was developed as part of the NEXLEVR Intermediate Data Analyst Internship – Task 1.

An interactive Power BI dashboard was created to monitor marketing traffic, channel performance, conversions, content engagement and marketing expenditure.

Important: The dataset used in this project is synthetic demonstration data generated for educational and portfolio purposes. It does not represent actual FreshBite business transactions or advertising results.

2. Business Problem

FreshBite uses digital marketing channels to promote its products and attract customers. However, the business needs a structured way to understand which channels generate traffic, which produce conversions, and which content attracts the most engagement.

The dashboard provides a way to examine these performance indicators and support better marketing decisions.

3. Project Objectives

- Measure marketing traffic and audience engagement.
- Compare performance across Instagram, Facebook, WhatsApp and Google.
- Identify content with high engagement.
- Monitor marketing expenditure and cost per conversion.
- Present findings through an interactive Power BI dashboard.

4. Tools Used

- Microsoft Excel – Dataset storage and initial review.
- Power Query – Data cleaning, transformation and quality checks.
- Power BI – Dashboard development and visualisation.
- DAX – Measures and KPI calculations.
- GitHub – Project documentation and portfolio publishing.

5. Dataset Description

The dataset contains 600 records covering 1 September 2026 to 14 November 2026.

It contains the following fields:

- Date
- Channel
- Campaign
- Content_Name
- Content_Type
- Impressions
- Clicks
- Sessions
- Conversions
- Engagements
- Spend_NGN
- Record_ID

The marketing channels are Instagram, Facebook, WhatsApp and Google.

6. Data Preparation and Quality Checks

The dataset was prepared using Power Query.

Tasks performed included:

- Checked for duplicate records.
- Applied Trim and Clean to text columns.
- Corrected column data types.
- Checked for missing and empty values.
- Checked for negative values in numerical fields.
- Verified the date range and marketing channel categories.
- Checked logical relationships between impressions, clicks, sessions and conversions.

The final dataset contained 600 rows and 12 columns, with zero errors and zero empty values. No complete duplicate records were identified.

7. DAX Measures

The following measures were created:

Total Sessions

Total Sessions = SUM(Marketing_Data[Sessions])

Total Impressions

Total Impressions = SUM(Marketing_Data[Impressions])

Total Clicks

Total Clicks = SUM(Marketing_Data[Clicks])

Total Conversions

Total Conversions = SUM(Marketing_Data[Conversions])

Total Marketing Spend

Total Marketing Spend = SUM(Marketing_Data[Spend_NGN])

Total Engagements

Total Engagements = SUM(Marketing_Data[Engagements])

Conversion Rate

Conversion Rate =
DIVIDE([Total Conversions], [Total Sessions], 0)

Click Through Rate

Click Through Rate =
DIVIDE([Total Clicks], [Total Impressions], 0)

Cost per Conversion

Cost per Conversion =
DIVIDE([Total Marketing Spend], [Total Conversions], 0)

8. Overall Marketing Performance

KPI| Result
Total Impressions| 548,099
Total Clicks| 43,955
Total Sessions| 38,021
Total Conversions| 4,438
Conversion Rate| 11.67%
Click Through Rate| 8.02%
Total Marketing Spend| ₦3,586,708.82
Cost per Conversion| ₦808.18

These results describe the synthetic demonstration dataset, not actual business performance.

9. Dashboard Features

The Power BI dashboard includes six KPI cards:

- Total Sessions
- Total Conversions
- Conversion Rate
- Total Marketing Spend
- Cost per Conversion
- Click Through Rate

Five main visualisations:

1. Daily Marketing Traffic Trend.
2. Traffic Distribution by Channel.
3. Conversions by Marketing Channel.
4. Top-Performing Marketing Content.
5. Marketing Spend by Channel.

Interactive slicers:

- Date
- Channel
- Campaign

10. Key Findings

Based on the synthetic dataset:

- Instagram recorded the highest marketing traffic.
- Facebook recorded the lowest marketing traffic.
- Google generated the highest number of conversions.
- Facebook recorded the lowest number of conversions.
- Jollof Platter Photo recorded the highest engagement.
- Google recorded the highest marketing spend.
- WhatsApp recorded the lowest marketing spend.

11. Business Recommendations

1. Continue postng attractive food photography, short videos and promotional content on Instagram to build traffic.
2. Investigate Google's conversion performance and assess its cost efficiency before increasing its budget.
3. Review Facebook's audience targeting, content quality and campaign objectives.
4. Test more content formats similar to the high-engagement Jollof Platter Photo.
5. Compare conversion rates and cost per conversion across channels before reallocating marketing resources.

12. Project Limitations

- The reporting period covers September 2026 to 14 November 2026, with November being a partial month.
- Marketing expenditure is illustrative. WhatsApp expenditure represents an allocated campaign or content effort and should not automatically be interpreted as paid advertising spend.

13. Project Deliverables

- Excel marketing dataset.
- Power BI interactive dashboard
- Project documentation.
- Dashboard screenshots.

14. Skills Demonstrated

- Data cleaning and transformation.
- Data quality assessment.
- Power Query.
- DAX calculations.
- KPI development.
- Data visualisation.
- Marketing performance analysis.
- Business insight generation.
- Dashboard design and reporting.

15. Project Information

Project: FreshBite Restaurant Marketing Performance Analysis
Programme: NEXLEVR Data Analyst Internship
Track: Intermediate
Task: Task 1 – Marketing Dashboard
Tools: Excel, Power Query, Power BI and DAX
Prepared by: Moses Selzing
