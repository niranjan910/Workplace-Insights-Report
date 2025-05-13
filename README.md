# Workplace Insight Report

- **Author:** Niranjan 
- **Date:** 13 - MArch - 2025 

---

## Project Background

This project analyzes **employee well-being, job satisfaction, and organizational structure** using HR analytics data. As a Data Analyst, my goal was to explore factors affecting workplace productivity, stress levels, and job satisfaction to uncover actionable insights for HR optimization and employee experience enhancement.

This analysis aims to support better **workload management**, **employee retention strategies**, and **organizational structure improvements**.

---

## Dataset Description

The dataset contains **employee records** with comprehensive workplace metrics, including:

- Employee demographics (age, gender, education)
- Job characteristics (department, job level, team size)
- Well-being indicators (stress levels, sleep hours, physical activity)
- Satisfaction metrics (job satisfaction, work environment rating)

Key characteristics:
- Contains 22 features covering multiple workplace dimensions
- Includes both categorical and numerical variables
- Suitable for **exploratory data analysis (EDA)** and **HR analytics**

---

## Data Structure

| Column Name             | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| EmpID                   | Unique employee identifier                                                  |
| Gender                  | Gender (Male/Female/Other)                                                  |
| Age                     | Employee age in years                                                       |
| MaritalStatus           | Marital status (Single/Married/Divorced)                                    |
| JobLevel                | Organizational hierarchy level (1-5)                                        |
| Experience              | Total years of professional experience                                      |
| Dept                    | Department (IT/HR/Finance/Sales etc.)                                       |
| EmpType                 | Employment type (Permanent/Contract/Part-time)                              |
| WorkEnv                 | Work environment rating (1-5 scale)                                         |
| PhysicalActivityHours   | Weekly physical activity hours                                             |
| Workload                | Perceived workload rating (1-5 scale)                                       |
| Stress                  | Self-reported stress level (1-5 scale)                                      |
| SleepHours              | Average daily sleep hours                                                   |
| CommuteMode             | Transportation method to work                                               |
| CommuteDistance         | Home-to-office distance in kilometers                                       |
| NumCompanies            | Number of previous employers                                                |
| TeamSize                | Number of team members                                                      |
| NumReports              | Count of direct reports                                                     |
| EduLevel                | Highest education qualification                                            |
| haveOT                  | Overtime frequency (Yes/No)                                                 |
| TrainingHoursPerYear    | Annual training hours                                                       |
| JobSatisfaction         | Self-reported job satisfaction (1-5 scale)                                  |

---

## Executive Summary

### Key Highlights

- **Well-being Insights:** Correlation between sleep hours, stress levels, and job satisfaction
- **Department Analysis:** Variations in workload and satisfaction across departments
- **Organizational Structure:** Relationship between job level, team size, and direct reports
- **Work-Life Balance:** Impact of commute and overtime on employee stress

---

## Data Cleaning Steps

- ✔️ Handled missing values (imputation/removal based on analysis)
- ✔️ Standardized categorical variables (consistent formatting)
- ✔️ Verified numerical ranges for logical consistency
- ✔️ Removed duplicate entries (if any)

---

## Next Steps

- **Predictive Modeling:** Employee attrition risk based on stress/satisfaction
- **Department Benchmarking:** Compare well-being metrics across teams
- **Time Analysis:** Incorporate historical trends (if data available)
- **Interactive Dashboard:** Create visualization tools for HR team

---

## Assumptions & Caveats

- Data represents a single time point (cross-sectional analysis)
- Self-reported metrics may have subjective bias
- Some features may have correlation without causation

---

## 📬 Contact

For queries or collaborations:  
- **Email:** [your-email@domain.com]  
- **LinkedIn:** [Your Profile URL]  
"""

# Write to README.md file
with open("README.md", "w") as file:
    file.write(readme_content)

print("README.md file generated successfully!")
