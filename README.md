# HSE Safety Performance Metric Analysis (Excel & Power BI)

[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/)

> **134K Man-hours. 128 Open Incidents. 1 comprehensive safety dataset.**
> Here's how I cleaned raw HSE data in Excel and transformed it into a 4-page interactive Power BI dashboard that reveals aging safety actions, high-risk departments, and environmental footprints.

> **Note:** Data was synthetically generated to mirror real site data.

## 📌 Project Overview

This project simulates the workflow of an HSE (Health, Safety, and Environment) Analyst. The goal was to take raw, messy operational safety logs, clean them in Excel, and visualize the data in Power BI to provide executive leadership with a decision-ready dashboard. This is a static reporting dashboard (not automated) built to monitor Safety, Operations, and Environment.

**Time Period:** 2026 (H1)
**Total Man-hours:** 134,000
**Safety KPIs:** TRIR (5.20), LTIFR (1.67), Safety Index (41.30)

## 🎯 Business Objectives

- Clean and validate raw HSE incident and inspection data.
- Analyze incident trends, severity, and Lost Time Injuries (LTIs).
- Track the status of safety actions, Permits to Work (PTWs), and contractor compliance.
- Monitor environmental metrics including Waste, CO2, and Water usage.

## 🛠️ Tools & Skills Demonstrated

| Stage | Tool | Key Skills |
| :--- | :--- | :--- |
| **Data Modeling** | Power BI / DAX | TRIR calculation, LTIFR calculation, Aging buckets (31-60, 61-90, 90+ days), KPI Measures |
| **Visualization** | Power BI | Executive Dashboards, Trend Lines, Pareto analysis, Gauge charts, Interactive Tables |

## 🧩 Dashboard Pages

### 1. Executive Dashboard
Macro view of safety performance. Features Total Man-hours, TRIR, LTIFR, Open Incidents, LTIs, and Safety Index. The "Open Items Age" chart is a critical visual, showing 55 items are over 90+ days old.

### 2. Incident & Safety
Focuses on incident breakdowns. Includes Near Miss Ratio (0.20), LTI Trend, Days Lost by Department, and a Severity Breakdown (High, Medium, Low). A detailed data table allows drill-down into specific incidents.

### 3. Operational Control
Tracks equipment conditions (Fire Extinguishers, SCBA, Gas Detectors) and reveals an Equipment Pass Rate of 0.66 (against a 0.90 target). Also tracks 282 Cancelled PTWs and Contractor HSEScores (e.g., Dorman Long, Julius Berger).

### 4. Environmental Health
Monitors Total Waste (178K kg), CO2 (8.25K), and Water (11M L). Visualizes waste disposal methods (Landfill 34.6%, Incinerate 34.2%, Recycle 31%), highlighting a heavy reliance on non-sustainable disposal.

## 🔍 Key Findings

- **Aging Actions:** 55 safety items are over 90 days old, indicating systemic delays in closing out safety actions.
- **High-Risk Department:** HSE logged the highest number of incidents (70) and the highest days lost (165 days).
- **Equipment Failures:** Equipment pass rate is 0.66, well below the 0.90 target, particularly for Fire Extinguishers and Gas Detectors.
- **Incident Trend:** Incidents spiked in Jan/Feb but decreased by Q2. However, the proportion of LTIs remained steady.
- **Environmental:** Heavy reliance on Landfill (34.67%) for waste disposal.

## 📂 Repository Structure

```

hse-safety-dashboard/
├── data/
│   ├── HSE_Raw_Data.xlsx        # Original messy data
│   └── HSE_Cleaned_Data.xlsx    # Cleaned data ready for Power BI
├── dashboard/
│   └── HSE_Safety_Metrics.pbix  # Power BI Dashboard File
└── README.md

```

## 🚀 Setup / Reproduction

1. Open the `.pbix` file in Power BI Desktop.
2. The data is already loaded (synthetic). If you wish to connect it to your own site data, update the data source settings to point to your Excel/SQL database.
3. *Note: This dashboard is not automated. Data refreshes require a manual connection refresh.*

## 🏁 Conclusion

This project demonstrates an end-to-end HSE analytics workflow. It proves that visualizing safety metrics isn't just about counting incidents; it's about identifying where controls are failing, tracking the aging of unresolved hazards, and providing leadership with the insights needed to intervene before a near-miss becomes a catastrophe.

---
**Author:** Omini Assurance Justman 
**Contact:** [blessedassurance998@outlook.com / www.linkedin.com/in/assurance-justman / https://b-a-analytics.my.canva.site/assurance-justman.
