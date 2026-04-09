# 🎓 Student Performance Dashboard

## 📌 Overview
This repository contains interactive **Power BI dashboards** analyzing student academic performance across demographics, socioeconomic factors, and preparation habits.  
It is divided into two pages:

1. **Students Performance Overview** – Baseline averages and distributions.  
2. **Advanced Analysis & Relationships** – Extremes, correlations, and deeper insights.

---

## 📊 Dashboard 1: Students Performance Overview
- **KPIs:** Average Math, Reading, Writing, and Overall Score.  
- **Gender Comparison (Bar Chart):** Female students score higher on average than male students.  
- **Parental Education (Line Chart):** Scores decline as parental education level decreases.  
- **Race/Ethnicity Distribution (Pie Chart):** Group C is the largest demographic.  
- **Lunch Type Distribution (Pie Chart):** Majority of students are on free/reduced lunch.

  <img width="516" height="290" alt="image" src="https://github.com/user-attachments/assets/23c9b6a7-5651-4675-b02e-438411cc4562" />


---

## 📊 Dashboard 2: Advanced Analysis & Relationships
- **KPIs:** Highest Math Score, Lowest Reading Score, Students Completed Prep Course, Top Student Average Score.  
- **Lunch Type (Stacked Bar):** Standard lunch students consistently outperform free/reduced lunch students.  
- **Parental Education (Line Chart):** Higher parental education strongly correlates with better scores across all subjects.  
- **Scatter Plot (Correlation):** Math and Reading scores show a positive correlation; bubble size reveals Writing performance differences by gender.  
- **Decomposition Tree:** Drill‑down analysis of performance drivers (Gender → Race → Parental Education → Lunch → Test Prep).

  <img width="513" height="293" alt="image" src="https://github.com/user-attachments/assets/3c0e857b-68ea-4a82-9b31-3fb7a25c16f8" />


---

## 📂 Repository Structure
Student_Performance_Dashboard/
│
├── data/
│   └── cleaned_student_performance.csv
│
├── dashboards/
│   └── StudentsPerformanceOverview.pbix
│   └── AdvancedAnalysisRelationships.pbix
│
├── images/
│   └── overview_screenshot.png
│   └── advanced_analysis_screenshot.png
│
└── README.md

## Code

---

## 🚀 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/Sridevi-coder62/Student_Performance_Dashboard.git
Open .pbix files in Power BI Desktop.

Explore dashboards interactively.

Review screenshots in /images if Power BI is not available.

## 💡 Key Insights
Female students outperform male students on average.

Parental education is a strong predictor of student success.

Socioeconomic factors (lunch type) significantly impact performance.

Test preparation courses improve outcomes, but disparities remain.

Math and Reading scores are positively correlated, with Writing adding a third dimension.

## 📈 Future Work
Add forecasting models (What‑If analysis).

Explore predictive analytics using regression or ML.

Expand dataset with attendance, extracurriculars, or socio‑economic indicators.

## 🏆 Credits
Created by Sridevi for datathon/portfolio showcase.
Built with Power BI and structured for reproducibility.
