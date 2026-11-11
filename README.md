# Healthcare-Data-Analysis
## 1.Problem Statement
- The healthcare industry generates vast amounts of data daily, providing valuable insights for 
healthcare providers and policymakers to improve patient care, allocate resources effectively, 
and manage healthcare costs. This project aims to analyze a comprehensive healthcare dataset 
comprising medical examinations, hospitalization details, and customer profiles to extract 
insights into patient health profiles, medical histories, and healthcare costs. By exploring 
relationships between various health metrics, identifying trends, and visualizing key patterns, we 
aim to deliver actionable insights to healthcare stakeholders for informed decision-making 
through rigorous data cleaning, transformation, exploration, and analysis.  
## 2.Dataset Description
- Healthcare data of 2335 patients with Age, BMI, HbA1c, Diabetes Status, Weight Status, Smoker, Cancer History, Hospital Tier, Major Surgeries and Medical Charges. Used to analyze how lifestyle factors affect medical cost.
## 3.Data Preprocessing
- IN preprocessing stage,Cleaned the raw data by removing duplicates and handling missing values. Created new categories like Weight Status from BMI and Diabetes Status for easy analysis. Formatted Age, BMI, HbA1c and Charges into proper number format for dashboard.
## 4.Data Transformation
- Created Weight Status from BMI values (Underweight, Normal, Overweight, Obese). Grouped Diabetes Status, Smoker, Cancer History and Hospital Tier into categories. Converted HbA1c and Charges into clean numeric format for charts and slicers.
## 5.Data Exploration, Analysis & Visualization
- Explored the data using charts and slicers to find patterns. Analyzed how Age, BMI, HbA1c, Smoking and Cancer History affect Medical Charges. Created an interactive Excel Dashboard with Pie Charts, Bar Charts and KPI cards to show key insights clearly.
## 6.Dashboard Creation
- I created an interactive Excel Dashboard to understand how lifestyle factors affect medical charges.KPI cards show Total Patients 2335, Total Charges 31.32M, Average Charge 13.41K, Average Age 37.61, Average BMI 30.64 and Average HbA1c 5.67.Bar Charts show Obese patients and Diabetic patients have the highest average charges.
- Hospital Tier 2 charges more than Tier 1 and Tier 3.
- Pie Charts show 44% patients have abnormal HbA1c and only 15% had major surgeries.
- Doughnut Chart shows Smokers have higher Cancer History than Non-Smokers.
- Scatter with Trendline is the most important chart. In Age vs Charges chart, as Age increases, Charges also increase - upward trend line proves it. In Age vs BMI, HbA1c and Charges chart, we can see BMI and Charges increase together with Age.
## 7.Conclusion
- From my analysis side i would say that Age, BMI, Diabetes, Smoking and HbA1c directly increase medical cost. Maintaining healthy BMI and controlling diabetes can reduce medical charges.
