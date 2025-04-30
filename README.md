### Global Cancer Patients Dashboard (2015-2024)
Overview
This repository contains a Power BI dashboard designed to provide insights into global cancer patient data from 2015 to 2024. The dataset includes key details such as patient demographics, cancer types, survival years, treatment costs, and risk factors (smoking, alcohol use, air pollution, and genetic predisposition).

The dashboard provides a comprehensive view of the dataset, enabling healthcare professionals, researchers, and policymakers to analyze trends, distributions, and correlations effectively.

Key Features
1. Interactive Visuals
Gender and Survival Years Slicers: Filter the data by gender and survival years.
Line Chart: Visualizes the total treatment cost by year, identifying cost trends.
Bar Chart: Displays patient count segmented by cancer type.
Pie Chart: Highlights the average risk factor metrics (e.g., age, air pollution, alcohol use, and smoking) by cancer stage.
Map Visualization: Shows total patient count and average genetic risk across global regions.
2. Key Metrics
Total Patients: Displays the cumulative patient count in the dataset.
Average Treatment Cost: Calculates the average treatment cost per patient.
3. Dynamic Filters
Allows interactive filtering for more focused analyses.

*Dataset Description
The dataset includes:
Patient Demographics: Gender, age, and survival years.
Cancer Data: Type, stage, and severity score.
Risk Factors: Smoking, alcohol use, air pollution, and genetic risk.
Costs: Treatment costs in USD.
Global Distribution: Country/region-specific data.

*Dashboard Highlights

How to Use
Clone the repository:
git clone https://github.com/your-username/global-cancer-dashboard.git
Open the .pbix file in Power BI Desktop.
### Dashboard
![Screenshot 2025-04-29 225733](https://github.com/user-attachments/assets/bf77e24f-b954-4cc2-b5b7-8624ac8b98b8)
Interact with the slicers and visuals to explore the data.

*DAX Calculations
The dashboard uses the following DAX measures:
Avg Treatment Cost:
Avg Treatment Cost = AVERAGE('TableName'[Treatment_Cost_USD])
Patient Count:
Patient Count = DISTINCTCOUNT('TableName'[Patient_ID])

*Acknowledgments
Special thanks to the creators and maintainers of the dataset for making this analysis possible.
