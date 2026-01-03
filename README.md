# Employee Skills Clustering and Training Insights

## Project Overview
This project analyzes employee skill assessments, training enrollment, and survey data to identify distinct employee skill groups and derive actionable insights for workforce development and training strategy.

Using relational data from multiple sources, I applied dimensionality reduction and clustering techniques to segment employees based on performance, engagement, and skill patterns.

---

## Business Problem
Organizations often invest in training programs without clearly understanding:
- Which employees benefit most from specific courses
- How skill levels vary across locations and roles
- Where targeted training can improve performance outcomes

The goal of this project was to use data-driven segmentation to support smarter training and workforce planning decisions.

---

## Data Sources
The analysis integrates multiple relational datasets, including:
- Employee profiles
- Course offerings and enrollments
- Skill assessments
- Employee survey responses
- Local office and regional information

The datasets were connected using appropriate primary and foreign keys to ensure correct granularity and avoid double counting.

---

## Methodology
- Data cleaning and validation across multiple tables
- Relational joins and aggregation
- Exploratory data analysis
- Principal Component Analysis (PCA) for dimensionality reduction
- K-means clustering to identify employee groups
- Interpretation of clusters using performance and survey metrics

---

## Key Insights
- Employees naturally group into distinct clusters based on skill levels and engagement
- Some clusters show strong performance but low training participation, indicating missed development opportunities
- Other clusters benefit significantly from targeted training programs
- Skill gaps vary by location and role, suggesting a one-size-fits-all training strategy is inefficient

---

## Tools & Technologies
- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Jupyter Notebook

---

## Files in This Repository
- `final_case_2.ipynb` – Main analysis notebook
- `nls_employees.csv` – Employee-level data
- `nls_courses.csv` – Training course information
- `nls_enrollment.csv` – Course enrollment records
- `nls_assessments.csv` – Skill assessment results
- `nls_emp_survey.csv` – Employee survey responses
- `nls_local_offices.csv` – Office-level data
- `nls_regional_centers.csv` – Regional structure data

---

## How to Run
1. Clone the repository
2. Open `final_case_2.ipynb`
3. Run cells top to bottom

---

## Author
Tanjina Moon  
MS in Business Analytics, University of Rochester  

