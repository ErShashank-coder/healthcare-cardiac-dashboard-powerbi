# 🫀 Cardiac Patient Outcome Analysis | Power BI Dashboard

## 📌 Project Overview
This project analyzes cardiac patient data to evaluate survival outcomes, emergency response efficiency, hospital performance, and treatment cost patterns. The goal is to identify high-risk patient profiles, optimize emergency care, and provide data-driven insights for healthcare decision-making using an interactive multi-page Power BI dashboard.

---

## ❓ Problem Statement
Hospitals handle critical cardiac patients daily, but delayed emergency response, high-risk patient conditions, and resource allocation inefficiencies can impact survival rates and treatment costs.  
This project aims to uncover patterns affecting cardiac arrest, survival probability, hospital efficiency, and financial burden to support better clinical and operational decisions.

---

## 🛠️ Tools & Technologies Used
- Power BI Desktop  
- Power Query (Data Cleaning & Transformation)  
- DAX (Calculated Columns & Measures)  
- Data Visualization & Storytelling  
- Healthcare Analytics Domain Knowledge  

---

## 📂 Dataset Description
Each record represents a patient admission containing:
- Demographics: Age, Gender, Region
- Clinical Metrics: Heart Rate, BP, Oxygen Level, Cholesterol
- Risk Factors: Diabetes, Smoking Status, Previous Heart Disease
- Operational Data: Emergency Response Time, Admission Type, Shift Time
- Outcomes: Cardiac Arrest, Survival Status
- Financials: Length of Stay, Treatment Cost (INR)

---

## ⚙️ Steps Performed
1. Data cleaning and validation using Power Query  
2. Created calculated columns:
   - Age Group
   - High-Risk Patient Flag
   - Response Time Category  
3. Developed core KPIs using DAX:
   - Survival Rate %
   - Cardiac Arrest Rate %
   - Avg Emergency Response Time
   - Avg Treatment Cost
   - Avg Length of Stay  
4. Built an interactive 5-page Power BI dashboard with slicers and dynamic filtering  
5. Performed clinical, operational, and financial analysis to derive actionable insights  

---

## 📊 Dashboard Pages & Analysis

### 🔹 Page 1: Executive Summary
KPIs:
- Total Patients
- Survival Rate %
- Cardiac Arrest Rate %
- Avg Emergency Response Time
- Avg Treatment Cost (INR)

Insights:
- Senior patients show higher cardiac arrest risk  
- Regions with delayed response have lower survival rates  

---

### 🔹 Page 2: Patient Risk & Clinical Analysis
Visuals:
- Survival Rate by Age Group
- Impact of Diabetes, Smoking, and Previous Heart Disease
- Oxygen Level vs Heart Rate Scatter Analysis

Insights:
- Low oxygen + high heart rate strongly correlates with mortality  
- High-risk patients (diabetic smokers with heart disease) have significantly lower survival probability  

---

### 🔹 Page 3: Hospital & Emergency Performance
Visuals:
- Avg Emergency Response Time by Hospital
- Survival Rate by Shift Time
- Quick vs Delayed Response Comparison

Insights:
- Emergency response time is the strongest driver of survival  
- Night shifts show relatively lower survival rates  

---

### 🔹 Page 4: Cost & Length of Stay Analysis
Visuals:
- Treatment Cost vs Length of Stay Scatter Plot
- Avg Cost by Insurance Type
- Length of Stay by Admission Type

Insights:
- Longer hospital stays exponentially increase treatment cost  
- Critical patients incur higher financial burden  

---

### 🔹 Page 5: Final Insights & Recommendations
Key Findings:
- Faster emergency response (<10 min) significantly improves survival  
- High-risk patients form a small group but drive higher costs  
- Hospital performance varies significantly across regions  

Recommendations:
- Optimize emergency staffing during night shifts  
- Early monitoring for high-risk patients  
- Improve oxygen stabilization protocols  
- Replicate best-performing hospital practices across regions  

---

## 🎯 Key KPIs Created
- Total Patients
- Survival Rate %
- Cardiac Arrest Rate %
- Avg Emergency Response Time (Min)
- Avg Length of Stay (Days)
- Avg Treatment Cost (INR)
- High-Risk Patient Count

---

## 🎛️ Interactive Features
- Dynamic slicers: Region, Hospital, Gender, Admission Type, Date  
- Drill-down capability for detailed analysis  
- Cross-filtering across all visuals  
- Conditional formatting for performance comparison  

---

## 📈 Business Impact
This dashboard helps:
- Hospital administrators improve emergency response planning  
- Doctors identify high-risk patient segments early  
- Healthcare policymakers optimize resource allocation  
- Insurance providers understand cost drivers in cardiac care  

---

## 🖼️ Dashboard Preview
<img width="1229" height="542" alt="1 Home" src="https://github.com/user-attachments/assets/b90fc33e-3ab5-42cd-8d79-023afc45c062" />


---

## 🚀 Conclusion
This project demonstrates how healthcare data can be transformed into actionable insights using Power BI. The dashboard enables proactive risk identification, improved emergency care efficiency, and cost optimization, ultimately supporting better patient survival outcomes and data-driven hospital management.

---
