# 💊 VaidyaRX Prescription Dashboard Analysis

This project showcases an end-to-end **Power BI Dashboard** built for analyzing outpatient prescription behavior. It includes **data cleaning, DAX measures, visualizations**, and a **professional-grade PDF report**.

---

## 📌 Dashboard Objective (Interview Assignment)

This dashboard answers 10 business-critical queries:

1. Distribution of 1–5 medicines per prescription, department-wise  
2. Distribution of antibiotics prescribed, by age group (0–18, 19–64, 65+)  
3. Distribution of FDC & Non-FDC medicines from NLEM  
4. Gender-wise usage of Analgesics & NSAIDs per department  
5. No. of medicines prescribed as FDC and Non-FDC  
6. Top 5 prescribed Analgesics & NSAIDs  
7. Prescriptions with ≤3 vs >3 medicines  
8. Distribution by dosage form  
9. Top 5 antibiotics prescribed  
10. Branded vs Generic breakdown (Drill-down → Category → Medicine)

---

## 📊 Tools Used

| Tool | Purpose |
|------|---------|
| Power BI | Interactive dashboard creation |
| Power Query | Data cleaning and transformation |
| DAX | Business calculations and metrics |
| Python (FPDF) | Auto-generated PDF report |
| Git & GitHub | Version control & project hosting |

---

## 🧾 Files Included

| File Name | Description |
|-----------|-------------|
| `VaidyaRx.Analytics.Dashboard.pbix` | Power BI dashboard file |
| `Prescription_Dashboard_Report.pdf` | Auto-generated business report |
| `VaidyaRx - Test data set- Dashboard Creation.xlsx` | Cleaned Excel dataset |
| `Report_Generator.py` | Python code to export report as PDF |
| `studio-background.jpg`, `vivid-blurred.jpg` | Visual assets used as background |

---

## 🚀 How to Run the Project

1. Open the `.pbix` file in **Power BI Desktop**
2. Explore visuals & KPIs: Filter by age, gender, department, date
3. Run `Report_Generator.py` (if Python is installed) to regenerate PDF summary

---

## 🧠 Key Features

- **Dynamic Drill-down**: Branded → Therapeutic Category → Medicine
- **Interactive Slicers**: Department, Age Group, Visit Date
- **Top N Ranking**: Filtered views for most-prescribed drugs
- **Categorical Donuts & Pie Charts**: For dosage form, FDC share
- **Stacked Visuals**: Gender breakdown, departmental analysis

---

## 📁 Folder Structure (as in your D:\ drive)

