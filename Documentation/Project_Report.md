FreshBite Restaurant – Marketing Performance Analysis

1. Project Overview

This project analyses the marketing performance of FreshBite Restaurant, a fictional Nigerian restaurant based in Lekki, Lagos.

The project was completed as part of the NEXLEVR Intermediate Data Analyst Internship – Task 1.

An interactive Power BI dashboard was developed to monitor marketing traffic, channel performance, conversions, content engagement and marketing expenditure.

Data disclaimer: The dataset is synthetic demonstration data generated for educational and portfolio purposes. It does not represent actual FreshBite business transactions or advertising results.

2. Business Problem

The business needs a structured way to understand which marketing channels generate traffic, which produce conversions, and which content attracts the most engagement.

The dashboard helps examine these performance indicators and supports better marketing decisions.

3. Project Objectives

- Measure marketing traffic and audience engagement.
- Compare performance across Instagram, Facebook, WhatsApp and Google.
- Identify content with high engagement.
- Monitor marketing expenditure and cost per conversion.
- Present findings through an interactive Power BI dashboard.

4. Tools Used

- Microsoft Excel: Dataset storage and initial review.
- Power Query: Data cleaning, transformation and quality checks.
- Power BI: Dashboard development and visualisation.
- DAX: Measures and KPI calculations.
- GitHub: Project documentation and portfolio publishing.

5. Dataset Description

The dataset contains 600 records covering 1 September 2026 to 14 November 2026.

Fields include Date, Channel, Campaign, Content_Name, Content_Type, Impressions, Clicks, Sessions, Conversions, Engagements and Spend_NGN.

A Record_ID column was added during data preparation.

6. Data Preparation and Quality Checks

The following activities were completed:

- Reviewed the dataset structure and column quality.
- Checked for duplicate records.
- Cleaned text fields using Trim and Clean.
- Corrected column data types.
- Checked for missing values and errors.
- Verified that clicks did not exceed impressions.
- Verified that sessions did not exceed clicks.
- Verified that conversions did not exceed sessions.
- Checked that marketing spend was not negative.
- Confirmed the date range and channel categories.

The final dataset contained 600 rows and 12 columns, with no identified errors, empty values or duplicate records.

7. DAX Measures

Total Sessions =
SUM(Marketing_Data[Sessions])

Total Impressions =
SUM(Marketing_Data[Impressions])

Total Clicks =
SUM(Marketing_Data[Clicks])

Total Conversions =
SUM(Marketing_Data[Conversions])

Total Marketing Spend =
SUM(Marketing_Data[Spend_NGN])

Total Engagements =
SUM(Marketing_Data[Engagements])

Conversion Rate =
DIVIDE([Total Conversions], [Total Sessions], 0)

Cost per Conversion =
DIVIDE([Total Marketing Spend], [Total Conversions], 0)

Click Through Rate =
DIVIDE([Total Clicks], [Total Impressions], 0)

8. Overall Performance Results

KPI| Result
Total Impressions| 548,099
Total Clicks| 43,955
Total Sessions| 38,021
Total Conversions| 4,438
Conversion Rate| 11.67%
Click Through Rate| 8.02%
Marketing Spend| ₦3,586,708.82
Cost per Conversion| ₦808.18

9. Dashboard Features

The Power BI dashboard includes:

- KPI cards for key marketing performance indicators.
- Daily marketing traffic trend.
- Traffic distribution by channel.
- Conversions by marketing channel.
- Top-performing content by engagement.
- Marketing spend by channel.
- Interactive filters for channel, date, campaign and content type.

10. Key Findings

- Instagram generated the highest traffic.
- Facebook generated the lowest traffic.
- Google recorded the highest number of conversions.
- Facebook recorded the lowest number of conversions.
- Jollof Platter Photo recorded the highest engagement.
- Google recorded the highest marketing spend.
- WhatsApp recorded the lowest marketing spend.

These findings describe the synthetic dataset used in this project.

11. Recommendations

1. Continue testing engaging food photography and short videos on Instagram.
2. Investigate Google campaigns to understand the factors behind their higher conversion volume.
3. Review Facebook targeting, content quality and campaign objectives.
4. Test content formats similar to the high-engagement Jollof Platter Photo.
5. Compare conversion rates and cost per conversion before reallocating marketing budgets.

12. Project Limitations

- The dataset is synthetic and does not represent actual business performance.
- The analysis covers a limited period.
- WhatsApp marketing spend is an illustrative allocation, not necessarily paid advertising expenditure.
- Findings should be validated with real business data before making actual budget decisions.

13. Project Deliverables

- FreshBite_Marketing_Dataset_NEXLEVR.xlsx
- FreshBite_Marketing_Dashboard.pbix
- FreshBite_Marketing_Dashboard.pdf
- Power BI dashboard screenshot
- Project documentation

14. Skills Demonstrated

- Data cleaning and transformation.
- Data quality assessment.
- Exploratory data analysis.
- DAX calculations and KPI development.
- Power BI dashboard design.
- Business insight generation.
- Data storytelling and documentation.
- GitHub portfolio management.

Prepared as: NEXLEVR Intermediate Data Analyst Internship – Task 1

Project: FreshBite Restaurant Marketing Performance Analysis
