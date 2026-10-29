# LG Production Efficiency & Trend Analysis

## 📌 Project Overview

The **LG Production Efficiency & Trend Analysis** project is a Power BI dashboard designed to analyze manufacturing production, quality control performance, production costs, and demand forecasts.

The dashboard provides insights into product-wise production volume, defective units, defect rates, quality control outcomes across manufacturing plants, regional cost distribution, and monthly production trends compared with demand forecasts.

## 🎯 Project Objectives

- Analyze total manufacturing costs and their components.
- Compare production volume and defective units across products.
- Evaluate defect rates to identify potential quality improvement areas.
- Analyze quality control performance across manufacturing plants.
- Understand cost distribution across regions.
- Compare monthly production with demand forecasts.

## 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop** — Dashboard development and data visualization
- **DAX (Data Analysis Expressions)** — Measures and calculations
- **CSV** — Source dataset

## 📊 Dashboard Features

### 1. Key Performance Indicators (KPIs)

The dashboard displays the following cost metrics:

- Total Cost
- Energy Cost
- Labor Cost
- Material Cost

### 2. Production Volume and Defect Rate by Product

Compares units produced and defective units across the following product categories:

- Microwave
- TV
- Washing Machine
- Refrigerator
- AC

The chart also displays the defect rate to help identify products that may require quality improvement.

### 3. QC Performance Distribution Across Manufacturing Plants

Analyzes quality control outcomes across manufacturing plants, using the following categories:

- Pass
- Fail
- Recheck

This visualization helps compare quality control results between factories.

### 4. Region-wise Total Cost

Displays the distribution of total manufacturing costs across regions:

- NA
- SA
- APAC
- EMEA

This analysis helps understand how costs are distributed geographically. Missing or unassigned region values should be validated before interpreting NA as a genuine region.

### 5. Units Produced vs Demand Forecast

Compares monthly production volume with demand forecasts from January to December.

This visualization helps identify potential production shortfalls and differences between forecast demand and actual production.

## 📈 Key Insights

The dashboard supports analysis of:

- Overall manufacturing expenditure and cost composition.
- Differences in production volume across product categories.
- Product-wise defect rates and potential quality concerns.
- Quality control outcomes across manufacturing plants.
- Regional manufacturing cost distribution.
- Monthly gaps between production and forecast demand.

Actual business conclusions should be drawn after validating the source data and measures.

## 🧮 DAX Measures

### Defect Rate (%)

```DAX
Defect Rate (%) =
DIVIDE(
    [Total Defective Units],
    [Total Units Produced],
    0
)
```

Format the defect rate as a percentage.

## 📂 Project Files

- 📊 [**Dataset (CSV)**](./[lg_production_data.csv](https://github.com/SahilKumar-003/LG-Production-Efficiency-Trend-Analysis/blob/main/lg_production_data.csv)) — Source data used for production and cost analysis.
- 📈 [**Dashboard (Power BI PDF)**](./[project_LG_power_bi.pdf](https://github.com/SahilKumar-003/LG-Production-Efficiency-Trend-Analysis/blob/main/project_LG(power_bi).pdf)) — View the exported dashboard report.
- 🖼️ [**Dashboard Screenshot**](./[screenshots/dashboard.png](https://github.com/SahilKumar-003/LG-Production-Efficiency-Trend-Analysis/blob/main/Lg_production_dashboard.png)) — Preview the dashboard directly in the README.
- 💻 [**Power BI Report (.pbix)**](./[project_LG.pbix](https://github.com/SahilKumar-003/LG-Production-Efficiency-Trend-Analysis/blob/main/project_LG(power_bi).pbix)) — Open the interactive report in Power BI Desktop, if included.

## 📊 Dashboard Preview

Click the link below to view the dashboard:

[**View LG Production Efficiency & Trend Analysis Dashboard**](./[project_LG_power_bi.pdf](https://github.com/SahilKumar-003/LG-Production-Efficiency-Trend-Analysis/blob/main/project_LG(power_bi).pdf))



## 🚀 How to Use

1. Download or clone this repository.
2. Open the dashboard PDF to view the report.
3. Open the `.pbix` file in Microsoft Power BI Desktop for interactive analysis, if included.
4. To rebuild the dashboard, import the CSV dataset using **Home → Get Data → Text/CSV**.
5. Verify column data types, date fields, and data quality.
6. Create the required measures and visuals.
7. Refresh the report when the source data changes.

## 🔍 Data Quality Considerations

Before using the dashboard for business decisions:

- Validate missing or invalid production dates before interpreting monthly trends.
- Investigate missing region values.
- Confirm that quality control quantities are correctly associated with Pass, Fail, and Recheck statuses.
- Ensure defective units are not incorrectly counted as additional production.
- Verify that cost components reconcile with total cost.
- Confirm that production and demand forecast values use compatible units.
- Ensure dates are sorted chronologically in monthly charts.

## 💡 Future Improvements

- Add additional production efficiency KPIs.
- Introduce interactive slicers for product, factory, region, and date.
- Add a 100% stacked column chart for comparing QC proportions.
- Improve data quality handling and missing-value treatment.
- Add conditional formatting to highlight high defect rates.
- Improve dashboard accessibility with readable labels and consistent formatting.

## 👤 Author

**Author:** Sahil Kumar  
**Project:** LG Production Efficiency & Trend Analysis  
**Technology:** Microsoft Power BI
