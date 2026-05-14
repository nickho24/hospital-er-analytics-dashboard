# Hospital ER Analytics Dashboard

## Overview
This project is an interactive Power BI dashboard built to analyse Emergency Room (ER) operations and patient experience. It focuses on key performance indicators such as total patients, average waiting time, satisfaction score, referral sources, hourly activity, demographic breakdowns, and appointment patterns.

The dashboard was designed to turn raw hospital visit data into clear and actionable insights that support operational monitoring and decision-making.

## Objectives
- Track overall ER patient activity and trends over time
- Analyse average waiting time and patient satisfaction
- Understand referral patterns by department
- Explore visit distribution by gender, race, age group, hour, and weekday
- Identify patterns that may support service improvement and resource planning

## Tools Used
- Power BI
- Power Query
- DAX
- Data Modelling
- Excel / CSV data source

## Data Model
The project uses a structured model with:
- **Fact table:** Hospital ER visit data
- **Dimension tables:** Date and Time
- **Measure table:** Centralised KPI measures
- **Field Parameter table:** Used for visual interactivity

This approach improves scalability, readability, and report usability.

## Key Features
- KPI cards for total patients, average waiting time, and average satisfaction score
- Trend analysis by month
- Referral analysis by department
- Demographic analysis by race, age group, and gender
- Heatmaps for hourly and weekday activity
- Satisfaction analysis by waiting time and department
- Multi-page dashboard design for visit overview and satisfaction overview

## DAX / KPI Examples
The dashboard includes measures such as:
- Total Patients
- Average Waiting Time
- Average Satisfaction Score
- % Referred Patients
- % Male / Female / Unknown Visits
- Year-to-date and last-year comparisons

## Insights Generated
- Patient demand trends can be tracked across months and time periods
- Waiting time and satisfaction can be compared across age groups and departments
- Referral sources can be analysed to understand demand concentration
- Hourly and weekday patterns provide visibility into service utilisation
- Demographic views help identify differences in patient activity across groups

## Files
- `Hospital ER.csv` – raw dataset
- `Hospital_ER_Dashboard.pbix` – Power BI report file
- `screenshots/` – dashboard screenshots
- `README.md` – project documentation

## Screenshots
Include screenshots of:
- Visit Overview
- Satisfaction Overview
- Data Model

## Project Value
This project demonstrates practical skills in:
- Power BI dashboard development
- DAX measure creation
- Data modelling
- Healthcare data analysis
- KPI reporting
- Insight communication