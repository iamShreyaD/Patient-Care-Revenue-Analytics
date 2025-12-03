# Patient-Care-Revenue-Analytics

**Excel, Power Query, XLOOKUP, PivotTables, Pivot Charts, Interactive Dashboard, GitHub**

---

## Project Overview
Analyze hospital patient records (10,000 rows) to derive insights on patient demographics, revenue performance, doctor workload, and insurance impact — enabling data-driven decisions to optimize care and revenue.

---

## Table of Contents
- [Dataset](https://www.kaggle.com/datasets/prasad22/healthcare-dataset)
- [Objectives](#objectives)
- [Tools & Technologies](#tools--technologies)
- [How I approached the problem](#how-i-approached-the-problem)
- [Key Findings](#key-findings)
- [Dashboard Walkthrough](#dashboard-walkthrough)


---

## Dataset
- **Rows**: 10,000  
- **Columns**: Name, Age, Gender, Blood Type, Medical Condition, Date of Admission, Doctor, Hospital, Insurance Provider, Billing Amount, Room Number, Admission Type, Discharge Date, Medication, Test Results  
- Note: a cleaned version of the dataset is included (`dataset_cleaned.xlsx`).

---

## Objectives
1. Identify which conditions drive the most revenue.
2. Compare hospital and doctor performance (revenue, patient volume, LOS).
3. Assess insurance provider contribution and identify friction points.
4. Build an interactive Excel dashboard for stakeholders.

---

## Tools & Technologies
- Microsoft Excel (Power Query, PivotTables, Pivot Charts, Timeline, Slicers, XLOOKUP)
- Git & GitHub for version control

---

## How I approached the problem
1. **Ingest & Clean**: Used Power Query to standardize dates, names, and remove duplicates.
2. **Feature Engineering**: Added `Length of Stay`, `Month`, `Risk Level` (via XLOOKUP mapping).
3. **Pivot Analysis**: Built pivots for revenue, condition analysis, doctor workload, and insurance impact.
4. **Dashboard**: Assembled KPI cards, pivot charts, slicers, and timeline to enable interactive exploration.
5. **Recommendations**: Derived actionable steps based on underperformers and insurance delays.

---

## Key Findings (example — replace after analysis)
- Top 3 conditions account for ~60% of billing revenue.
- Hospital A generates highest revenue per patient; Hospital C has longest Avg LOS.
- Insurance Provider X shows higher-than-average LOS, suggesting discharge authorization delays.

---

## Dashboard Walkthrough
1. **Top-left**: KPI cards (Total Revenue, Avg Billing per Patient, Avg LOS).
2. **Center**: Revenue trend by Hospital/Doctor (Pivot Chart + Timeline).
3. **Right**: Condition revenue ranking + Pareto chart.
4. **Bottom**: Insurance contribution & Insured vs Uninsured comparison.
5. **Controls**: Slicers for Hospital, Doctor, Condition, Admission Type; Timeline for date filtering.
