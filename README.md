
# 🏥 Healthcare Data Analysis – sql & Power BI Project

This project is a complete end-to-end data analysis of healthcare admissions, designed to uncover meaningful insights that can drive better decision-making in hospital operations, resource allocation, and patient care.

## 📥 Data Source
The original dataset was extracted from **Microsoft SQL Server** and exported as a flat file (`Admissions.csv`). This flat file was then imported into **Power BI** for modeling and analysis.

## 🔧 What I Did

### ✅ Data Extraction
- Imported a flat file (Admissions data) into Power BI for analysis.

### ✅ Data Modeling
- Transformed flat structure into a **Star Schema**:
  - **Fact Table:** Admissions
  - **Dimension Tables:** Patients, Doctors, Hospitals, Admission Types, etc.

### ✅ Data Cleaning
- Removed nulls, blanks, and duplicates using Power Query
- Fixed data types
- Created calculated columns such as **Length of Stay**

### ✅ Dashboard Design
- Built interactive dashboards with slicers and filters
- Included KPIs, demographic visuals, time trends, billing analysis

## 📊 Key KPIs
- Average Length of Stay
- Urgent Admissions
- Admissions by Hospital & Doctor
- Age & Gender Distribution
- Billing by Medical Condition & Insurance Provider

## 📌 Insights Extracted
- **Gender Distribution:** Nearly equal between females (50.75%) and males (49.25%)
- **Top Age Group:** 46–60 years (2.2K admissions)
- **Blood Types:** AB+ and AB- most common among admitted patients
- **Top Medical Conditions:** Cancer, Asthma, Hypertension, Diabetes
- **Highest Billing Conditions:** Cancer ($43.49M), Asthma ($43.41M)
- **Top Hospital:** Smith and Sons ($477.64K)
- **Top Insurers:** Cigna (20.51%) and Athena (20.5%)
- **Most Used Medication:** Aspirin

## 💡 Recommendations
- Prioritize resources toward Cancer & Asthma management
- Launch preventive care for Hypertension & Diabetes
- Target ages 46–75 with wellness campaigns
- Optimize high-billing hospitals like Smith and Sons
- Strengthen partnerships with major insurers
- Educate patients on chronic conditions like Obesity & Arthritis

## 📁 Included Files
- `Healthcare_Admissions.pbix`: Power BI report file
- `Insights_Summary.docx`: Business insights and recommendations
- `Screenshots/`: Sample dashboard images

## 🛠 Tools & Technologies
- Power BI
- Power Query
- DAX
- Microsoft SQL Server
