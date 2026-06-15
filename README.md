
# HR & Workforce Analytics Dashboard
### Power BI | IBM HR Analytics Dataset | 1,470 Employees

## Live Dashboard
[View Live Dashboard](paste your Power BI link here)

## Download Dashboard File
[Download Power BI File (.pbix)](paste your Google Drive link here)

## Overview
An end-to-end Power BI dashboard analysing workforce data 
for 1,470 employees. The dashboard answers critical HR 
business questions around attrition, salary, job satisfaction, 
and workforce demographics.

## Business Questions Answered
- What is the overall employee attrition rate?
- Which departments and job roles have the highest attrition?
- Do employees who work overtime leave more often?
- Is there a salary gap between employees who stay vs leave?
- Which departments have the lowest job satisfaction?
- Does age affect attrition rate?

## Dashboard Pages

### Page 1 — HR Overview
![HR Overview](PIC%201.png)
- Total Employees, Active Employees, Total Attrition, Attrition Rate
- Donut chart — Active vs Departed Employees
- Bar chart — Attrition by Department
- Slicers — Department, Gender, Overtime

### Page 2 — Attrition Analysis
![Attrition Analysis](PIC%202.png)
- Attrition Rate, Overtime Attrition Rate, Male Attrition Rate
- Bar chart — Attrition by Job Role
- Bar chart — Attrition Rate by Age
- Donut chart — Attrition by Overtime Status
- Slicers — Department, Gender

### Page 3 — Salary & Satisfaction
![Salary & Satisfaction](PIC%203.png)
- Avg Monthly Income, Salary Gap, Avg Job Satisfaction
- Scatter chart — Age vs Monthly Income by Job Role
- Bar chart — Job Satisfaction by Department
- Slicer — Department

## Technical Details
- **Tool:** Power BI Desktop
- **Dataset:** IBM HR Analytics Employee Attrition (1,470 employees)
- **Data Model:** Single table — no relationships needed
- **Calculations:** 10 DAX measures

## DAX Measures Built
- Total Employees (COUNTROWS)
- Total Attrition (COUNTROWS + FILTER)
- Attrition Rate (DIVIDE)
- Avg Monthly Income (AVERAGE)
- Overtime Attrition Rate (CALCULATE)
- Salary Gap (CALCULATE comparison)
- Active Employees (CALCULATE)
- Avg Age (AVERAGE)
- Avg Job Satisfaction (AVERAGE)
- Male Attrition Rate (CALCULATE)

## Key Insights
- Overall attrition rate of 16% across the organisation
- Sales department has the highest attrition rate
- Employees working overtime are significantly more likely to leave
- Employees who left earned less on average than those who stayed
- Research & Development has the highest job satisfaction scores

## Files
- `P2_HR_Workforce_Dashboard.pbix` — Power BI report file
- `Pic 1.png` — HR Overview page screenshot
- `Pic 2.png` — Attrition Analysis page screenshot
- `Pic 3.png` — Salary & Satisfaction page screenshot
