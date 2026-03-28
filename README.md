# 🏥 Medical Data Warehouse Cost Analysis

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-0052CC?style=for-the-badge&logo=data&logoColor=white)

## 📌 Project Overview
This project analyzes a medical data warehouse comprising 1,338 patient records to uncover the primary demographic and lifestyle factors driving healthcare costs. By establishing an automated ETL (Extract, Transform, Load) pipeline and developing a dynamic, interactive Excel dashboard, this analysis translates raw patient data into actionable business intelligence for healthcare and insurance stakeholders.

**Author:** Naveen Shaji  
**Domain:** Healthcare Analytics & Business Intelligence

---

## 🛠️ Tools & Technologies Used
* **Microsoft Excel:** Data aggregation, PivotTables, and PivotCharts.
* **Power Query:** ETL pipeline execution, data cleaning, and feature engineering (M code logic).
* **UI/UX Design:** Maximizing data-ink ratio for distraction-free, executive-level dashboarding.

---

## 🔄 The Data Pipeline (ETL & EDA)

### 1. Extraction & Transformation
Raw CSV data was imported via Power Query. To streamline demographic analysis, continuous variables were engineered into discrete categorical buckets using conditional logic:
* **Age Grouping:** Patients segmented into `<30`, `30-50`, and `50+`.
* **BMI Categorization:** Patients classified as `Underweight`, `Normal weight`, `Overweight`, and `Obese`.

### 2. Exploratory Data Analysis (EDA)
PivotTables were constructed to aggregate the average medical charges across various patient dimensions (Age, Region, Sex, BMI, Smoker Status), exposing baseline trends and anomalies within the risk pools.

### 3. Interactive Dashboard
A centralized, dark-themed dashboard was built utilizing PivotCharts. Interactive Slicers were connected to the data model, serving as a control panel for dynamic cross-filtering by region, sex, and smoker status.

*(Insert a screenshot of your final dashboard here by dragging and dropping the image into the GitHub editor)*
`![Dashboard Preview](link-to-your-image.png)`

---

## 📊 Key Insights & Business Recommendations

Based on the visual analysis, several major narratives emerged regarding medical warehouse costs:

1. **The Smoking Penalty:** Smoking status is the single largest driver of healthcare expenses. The data reveals a stark, immediate premium gap between smokers and non-smokers, completely dwarfing the financial impact of standard demographic factors.
2. **BMI as a Cost Multiplier:** While age provides a steady, linear baseline for cost increases over a patient's lifetime, Body Mass Index acts as a severe financial multiplier. Patients crossing into the "Obese" category (BMI > 30) experience a disproportionate spike in charges, accelerating drastically if the patient also smokes.
3. **Geographic Neutrality:** Average costs and risk distributions remain surprisingly uniform across the Northeast, Northwest, Southeast, and Southwest regions.

**Strategic Action Items:**
* **Restructure Premium Tiering:** Implement strict pricing models heavily weighted by smoking status, offering discounted premiums for non-smokers.
* **Incentivize Preventative Wellness:** Invest in preventative health initiatives (e.g., smoking cessation programs) to mitigate the compounding costs of high BMI and smoking.

---

## 📂 How to Use This Repository
1. Clone the repository to your local machine.
2. Open the `Medical_Cost_Analysis_Dashboard.xlsx` file in Microsoft Excel.
3. Navigate to the **Dashboard** sheet.
4. Use the Slicers (Smoker, Region, Sex) at the top of the dashboard to dynamically filter the charts and explore specific patient demographics.

---

## 🌐 More from my Portfolio
This BI reporting tool is part of a broader data analytics portfolio. Feel free to check out my other predictive modeling and analytics projects:
* [Financial Fraud Detection Model](link-to-your-repo)
* [End-to-End Customer Churn & Retention Analysis](link-to-your-repo)

**Let's Connect!**
Feel free to reach out for collaborations or opportunities in Data Analytics and Data Science.
