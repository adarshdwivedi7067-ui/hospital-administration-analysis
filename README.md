# Reducing Readmissions: A Hospital Administration Case Study  
**Developed by:** Adarsh Dwivedi | **Role:** Data & Business Analyst  

---

##  Project Overview  
This project, conducted for **Novartis Administration Department**, is a deep-dive data analysis focused on hospital readmission rates.  
The goal is to identify factors that affect patient care quality and healthcare costs, and propose strategies to reduce unnecessary readmissions.  

---

##  Problem Statement  
Hospitals have observed a sudden spike in readmission rates, which is costly and raises concerns about quality of care.  
This analysis aims to uncover patterns and provide actionable recommendations to minimize avoidable readmissions.  

---

##  Dataset & Structure  
Main dataset: **HA Data.csv** containing patient records and medical history.  

- **Patient Demographics:** Age, Race, Gender, Weight  
- **Clinical Data:** Time in hospital, medical specialty, number of medications, lab procedures  
- **History:** Emergency visits, outpatient/inpatient visits  
- **Outcome:** Readmission status (Target variable)  

---

##  Analysis & Key Insights (Data-Driven)  
Analyzed 10 key questions (Q1–Q10) to uncover drivers of readmissions:  

- **Age & Readmission:** Patients aged 70–90 show the highest readmission (~48%)  
- **Medical Specialty:** Pediatrics-Pulmonology & Physical Medicine have longer average stays  
- **Medication Correlation:** Strong positive correlation (0.46) between number of medications & hospital stay duration  
- **Diabetes Impact:** Patients on diabetes medication show higher readmission (~47%) vs. non-diabetic (~40%)  
- **Emergency Visits:** Positive correlation between emergency visits & readmission → identifies high-risk patients  
- **Medication Change:** Treatment changes (Ch) increase readmission risk significantly  

---

##  Tools Used  
- **Python (Jupyter Notebook / Google Colab)** → Data cleaning, correlation analysis  
- **Pandas & NumPy** → Preprocessing, handling missing values, statistical analysis  
- **Seaborn & Matplotlib** → Visualizations (correlation plots, trendlines)  
- **Excel** → Supplementary pivot tables & charts for quick summaries  

---

##  Proposed Solutions  
- **Follow-up Program:** Discharge follow-up calls within 48 hours for high-risk age groups (70+)  
- **Medication Management:** Dedicated pharmacist review for patients with medication changes  
- **Specialized Care:** Optimized treatment plans for Pediatrics-Pulmonology to reduce stay duration  

---

##  Project Structure  
- `HA Data.csv` → Patient dataset  
- `Hospital_Readmission_Analysis.ipynb` → Python notebook with EDA & correlation analysis  
- `Hospital_Readmission_Report.pdf` → Detailed case study & solution guide  
- `README.md` → Executive summary & project documentation  
